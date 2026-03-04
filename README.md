# 🏦 Loan Approval Prediction Using Machine Learning

## 📌 Project Overview

This project builds and compares multiple Machine Learning classification models to predict whether a loan application will be approved based on applicant financial and credit-related features.

The model is trained using the dataset:

📂 **Dataset File:** `credit (3).csv`

The objective is to identify the most accurate model for assisting financial institutions in automating loan approval decisions and reducing credit risk.

---

## 📊 Dataset Description

The dataset (`credit (3).csv`) contains structured applicant financial data including:

- Age
- Income
- Years at Job
- Credit Score
- Number of Credit Cards
- Loan Approval Status (Target Variable)

### 🎯 Target Variable
- `approved = 1` → Loan Approved  
- `approved = 0` → Loan Rejected  

This is a **binary classification problem**.

---

## 🧠 Machine Learning Approach

### 1️⃣ Data Preparation
- Loaded dataset from `credit (3).csv`
- Checked for missing values
- Performed feature selection
- Split data into training (80%) and testing (20%) sets

---

### 2️⃣ Models Implemented

The following classification algorithms were trained and evaluated:

- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  
- Gradient Boosting Classifier  
- AdaBoost Classifier  
- K-Nearest Neighbors  
- Support Vector Classifier  
- Naive Bayes  

---

## 📈 Model Performance Comparison

| Model                     | Accuracy |
|----------------------------|----------|
| Logistic Regression        | 72%      |
| Decision Tree              | 94%      |
| Random Forest              | 95%      |
| Gradient Boosting          | 95%      |
| AdaBoost                   | 95%      |
| K-Nearest Neighbors        | 84%      |
| Support Vector Classifier  | 73%      |
| Naive Bayes                | 88%      |

### 🏆 Best Performing Models
- Random Forest
- Gradient Boosting
- AdaBoost

These ensemble models achieved the highest accuracy (95%), showing strong performance on structured financial data.

---

## 🔍 Key Insights

- Ensemble methods outperform linear models in this dataset.
- Tree-based models effectively capture nonlinear financial patterns.
- Credit-related attributes significantly influence approval decisions.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn

---

## ▶️ How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/loan-approval-prediction.git
