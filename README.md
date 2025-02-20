# HELOC Credit Risk Prediction

## 📌 Project Description
This project aims to predict **credit risk** using the **HELOC (Home Equity Line of Credit) dataset**. It employs a pre-trained **XGBoost model** for predictions and uses **SHAP analysis** for explainability.

## 🚀 Features
- **Preprocessing:** Handling missing values and outliers.
- **Credit Risk Prediction:** Utilizing an XGBoost model.
- **Explainability:** Using SHAP values to understand model decisions.

## 📂 Dataset
- The dataset includes financial features related to HELOC applications.
- Missing values represented by `-9, -8, -7` are replaced with NaN.
- Features with more than **15% missing values** are dropped.


## 🔍 Model & Explanation
- **XGBoost** is used for credit risk classification.
- **SHAP (SHapley Additive Explanations)** is used for feature importance and decision explainability.
- **Beeswarm Plots** are generated for visual interpretation of model behavior.

## 📊 SHAP Analysis
SHAP values help to explain the model’s predictions by showing how each feature contributes to the output.
