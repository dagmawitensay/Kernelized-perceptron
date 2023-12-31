# Kernelized Perceptron

## Overview:

This repository contains a Python implementation of a Kernelized Perceptron, a variant of the traditional perceptron algorithm capable of handling non-linearly separable data. The implementation is designed to use the Radial Basis Function (RBF) kernel, providing flexibility for capturing complex relationships within the data.

## Contents:

1. **`kernelized_perceptron.py`:**
   - Contains the implementation of the Kernelized Perceptron along with supporting functions.

2. **`data_generation.py`:**
   - Provides a function for generating non-linearly separable data, useful for testing the Kernelized Perceptron.

3. **`test_kernelized_perceptron.py`:**
   - Includes a test script demonstrating the functionality of the Kernelized Perceptron on both generated and real-world data.

4. **`data_banknote_authentication.txt`:**
   - A dataset used for testing the Kernelized Perceptron on real-world data. Obtained from Kaggle, the dataset involves banknote authentication.

## Usage:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/dagmawitensay/kernelized-perceptron.git
   cd kernelized-perceptron

2. **Run Tests:**
   ```bash
   python test_kernelized_perceptron.py

## Dependencies:
- numpy
- pandas
- sckit-learn

## Additional Notes:
- The Kernelized Perceptron is implemented with the RBF kernel, providing a foundation for understanding kernelized learning in perceptrons.
- The repository includes a function for generating non-linearly separable data, useful for testing and experimentation.
- The test script demonstrates the algorithm's performance on both generated and real-world data.
