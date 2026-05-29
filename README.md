# Breast Cancer Survival Prediction

## Overview

This project predicts breast cancer patient survival status (Alive/Dead) using clinical and demographic features.

## Dataset Features

* Age
* Tumor Size
* T Stage
* N Stage
* Grade
* Differentiate
* Hormone Receptor Status
* Regional Node Information

Target:

* Alive (0)
* Dead (1)

## Project Workflow

1. Data Cleaning
2. Data Leakage Detection and Removal
3. Feature Encoding
4. Feature Scaling
5. Class Imbalance Handling (SMOTE)
6. Model Training and Evaluation

## Models Used

* Logistic Regression
* Random Forest
* XGBoost

## Key Findings

* Removed `Survival Months` to prevent target leakage.
* Applied SMOTE to address class imbalance.
* Compared multiple machine learning models.
* Evaluated performance using Precision, Recall, F1-Score, and Confusion Matrix.
* Logistic Regression with SMOTE achieved the best balance between precision and recall.

## Technologies

Python, Pandas, NumPy, Scikit-Learn, XGBoost, Matplotlib, Seaborn, Imbalanced-Learn

## Future Work

* Hyperparameter tuning
* Feature selection
* Cross-validation
* Model explainability using SHAP
