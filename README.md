# 🩺 Liver Disease Prediction using Machine Learning

A Machine Learning project that predicts the likelihood of liver disease using patient health and lifestyle-related features.

This project explores data preprocessing, exploratory data analysis, machine learning model training, evaluation, feature importance analysis, and ROC-AUC analysis using Python and Scikit-learn.

---

## 📌 Project Overview

Liver diseases can be influenced by multiple factors such as age, BMI, alcohol consumption, physical activity, genetic risk, smoking, and liver function indicators.

The objective of this project is to build a classification model capable of predicting whether a patient is likely to have liver disease based on available clinical and lifestyle features.

The project follows a complete Machine Learning workflow:

> **Data → Preprocessing → EDA → Feature Engineering → Model Training → Evaluation → Feature Importance → ROC Curve**

---

## 🎯 Objectives

- Analyze the dataset and understand important health-related features.
- Perform data preprocessing and prepare the data for Machine Learning.
- Train a Random Forest classification model.
- Evaluate the model using classification metrics.
- Analyze feature importance.
- Evaluate the model using ROC-AUC.
- Understand which factors contribute most to the model's predictions.

---

## 🧠 Machine Learning Model

### Random Forest Classifier

The main model used in this project is:

**Random Forest Classifier**

Configuration:

```python
RandomForestClassifier(
    n_estimators=100,
    random_state=42
)
