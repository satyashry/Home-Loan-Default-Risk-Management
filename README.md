# Home Loan Default Risk Management

## Project Overview

This project aims to analyze customer loan application data and build a machine learning model to identify potential loan defaulters. The objective is to help financial institutions improve risk management and make better lending decisions.

## Problem Statement

Develop a predictive model to identify customers who are likely to default on a home loan based on demographic, financial, and employment-related information.

## Domain

Banking

## Dataset

The project uses the **Home Credit Loan Default Dataset** provided by DataMites.

Main dataset used:

* `application_train.csv`

Target Variable:

* `TARGET = 1` → Defaulter
* `TARGET = 0` → Non-Defaulter

## Project Workflow

1. Data Loading and Understanding
2. Missing Value Analysis
3. Data Cleaning and Preprocessing
4. Exploratory Data Analysis (EDA)
5. Feature Encoding
6. Model Building
7. Model Evaluation
8. Model Comparison
9. Conclusion

## Machine Learning Models Used

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* Logistic Regression with SMOTE

## Results

Among all models, **Logistic Regression** provided the best performance for identifying loan defaulters based on Recall and F1-Score.

### Best Model Performance

* Accuracy: 68.87%
* Precision: 16.01%
* Recall: 67.27%
* F1 Score: 25.87%

## Key Challenges

* High percentage of missing values
* Class imbalance in target variable
* Presence of outliers
* Model evaluation on imbalanced data

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Imbalanced-learn (SMOTE)
* Jupyter Notebook

## Repository Structure

```text
HomeLoanDefault/
│
├── data/
├── home_loan_def.ipynb
├── README.md
└── .gitignore
└── license

```

## Author

**P Satyashry**

GitHub: https://github.com/satyashry
LinkedIn: https://www.linkedin.com/in/satyashry/

## Project Status

Completed ✅
