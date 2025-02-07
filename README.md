# Predicting Customer Churn in a Telecommunications Company

## Overview
This project predicts customer churn in a telecommunications company using machine learning. Identifying at-risk customers enables proactive retention strategies, reducing churn and increasing satisfaction.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Modeling](#modeling)
- [Results](#results)
- [Contributors](#contributors)

## Introduction
Customer churn is a major challenge for telecom companies. This project develops a predictive model using:
- Data preprocessing
- Feature selection
- Model training & evaluation
- Hyperparameter tuning

## Dataset
Using the Telco Customer Churn Dataset:
- **7,043 rows, 21 columns**
- **Target:** Churn (Yes/No)
- **Features:** Customer info, services, and account details

## Data Preprocessing
- **EDA:** Checked for missing values, visualized distributions
- **Cleaning:** Converted `TotalCharges` to float, dropped `customerID`
- **Encoding:** One-Hot Encoding for categorical features
- **Scaling:** Standardized numerical features
- **Feature Selection:** Removed highly correlated variables
- **Train-Test Split:** 80-20 split

## Modeling
### Algorithms Used:
- Decision Tree, Random Forest, SVM, Neural Network, Logistic Regression, K-Means (unsupervised)

### Hyperparameter Tuning:
- Grid Search with 5-fold cross-validation
- Evaluation Metrics: **F1-Score & Recall**

## Results
| Model             | Accuracy | Precision | Recall | F1 Score |
|------------------|----------|-----------|--------|----------|
| Decision Tree    | 73.0%    | 49.0%     | 80.0%  | 61.0%    |
| SVM             | 75.0%    | 52.0%     | 84.0%  | 64.0%    |
| Random Forest   | 76.0%    | 53.0%     | 83.0%  | 65.0%    |
| Neural Network  | 81.0%    | 65.0%     | 60.0%  | 62.0%    |

- **Random Forest** performed best overall (**F1-Score: 65.0%**)
- **SVM** had slightly higher recall (**84.0%**)
- **Neural Network** had the highest accuracy (**81.0%**) but lower recall

## Contributors
**Aadit Shah**  
*Computer Science, FLAME University*  
📧 aadit.shah@flame.edu.in
