# Simple-Perceptron-Network

## Motivation
There is a considerable amount of neural network instruction that uses matrix math for forward and backward propagation. In terms of efficiency, this matrix math is the preferred solution as it takes advantage of the parallel processing capabilities of modern GPUs. The problem is that this matrix math can sometimes make it difficult to understand how the neural network is actually operating.

This project is designed to create simple neural networks, from scratch, in Python, without using a library like Tensorflow, by creating a Perceptron class. As most people are aware, neural networks are the combination of nodes, so representing each node as an instance of a Perceptron class, while computationally inefficient, can potentially lead to a better understanding of the process of forward and backward propagation.

## Objectives
Using a simple Perceptron class and a single Perceptron instantiated from that class, I am going to build and train:
* A classifier to determine if a point is above or below a line
* A network that computes a logical AND from two boolean inputs
* A network that computes a logical OR from two boolean inputs

Using the same Perceptron class and a multi-layer network with multiple Perceptrons instantiated from that class, I am going to build and train:
* A network of two nodes that computes a logical XOR from two boolean inputs
* A network of three nodes that computes a logical XOR from two boolean inputs

### Helpful online resources
[An Introduction to Python Machine Learning with Perceptrons](https://www.codementor.io/mcorr/an-introduction-to-python-machine-learning-with-perceptrons-k7pn85vfi) by Matthew Corrigan

[Python Course - Neural Networks](https://www.python-course.eu/neural_networks.php)

[A Step by Step Backpropagation Example](https://mattmazur.com/2015/03/17/a-step-by-step-backpropagation-example/) by Matt Mazur

[The XOR Problem and Solution](http://www.mind.ilstu.edu/curriculum/artificial_neural_net/xor_problem_and_solution.php?modGUI=239&compGUI=1286&itemGUI=2253) by Peter Bradley

[XOR classification using multilayer perceptrons is outputting 1 for all inputs](https://stackoverflow.com/questions/43390463/xor-classification-using-multilayer-perceptrons-is-outputting-1-for-all-inputs) on Stack Overflow
