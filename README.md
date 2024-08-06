# 🧠 Predicting Obesity with Neural Networks

## Introduction

Welcome to this repository where we analyze the **Estimation of Obesity Levels** dataset from the UC Irvine Machine Learning Repository. This dataset provides insights into how eating habits and physical conditions correlate with obesity levels, with the ultimate goal of building an effective neural network model for prediction.

## Repository Structure

This repository contains:

- **`predicting-obesity-with-neural-networks.ipynb`**: The Jupyter notebook with the complete analysis, including data preprocessing, model architecture, training, and evaluation.
- **`data/`**: Folder containing the dataset files:
  - **`data_ready.csv`**: A cleaned and imputed subset of 1,000 samples for model training and testing. Columns 'gender' and 'Weight' were removed to enhance model performance and avoid collinearity.
  - **`test_later.csv`**: Additional data for final model evaluation.

## Model Training and Evaluation

We employed a Neural Network model using Keras with TensorFlow backend. The model was trained and tuned using cross-validation. Key results include:

### On `data_ready.csv`:

- **Accuracy**: 0.80
- **Recall for Class 1 (Obesity)**: 0.94

### On `test_later.csv`:

- **Accuracy**: 0.82
- **Recall for Class 1 (Obesity)**: 0.96

The recall for identifying obesity, our primary objective, demonstrates the model’s effectiveness in detecting individuals with obesity. The notebook details the model development process, including data preprocessing, neural network architecture design, and hyperparameter tuning.

## Explore Further

- **Kaggle Notebook**: Dive deeper into the analysis and code by visiting the Kaggle notebook [here](https://www.kaggle.com/code/jbasurtod/predicting-obesity-with-neural-networks).
- **Live Model**: Experience the model in action on the Streamlit app [here](https://obesitypred.streamlit.app/).

## Getting Started

To replicate the analysis, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/jbasurtod/predicting_obesity_neural_networks.git
