# ANN Credit Card Fraud Detection

# Project Overview
This project implements an Artificial Neural Network (ANN) to detect fraudulent credit card transactions. The goal is to accurately classify transactions as fraudulent or legitimate using historical transaction data. The model helps financial institutions reduce losses caused by fraud while minimizing false positives.

# Objectives
Build an ANN-based binary classification model
Detect fraudulent transactions with high accuracy.
Handle class imbalance effectively
Evaluate model performance using appropriate metrics

# Technology Stack
Programming Language: Python
Libraries & Frameworks:
NumPy
Pandas
Matplotlib / Seaborn
Scikit-learn
TensorFlow / Keras

# Dataset Description
The dataset contains credit card transaction records
Features are numerical (often PCA-transformed for privacy)
Target column:
`0` → Legitimate transaction
`1` → Fraudulent transaction
Highly **imbalanced dataset** (fraud cases are rare)

⚙️ Data Preprocessing
Handling missing values
Feature scaling using StandardScaler
Splitting data into training and testing sets
Addressing class imbalance using:
Class weights / Oversampling (SMOTE)

# Model Architecture (ANN)
Input Layer: Based on number of features
Hidden Layers:
Dense layers with ReLU activation
Dropout for regularization
Output Layer:
neuron with Sigmoid activation

# Model Training
Loss Function: `Binary Crossentropy`
Optimizer: `Adam`
Evaluation Metrics:
Accuracy
Precision
Recall
F1-score
ROC-AUC

# Model Evaluation
Confusion Matrix
Classification Report
ROC Curve
Emphasis on Recall to reduce false negatives (missed fraud cases)

# Results
The ANN model successfully identifies fraudulent transactions
Improved fraud detection compared to traditional ML models
Balanced performance between precision and recall

# Author
Tanvi Bramhnakar

This project is for educational and research purposes only.
