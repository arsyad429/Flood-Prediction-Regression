# 🌊 Flood Probability Prediction using Regression

This project aims to predict flood probability using regression models based on environmental and hydrological data. The models are evaluated using common regression metrics: MAE, MSE, and R².

## 📌 Project Overview

Floods are one of the most frequent natural disasters that threaten both rural and urban areas. This project builds a machine learning model to estimate the probability of flooding, which can be useful for early warning systems or urban planning.

## 📊 Models Used

| Model                     | MAE     | MSE     | R²       |
|--------------------------|---------|---------|----------|
| **Lars**                 | 0.8065  | 0.9982  | 0.0008   |
| **Linear Regression**    | 0.3291  | 0.1713  | 0.8285   |
| **GradientBoostingRegressor** | 0.5127  | 0.3805  | 0.6191   |

From the results, **Linear Regression** performed best with the lowest error and highest R² score.

## 🧠 Features

- Multiple regression models for comparison
- Performance evaluation using:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - R² Score
- Data preprocessing and feature selection pipeline
- Model training and prediction on flood-related data


## 🚀 How to Run

1. Clone the repository
2. Install the dependencies
3. jupyter notebook Flood_Prediction_Regression.ipynb
