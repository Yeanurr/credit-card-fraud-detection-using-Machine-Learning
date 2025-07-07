# 💳 Credit Card Fraud Detection with Machine Learning



## 📌 What This Project Does

This project helps detect fraud in credit card transactions using machine learning.  
We use real transaction data and train models that can predict whether a transaction is **safe** or **fraud**.

### 🔧 Steps We Followed:
- Cleaned and prepared the data  
- Handled **imbalanced data** using SMOTE (because fraud cases are very few)  
- Trained multiple models like:
  - Logistic Regression  
  - Decision Tree  
  - Random Forest  
  - XGBoost  
  - SVM  
- Compared their performance using common metrics  
- Visualized the results for better understanding

---

## 🔍 Main Features

- Handles imbalanced data using SMOTE  
- Tests several popular ML models  
- Measures Accuracy, Precision, Recall, F1 Score, and ROC-AUC  
- Can be reused for other fraud or anomaly detection problems  

---

## 🧠 Tools & Libraries Used

- **Python 3.8+**
- **Jupyter Notebook**
- `Pandas` and `NumPy` – for working with data  
- `Scikit-learn` – for ML models  
- `Imbalanced-learn` – for SMOTE  
- `Matplotlib` and `Seaborn` – for graphs  

---

## 📁 About the Dataset

- **Source**: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)  
- **Total transactions**: 284,807  
- **Fraud cases**: Only 492 (~0.17%)  
- **Note**: Most columns are anonymous due to privacy (named V1 to V28)

---

## 📊 Model Evaluation

We measured how well the models performed using:
- Accuracy  
- Precision  
- Recall  
- F1 Score  
- ROC-AUC  

✅ **Random Forest** and **XGBoost** gave the best results after applying SMOTE.

---

## 👨‍💻 Team Members

| Student ID     | Name                          |
|----------------|-------------------------------|
| 2121800642     | Most Yeanur Akter             |
| 2212717042     | Most. Aysha Siddika Sumona    |
| 2131804642     | Eershan Reza Khan             |
| 2212426642     | Mohammed Nafees Imtiaz        |

**Course**: CSE445 – Machine Learning  
**Supervisor**: Mohammad Shifat-E-Rabbi  
**Department**: Electrical and Computer Engineering  
**University**: North South University  


