# NBA Game Outcome Prediction Model

This repository contains a machine learning model built to predict the outcome of NBA games. The model is designed as a binary classification task, where:

1 = Win

0 = Loss

## Model Overview
**Model Type:** Multiple Logistic Regression **(MLR)** & Random Forest Classifier

**Target Variable:** Game Outcome **(Win = 1, Loss = 0)**

**Evaluation Metrics:** Accuracy, AUC-ROC Curve, Precision, Recall, F1-Score

**Validation Method:** K-Fold Cross Validation

## Techniques Used
Binary Classification using MLR & RandomForestClassifier from **sklearn.ensemble**

**K-Fold Cross Validation** for robust model evaluation.

**ROC Curve** and **AUC Score** to evaluate the model's ability to separate classes.

**Feature Engineering** to include relevant game, team, and player stats.

**Data Preprocessing** including handling missing values, encoding, and scaling.
