# Code-a-Neural-Network-from-scratch-almost: Neural Network Implementation

## Project Overview

This project is a pedagogical implementation of an **Artificial Neural Network (ANN)**, specifically a Multi-Layer Perceptron (MLP), coded **entirely from scratch** (or almost, using only `numpy` for matrix operations).

The main goal is to deconstruct the inner workings of Machine Learning libraries (like PyTorch or TensorFlow) by manually coding the fundamental building blocks:
*   Layers (here, the `Linear` layer).
*   Activation functions (here, `ReLU`, `CrossEntropy`, `L1`).
*   The loss function (`MSE`, `SIGMOID`, `LEAKYRELU` and `TANH`).
*   The **backpropagation** mechanism (`backward` pass) for learning.

The model is trained on a simplified version of the famous **MNIST** dataset for handwritten digit classification.
