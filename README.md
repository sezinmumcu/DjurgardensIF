# Djurgardens IF Hockey - Goal Prediction Analysis

## Overview
This project aims to predict the total number of goals scored by players of Djurgardens IF, a Swedish ice hockey team. The analysis uses machine learning techniques to explore various player attributes and their relationship with goal-scoring performance.

## Data Source
The dataset was manually scraped from [eliteprospects.com](https://www.eliteprospects.com/team/3/djurgardens-if). It includes various player attributes such as age, height, weight, position, games played, assists, penalty minutes, and more.

## Project Structure
- `DjurgardensIF.ipynb`: Jupyter notebook containing the data analysis and modeling code
- `djurgardens.xlsx`: Raw data file (not included in the repository)
- `Report_Predicting_Total_Goals.pdf`: Detailed report of the analysis and findings

## Skills and Techniques Demonstrated
- Data cleaning and preprocessing using pandas
- Exploratory Data Analysis (EDA) with matplotlib, seaborn, and Lux
- Feature scaling using RobustScaler
- Machine learning model implementation:
  - Support Vector Machines (SVM)
  - XGBoost
  - Linear Regression
  - Random Forest Regression
- Hyperparameter tuning with GridSearchCV
- Cross-validation techniques
- Feature importance analysis
- Model evaluation using R-squared and Median Absolute Error metrics
- Data visualization for model performance analysis

## Key Features
1. Data cleaning and preprocessing
2. Exploratory Data Analysis (EDA) using various visualization techniques
3. Model selection and evaluation (SVM, XGBoost, Linear Regression, Random Forest)
4. Hyperparameter tuning for the Random Forest model
5. Feature importance analysis

## Main Findings
- Assists and games played showed strong positive correlations with total goals scored
- The Random Forest model achieved the best performance with an R² score of 0.5808 on the test set
- Assists, games played, and penalty minutes were identified as the most important features for predicting goals

## Requirements
- Python 3.x
- Libraries: pandas, matplotlib, seaborn, numpy, scikit-learn, xgboost, lux
