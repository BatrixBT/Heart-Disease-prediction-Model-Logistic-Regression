
# Heart Disease Prediction using Logistic Regression

## Overview

This repository contains a machine learning project aimed at predicting heart disease using a Logistic Regression model. The dataset is preprocessed, balanced using SMOTE, and evaluated with multiple performance metrics.

## Dataset

The dataset used in this project is sourced from the Framingham Heart Study and includes various health-related features.

## Features Used

Age

Sex

Blood Pressure

Cholesterol

Smoking Habit

Diabetes

Target Variable: Presence of heart disease (1 = Yes, 0 = No)

## Libraries Used

Pandas for data manipulation

Numpy for numerical operations

Scikit-learn for machine learning models and preprocessing

Imbalanced-learn for handling class imbalance with SMOTE

Matplotlib and seaborn for data visualization

## Model Training & Evaluation

Data Preprocessing: Handling missing values, scaling features

Balancing the Dataset: Using SMOTE to address class imbalance

Logistic Regression Model: Applied with hyperparameter tuning using GridSearchCV

## Valuation Metrics:

Accuracy

ROC-AUC Score

Confusion Matrix

Precision, Recall, F1-score

## Results

Model achieved an accuracy of 67% and ROC-AUC score of 73%.

Performance improved after using SMOTE to handle class imbalance.

## Links
Dataset: https://www.kaggle.com/datasets/dileep070/heart-disease-prediction-using-logistic-regression
Kaggle notebook: https://www.kaggle.com/code/nejczavodnik/heart-disease-prediction-model-logistic-regression



