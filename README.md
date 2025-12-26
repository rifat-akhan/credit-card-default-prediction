# A Machine Learning Approach to Credit Card Default Prediction

## Project Overview

Credit card defaults create major financial risk for banks and lending institutions. This project builds machine learning models to predict whether a credit card customer will default on their payment based on demographic information, credit limits, billing history, and past payments.

The project evaluates several machine learning models and identifies the most effective technique for default prediction.

## Dataset

This project uses the Default of Credit Card Clients Dataset from Kaggle/UCI.

The dataset contains:

- 30,000 records
- 24 features including:
  - credit limit
  - age
  - education level
  - marital status
  - past payment status for the last 6 months
  - bill amounts
  - payment amounts
- target variable: default payment (Yes/No)

Dataset link:  
https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset

## Methods and Models Used

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Random Forest
- Multi-Layer Perceptron (Neural Network)
- XGBoost

## Data Preprocessing Steps

- handled outliers using the Interquartile Range (IQR) method
- applied one-hot encoding to categorical variables
- balanced the dataset using SMOTE
- scaled features using StandardScaler

## Key Result

- XGBoost achieved the best overall performance
- models were evaluated using
  - accuracy
  - precision
  - recall
  - F1-score

## Applications

- credit risk assessment
- loan approval decision support
- customer risk profiling
