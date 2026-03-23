[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1sPOw5qI0TQ4VBz-b8XNa5CM0SEnYNKcG?usp=sharing)
# 📊 Customer Churn Prediction

This project focuses on predicting whether a customer will churn (leave a service) using machine learning techniques. It is based on the Telco Customer Churn dataset and demonstrates a complete ML workflow from preprocessing to model evaluation.

---

## 🚀 Project Overview

Customer churn is a critical problem for businesses. In this project, we analyze customer data and build classification models to predict churn, helping companies take proactive retention actions.

---

## 📁 Dataset

* **Dataset Name:** Telco Customer Churn Dataset
* **Total Records:** 7043
* **Features:** 21
* **Target Variable:** `Churn` (Yes/No)

---

## ⚙️ Steps Performed

### 🔹 1. Data Preprocessing

* Removed unnecessary columns (`customerID`)
* Converted `TotalCharges` to numeric
* Handled missing values
* Encoded categorical variables using one-hot encoding
* Converted target variable into binary (0/1)

---

### 🔹 2. Exploratory Data Analysis (EDA)

* Churn distribution visualization
* Tenure vs Churn analysis
* Monthly Charges vs Churn analysis
* Correlation heatmap

---

### 🔹 3. Model Building

* Logistic Regression (with feature scaling)
* Random Forest Classifier

---

### 🔹 4. Model Evaluation

* Accuracy Score
* Classification Report
* Confusion Matrix

---

### 🔹 5. Feature Importance

* Identified top features influencing churn using Random Forest

---

## 📊 Results

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | ~82%     |
| Random Forest       | ~79%     |

---

## 📈 Key Insights

* Customers with **low tenure** are more likely to churn
* Higher **monthly charges** increase churn probability
* Contract type and service features impact retention
* Logistic Regression performed slightly better than Random Forest

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## ▶️ How to Run

1. Open the notebook in Google Colab or Jupyter Notebook
2. Upload or load the dataset
3. Run all cells step by step

---

## 📌 Future Improvements

* Hyperparameter tuning
* Try advanced models (XGBoost, Gradient Boosting)
* Deploy model using Flask or Streamlit

---

## 👩‍💻 Author

**Himanshi Garg**
B.Tech CSE (AI/ML Student)

---

## ⭐ Acknowledgment

Dataset sourced from Telco Customer Churn dataset (Kaggle)

