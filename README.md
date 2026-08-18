#  Liver Disease Prediction

A supervised classification project that predicts the likelihood of liver disease using clinical, demographic, genetic, and lifestyle-related features.

## 📌 Project Overview

This project focuses on building a classification model capable of identifying whether a patient is likely to have liver disease based on multiple health-related attributes.

Unlike a basic prediction workflow, this project includes model evaluation, ROC-AUC analysis, feature-importance interpretation, and visual exploration of the factors contributing to predictions.

## 🧠 Machine Learning Approach

- Learning Type: Supervised Learning
- Problem Type: Binary Classification
- Algorithm: Random Forest Classifier
- Number of Estimators: 100
- Random State: 42
- Train-Test Split: Used for model evaluation

## 📊 Features Used

The model uses features including:

- Age
- Gender
- BMI
- Alcohol Consumption
- Smoking
- Physical Activity
- Genetic Risk
- Hypertension
- Liver Function Test

## 📈 Model Performance

The Random Forest model achieved approximately:

**Accuracy: 90.29%**

The model was additionally evaluated using an ROC curve.

**ROC-AUC: approximately 0.95**

The ROC curve demonstrates the model's ability to distinguish between the two target classes across different classification thresholds.

## 🔍 Feature Importance

Random Forest feature importance was used to understand which variables contributed most to the model's predictions.

The analysis indicated that features such as:

1. Alcohol Consumption
2. Liver Function Test
3. BMI
4. Age
5. Physical Activity

were among the more influential features in the trained model.

## 📉 ROC Curve

The project includes an ROC curve to evaluate the classifier's performance beyond simple accuracy.

The ROC curve plots:

- True Positive Rate
- False Positive Rate

and the AUC value summarizes the model's discrimination ability.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🔬 Project Workflow

1. Data loading
2. Data preprocessing
3. Feature and target separation
4. Train-test splitting
5. Random Forest model training
6. Prediction
7. Accuracy evaluation
8. Feature importance analysis
9. ROC curve generation
10. Model performance interpretation

## 🎯 Key Learning Outcomes

Through this project, I worked with:

- Supervised classification
- Ensemble learning
- Random Forest
- Model evaluation
- ROC-AUC analysis
- Feature importance
- Data preprocessing
- Data visualization
- Interpreting machine-learning predictions

## ⚠️ Disclaimer

This project is intended for educational and machine-learning purposes only. It is not a medical diagnostic system and should not be used as a substitute for professional medical advice.

## 👩‍💻 Author

**[Your Name]**

If you found this project useful, feel free to ⭐ the repository.
