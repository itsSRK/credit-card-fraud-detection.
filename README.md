# 💳 Credit Card Fraud Detection Dashboard

## Overview
This project provides a complete solution to detect and monitor credit card fraud using machine learning. It includes an **interactive dashboard** and a **text-based report**, helping you visualize model performance and identify high-risk transactions.

## Features

### 1. Interactive Dashboard (`fraud_dashboard.py`)
- Compare **Logistic Regression** and **LightGBM** models.
- **Adjustable probability threshold** to flag transactions dynamically.
- Visualize **Confusion Matrix**, **ROC Curve**, and **Precision/Recall/F1** metrics.
- Display **Top 20 high-risk transactions** in a table with conditional color-coding.
- **Download flagged transactions** as CSV for auditing or further review.

### 2. Text-Based Report (`fraud_report.py`)
- Prints **model performance metrics**: Precision, Recall, F1-score, ROC-AUC.
- Lists **Top 20 high-risk transactions** with predicted labels and probabilities.
- Useful for non-interactive reporting or exporting results.

## Dataset
- Uses [Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) from Kaggle.
- Contains anonymized credit card transactions labeled as **Fraud (1)** or **Non-Fraud (0)**.

## Technologies & Libraries
- Python 3.x
- pandas, numpy, scikit-learn
- lightgbm
- matplotlib, seaborn
- dash, dash-bootstrap-components, plotly

## Installation
1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/credit-card-fraud-detection.git
cd credit-card-fraud-detection
