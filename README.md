# Credit-Card-Fraud-Flagger

## Overview
This project implements a machine learning-based system to detect fraudulent credit card transactions. Using anonymized transaction data, the model identifies patterns and anomalies that differentiate fraudulent transactions from legitimate ones. The project focuses on handling imbalanced datasets and achieving high precision and recall to minimize false negatives and false positives.

## Features
Supervised Machine Learning Pipeline: Utilizes Random Forest for robust classification.
Class Imbalance Handling: Adjusts model weights to prioritize minority class detection without oversampling.
Metrics-Driven Evaluation: Precision, recall, F1-score, and AUC-ROC are used to evaluate model effectiveness.
End-to-End Data Workflow: Includes data preprocessing, feature normalization, and stratified train-test splitting.

## Dataset
The dataset used is a public credit card fraud detection dataset containing anonymized features (V1, V2, ..., V28), transaction amounts (Amount), and a binary label (Class):

Class=0: Legitimate transaction.
Class=1: Fraudulent transaction.

## Results
The model achieved the following performance on the test set:

Accuracy: 99.9%
Precision (Fraud Detection): 92%
Recall (Fraud Detection): 74%
AUC-ROC: 97.3%
These results demonstrate the system's effectiveness in distinguishing between fraudulent and legitimate transactions.

