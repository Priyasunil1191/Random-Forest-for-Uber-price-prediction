# Dynamic Pricing Analysis & Prediction

## Problem Statement
Pricing in ride-hailing platforms such as Uber and Lyft is dynamic and influenced by multiple factors including distance, time, demand, weather, and location.  
The objective of this project is to **analyse pricing behaviour and build predictive models** to estimate trip prices based on trip and contextual features.

---

## Dataset
This project uses publicly available **Uber / Lyft trip pricing datasets** sourced from Kaggle.

**Key features include:**
- Distance
- Trip duration
- Pickup and drop-off locations
- Time of day
- Weather conditions
- Ride type (UberX, Lyft, etc.)

> Due to GitHub file size limitations, the full dataset is not stored in this repository.  
> A small sample dataset is included for reproducibility and structure.

---

## Objectives
- Understand factors influencing ride pricing
- Perform exploratory data analysis (EDA) on trip and pricing data
- Build regression models to predict ride prices
- Compare baseline and advanced models
- Evaluate model performance using appropriate metrics

---

## Methods Used
- Exploratory Data Analysis (EDA)
- Data cleaning and preprocessing
- Feature engineering
- Handling missing values and outliers
- Regression modelling:
  - Linear Regression
  - Ridge / Lasso Regression
  - Random Forest Regressor
- Model evaluation and comparison

---

## Model Evaluation Metrics
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R² Score

---

## Results
- Tree-based models (Random Forest) performed better than linear models due to non-linear relationships in pricing data.
