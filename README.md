# Project 2: Image Classification
[//]: # (Image References)

[image1]: ./Images/cifar-10.jpeg


In this project the goal is to classify images from the *CIFAR-10 dataset*. The dataset contains 10 different image categories like airplanes, dogs and cats:

![alt text][image1]

In order to train the dataset on a convolutional neural network, it needs to be preprocessed. 
The images have to be normalized and the labels one-hot encoded.

The neural network consists of a convolutional layer, a max pool layer and a fully connected layer.
At the end we'll predict sample images by running them through ne convolutional network.
