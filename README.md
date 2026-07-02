# 🌍 Air Quality Index (AQI) Prediction Using Machine Learning

## 📌 Project Overview

This project develops a supervised machine learning regression model to predict the **Air Quality Index (AQI)** using historical air pollutant and meteorological data. The model utilizes pollutants such as **PM2.5, PM10, NO₂, CO, O₃** along with **Temperature** and **Humidity** to forecast AQI. The project aims to support environmental monitoring, early warning systems, and data-driven decision-making for smart cities.

---

## 🎯 Objectives

- Predict Air Quality Index (AQI) using supervised machine learning.
- Perform data preprocessing and feature engineering.
- Analyze relationships between pollutants and AQI.
- Build an end-to-end machine learning pipeline.
- Evaluate model performance using regression metrics.
- Visualize insights through correlation heatmaps and feature importance.
- Support early warning systems for poor air quality.

---

## 📂 Dataset

The dataset contains historical air quality and weather information with the following features:

| Feature | Description |
|---------|-------------|
| PM2.5 | Fine particulate matter |
| PM10 | Coarse particulate matter |
| NO₂ | Nitrogen Dioxide |
| CO | Carbon Monoxide |
| O₃ | Ozone |
| Temperature | Atmospheric Temperature |
| Humidity | Relative Humidity |
| AQI | Air Quality Index (Target Variable) |

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Project Workflow

### 1. Data Preprocessing
- Load dataset
- Handle missing values
- Feature selection
- Data normalization
- Train-Test Split

### 2. Exploratory Data Analysis (EDA)
- Dataset overview
- Missing value analysis
- Correlation matrix
- Correlation heatmap
- Distribution analysis

### 3. Feature Engineering
- Data scaling
- Preprocessing pipeline
- Feature transformation

### 4. Model Development
- Random Forest Regression
- Model training
- Prediction

### 5. Model Evaluation
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

### 6. Visualization
- Correlation Heatmap
- Actual vs Predicted AQI
- Residual Distribution
- Feature Importance

### 7. Early Warning System
The predicted AQI is classified into:
- 🟢 Good
- 🟡 Moderate
- 🟠 Poor
- 🔴 Very Poor
- ☠️ Severe

---

## 📈 Machine Learning Pipeline

```
Historical Air Quality Data
           │
           ▼
     Data Preprocessing
           │
           ▼
   Feature Engineering
           │
           ▼
    Train-Test Split
           │
           ▼
 Random Forest Regressor
           │
           ▼
     AQI Prediction
           │
           ▼
   Performance Evaluation
           │
           ▼
 Early Warning Classification
```

---

## 📊 Visualizations Included

- Correlation Matrix
- Correlation Heatmap
- Actual vs Predicted AQI Plot
- Residual Distribution Plot
- Feature Importance Graph

---

## 📏 Evaluation Metrics

The model is evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score
- XG Boost

These metrics measure the prediction accuracy and overall performance of the regression model.



## 📌 Results

- Successfully developed an end-to-end machine learning pipeline for AQI prediction.
- Identified the most influential pollutants affecting AQI using feature importance analysis.
- Visualized pollutant relationships through correlation heatmaps.
- Built an early warning classification system for different AQI levels.
- Demonstrated the application of supervised machine learning in environmental monitoring.

---
##  Dataset link 
www.kaggle.com/datasets/sohails07/delhi-weather-and-aqi-dataset-2025

