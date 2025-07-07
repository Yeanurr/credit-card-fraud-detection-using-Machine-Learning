
# 💳 Credit Card Fraud Detection Using Machine Learning

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> **🔓 Open Source | MIT License**  
> This project was developed as part of the **CSE445 Machine Learning** course at **North South University**. The aim is to detect fraudulent credit card transactions using various machine learning models and evaluate their effectiveness on real-world financial data.

---

## 📌 Project Overview

The goal of this project is to build a robust **Fraud Detection System** using **supervised machine learning techniques**, capable of identifying fraudulent transactions from highly imbalanced datasets. The key steps include:

- Preprocessing and analyzing transactional data  
- Addressing class imbalance using **SMOTE (Synthetic Minority Oversampling Technique)**  
- Training and comparing multiple ML models  
- Evaluating each model’s performance on standard classification metrics  
- Visualizing fraud detection results and model effectiveness  

---

## 🔍 Key Features

- **Imbalanced Data Handling**: Applies SMOTE to synthesize minority class samples and balance the dataset.  
- **Model Comparisons**: Includes models such as Logistic Regression, Decision Trees, Random Forest, XGBoost, and SVM.  
- **Performance Metrics**: Calculates Accuracy, Precision, Recall, F1-Score, ROC-AUC for fair model comparison.  
- **Reusability**: The data preparation and model pipeline can be adapted to other anomaly detection domains (e.g., insurance fraud, network intrusion).  

---

## 🧠 Technologies Used

### Machine Learning & Data Processing
- `Scikit-learn` – ML algorithms & metrics  
- `Imbalanced-learn` – SMOTE technique  
- `Pandas` & `NumPy` – Data manipulation  
- `Matplotlib` & `Seaborn` – Data visualization  

### Development Tools
- Python 3.8+  
- Jupyter Notebook  
- Git & GitHub  

---

## 📁 Dataset

- **Source**: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)  
- **Description**: Real credit card transactions by European cardholders.  
- **Size**: 284,807 transactions  
- **Fraud Cases**: 492 transactions (~0.17%) labeled as fraud  

---

## 📈 Performance Evaluation

The models are evaluated on the following metrics:

- Accuracy  
- Precision  
- Recall  
- F1-Score  
- ROC Curve / AUC  

> 🏆 **Best performance** was achieved using **Random Forest** and **XGBoost** classifiers, enhanced by the **SMOTE** technique.

---

## 👥 Team Members

| Student ID     | Name                          |
|----------------|-------------------------------|
| 2121800642     | Most Yeanur Akter             |
| 2212717042     | Most. Aysha Siddika Sumona    |
| 2131804642     | Eershan Reza Khan             |
| 2212426642     | Mohammed Nafees Imtiaz        |

**Course**: CSE445 – Machine Learning  
**Faculty Supervisor**: Mohammad Shifat-E-Rabbi  
**Department**: Department of Electrical and Computer Engineering  
**University**: North South University  

---

## 📜 License

This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for more information
