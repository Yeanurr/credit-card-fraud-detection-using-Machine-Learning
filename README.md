# Credit Card Fraud Detection Using Machine Learning

## Abstract
Credit card fraud is a growing concern, resulting in billions of dollars in losses annually. Machine learning offers a promising solution to identify fraudulent credit card transactions by analyzing patterns that indicate fraud. This project proposes the development of a machine learning model to detect such fraudulent transactions, using historical credit card transaction data. The model will be trained and evaluated on a holdout dataset to predict fraud effectively.

**Keywords**: Credit Card Fraud Detection, Fraud Detection, Fraudulent Transactions, K-Nearest Neighbors, Support Vector Machine, Logistic Regression, Decision Tree.

## Overview
With the increasing use of credit cards worldwide, ensuring the security of transactions has become a critical concern for financial institutions. In 2020, the number of reported credit card fraud cases in the U.S. surged by 44.7%. Fraud can occur in two major forms:
1. Identity thieves opening accounts under a victim's name, and
2. Stealing card information from existing accounts.

The increasing prevalence of these fraud types has motivated this project to employ machine learning techniques to detect fraudulent transactions in real-time.

## Project Goals
The primary goal of this project is to detect fraudulent credit card transactions, helping customers avoid being charged for purchases they didn’t make. Various machine learning models will be applied to detect fraud, including K-Nearest Neighbors (KNN), Logistic Regression, Support Vector Machine (SVM), and Decision Trees. By evaluating the performance of these models, we aim to identify the most effective model for fraud detection and present comparative results with performance metrics such as accuracy, precision, recall, and F1 score.

## Data Source
The dataset used for this project was sourced from Kaggle and contains transaction data from European credit card users for two days in 2013. The dataset consists of 31 attributes and 284,808 rows. Twenty-eight of these attributes are numerical and were transformed using PCA for privacy reasons. The remaining attributes include:
- **Time**: Represents the time elapsed between transactions.
- **Amount**: Denotes the transaction amount.
- **Class**: A binary variable where "1" indicates a fraudulent transaction and "0" represents a non-fraudulent transaction.

### Link to Kaggle Dataset
[Credit Card Fraud Detection Dataset on Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

## Algorithms Used
- **K-Nearest Neighbor (KNN)**: A simple yet effective algorithm for classification by identifying the closest data points.
- **Logistic Regression (LR)**: A linear model for binary classification that is efficient and interpretable.
- **Support Vector Machine (SVM)**: A powerful model for classification that works well in high-dimensional spaces.
- **Decision Tree (DT)**: A tree-based model that splits the data based on the feature that best separates the classes.

## Future Work
There are several potential improvements for this project:
- Applying the model to different datasets of varying sizes and types.
- Experimenting with different data splitting ratios and algorithms.
- Integrating additional data sources, such as telecom data, to track the location of cardholders and enhance fraud detection. For example, if a cardholder is in Dubai and a transaction occurs in Abu Dhabi, it can easily be flagged as fraudulent.

## Conclusion
The main goal of this project was to identify the most effective machine learning model for detecting credit card fraud. After building and evaluating four models, the best performing models in terms of accuracy were K-Nearest Neighbors (KNN) and Decision Trees, both achieving high accuracy scores. This model improves customer security and satisfaction by providing a more secure credit card transaction system.

## Team Members
| Student ID  | Name                      |
|-------------|---------------------------|
| 2121800642  | Most Yeanur Akter         |
| 2212717042  | Most. Aysha Siddika Sumona |
| 2131804642  | Eershan Reza Khan         |
| 2212426642  | Mohammed Nafees Imtiaz    |

## Course Information
- **Course**: CSE445 – Machine Learning
- **Supervisor**: Mohammad Shifat-E-Rabbi
- **Department**: Electrical and Computer Engineering
- **University**: North South University
