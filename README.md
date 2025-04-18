# Wind Power Generation Forecasting

![Wind Turbine](https://images.unsplash.com/photo-1508514177221-188b1cf16e9d?ixlib=rb-1.2.1&auto=format&fit=crop&w=1200&q=80)

A machine learning pipeline for forecasting wind power generation using weather data from multiple locations.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Data Description](#data-description)
- [Methodology](#methodology)
- [Results](#results)
- [Future Improvements](#future-improvements)
- [Contributing](#contributing)
- [License](#license)

## 🚀 Project Overview
This project develops predictive models for wind power generation using meteorological data from different locations. The pipeline includes:

- Data loading and merging  
- Exploratory Data Analysis (EDA)  
- Feature engineering  
- Multiple machine learning models  
- Hyperparameter tuning  
- Model evaluation  

## ✨ Features
- **Data Processing**: Merges meteorological data with proper encoding  
- **Visualizations**: Histograms, box plots, scatter plots, correlation matrices  
- **Machine Learning Models**:
  - Linear Regression (baseline model)
  - Random Forest Regressor
  - XGBoost Regressor (with hyperparameter tuning)
- **Evaluation Metrics**: MAE, MSE, and R² scores  

## 🛠 Installation
Clone the repository:
```bash
git clone https://github.com/Yasaswini-ch/Wind_Power_Generation_Forecasting.git
cd Wind_Power_Generation_Forecasting
```
Install required packages:

```bash

pip install -r requirements.txt
```
Or manually:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn xgboost
```
