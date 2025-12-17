# 🚢 Titanic Survival Prediction

This project predicts whether a passenger survived the Titanic disaster using machine learning.  
The goal is to build a classification model based on passenger features such as age, sex, ticket class, fare, and family size.

---

## 📌 Project Overview
The Titanic dataset is a classic beginner-friendly dataset used for data analysis and machine learning.  
It contains demographic and travel information for passengers aboard the RMS Titanic.

In this project, we:
- Loaded and explored the dataset  
- Handled missing values  
- Performed feature engineering  
- Converted categorical variables into numerical form  
- Split the data into training and test sets  
- Built a Logistic Regression model  
- Evaluated model performance  

---

## 📊 Dataset Features
Key columns used in prediction:
- `Pclass` — Ticket class (1st, 2nd, 3rd)
- `Sex` — Male or Female  
- `Age` — Passenger age  
- `SibSp` — Number of siblings/spouses aboard  
- `Parch` — Number of parents/children aboard  
- `Fare` — Ticket cost  
- `Embarked` — Port of embarkation (C, Q, S)
- `Survived` — Target variable (0 = No, 1 = Yes)

---

## 🧠 Machine Learning Model
We used **Logistic Regression** because it is simple, interpretable, and performs well on binary classification tasks.

### Steps:
1. Preprocess data  
2. Encode categorical variables  
3. Scale numerical features  
4. Train Logistic Regression  
5. Evaluate using accuracy, confusion matrix, etc.

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## By Rakesh Meka
