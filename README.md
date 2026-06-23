# Credit Card Fraud Detection System

## Overview
A machine learning-powered credit card fraud detection system built using Python, Flask, and Scikit-Learn.

The application analyzes transaction data and identifies potentially fraudulent transactions using a trained Random Forest model.

## Features

- Fraud Detection using Machine Learning
- CSV Dataset Upload
- Fraud Rate Analysis
- Threat Level Classification
- Security Dashboard
- Fraud Analytics Visualization
- Security Logs
- Flask Web Application

## Technologies Used

- Python
- Flask
- Pandas
- NumPy
- Scikit-Learn
- Joblib
- HTML
- CSS
- JavaScript
- Chart.js

## Project Structure

```text
CreditCardFraudDetection/
│
├── app.py
├── README.md
├── requirements.txt
│
├── models/
│   └── fraud_detector.pkl
│
├── templates/
│   └── index.html
│
└── data/
    └── creditcard.csv
```

## Installation

```bash
git clone <repository-url>
cd CreditCardFraudDetection

python -m venv venv

# Activate environment

# Windows
venv\Scripts\activate

pip install -r requirements.txt
```

## Run

```bash
python app.py
```

Open:

```text
http://127.0.0.1:5000
```

## Dataset

Kaggle Credit Card Fraud Detection Dataset

https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

## Author
Tharindi Weerasinghe
