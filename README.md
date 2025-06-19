📊 Customer Churn Prediction – Exploratory Data Analysis & Modeling
📌 Project Objective
To analyze telecom customer data and build a predictive model that can classify whether a customer is likely to churn or not. The goal is to help businesses retain customers using data-driven strategies.

🧾 Dataset Description
Source: Telco Customer Churn Dataset

Records: 7043 rows × 21 columns

Target Variable: Churn (Yes/No)

Features include: Customer demographics, tenure, service details, billing, contract type, etc.

🛠️ Tools & Technologies
Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

Environment: Jupyter Notebook

📊 Project Workflow

🔹 1. Data Preprocessing
Cleaned missing values in TotalCharges

Converted categorical values using Label Encoding

Feature selection for model input

🔹 2. Exploratory Data Analysis (EDA)
Analyzed churn distribution across contract types, payment methods, tenure, and monthly charges

Visualized key patterns using count plots, violin plots, and heatmaps

🔹 3. Model Building (Logistic Regression)
Applied Logistic Regression to predict churn

Split data into train-test sets (70-30)

Used accuracy_score, confusion_matrix, and classification_report to evaluate model performance

🔹 4. Model Results
Accuracy: ~81%

Findings: The model was able to distinguish churn vs non-churn customers reasonably well

Set the foundation for deploying more advanced models (Random Forest, XGBoost, etc.)

📈 Key Insights from EDA
Month-to-month contracts show significantly higher churn

Higher churn observed among customers using electronic check payments

Short tenure and high monthly charges → more churn probability

Senior citizens and Fiber optic users churn more than others

✅ Outcome
Successfully combined EDA and machine learning for churn prediction

Delivered actionable business insights along with a working model

The project can be extended into a full deployment pipeline or dashboard integration
