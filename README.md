# Loan Prediction Neural Network (TensorFlow)

## Project Overview
Predicts loan approval using a Neural Network in TensorFlow. Includes feature scaling, preprocessing, EDA, model training and evaluation.

## Dataset
- Source: loan.csv
- Features: Gender, Married, Education, ApplicantIncome, etc.
- Target: Loan_Status (0/1)

## Model
- Sequential Neural Network
- Layers: Dense(64) → Dropout(0.3) → Dense(32) → Dropout(0.2) → Dense(1, Sigmoid)
- Optimizer: Adam
- Loss: Binary Crossentropy
- Metrics: Accuracy, F1 Score

## Results
- Validation Accuracy: 0.7723577235772358%
- F1 Score: 0.8390804597701149%
- Confusion matrix visualization included

## Usage
1. Open the Colab notebook
2. Run all cells
3. Save/load the model for deployment

