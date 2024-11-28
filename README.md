# and-gate-neural-network
A Simple Neural Network: Training an AND Gate
This project aims to learn the functionality of a logical AND gate using a basic neural network. The code trains and tests the network using forward propagation and backpropagation methods, leveraging the sigmoid activation function.

Features

->Sigmoid Activation Function: Enables the network to learn non-linear decision boundaries.

->Sigmoid Function Derivative: Used during backpropagation to update the weights.

->Training Data: Two-dimensional binary inputs ([0,0],[0,1],[1,0],[1,1]) and corresponding outputs ([0,0,0,1]).

->Objective: To enable a single-layer neural network to learn the behavior of a logical AND gate.

Code Structure

1. Function Definitions:

->sigmoid(net): Calculates the sigmoid activation function.

->sigmoid_derivative(net): Calculates the derivative of the sigmoid function.

2. Parameters:
->Defines the number of training iterations (epochs) and the learning rate.

->Initializes weights and bias manually.

3. Training Loop:
->Forward Propagation: Calculates the net output using inputs and weights.

->Error Calculation: Computes the difference between the actual output and the network's output.

-<Backpropagation: Updates weights and bias by multiplying the error with the sigmoid derivative.

4. Model Testing:
->The trained network is tested on the training data, and the results are displayed.
