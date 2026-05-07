# Flight Price Prediction - Machine Learning Project

## Overview

Airline ticket prices vary depending on several factors such as flight
duration, booking date, number of stops, and airline company.

In this project, we work for a flight booking platform with the
objective of analyzing pricing patterns and building a reliable machine
learning model to predict ticket prices with controlled error.

The dataset contains more than 300,000 flight booking records.

Business objective: achieve a Mean Absolute Error (MAE) lower than 15€
with a confidence interval.

------------------------------------------------------------------------

## Objectives

-   Perform exploratory data analysis (EDA)\
-   Identify relationships between features and the target variable
    (price)\
-   Formulate and test statistical hypotheses\
-   Build a preprocessing pipeline\
-   Train and compare regression models\
-   Evaluate and select a final model

------------------------------------------------------------------------

## Dataset

File: Clean_Dataset.csv

Main features: - Airline\
- Source and destination\
- Flight duration\
- Number of stops\
- Days left before departure\
- Price (target variable)

------------------------------------------------------------------------

## Project Workflow

### 1. Data Loading

-   Import libraries\
-   Load dataset\
-   Inspect structure and shape

### 2. Variable Analysis

-   Identify categorical and numerical variables\
-   Check data types\
-   Detect required transformations

### 3. Univariate Analysis

-   Categorical variables: distribution and bar plots\
-   Numerical variables: statistics, histograms, boxplots

### 4. Multivariate Analysis

Study relationships with price: - Duration vs price\
- Airline vs price\
- Stops vs price\
- Days before departure vs price

Tools: - Boxplots\
- Grouped analysis\
- Visual exploration

------------------------------------------------------------------------

### 5. Hypothesis Testing

-   Define H0 / H1\
-   Apply:
    -   Pearson correlation\
    -   ANOVA\
-   Interpret p-values (5% threshold)

------------------------------------------------------------------------

### 6. Preprocessing

-   Handle missing values\
-   Encode categorical variables\
-   Transform ordinal variables\
-   Standardize numerical features\
-   Build sklearn pipeline

------------------------------------------------------------------------

### 7. Modeling

Models: - DummyRegressor\
- Linear Regression\
- Ridge Regression\
- Random Forest

For each: - Cross-validation\
- Metrics: MAE, RMSE, R²\
- Performance comparison

------------------------------------------------------------------------

### 8. Final Evaluation

-   Select best model\
-   Train on full training data\
-   Evaluate on test set

------------------------------------------------------------------------

### 9. Confidence Interval

-   Compute absolute errors\
-   Estimate MAE\
-   Calculate standard error\
-   Build 95% confidence interval

------------------------------------------------------------------------

### 10. Model Export

-   Save full pipeline\
-   Store metadata\
-   Prepare for reuse

------------------------------------------------------------------------

## Technologies Used

-   Python\
-   Pandas / NumPy\
-   Seaborn / Matplotlib\
-   Scikit-learn

------------------------------------------------------------------------

## Project Structure

Flight-Price-Prediction-ML/\
│── data/\
│── notebooks/\
│── src/\
│── models/\
│── README.md\
│── requirements.txt

------------------------------------------------------------------------

## Team & Collaboration

-   Group project\
-   Collaboration across all stages

------------------------------------------------------------------------

## Timeline

-   Duration: 5 days\
-   From: April 20, 2026\
-   To: April 24, 2026 (17:00 deadline)

------------------------------------------------------------------------

## Expected Outcome

A machine learning model capable of predicting flight prices with strong
accuracy and meeting the business constraint of MAE \< 15€, along with a
reproducible data pipeline.
