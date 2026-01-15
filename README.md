# 📊 SaaS Customer Churn Prediction (Synthetic Data)

## 🔍 Problem Statement
Predicting customer churn is critical for SaaS businesses to retain customers and minimize revenue loss.  

This project uses **synthetic customer data** to simulate real-world scenarios and build predictive ML models.  

**Business Impact:**  
- Identify at-risk customers early  
- Improve retention strategies  
- Optimize marketing and support efforts  

---

## 📂 Dataset
- **Type:** Synthetic CSV data simulating SaaS customer metrics  
- **Target Variable:** `Churn` (Yes / No)  
- **Features:** Customer demographics, subscription info, usage patterns  

---

## 🧠 Project Workflow

### 1️⃣ Problem Definition
- Binary classification: Predict whether a customer will churn.

### 2️⃣ Data Understanding (EDA)
- Explored feature distributions and correlations  
- Visualized churn patterns across simulated segments using **Seaborn & Matplotlib**

### 3️⃣ Data Cleaning
- Checked for missing or inconsistent values  
- Verified correct data types  
- Handled outliers and duplicates

### 4️⃣ Feature Engineering
- Encoded categorical variables  
- Created derived features (e.g., tenure categories, usage ratios)  
- Normalized numeric features

### 5️⃣ Feature Selection
- Removed irrelevant or highly correlated features  
- Focused on features contributing most to model performance

### 6️⃣ Train–Test Split
- Split dataset into training and testing sets

---

## 🤖 Models Used
- **Logistic Regression** – Baseline classifier  
- **Random Forest Classifier** – Standard implementation  

---

## 📊 Model Evaluation
- Metrics used to evaluate model performance:
  - Accuracy  
  - Precision  
  - Recall  
  - F1-Score  
- Confusion matrix used for visualization  

---

## ❌ Error Analysis
- Examined false positives and false negatives  
- Identified features contributing to misclassifications  

---

## 🛠️ Tech Stack
- **Python**  
- **Pandas, NumPy**  
- **Seaborn, Matplotlib**  
- **Scikit-learn**  
- **Git & Bash**

---

## 🌟 Key Learnings
- Practiced end-to-end ML workflow on synthetic datasets  
- Learned basic model selection and evaluation  
- Gained insights into churn prediction for SaaS businesses  

---

✨ *This project demonstrates a complete ML workflow from synthetic data exploration to model evaluation using logistic regression and random forest.*
