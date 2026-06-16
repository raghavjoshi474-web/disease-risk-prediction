# Disease Risk Prediction (Heart Disease)

A machine learning project to predict whether a patient is at risk of heart disease based on clinical health parameters.

## Problem Statement
Early detection of heart disease risk can help doctors intervene sooner and save lives. This project builds a model to classify patients as at-risk or not, based on medical attributes.

## Dataset
- Source: [Heart Disease Dataset - Kaggle](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
- 302 unique patients (after removing 723 duplicates) | 13 clinical features

## What I Did
- Performed EDA to find patterns between clinical features and disease risk
- Identified duplicate records and cleaned the dataset
- Split data into train/test sets and applied feature scaling
- Trained 2 models: Logistic Regression, Random Forest
- Selected Random Forest as final model for best overall performance

## Results
| Model | Accuracy | Disease Recall | AUC |
|---|---|---|---|
| Logistic Regression | 77.05% | 0.90 | - |
| Random Forest | 83.61% | 0.90 | 0.88 |

## Key Findings
- Chest pain type (cp) is a strong predictor of heart disease
- Maximum heart rate achieved (thalach) is the top
