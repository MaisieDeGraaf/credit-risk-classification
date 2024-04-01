# Credit Risk Classification

## Overview

This repository contains code and analysis for predicting credit risk using logistic regression. The analysis utilizes a dataset of lending data to train a logistic regression model to predict whether a loan is high-risk or healthy based on various financial factors.

## Dataset

The lending data used for analysis is stored in a CSV file named `lending_data.csv`, located in the `Resources` folder. This dataset contains the following columns:

- loan_size
  
- interest_rate
  
- borrower_income
  
- debt_to_income
  
- num_of_accounts
  
- derogatory_marks
  
- total_debt
  
- loan_status (target variable)

## Analysis

The analysis is performed in a Jupyter Notebook named `credit_risk_analysis.ipynb`. The notebook contains the following main sections:

1. Data Exploration and Preprocessing: The dataset is loaded into a Pandas DataFrame, and basic data exploration is performed.
   
2. Model Training and Evaluation: The data is split into training and testing sets, and a logistic regression model is trained using the training data. The model's performance is evaluated using a confusion matrix and a classification report.

## Instructions

To run the analysis:

1. Clone this repository to your local machine.

2. Install the necessary dependencies listed in the notebook

3. Open Google Colab and upload the csv file located in "Resources"

## Files Included

- `credit_risk_analysis.ipynb`: Jupyter Notebook containing the analysis code.

- `lending_data.csv`: CSV file containing the lending data.
  
- `Credit Risk Challenge Analysis` : Word Document with a report analysis of the machine leraning used, accuracy, and summary
  
- `README.md`: This file providing an overview of the repository.

## Requirements
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
