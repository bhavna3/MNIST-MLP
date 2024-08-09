# MNIST Classification with Multilayer Perceptron

This project demonstrates how to classify handwritten digits from the MNIST dataset using a Multilayer Perceptron (MLP) implemented with Scikit-learn. The MLP model is trained to recognize digits, and its performance is evaluated with accuracy and classification metrics.

## Table of Contents

- [Overview](#overview)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Visualization](#visualization)
- [License](#license)

## Overview

The MNIST dataset consists of 28x28 pixel grayscale images of handwritten digits (0-9). This project uses a Multilayer Perceptron classifier from Scikit-learn to train on this dataset and make predictions. The implementation includes data loading, model training, evaluation, and visualization of results.

## Requirements

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/mnist-mlp.git
   cd mnist-mlp

2. Install the required packages:
   ```bash
   pip install numpy pandas matplotlib scikit-learn

## Usage

1. Run the script to load the dataset, train the MLP model, and evaluate its performance:
   ```bash
   python mnist_mlp.py
2. The script will output classification metrics and display a grid of test images with their true and predicted labels.

## Results

The model is evaluated using accuracy and a detailed classification report, which includes precision, recall, and F1-score for each digit class. The performance metrics will be printed to the console after training.

## Visualization

The script includes functionality to visualize a subset of test images along with their true labels and predictions. This helps in understanding how well the model is performing visually.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.


















