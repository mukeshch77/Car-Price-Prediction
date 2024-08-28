# Car Price Prediction with Mini-Batch Gradient Descent

This repository contains a Python script for predicting car prices using Mini-Batch Gradient Descent with L2 Regularization. The script preprocesses a dataset, normalizes features, splits the data into training and test sets, trains a model, and evaluates its performance.

## Overview

The script performs the following tasks:
1. **Data Loading and Preprocessing**: Loads the car price dataset, handles missing values, and converts data types.
2. **Feature Selection and Encoding**: Selects relevant features and adjusts target values.
3. **Normalization**: Normalizes features for better performance.
4. **Train-Test Split**: Splits the data into training and test sets.
5. **Mini-Batch Gradient Descent**: Implements Mini-Batch Gradient Descent with L2 Regularization for training the model.
6. **Model Evaluation**: Evaluates the model performance using Mean Absolute Error (MAE) and plots the results.

## Prerequisites

Before running the script, make sure you have the following Python packages installed:
- `numpy`
- `pandas`
- `matplotlib`

You can install the required packages using pip:
```bash
pip install numpy pandas matplotlib
