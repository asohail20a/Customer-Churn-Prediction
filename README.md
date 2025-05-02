# Customer Churn Prediction

## 📌 Overview

This project aims to predict customer churn (i.e., whether a customer will leave or stay) using machine learning.
Accurately predicting churn helps companies take early action to retain valuable customers.

## 🧾 Dataset

The dataset (`churn_dataset.xlsx`) includes customer information such as:

- Age
- Gender
- Various features related to customer behavior
- Churn status (Yes/No)

Data preprocessing steps included:
- Converting categorical variables to numeric (e.g., Gender and Churn columns)
- Handling missing values
- Splitting data into training and testing sets

## 🧠 Model Used

We applied the **Gaussian Naive Bayes** algorithm to classify customers into churners and non-churners. The steps include:

- Feature selection
- Model training using `GaussianNB` from `sklearn`
- Evaluation using **accuracy score**

## ✅ Results

- The model achieved an accuracy of **80%**.
- Predictions were made on a test set using a 70/30 train-test split.

## 📊 Tools & Libraries

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## 🔧 How to Run

1. Clone the repo
2. Make sure you have the dataset `churn_dataset.xlsx` in the same directory
3. Run the notebook
