# Data Science Internship Tasks

This repository contains solutions to two data science tasks:
1. Titanic Survival Classification
2. Stock Price Prediction

## Task 1: Titanic Survival Classification

### Overview
Built a machine learning model to predict passenger survival on the Titanic using features like age, gender, ticket class, and fare.

### Key Steps:
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Model building with Random Forest
- Hyperparameter tuning using GridSearchCV
- Model evaluation with various metrics

### Results:
- Best model achieved 77% accuracy (your actual result)
- Most important features: [Age, Fare, Sex, Pclass, Family Size]

## Task 2: Stock Price Prediction

### Overview
Developed an LSTM model to predict future stock prices based on historical data.

### Key Steps:
- Data collection using yfinance
- Feature engineering (moving averages, daily returns)
- Data preprocessing for time series
- LSTM model architecture
- Model training with early stopping
- Future price prediction

### Results:
- Achieved RMSE of 4.20 
- Visualized predictions vs actual prices

## Requirements
- Python 3.8+
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, tensorflow, yfinance

## Usage
1. Clone the repository
2. Install required packages: `pip install -r requirements.txt`
3. Run the Jupyter notebook: `jupyter notebook`

## Author
[Danyal Shah]
