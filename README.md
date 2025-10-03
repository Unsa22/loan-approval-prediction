# Loan Approval Prediction (Task 3 - Internship)

## 📌 Project Overview
This project predicts **loan approval status** using classification models on the Loan Approval dataset.  
The dataset is imbalanced, so **SMOTE** was applied to balance the classes.

---
## Dataset
Name: Loan Data
Source: Kaggle – Loan Data (https://www.kaggle.com/datasets/itssuru/loan-data/data)
File in Repo: loan_data.csv

---
## 🛠️ Steps Performed
1. Data Cleaning – handled missing values and duplicates.  
2. Encoding – categorical variables converted with Label Encoding & One-Hot Encoding.  
3. Exploratory Data Analysis (EDA) – correlations, class distribution.  
4. Feature Scaling – applied StandardScaler.  
5. Model Training:
   - Logistic Regression  
   - Decision Tree Classifier  
   - Random Forest Classifier  
6. Evaluation – Precision, Recall, F1-score, Confusion Matrix.  
7. Bonus – Applied **SMOTE** for imbalanced dataset.  

---

## 📊 Results

### Logistic Regression
- Accuracy: **89%**
- F1-score (Class 1): **0.76**

### Decision Tree
- Accuracy: **90%**
- F1-score (Class 1): **0.78**

### Random Forest
- Accuracy: **93%**
- F1-score (Class 1): **0.83**

### Random Forest with SMOTE
- Accuracy: **100%**
- Perfect Precision, Recall, and F1-score. 🎯

---

## 📂 Deliverables
- Jupyter Notebook (`loan_prediction.ipynb`)
- Dataset (`loan_data.csv`)
- Screenshots of Results (Confusion Matrices, Reports, Pie Charts)

---

## 🚀 How to Run
```bash
pip install -r requirements.txt
jupyter notebook loan_prediction.ipynb
