# predicting type of Breast Cancer
McCulloch Pitts Neuron model is used to predict type of breast cancer.

## Data :
Data is binarised because MP neuron only accepts binary data.

## Optimizer :
Since there is only one parameter in this model, we can use  brute force search algorithm.

## Model :
<a href="https://www.codecogs.com/eqnedit.php?latex=y&space;=&space;\left\{\begin{matrix}&space;1&space;\:&space;\if&space;\sum&space;x_i&space;\geq&space;b&space;\\&space;\\&space;0&space;\:&space;otherwise&space;\end{matrix}\right." target="_blank"><img src="https://latex.codecogs.com/gif.latex?y&space;=&space;\left\{\begin{matrix}&space;1&space;\:&space;\if&space;\sum&space;x_i&space;\geq&space;b&space;\\&space;\\&space;0&space;\:&space;otherwise&space;\end{matrix}\right." title="y = \left\{\begin{matrix} 1 \: \if \sum x_i \geq b \\ \\ 0 \: otherwise \end{matrix}\right." /></a>

## Loss function : 
<a href="https://www.codecogs.com/eqnedit.php?latex=loss&space;=&space;\left\{\begin{matrix}&space;1&space;\:&space;if&space;\&space;\hat{y}&space;=&space;y\\&space;\\&space;0&space;\:&space;otherwise&space;\end{matrix}\right." target="_blank"><img src="https://latex.codecogs.com/gif.latex?loss&space;=&space;\left\{\begin{matrix}&space;1&space;\:&space;if&space;\&space;\hat{y}&space;=&space;y\\&space;\\&space;0&space;\:&space;otherwise&space;\end{matrix}\right." title="loss = \left\{\begin{matrix} 1 \: if \ \hat{y} = y\\ \\ 0 \: otherwise \end{matrix}\right." /></a>

## Evaluation :
accuracy score
