# Neural Network for Pima Indians Diabetes Classification

## Project Overview

This project implements a feedforward neural network to classify whether
a patient has diabetes using medical diagnostic measurements.

The workflow includes: - Data preprocessing - Feature scaling - Model
design - Training with early stopping - Model evaluation - Visualization
of results

------------------------------------------------------------------------

## Dataset

-   768 samples
-   8 input features
-   Binary classification (0 = No Diabetes, 1 = Diabetes)

------------------------------------------------------------------------

## Model Architecture

Input Layer: 8 features  
Hidden Layer 1: 32 neurons (ReLU)  
Hidden Layer 2: 16 neurons (ReLU)  
Output Layer: 1 neuron (Sigmoid)

Loss: Binary Crossentropy  
Optimizer: Adam (lr=0.001)  
Early Stopping applied

------------------------------------------------------------------------

## Results

Test Accuracy: 75%

Confusion Matrix: - TN: 82 - FP: 18 - FN: 21 - TP: 33

The model generalizes well with minimal overfitting. However, recall for
diabetic cases is 61%, indicating room for improvement.

------------------------------------------------------------------------

## How to Run

Install dependencies:

pip install numpy pandas matplotlib seaborn scikit-learn tensorflow

Run: pima_diabetes_nn.ipynb

------------------------------------------------------------------------

## Files Included

-   pima_diabetes_nn.ipynb
-   confusion_matrix.png
-   training_curves.png
-   metrics_summary.txt
-   README.md
