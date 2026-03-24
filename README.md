# COMP 841 - Deep Learning

This repository contains coursework for COMP 841 Deep Learning course.

## Homework 1: Gradient Descent

Implementation of gradient descent algorithm for linear regression from scratch.

### Overview

This assignment demonstrates the gradient descent optimization algorithm by finding the optimal parameters for a simple linear regression model of the form `y = a + bx`.

### Features

- Custom gradient descent implementation without using machine learning libraries
- Comparison with analytical solution (ground truth)
- Residual Sum of Squares (RSS) evaluation
- Convergence tracking and visualization

### Dataset

Simple 1D dataset:
- X = [1, 2, 4, 6, 8]
- Y = [2, 5, 6, 9, 11]

### Results

The gradient descent algorithm converges to:
- **a (intercept)**: 1.551
- **b (slope)**: 1.202
- **Epochs**: 2,223
- **RSS Difference from Analytical Solution**: ~1.89e-05

### Requirements

- Python 3.x
- NumPy

### Usage

Open and run the Jupyter notebook:

```bash
jupyter notebook brandon_byrd_hw1_gradient_descent.ipynb
```

## Homework 2: Neural Network with Backpropagation

Implementation of a multi-layer neural network using TensorFlow/Keras.

### Overview

This assignment implements a 4-layer feedforward neural network trained via backpropagation using the Adam optimizer.

### Architecture

- Input layer: 2 nodes
- Hidden layers: 3 dense layers (2 nodes each, sigmoid activation)
- Output layer: 2 nodes (sigmoid activation)
- Optimizer: Adam
- Loss: Mean Squared Error (MSE)

### Dataset

Simple 2D dataset tiled 1000 times:
- X = [0.05, 0.1]
- Y = [0.01, 0.99]

### Results

The network converges within 10 epochs:
- **Final loss**: ~2.1e-05
- **Final accuracy**: 100%

### Requirements

- Python 3.x
- TensorFlow / Keras
- NumPy
- Matplotlib

### Usage

Open and run the Jupyter notebook:

```bash
jupyter notebook homework_2/Brandon_Byrd.ipynb
```

## Author

Brandon Byrd
