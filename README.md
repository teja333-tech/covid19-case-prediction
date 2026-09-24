# COVID19-ML-Project
COVID-19 data analysis and confirmed case prediction using Linear Regression.

## Overview

This project performs data analysis and machine learning on COVID-19 daily case data. The dataset contains country-wise information on confirmed cases, deaths, recovered cases, and active cases.

The project includes data preprocessing, exploratory data analysis, feature engineering, visualization, and Linear Regression for confirmed case prediction.

## Objectives

- Load and inspect the COVID-19 dataset
- Handle duplicate and missing values
- Perform data preprocessing
- Calculate death and recovery rates
- Analyze COVID-19 trends over time
- Create visualizations of confirmed cases and deaths
- Perform feature engineering using previous-day and previous-week cases
- Build a Linear Regression model
- Evaluate the model using MAE, RMSE, and R²

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab
- Jupyter Notebook

## Machine Learning Model

**Linear Regression**

The model uses previous COVID-19 case information as features to predict confirmed cases.

### Evaluation Metrics

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

The actual metric values are available in the notebook output.

## Project Structure

```text
COVID19-ML-Micro-Project/
│
├── COVID19_ML_Micro_Project.ipynb
├── covid19_ml_micro_project_raw.csv
└── README.md


**WORK FLOW**

Data Loading
     ↓
Data Inspection
     ↓
Data Cleaning
     ↓
Exploratory Data Analysis
     ↓
Feature Engineering
     ↓
Train-Test Split
     ↓
Linear Regression
     ↓
Model Prediction
     ↓
Model Evaluation
     ↓
Visualization


## Google Colab

 [Open Project in Google Colab](https://colab.research.google.com/drive/1LxryuXRIe2l2CMz9rgzsreQm0jatARA6#scrollTo=d2fb89bf)
