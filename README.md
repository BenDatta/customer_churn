# 📉 Telco Customer Churn Prediction 🔍

Predicting customer churn using machine learning on the Telco dataset 📊.

---

## 🧠 Project Overview

This project builds a machine learning model to predict whether a customer will churn based on their service usage, contract type, and demographic information. It includes data preprocessing, exploratory data analysis, model training, and evaluation using Logistic Regression.

---

## 📁 Dataset

The dataset is from IBM Sample Data: `WA_Fn-UseC_-Telco-Customer-Churn.csv`

- 📦 7043 customers
- 🏷️ 21 features
- 🎯 Target: `Churn` (Yes/No)

---

## 🛠️ Tech Stack

- 🐍 Python (Pandas, NumPy, Scikit-learn)
- 📈 Matplotlib & Seaborn (for EDA)
- 🤖 Scikit-learn (Logistic Regression)
- 🧹 DictVectorizer (for encoding categorical features)

---

## 📊 Key Insights

- Customers with **month-to-month contracts** churn more than those with long-term contracts 📆
- **Short tenure** and **high monthly charges** are strong indicators of churn ⚠️
- Features like `OnlineSecurity`, `TechSupport`, and `Contract` are most predictive 🧠

---

## 🚀 Model Performance

| Dataset     | Accuracy 📈 |
|-------------|-------------|
| Validation  | 80.3% ✅     |
| Test        | 81.4% ✅     |

- Model: Logistic Regression 🔍
- Evaluation Metric: Accuracy

---

## 🧪 How to Use

1. Clone the repo 📁  
```bash
git clone https://github.com/your-username/telco-churn-prediction.git
cd telco-churn-prediction
