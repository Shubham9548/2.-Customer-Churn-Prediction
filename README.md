# 📊 Customer Churn Prediction – Exploratory Data Analysis & Modeling

## 📌 Project Objective
To analyze telecom customer data and build a predictive model that can classify whether a customer is likely to churn or not. The goal is to help businesses retain customers using data-driven strategies.

---

## 🧾 Dataset Description
- **Source:** Telco Customer Churn Dataset  
- **Records:** 7043 rows × 21 columns  
- **Target Variable:** `Churn` (Yes/No)  
- **Features include:** Customer demographics, tenure, service details, billing, contract type, etc.

---

## 🛠️ Tools & Technologies
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Environment:** Jupyter Notebook

---

## 📊 Project Workflow

### 🔹 1. Data Preprocessing
- Cleaned missing values in `TotalCharges`
- Converted categorical values using Label Encoding
- Performed feature selection

### 🔹 2. Exploratory Data Analysis (EDA)
- Visualized churn distribution across various features
- Analyzed patterns in customer behavior based on contract type, payment method, tenure, and charges

### 🔹 3. Model Building (Logistic Regression)
- Applied Logistic Regression for churn classification
- Used train-test split (70%-30%) for evaluation
- Evaluated using accuracy score, confusion matrix, and classification report

### 🔹 4. Model Results
- **Accuracy:** ~81%
- The model successfully predicted churn probability and revealed key contributing factors

---

## 📈 Key Insights from EDA
- Customers with **month-to-month contracts** have higher churn rate
- Customers using **electronic checks** are more likely to churn
- Churn is higher in customers with **low tenure** and **high monthly charges**
- Senior citizens and fiber optic users show higher churn

---

## ✅ Outcome
- Performed comprehensive analysis and built a working prediction model
- Generated insights that can help improve retention strategies
- Project lays the foundation for further advanced modeling and dashboard deployment

---
