# 🧠 Depression Detection – Binary Classification Project

This project was part of the **Kaggle Playground Series**, where the goal was to predict whether an individual is experiencing depression based on survey and lifestyle data.

Using multiple machine learning models and structured preprocessing steps, I built a binary classification pipeline that achieved **92% accuracy** with the CatBoost model.

---

## 📊 Overview

- **Type:** Binary Classification  
- **Tools:** Python, Pandas, NumPy, Scikit-learn, XGBoost, CatBoost, LightGBM  
- **Accuracy:** 92% (CatBoost)

---

## 🔧 Workflow Summary

### 🧹 1. Data Cleaning & Preprocessing
- Handled missing values using `pandas` and cleaned inconsistencies across features
- Performed feature engineering (e.g., mapping values for *Sleep Duration*)
- Removed irrelevant or redundant columns for better signal-to-noise ratio

### 🔠 2. Categorical Encoding
- Applied `LabelEncoder` to transform categorical features
- Ensured consistent encoding across train/test splits

### 🧠 3. Model Building & Evaluation
Compared several models for classification:
- **Logistic Regression** (baseline)
- **XGBoost**, **CatBoost**, and **LightGBM** for boosted performance

**Best Model:**  
- **CatBoost** achieved **92% accuracy**, outperforming other methods on the validation set  
- Chosen for its handling of categorical features and ease of tuning

---

## 📁 Files Included

- `mental_health_data.ipynb`: Main notebook with preprocessing, modeling, and results  
- `train.csv, test.csv`: Input dataset (included for convenience)  

---

## 🚀 How to Run

```bash
git clone https://github.com/PranjaliD11/Depression_Detection.git
cd Depression_Detection
open depression_detection.ipynb
