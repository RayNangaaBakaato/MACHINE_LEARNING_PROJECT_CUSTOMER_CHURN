# MACHINE_LEARNING_PROJECT_CUSTOMER_CHURN

# 🧠 Predicting Customers Churn with Machine Learning

### 📍 Real-World Classification Project | Data Science Portfolio by  Ray NANGAA BAKAATO MANGALAZA

## 🚀 Project Overview

In this end-to-end machine learning project, I tackled a real-world customer retention problem using classification modeling. The goal was to accurately **predict customer churn** — identifying which customers are most likely to leave a service or subscription based on their behavior, demographics, and interactions.

I implemented this using the **RAY Framework**, which guides projects from raw data to meaningful business insights, emphasizing model performance, interpretability, and communication.

---

## 🎯 Problem Statement

The challenge was to build a model that can **predict whether a customer will churn** (yes/no) based on features like **tenure, monthly charges, service types, and payment method**.

Understanding churn helps businesses take **preventive actions**, increase **customer retention**, and reduce **revenue loss**.

---

## 📊 Dataset Summary

- ✅ Rows: `7,043`
- ✅ Features: `21` columns (after cleaning)
- ✅ Target: `Churn` (binary: Yes/No)
- ✅ Source: [Telco Customer Churn dataset](https://www.kaggle.com/blastchar/telco-customer-churn)

---

## 🛠️ Tools & Libraries Used

- **Python**, **Pandas**, **NumPy**
- **Scikit-learn**, **XGBoost**, **Matplotlib**, **Seaborn**
- **SHAP** for model explainability
- **Joblib** for saving models
- **Jupyter Notebook** for reproducibility and storytelling

---



# 🔍 Key Steps & Highlights

### 1. Exploratory Data Analysis (EDA)
	•	Uncovered class imbalance in churn (~27%)
	•	Explored correlations between tenure, charges, and churn
	•	Detected feature leakage and handled categorical encoding

### 2. Model Training & Comparison
	•	Trained multiple models: Logistic Regression, Random Forest, XGBoost, KNN, SVM
	•	Evaluated using AUC Score for better insight with imbalanced data
	•	Selected top 3 models for tuning

### 3. Hyperparameter Tuning
	•	Tuned models using GridSearchCV and RandomizedSearchCV
	•	Best model: ✅ Random Forest with AUC = 0.91

### 4. Model Explainability
	•	Used feature importance and SHAP to explain model decisions
	•	Top churn predictors: Contract Type, Tenure, Monthly Charges

### 5. Packaging & Deployment
	•	Saved model using joblib
	•	Notebook is clean, reproducible, and designed for technical portfolio showcase

⸻

## 📈 Results Summary

### Model	AUC Score
- Logistic Regression	0.84
- Random Forest	0.91 ✅
- XGBoost	0.89

The Random Forest model gave the best balance of accuracy and interpretability. It allows business users to understand why churn is likely to happen, not just that it will.

⸻

## 💡 What I Learned
	•	How to run a complete ML pipeline from EDA to deployment
	•	Importance of proper evaluation metrics (AUC over accuracy)
	•	How to explain model decisions with SHAP
	•	How to communicate complex workflows in a clean, professional notebook

⸻

📬 Let’s Connect

I’d love to hear from you!

Contact me: 
- LinkedIn: www.linkedin.com/comm/mynetwork/discovery-see-all?usecase=PEOPLE_FOLLOWS&followMember=ray-n-bakaato-mangalaza-292b93169
- Email: raybakaato@gmail.com
- Phone: +39 351 4727302











