# Artificial neural network from scratch

## Objective
To build a 2 layer neural network for a classification problem using objects (classes) in python. This would help in building a strong intuition behind the working of neural nets along with the mathematics. It also helps in experimenting arbitrary architectures like dropout, regularization, bias units and many more by acting as a good starting point. Eventually, as we move more and more towards popular and powerful frameworks like TensorFlow and Keras with black box implementations this exercise seeks to provide a good sense of computations happening in these libraries while implementing more complex networks like CNN, RNN etc.    

## Architecture
* Input layer with 9 inputs since the dataset has 9 features
* Hidden layer with 15 neurons and ReLU activation
* Single neuron output layer with sigmoid activation & binary cross entropy loss

## Dataset 
Cancer dataset is used from the UCI machine learning [repository](https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+%28original%29)
