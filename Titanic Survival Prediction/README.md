# 🚢 Titanic Survival Prediction – CodSoft Data Science Internship Project

This project is part of my **Data Science Internship at CodSoft**. Using the famous Titanic dataset, I built a predictive machine learning model to determine whether a passenger survived or not, based on various features such as age, gender, passenger class, and more.

---

## 📌 Problem Statement

Predict whether a passenger survived the Titanic disaster using features like:

- Passenger class
- Sex
- Age
- Fare
- Embarked location
- SibSp (Number of siblings/spouses aboard)
- Parch (Number of parents/children aboard)

---

## 🧰 Tools & Technologies Used

- Python 🐍
- Pandas, NumPy for data handling
- Matplotlib, Seaborn for data visualization
- Scikit-learn for model building
- XGBoost for advanced boosting
- GridSearchCV for hyperparameter tuning

---

## 📊 Steps Performed

### 1. Data Cleaning
- Handled missing values in columns like `Age`, `Embarked`
- Removed unnecessary columns (`Cabin`, `Ticket`, `Name`)

### 2. Feature Engineering
- Created a new feature: `FamilySize = SibSp + Parch`
- Converted categorical variables using **Label Encoding**

### 3. Data Visualization
- Survival comparison by gender, class, fare
- Feature importance plot for model interpretability

### 4. Model Building
- Trained using **Random Forest** and **XGBoost**
- Tuned hyperparameters using **GridSearchCV**
- Evaluated using:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report

---

## 🔍 Key Insights

- **Females had a much higher survival rate** than males
- **Higher class passengers (1st class)** had better survival chances
- Age and Fare also showed a mild impact on survival

---

## ✅ Conclusion

This project helped me apply essential data science techniques:
- Cleaning and preprocessing real-world data
- Choosing and tuning machine learning models
- Interpreting results using visualizations and metrics


---

## 📌 Tags

`#DataScience` `#MachineLearning` `#TitanicPrediction` `#CodSoftInternship` `#Python` `#XGBoost` `#ScikitLearn` `#WomenInTech` `#ShadowCoders`
