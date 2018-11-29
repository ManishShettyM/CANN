# CANN
C based Artificial Neural Network

This a simple library which integrates a lot of functionalities for basic ANN operations.

## Compile
gcc -w cann.c <test_main_file.c> -lm

## Execute
./a.out

## Comparison with python modules

### 1.Gate functionalities : Creating ANN for gates like XOR,AND,OR etc in a low level language like C is much faster and hiighly compatible too.

### 2.Regression : The Auto-Mpg dataset was used to solve a MULTIPLE LINEAR REGRESSION problem using the ANN.

#### Execution Time
|ANN library	|Iterations	|RMSE	|Time(sec)	|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|CANN	|10<sup>3</sup>	|9.586	|0.06558	|
|Keras	|10<sup>3</sup>	|5.516	|13.9793	|

  
### 3.Classification : The IRIS dataset was used to solve a 3 class problem using the ANN.

#### Execution Time
|ANN library	|Iterations	|Accuracy	|Time(sec)	|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|CANN	|10<sup>3</sup>	|96.7%	|0.1834	|
|Keras	|10<sup>3</sup>	|96.6%	|33.72608	|


 
  

