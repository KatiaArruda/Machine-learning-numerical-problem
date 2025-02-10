# Machine-learning-numerical-problem

# Digit Classification with PyTorch

# Description

This project implements an artificial neural network using PyTorch to classify handwritten digits from the MNIST dataset. The model receives 28x28 pixel images, converts them into tensors, and processes them through a fully connected network to predict which digit is represented in the image.

# Requirements

Before running the code, make sure to have the following dependencies installed:

- Python 3.x

- PyTorch

- Torchvision

- Matplotlib

- NumPy

#  Project Structure

The project consists of the following elements:

- Data Loading: Uses the MNIST dataset from torchvision.datasets.

- Pre-processing: Images are transformed into tensors and loaded into DataLoader to facilitate training.

- Model Definition: A neural network with three densely connected layers.

- Training: Uses the NLLLoss loss function and the SGD optimizer to adjust the network's weights.

- Validation: Evaluates the model's accuracy on a validation set.

#  Neural Network Structure

The implemented neural network has the following architecture:

- Input Layer: 784 neurons (28x28 pixels)

- Hidden Layer 1: 128 neurons (ReLU activation)

- Hidden Layer 2: 64 neurons (ReLU activation)

- Output Layer: 10 neurons (logarithmic softmax for classification from 0 to 9)

# Results

At the end of the training, the model is evaluated using a validation set. The script displays the network's accuracy in predicting the handwritten digits.
