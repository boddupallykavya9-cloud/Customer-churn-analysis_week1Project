# Telco Customer Churn Analysis

This repository contains a Jupyter Notebook (`.ipynb`) that performs an exploratory data analysis (EDA) and builds a predictive model to understand and predict customer churn in a telecommunications company.

## Project Overview

The goal of this project is to analyze factors influencing customer churn and build a model that can predict which customers are likely to churn. This can help the company take proactive measures to retain valuable customers.

## Dataset

The analysis is based on the `Telco-Customer-Churn_dataset.csv` dataset. This dataset contains customer information including demographic data, services subscribed, contract details, payment information, and churn status.

## Analysis and Modeling

The notebook covers the following steps:

1.  **Data Loading and Inspection:** Loading the dataset and performing initial checks for structure, missing values, and data types.
2.  **Data Cleaning:** Handling duplicate rows.
3.  **Exploratory Data Analysis (EDA):**
    *   Visualizing the distribution of the target variable (`Churn`).
    *   Examining the relationship between key features (like `MonthlyCharges` and `tenure`) and `Churn`.
    *   Analyzing correlations between numerical features.
    *   Comparing numerical feature means between churned and non-churned customers.
    *   Summarizing key observations from the EDA.
4.  **Model Building:**
    *   Preparing the data for modeling (handling categorical features, splitting data).
    *   Building and training a Logistic Regression model.
    *   Addressing model convergence issues (increasing `max_iter`).
    *   Scaling numerical features to improve model performance.
    *   Performing hyperparameter tuning using GridSearchCV.
    *   Evaluating the tuned model's performance using various metrics (accuracy, precision, recall, F1-score, confusion matrix).

## How to Run the Notebook

1.  **Clone the repository:** Clone this GitHub repository to your local machine or open it directly in Google Colab.
2.  **Upload the dataset:** Ensure the `Telco-Customer-Churn_dataset.csv` file is available in the environment where you are running the notebook (e.g., upload it to your Colab session storage).
3.  **Run the cells:** Execute the code cells sequentially to perform the data analysis and model building.

## Dependencies

The notebook requires the following Python libraries:

*   pandas
*   numpy (usually installed with pandas or scikit-learn)
*   seaborn
*   matplotlib
*   scikit-learn

These libraries can be installed using pip:
