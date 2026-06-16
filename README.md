# ICR — Identifying Age-Related Conditions
**Kaggle ICR Competition** | Binary Medical Classification

## Overview
Predicted whether a patient has one or more age-related medical conditions
based on 56 anonymized health measurement features. Built and compared
multiple classification models, handling class imbalance and missing values
throughout.

## Approach
- **EDA** on 56 anonymized biomarker features
- **Class imbalance handling** via RandomOverSampler
- **Missing value imputation** with SimpleImputer
- **Feature scaling** with MinMaxScaler
- **Feature selection** with SelectKBest (f_classif)
- **Models trained and compared:**
  - Logistic Regression
  - K-Nearest Neighbors
  - Decision Tree
  - Random Forest
  - XGBoost
- **Evaluation metric:** Balanced Log Loss

## Tools Used
Python (scikit-learn, XGBoost, imbalanced-learn, pandas, numpy,
matplotlib, seaborn)

## Competition
[Kaggle ICR — Identifying Age-Related Conditions](https://www.kaggle.com/competitions/icr-identify-age-related-conditions)
