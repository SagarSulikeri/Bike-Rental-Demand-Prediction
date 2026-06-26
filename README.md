# 🚲 Bike Rental Demand Prediction using Machine Learning

## 📌 Project Overview

This project predicts **daily bike rental demand** based on environmental and seasonal factors using Machine Learning. The objective is to analyze historical bike-sharing data, perform exploratory data analysis (EDA), build multiple regression models, compare their performance, and identify the best model for deployment.

This project was completed as part of the **PRCP-1018 Bike Rental Predictive Modelling** assignment. :contentReference[oaicite:0]{index=0}

---

## 🎯 Problem Statement

The project consists of two major tasks:

- Perform comprehensive Exploratory Data Analysis (EDA).
- Build predictive machine learning models to estimate daily bike rental counts based on weather and seasonal conditions.

---

## 📂 Dataset

The dataset contains information collected from a bike-sharing system.

### Features

| Feature | Description |
|----------|-------------|
| instant | Record index |
| dteday | Date |
| season | Season of the year |
| yr | Year (2011 or 2012) |
| mnth | Month |
| holiday | Holiday indicator |
| weekday | Day of week |
| workingday | Working day indicator |
| weathersit | Weather condition |
| temp | Normalized temperature |
| atemp | Feeling temperature |
| hum | Humidity |
| windspeed | Wind speed |
| casual | Casual users |
| registered | Registered users |
| cnt | Total bike rentals (Target Variable) |

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

## 📊 Exploratory Data Analysis

The notebook includes:

- Data inspection
- Missing value analysis
- Statistical summary
- Distribution plots
- Correlation heatmap
- Seasonal analysis
- Monthly rental trends
- Weather impact analysis
- Holiday vs Working Day comparison
- Temperature and Humidity analysis
- Feature relationships

---

## 🤖 Machine Learning Models

The following regression models were implemented:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

Each model was evaluated using standard regression metrics.

---

## 📈 Model Evaluation

The models were compared using:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

The best-performing model was selected based on prediction accuracy and generalization performance.

---

## 📁 Project Structure
