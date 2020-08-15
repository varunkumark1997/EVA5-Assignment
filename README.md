# EVA5-Assignment
this is the first neural network that we have worked on where we are trying to create Convolutional Neural Network (CNN) model to recognize the hand written digits for which we are using the MNIST dataset.
We Have used Pytorch Library and written the Python code in Google Colab.
The neural network architecture is as follows:

1. input image size is 28 * 28
2. the network contains 5 convolutional layers.
3. Each convolution layer is followed by activation function (RELu). Except for last one
3. Each activation function is followed by batch-normalization.
4. Each batch-normalization is followed by dropout.
5. after the 5th convolution we have global average pooling (GAP)
6. Then the final softmax layer.

Features:

1. the model has test accuracy of 95.5%
2. the total parameters used in the models is 19,450.
3. the model does not contain fully connected layers.



Group members :
Prashanth Gowda
Varun Kumar
