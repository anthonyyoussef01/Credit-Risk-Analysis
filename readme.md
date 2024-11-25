# Credit Risk Analysis

> An advanced machine learning project for predicting loan defaults using customer data analytics.

## Overview

This analysis leverages three powerful machine learning models to predict loan defaults:
- AdaBoost Classifier 
- Support Vector Classifier (SVC)
- Logistic Regression

### 📋 Dataset Features
I used a datase from Kaggle with the following features:
- Age
- Education level 
- Employment details
- Income
- Debt information
- Default status (target variable)

## Model Performance

### Accuracy Metrics
| Model | Accuracy |
|-------|----------|
| AdaBoost | 82.14% |
| SVC | 80.00% |
| Logistic Regression | 82.14% |

> **Key Finding**: AdaBoost and Logistic Regression demonstrated superior performance with identical accuracy scores.

## 🛠 Installation

Required dependencies:
```python
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Usage

Navigate through our analysis in `credit-risk-analysis.ipynb`:
1. Data preprocessing and cleaning
2. Model training and optimization
3. Model evaluation and comparison
4. Visualization of results