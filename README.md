# MNIST Handwritten Digit Classification with TensorFlow

This project implements a neural network to classify handwritten digits from the MNIST dataset using TensorFlow. The model is trained to achieve 98% accuracy, and training stops early if this threshold is reached before completing 10 epochs.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Requirements](#requirements)
3. [Implementation Details](#implementation-details)
4. [How to Run the Code](#how-to-run-the-code)
5. [Results](#results)
6. [License](#license)

---

## Project Overview

The goal of this project is to build and train a neural network to classify handwritten digits (0-9) from the MNIST dataset. The model is implemented using TensorFlow and Keras. Key features of the project include:

- A custom callback (`EarlyStoppingCallback`) to stop training once the model achieves 98% accuracy.
- A simple feedforward neural network architecture with one hidden layer.
- Normalization of input data to improve training efficiency.

---

## Requirements

To run this project, you need the following:

- Python 3.x
- TensorFlow 2.x
- NumPy

You can install the required libraries using pip:

```bash
pip install tensorflow numpy
