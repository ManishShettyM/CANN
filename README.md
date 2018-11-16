# CANN
C based Artificial Neural Network

This a simple library which integrates a lot of functionalities for basic ANN operations.

## Compile
gcc -w cann.c <test_main_file.c> -lm

## Execute
./a.out

## Comparison with python modules

1.Gate functionalities : Creating ANN for gates like XOR,AND,OR etc in a low level language like C is much faster and hiighly compatible too.

2.Regression : The Auto-Mpg dataset was used to solve a MULTIPLE LINEAR REGRESSION problem using the ANN.

### Dataset
  | cylinders |	displacement |	horsepower |	weight |	acceleration |	mpg 
  
  Here the first 5 paramters were used to predict a cars MPG(milleage).
### Results
  ANN&nbsp;               &nbsp;CANN&nbsp;           &nbsp;KERAS  
  
  Iterations&nbsp;         &nbsp;1000&nbsp;           &nbsp;1000&nbsp;   
  
  RMSE&nbsp;               &nbsp;9.586&nbsp;          &nbsp;5.516&nbsp;   
  
  Time(sec)&nbsp;          &nbsp;0.06558&nbsp;        &nbsp;13.9793&nbsp; 
 
3.Classification : The IRIS dataset was used to solve a 3 class problem using the ANN.

### Results
  ANN:              CANN          KERAS
  Iterations        1000          1000  
  Accuracy          96.7%         96.6%
  Time(sec)         0.06558       33.72608
  

