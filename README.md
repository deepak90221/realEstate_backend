# 🧠 Real Estate Price Prediction using Machine Learning

A Machine Learning-based system that predicts property prices using various real estate features. The goal is to help buyers, sellers, and developers make informed decisions backed by data-driven insights.

## 🔍 Overview

This project leverages supervised machine learning algorithms to predict property prices based on:
- Location
- Size (square feet)
- Number of bedrooms and bathrooms
- Nearby amenities
- Age of property

It uses regression models to estimate prices and also performs feature importance analysis to understand key market drivers.

## 💡 Features

- 📊 Predict property prices based on input features
- 🔍 Visualize correlations using heatmaps and pairplots
- 🧪 Evaluate models using RMSE, R², MAE
- ⚙️ Train and test different regression algorithms
- 📈 Feature selection and preprocessing pipeline

## 📁 Dataset

- Source: [Kaggle - Real Estate Dataset](https://www.kaggle.com/)
- Format: CSV
- Size: ~10,000 records
- Attributes:
  - `location`, `area`, `bedrooms`, `bathrooms`, `price`, etc.

## 🛠️ Tech Stack

- **Language**: Python
- **Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `xgboost`
- **Environment**: Jupyter Notebook / VS Code

## 📦 Model Pipeline

```python
1. Load data
2. Handle missing values
3. Encode categorical features
4. Normalize numerical features
5. Train-Test split
6. Apply ML algorithms:
   - Linear Regression
   - Random Forest
   - XGBoost
7. Evaluate metrics
8. Save model with Pickle
