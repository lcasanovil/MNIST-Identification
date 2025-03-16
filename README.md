# MNIST Identification

This project focuses on classifying handwritten digits (0-9) using the MNIST dataset. The goal is to build and train a Convolutional Neural Network (CNN) to achieve high accuracy on the test set.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [Usage](#usage)
- [License](#license)

## Overview
The MNIST dataset is a classic dataset in machine learning, consisting of 28x28 grayscale images of handwritten digits. This project uses a CNN to classify these digits with high accuracy.

## Dataset
The MNIST dataset contains 60,000 training images and 10,000 test images. Each image is labeled with the corresponding digit (0-9).

- **Source**: [MNIST Dataset](http://yann.lecun.com/exdb/mnist/)
- **Size**: 70,000 images (28x28 pixels)
- **Labels**: Digits 0-9

## Model Architecture
The model is a Convolutional Neural Network (CNN) with the following architecture:
- **Input Layer**: 28x28 grayscale image
- **Convolutional Layers**: Two convolutional layers with ReLU activation
- **Pooling Layers**: Max pooling after each convolutional layer
- **Fully Connected Layers**: Two dense layers with ReLU activation
- **Output Layer**: Softmax activation for classification

## Results
The model achieves the following performance:
- **Training Accuracy**: 99.2%
- **Test Accuracy**: 98.5%

## Usage
To run this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/MNIST-Identification.git
   cd MNIST-Identification
