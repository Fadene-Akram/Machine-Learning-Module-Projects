# 🧠 Machine Learning Projects: Classification & Regression

This repository contains two machine learning projects aimed at deepening understanding of key ML concepts through practical application and comparative analysis.

## 📁 Projects Overview

### 1. 🏠 House Price Prediction (Regression)
**Dataset:** King County House Sales (Seattle area, May 2014 - May 2015)

**Objective:** Predict house sale prices based on various property features using regression models.

**Techniques:**
- Data Cleaning & Feature Engineering
- Normalization (MinMaxScaler)
- Model Comparison using: 
  - Decision Tree Regressor
  - Random Forest Regressor
  - K-Nearest Neighbors (KNN)
  - Naïve Bayes
  - Support Vector Predictor (SVP)
  - Artificial Neural Network (ANN)
  - Linear Regression

**Best Model:** ✅ Random Forest Regressor  
**R² Score:** `0.854`  
**Evaluation Metrics:** MSE, MAE, R²

---

### 2. 👤 Adult Income Prediction (Classification)
**Dataset:** Adult Census Income Dataset (UCI ML Repository, 1994 Census Data)

**Objective:** Classify whether an individual's income exceeds \$50K/year based on demographic and socioeconomic features.

**Challenges:**
- Class imbalance (">50K" is only ~24%)
- Mixed data types (categorical and numerical)
- Feature encoding & stratified sampling

**Models Used:**
- Random Forest Classifier
- XGBoost
- Support Vector Classifier (SVC)
- K-Nearest Neighbors (KNN)
- Gaussian Naïve Bayes
- Neural Network (MLP)
- SMOTE for class balancing

**Best Model:** ✅ XGBoost Classifier  
**Accuracy:** `0.87`  
**F1-Score:** `0.73`

---

## 🔧 Methodology (Both Projects)
- Data visualization: Histograms, box plots, heatmaps
- Preprocessing: Cleaning, feature selection, handling missing values
- Model training, hyperparameter tuning, and performance evaluation
- Comparison of algorithmic performance using appropriate metrics

## 📊 Evaluation Metrics
- **Regression:** MSE, MAE, R²
- **Classification:** Accuracy, Precision, Recall, F1-score

## 🤝 Team Members
- Akram FADENE (G02 01)
- Ahmed SAYAD (G02 01)
- Islam Mohamed Eldera ABDERREZAK (G04 01)
- Ahmed Elamine MOUCHAAL (G04 01)
- Mohammed El Amine KICHAH (G04 01)

## 📌 Conclusion
- The **Random Forest Regressor** excelled in the house price prediction task.
- The **XGBoost Classifier** was most effective for the income classification problem.
- SMOTE significantly improved model performance on the imbalanced dataset.
- Ensemble methods (Random Forest, XGBoost) consistently outperformed others.

---
