# 🔐 Credit Card Fraud Detection using Machine Learning

This project demonstrates how Machine Learning can be used to detect **fraudulent credit card transactions** using a real-world dataset.

---

## 🧠 Objective

To build a classification model that can identify **fraudulent transactions** from a large pool of **highly imbalanced data**, ensuring that actual frauds are correctly detected without triggering too many false alarms.

---

## 📁 Dataset Overview

- **Rows**: 284,807 transactions
- **Features**: 
  - 30 anonymized features (V1 to V28, Time, Amount)
  - `Class`: Target variable (0 = genuine, 1 = fraud)
- **Imbalance**: Only 492 fraudulent transactions (0.17%)

📌 Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)

---

## 🔧 Tools & Libraries

- **Python** 🐍
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Scikit-learn** (Logistic Regression, Random Forest, Metrics)
- **Imbalanced-learn** (for SMOTE - optional)

---

## 🧪 Workflow

1. Load and explore the dataset
2. Check for null values and perform basic cleaning
3. Visualize class imbalance
4. Scale features (`Amount`)
5. Train-test split
6. Train a classifier (e.g., Logistic Regression / Random Forest)
7. Evaluate using:
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - Confusion matrix
8. (Optional) Use **SMOTE** to balance classes

---

## 📊 Model Performance

Evaluation is done using:
- Confusion Matrix
- Classification Report
- ROC Curve / AUC Score (optional)

Focus on **Recall** and **F1-score** for fraud detection rather than just accuracy due to class imbalance.

---

## 🔍 Results Summary

- With Random Forest, F1-score and Recall for fraud detection improved.
- SMOTE oversampling (optional) helps in balancing the dataset.
- Visualizations help in understanding misclassifications.

---

## 📷 Sample Visualizations

- Countplot showing fraud vs genuine distribution
- Correlation heatmap
- Confusion matrix heatmap after classification

---

