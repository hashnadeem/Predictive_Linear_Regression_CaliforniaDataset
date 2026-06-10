# Predictive Linear Regression Model Pipeline

## Overview

This project builds a supervised machine learning pipeline using the California Housing dataset.

The pipeline performs:

- Data Loading
- Exploratory Data Analysis (EDA)
- Missing Value Imputation
- Feature Scaling
- Categorical Encoding
- Linear Regression
- Ridge Regression
- Model Evaluation using R² Score and RMSE

---

## Dataset

California Housing Dataset from Scikit-Learn

Target Variable:

- MedHouseVal (Median House Value)

Features:

- MedInc
- HouseAge
- AveRooms
- AveBedrms
- Population
- AveOccup
- Latitude
- Longitude

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Google Colab

---

## Machine Learning Pipeline

```
Load Data
    ↓
EDA
    ↓
Train-Test Split
    ↓
Mean Imputation
    ↓
Feature Scaling
    ↓
Categorical Encoding
    ↓
Linear Regression
    ↓
Ridge Regression
    ↓
Evaluation
```

---

## Evaluation Metrics

- R² Score
- Root Mean Squared Error (RMSE)

---

## Results

The models successfully predict California housing prices.

Ridge Regression slightly improves generalization by applying L2 regularization.

---

## How to Run

1. Clone the repository

```
git clone https://github.com/hashnadeem/predictive-linear-regression-pipeline.git
```

2. Install dependencies

```
pip install -r requirements.txt
```

3. Open the notebook

```
Predictive_Linear_Regression_Pipeline.ipynb
```

---

## Author

Hashir Nadeem
