# MNIST Neural Network from Scratch

This project implements a simple Neural Network (NN) from scratch to classify digits from the MNIST dataset. The network is designed with a two hidden layer architecture, and it is built without relying on high-level deep learning libraries.

## Table of Contents

- [Architecture](#architecture)
- [Activation Functions](#activation-functions)
- [Loss Function](#loss-function)
- [Implementation Details](#implementation-details)
- [Requirements](#requirements)
- [Usage](#usage)

---

## Architecture

The neural network has the following architecture:

- **Input Layer**: 784 units (corresponding to the 28x28 pixels of the MNIST images).
- **First Hidden Layer**: 10-128 (check each of them using cross-validation) nodes.
- **Output Layer**: 10 units (corresponding to the 10 digit classes: 0-9).

## Activation Functions

- **ReLU (Rectified Linear Unit)**: Used for both hidden layers.
- **Softmax**: Applied to the output layer to convert the network's outputs into a probability distribution over the 10 digit classes.

## Loss Function

- **Cross-Entropy Loss**: This loss function is used for training the network. It is standard for classification tasks like digit recognition and measures the difference between the predicted probability distribution and the actual distribution.

## Implementation Details

- The entire network is implemented from scratch, without using high-level deep learning libraries like TensorFlow or PyTorch.
- The network's architecture and training process are handled manually to provide a deeper understanding of how neural networks function internally.
- The network is trained on the MNIST dataset, which consists of 60,000 training images and 10,000 testing images of handwritten digits.

## Requirements

- Python 3.x
- NumPy
- Matplotlib (optional, for visualizing results)

Install the required packages using:

```bash
pip install -r requirements.txt
```
## Usage
1. Clone the repository.
2. Open the notebook and follow the instructions to run the neural network training and evaluation process.
3. The notebook will guide you through building, training, and testing the neural network on the MNIST dataset.
