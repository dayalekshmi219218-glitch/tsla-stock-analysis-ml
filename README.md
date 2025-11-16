TSLA 5-Year Stock Analysis & Predictive Modeling

A complete Exploratory Data Analysis (EDA) and machine learning project exploring Tesla’s stock performance over the last five years, including trend analysis, volume behavior, technical indicators, and a Random Forest regression model to predict future closing prices.

Project Overview

This project analyzes Tesla (TSLA) stock data from the past five years to uncover key trends and patterns using Python-based data science techniques. It also builds and evaluates a machine learning model for stock price prediction using Random Forest Regression.

This repository demonstrates practical skills in:

Time-series exploratory data analysis

Data cleaning and feature engineering

Financial technical indicator construction

Model training and evaluation

Visualization and interpretation of insights

Communicating results clearly for technical and non-technical audiences

Key Features
1. Exploratory Data Analysis (EDA)

Price trend analysis

Volume dynamics

Moving averages and momentum behavior

Volatility observations

Market structure interpretation

2. Feature Engineering

Technical indicators such as:

20-day moving average

50-day moving average

Momentum indicators

Volume-based signals

Lag features

3. Predictive Modeling

Random Forest Regressor

Train/test split validation

RMSE and R² evaluation

Hyperparameter tuning for better generalization

4. Visualizations

The project includes curated visualizations, such as:

Stock price trend

Daily trading volume

Moving averages

Actual vs. predicted closing prices
(Stored in the images/ folder)

Repository Structure
tsla-5year-stock-analysis
│
├── notebook/
│   └── tsla_analysis.ipynb
│
├── images/
│   ├── price_trend.png
│   ├── volume.png
│   ├── moving_averages.png
│   ├── actual_vs_predicted.png
│   └── additional_visualizations.png
│
└── models/
    └── random_forest_model.pkl

Model Performance
Metric	Value
RMSE (tuned model)	21.46
R² Score	0.94

The model captures long-term price trends effectively but, as expected in financial time series, struggles with sudden price spikes and reversals. Regularization was prioritized over perfect fit to ensure robustness.

How to Run the Notebook

Clone the repository

Install the required dependencies

Open the notebook in Jupyter or VS Code

Run the analysis end-to-end

Data Source

The raw historical TSLA stock data was downloaded directly from Yahoo Finance.

Contact

If you’d like to connect, collaborate, or discuss data science, you can reach me here:
LinkedIn: [https://www.linkedin.com/in/daya-kumar27/]
Feel free to connect.
