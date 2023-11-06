# Planes in Satellite Imagery Binary Classification 

## Overview 

Binary image classifier implemented using a Convolutional Neural Network in PyTorch. The classifier is designed to classify images into one of two classes: "plane" or "no-plane."

## Data :airplane:

Data consists of satellite imagery of 4 airports (scenes), fragmented into 32000 images, from which 8000 are planes and 24000 are not planes.

The dataset can be found here: https://www.kaggle.com/datasets/rhammell/planesnet

## CNN architecture :wrench:

* CNN with two convolutional layers (an input layer and a second convolutional layer), one fully connected hidden layer, and an output layer for binary classification (2 classes: "plane" and "no-plane"). 

* The forward method defines the forward pass of the network, which involves applying the convolutional layers, max-pooling layers, and fully connected layers. The ReLU activation function is used after convolutional and fully connected layers to introduce non-linearity. The final layer with 2 output units is designed for binary classification, where each unit represents the probability of one class ("plane" or "no-plane").

## Results :heavy_check_mark:

After training for 10 epochs, the model reached a final `97.73 % Train Accuracy` and `96.94 % Test Accuracy`.




