# Heart Disease Prediction Project 🩺❤️

This project aims to predict heart disease based on patient health data using a Logistic Regression with Cross-Validation (LogisticRegressionCV) model.

## Project Overview

Heart disease is a critical global health issue, and accurate prediction models can aid in early detection and treatment. This project uses machine learning techniques to create a classifier that evaluates patient data and predicts the presence of heart disease.

## Key Highlights

**1. Data Analysis**
- Exploratory Data Analysis (EDA):
- Correlation matrix and heatmaps to identify relationships between features.
- Target variable distribution analysis for understanding class imbalance.

**2. Modeling**
LogisticRegressionCV Model:
  - Cross-validation ensures robust performance across folds.
  - Trained with max_iter=1000 for model convergence.

**3. Model Evaluation**

## The model demonstrates good performance:

✅ Accuracy:

  •	The overall accuracy is 84%, indicating reliable predictions for most cases.

✅ Precision and Recall:

  •	For patients without heart disease (label = 0):
  •	Precision: 86%, Recall: 80%
  •	For patients with heart disease (label = 1):
  •	Precision: 82%, Recall: 88%

✅ F1-Score:

  •	F1-scores reflect the balance between precision and recall:
  •	Label = 0: 0.83
  •	Label = 1: 0.85

✅ Confusion Matrix Analysis:

  •	Correctly classified:
  •	12 patients without heart disease.
  •	14 patients with heart disease.
  •	Misclassified:
  •	3 patients with heart disease as healthy.
  •	2 healthy patients as having heart disease.

## 📈 Overall Performance:

The model reliably predicts heart disease and achieves an AUC of 0.91 (ROC Curve) and AP of 0.91 (Precision-Recall Curve).

**Areas for Improvement**

While the model performs well, reducing the false negative rate (patients with heart disease misclassified as healthy) is critical in medical applications to minimize risks.
