# Fashion MNIST Classification using MLP

A deep learning project that classifies clothing images from the Fashion MNIST dataset using a Multi-Layer Perceptron (MLP) built with PyTorch.

## Overview

This project demonstrates how to build, train, and evaluate a neural network for image classification. The model is trained on the Fashion MNIST dataset, which contains grayscale images of different clothing categories.

The notebook covers:

- Loading and preprocessing the Fashion MNIST dataset
- Building an MLP neural network using PyTorch
- Training the model with backpropagation
- Evaluating model accuracy
- Visualizing predictions and results

## Dataset

The project uses the Fashion MNIST dataset from `torchvision.datasets`.

### Classes

| Label | Class |
|------|------|
| 0 | T-shirt/top |
| 1 | Trouser |
| 2 | Pullover |
| 3 | Dress |
| 4 | Coat |
| 5 | Sandal |
| 6 | Shirt |
| 7 | Sneaker |
| 8 | Bag |
| 9 | Ankle boot |

### Dataset Details

- 70,000 grayscale images
- Image size: 28×28
- 10 clothing categories

## Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib


## Model Architecture

The project uses a Multi-Layer Perceptron (MLP) consisting of:

- Input Layer: Flattened 28×28 image
- Hidden Layers with ReLU activation
- Output Layer with 10 classes

## Results

The trained model is able to classify Fashion MNIST clothing images with strong accuracy using a simple feedforward neural network.

Example outputs include:

- Training and validation accuracy
- Loss curves
- Sample predictions
- Visualization of classified images

## Learning Objectives

This project helps in understanding:

- Fundamentals of neural networks
- PyTorch workflow
- Image preprocessing
- Forward and backward propagation
- Model evaluation techniques
- Deep learning for computer vision
