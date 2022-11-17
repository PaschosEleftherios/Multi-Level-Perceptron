# Multi-Level-Perceptron
Artificial Neural Network

In this repository, is presented the code of a 2 layer and a 3 layer perceptron in files p1,p2 respectively.

We create 2 Datasets one for training the network and one for testing it.

The datasets are being created in the createDatasets() function of the code.
We create 4.000 points x1,x2 for each Dataset in [-1,1].
There are 4 categories that a point could belong so each category is  represented in format like:
(1,0,0,0),(0,1,0,0),(0,0,1,0),(0,0,0,1)
Format of the Dataset is : x1 x2 category 
This function is being commented after first run so we can have the same two datasets for testing in every run.

The network is being trained using the DatasetTrain and the backpropagation method with activation functions tanh or relu.
Training stops when the square error between two epochs is minimized(is under a given threshold.)

After the generalization ability of the network is computed with the DatasetTest.

For a brief explanation of the code, take a look on Multi-Layered-Perceptron.pdf
