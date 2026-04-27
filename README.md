Flight Price Prediction – Machine Learning Project
Overview
Airline ticket prices vary significantly depending on several factors such as flight duration, booking date, number of stops, and airline company.
In this project, we work for a flight booking platform with the objective of analyzing pricing patterns and building a reliable machine learning model to predict ticket prices with controlled error.
The dataset contains more than 300,000 flight booking records.
Business objective: achieve a Mean Absolute Error (MAE) lower than 15€ with a confidence interval.
Objectives
Perform a rigorous exploratory data analysis (EDA)
Identify relationships between features and target variable (price)
Formulate and test statistical hypotheses
Build a robust preprocessing pipeline
Train and compare multiple regression models
Evaluate and select a final model
Dataset
File: Clean_Dataset.csv
The dataset includes features such as:
Airline
Source and destination
Flight duration
Number of stops
Days left before departure
Price (target variable)
Project Workflow
1. Data Loading
Import required libraries
Load dataset
Inspect shape, structure, and basic information
2. Variable Analysis
Identify categorical and numerical variables
Check data types
Detect necessary transformations
3. Univariate Analysis
Categorical variables: class distribution and bar plots
Numerical variables: descriptive statistics, histograms, boxplots
4. Multivariate Analysis
Study the relationship between features and price:
Flight duration vs price
Airline vs price
Number of stops vs price
Days before departure vs price
Tools used:
Boxplots
Grouped analysis (binning)
Visual exploration
5. Hypothesis Testing
Define null and alternative hypotheses (H0 / H1)
Apply appropriate statistical tests:
Pearson correlation
ANOVA
Interpret p-values (significance level: 5%)
6. Preprocessing
Handle missing values
Encode categorical variables
Transform ordinal variables
Standardize numerical features
Build a Scikit-learn pipeline
7. Modeling
Models tested:
DummyRegressor (baseline)
Linear Regression
Ridge Regression
Random Forest Regressor
For each model:
Cross-validation
Evaluation using MAE, RMSE, and R²
Performance comparison
8. Final Evaluation
Select the best-performing model
Train on full training data
Evaluate on test set
9. Confidence Interval
Compute absolute errors
Estimate MAE
Calculate standard error
Build a 95% confidence interval
10. Model Export
Save the full pipeline (preprocessing + model)
Store model metadata
Prepare for future deployment
Technologies Used
Python
Pandas / NumPy
Seaborn / Matplotlib
Scikit-learn
Project Organization
Flight-Price-Prediction-ML/
│── data/
│── notebooks/
│── src/
│── models/
│── README.md
│── requirements.txt
Team & Collaboration
Group project
Collaboration required across all stages
Timeline
Duration: 5 days
From: April 20, 2026
To: April 24, 2026 (17:00 deadline)
Expected Outcome
A machine learning model capable of predicting flight prices with high accuracy and meeting the business constraint of MAE < 15€, along with a reliable and reproducible data pipeline.
