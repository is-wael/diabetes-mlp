# Diabetes MLP Classifier

This project implements a neural network from scratch for binary classification on the Pima Indians Diabetes dataset.

## Features

- Manual implementation of a multilayer perceptron (MLP) with customizable architecture
- Data preprocessing: missing value handling, feature scaling, and class balance analysis
- Visualization of feature distributions and missing data patterns
- Stratified splitting into training, validation, and test sets
- Support for multiple optimizers, including SGD and Adam
- L2 regularization (weight decay) for overfitting control
- Comparative analysis of optimizers (SGD vs. Adam) and architectures
- Training and validation monitoring with detailed loss and accuracy curves
- Evaluation with accuracy, precision, recall, F1-score, and confusion matrix
- Visualization of confusion matrices and class distributions
- Experiments on the effect of regularization and network architecture
- Modular code structure for easy experimentation and extension

## How to Run

1. Install dependencies:
   `pip install -r requirements.txt`
2. Download the dataset (see `/data/README.md`)
3. Run the main script:
   `python src/neural_network.py`

## Project Structure

- `src/`: Source code (Python scripts)
- `notebooks/`: Jupyter notebooks 
- `data/`: Dataset 
- `results/`: Output figures and tables
