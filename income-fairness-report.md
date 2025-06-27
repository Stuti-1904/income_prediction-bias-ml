# Fairness in Income Prediction using Logistic Regression

This project investigates *bias and fairness* in machine learning by predicting whether an individual's income is above or below $50K using the UCI Adult Income dataset.

## Problem Statement
Train a logistic regression model to predict income level, and explore gender-based fairness using SHAP.

## Model Used
- Logistic Regression (sklearn)
- Accuracy: ~80.7%
- Evaluated using Precision, Recall, F1-score

## SHAP Interpretability
Used SHAP to visualize how features like relationship, capital_gain, and education_num impact predictions.

## Bias Detection
Tested prediction accuracy for different genders:
- *Female Accuracy*: [0.89]
- *Male Accuracy*: [0.77]

## Tools & Tech
- Python, Google Colab
- scikit-learn, pandas, SHAP

## Dataset
[UCI Adult Income Dataset](https://archive.ics.uci.edu/ml/datasets/adult)

## Author
Stuti – Pre-final year CS undergrad passionate about AI, fairness, and impactful ML research.
