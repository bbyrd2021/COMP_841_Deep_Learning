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

## Author

Brandon Byrd
