# Customer Churn Prediction

## Project Overview

This project predicts whether a customer is likely to leave (churn) or stay with a subscription-based service using Machine Learning.

The model is trained on historical customer data, including demographics, subscription details, and service usage.

---

## Features

- Load customer churn dataset
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Encode categorical variables
- Train multiple Machine Learning models
- Compare model performance
- Predict customer churn
- Save the best model using Joblib

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib
- Jupyter Notebook

---

## Machine Learning Models

- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

---

## Dataset

Telco Customer Churn Dataset

Source:
https://www.kaggle.com/datasets/blastchar/telco-customer-churn

---

## Project Structure

Customer_Churn_Prediction/

├── dataset/

│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv

├── model/

│   ├── customer_churn_model.pkl

│   └── scaler.pkl

├── churn_prediction.ipynb

├── README.md

└── requirements.txt

---

## Workflow

1. Load the dataset
2. Clean the data
3. Perform Exploratory Data Analysis (EDA)
4. Encode categorical features
5. Split data into training and testing sets
6. Train Logistic Regression
7. Train Random Forest
8. Train Gradient Boosting
9. Evaluate all models
10. Save the best model
11. Predict customer churn

---

## Results

The models were evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report

Among the tested models, the one with the highest accuracy was selected as the final model.

---

## How to Run

1. Clone the repository

2. Install dependencies

pip install -r requirements.txt

3. Open

churn_prediction.ipynb

4. Run all notebook cells.

---

## Future Improvements

- Hyperparameter tuning
- Feature engineering
- Deploy using Flask or Streamlit
- Build a web interface
- Use XGBoost or LightGBM for better accuracy

---

## Author

Riya Tyagi