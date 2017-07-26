# Project 2: Image Classification
[//]: # (Image References)

[image1]: ./Images/cifar-10.jpeg


In this project the goal is to classify images from the *CIFAR-10 dataset*. 
The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class.
These are the 10 classes in the dataset, as well as 10 random images from each class:

![alt text][image1]

In order to train the dataset on a convolutional neural network, it needs to be preprocessed. 
The images have to be normalized and the labels one-hot encoded.

The neural network consists of a convolutional layer, a max pool layer and a fully connected layer.
At the end we'll predict sample images by running them through ne convolutional network.
