# Linear Regression from Scratch using Gradient Descent

This project implements a simple linear regression model from scratch using gradient descent optimization. The model is trained on a given dataset to predict the output for a given input.

## Introduction

Linear regression is a fundamental machine learning algorithm used for modeling the relationship between a dependent variable and one or more independent variables. In this project, we implement a basic linear regression model using gradient descent optimization, without relying on inbuilt functions.


Dataset: use the above dataset

## Implementation Details

The implementation involves the following steps:

1. **Initialization**: Initialize the parameters `m` (slope) and `c` (y-intercept) to zero.
2. **Loss Function**: Define the loss function as Mean Squared Error (MSE).
3. **Gradient Calculation**: Calculate the gradients of the loss function with respect to `m` and `c`.
4. **Parameter Update**: Update the parameters `m` and `c` using the gradients and a learning rate.
5. **Gradient Descent**: Iterate the above steps for a fixed number of iterations or until convergence.
6. **Cost Function Plot**: Plot the cost function over iterations to observe convergence.
7. **Prediction**: After the model is trained, predict the output for a given input and compare it with the actual output.

## Usage

To use the linear regression model:

1. **Clone the Repository**:

```bash
git clone https://github.com/your-username/linear-regression-from-scratch.git
```
