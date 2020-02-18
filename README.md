# Predicting Type of Breast Cancer
McCulloch Pitts Neuron model and perceptron model is used to predict type of breast cancer.

## MP Neuron Model:
### Data :
Data is binarised because MP neuron only accepts binary data.

### Model :
<a href="https://www.codecogs.com/eqnedit.php?latex=y&space;=&space;\left\{\begin{matrix}&space;1&space;\:&space;\if&space;\sum&space;x_i&space;\geq&space;b&space;\\&space;\\&space;0&space;\:&space;otherwise&space;\end{matrix}\right." target="_blank"><img src="https://latex.codecogs.com/gif.latex?y&space;=&space;\left\{\begin{matrix}&space;1&space;\:&space;\if&space;\sum&space;x_i&space;\geq&space;b&space;\\&space;\\&space;0&space;\:&space;otherwise&space;\end{matrix}\right." title="y = \left\{\begin{matrix} 1 \: \if \sum x_i \geq b \\ \\ 0 \: otherwise \end{matrix}\right." /></a>

### Learning Algorithm :
Brute force search algorithm can be used as there is only one parameter in this model.
<a href="https://www.codecogs.com/eqnedit.php?latex=0&space;<&space;\sum&space;x_i&space;<&space;\&space;$number&space;of&space;parameters$" target="_blank"><img src="https://latex.codecogs.com/gif.latex?0&space;<&space;\sum&space;x_i&space;<&space;\&space;$number&space;of&space;parameters$" title="0 < \sum x_i < \ $number of parameters$" /></a><br>
<a href="https://www.codecogs.com/eqnedit.php?latex=0&space;\leq&space;b&space;\leq&space;\&space;$number&space;of&space;parameters$" target="_blank"><img src="https://latex.codecogs.com/gif.latex?0&space;\leq&space;b&space;\leq&space;\&space;$number&space;of&space;parameters$" title="0 \leq b \leq \ $number of parameters$" /></a><br>
values of b greater or less than this range will not effect the result.
So we will iterate over all these values of b and find the value which will give the maximum accuracy.

### Loss function : 
<a href="https://www.codecogs.com/eqnedit.php?latex=loss&space;=&space;\left\{\begin{matrix}&space;1&space;\:&space;if&space;\&space;\hat{y}&space;=&space;y\\&space;\\&space;0&space;\:&space;otherwise&space;\end{matrix}\right." target="_blank"><img src="https://latex.codecogs.com/gif.latex?loss&space;=&space;\left\{\begin{matrix}&space;1&space;\:&space;if&space;\&space;\hat{y}&space;=&space;y\\&space;\\&space;0&space;\:&space;otherwise&space;\end{matrix}\right." title="loss = \left\{\begin{matrix} 1 \: if \ \hat{y} = y\\ \\ 0 \: otherwise \end{matrix}\right." /></a>

### Evaluation :
Accuracy score

## Perceptron Model:
### Data:
No need to binarise the data, because perceptron can accept real valued inputs.

### Model :
<a href="https://www.codecogs.com/eqnedit.php?latex=y&space;=&space;\left\{\begin{matrix}&space;&1&space;\;&space;\if&space;\;&space;\sum{x_iw_i}&space;\geq&space;\&space;b&space;\\&space;&&space;\\&space;&&space;0&space;\;&space;\&space;otherwise&space;\end{matrix}\right." target="_blank"><img src="https://latex.codecogs.com/gif.latex?y&space;=&space;\left\{\begin{matrix}&space;&1&space;\;&space;\if&space;\;&space;\sum{x_iw_i}&space;\geq&space;\&space;b&space;\\&space;&&space;\\&space;&&space;0&space;\;&space;\&space;otherwise&space;\end{matrix}\right." title="y = \left\{\begin{matrix} &1 \; \if \; \sum{x_iw_i} \geq \ b \\ & \\ & 0 \; \ otherwise \end{matrix}\right." /></a>

### Learning Algorithm :
Perceptron Learning algorithm is used.
It basically tries to find the line which will seperate positive and negative points.

### Loss function :
<a href="https://www.codecogs.com/eqnedit.php?latex=loss&space;=&space;\left\{\begin{matrix}&space;1&space;\:&space;if&space;\&space;\hat{y}&space;=&space;y\\&space;\\&space;0&space;\:&space;otherwise&space;\end{matrix}\right." target="_blank"><img src="https://latex.codecogs.com/gif.latex?loss&space;=&space;\left\{\begin{matrix}&space;1&space;\:&space;if&space;\&space;\hat{y}&space;=&space;y\\&space;\\&space;0&space;\:&space;otherwise&space;\end{matrix}\right." title="loss = \left\{\begin{matrix} 1 \: if \ \hat{y} = y\\ \\ 0 \: otherwise \end{matrix}\right." /></a>

### Evaluation :
Accuracy score
