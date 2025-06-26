# 🎬 Movie Rating Prediction using Machine Learning

## 📌 Project Description

This project predicts movie ratings using machine learning techniques based on features like genre, cast, director, budget, and other metadata. It helps stakeholders make informed decisions about production and marketing before a movie’s release.

---

## 🧾 Dataset Overview

The dataset includes:
- 🎥 Movie Title  
- 🏷️ Genre  
- 🎭 Cast & Director  
- 💰 Budget & Revenue  
- ⭐ IMDb/User Ratings (Target)

> 🔍 Note: Preprocessing includes null value treatment, label encoding, and scaling.

---

## ⚙️ Technologies Used

- **Python**
- **Jupyter Notebook**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Scikit-learn** (Linear Regression, metrics)

---

## 🧠 Machine Learning Approach

- **Model Used**: Linear Regression
- **Metrics**: 
  - R² Score  
  - Mean Absolute Error (MAE)  
  - Mean Squared Error (MSE)

---

## 🔄 Workflow

1. **Data Cleaning**
   - Removed duplicates & handled missing values
2. **Feature Engineering**
   - Encoded categorical features
   - Feature selection
3. **Splitting Dataset**
   - 80% training and 20% testing
4. **Model Training**
   - Used Linear Regression
5. **Model Evaluation**
   - Evaluated using R² Score and plotted results

---

## 📈 Sample Output

```text
R² Score: 0.66  
MAE: 0.52  
Predicted Rating Example: 7.3
