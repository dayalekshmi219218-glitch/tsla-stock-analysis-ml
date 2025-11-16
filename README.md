TSLA 5-Year Stock Analysis & Predictive Modeling

A complete Exploratory Data Analysis (EDA) and machine learning project exploring Tesla’s stock performance over the past five years, including trend behavior, trading volume patterns, technical indicators, and a Random Forest regression model for predicting closing prices.

1. Project Overview

This project examines Tesla (TSLA) stock data to uncover key financial patterns and construct a predictive model for future price movements.
It demonstrates practical data science and machine learning skills, including:

Time-series exploratory data analysis

Data cleaning and preprocessing

Feature engineering using technical indicators

Building and evaluating machine learning models

Visual analytics and financial interpretation

Clear communication of insights for both technical and non-technical audiences

2. Key Features
Exploratory Data Analysis (EDA)

Long-term price trend analysis

Trading volume dynamics

Moving averages and momentum interpretation

Market structure and volatility insights

Feature Engineering

Includes commonly used financial indicators:

20-day moving average

50-day moving average

Momentum-based features

Volume signals

Lag features for temporal modeling

Predictive Modeling

A Random Forest Regressor was trained using engineered features.
Includes:

Train/test split validation

RMSE and R² evaluation

Hyperparameter tuning for increased generalization

Visualizations

Stored in the images/ folder:

Price trend line

Daily trading volume

Moving averages

Actual vs. predicted closing prices

3. Repository Structure
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

4. Model Performance
Metric	Value
RMSE (tuned model)	21.46
R² Score	0.94

The model effectively captures long-term price direction but, due to the inherent volatility of financial markets, struggles with abrupt spikes or drops.
Regularization during tuning prioritized stability over aggressive fitting, resulting in a more reliable model.

5. How to Run the Notebook

* Clone the repository

* Install the required Python dependencies

* Open the notebook in Jupyter or VS Code

* Run all cells to reproduce the analysis

6. Data Source

Historical TSLA stock data was downloaded directly from Yahoo Finance.

7. Contact

Feel free to connect or reach out:
LinkedIn: [https://www.linkedin.com/in/daya-kumar27/]

If you'd like this in a more minimal, more aesthetic, or more technical style, I can rewrite it again.
If you want, I can also design a banner image for the GitHub repo header to make it look even more polished.
