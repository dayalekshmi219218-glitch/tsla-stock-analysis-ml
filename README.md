TSLA Stock Analysis and Price Prediction Using Machine Learning
Overview

This project presents a complete end-to-end analysis of TSLA stock performance over a five-year period, combining data cleaning, exploratory data analysis (EDA), feature engineering, technical indicators, and a machine learning model built using a Random Forest regressor. The objective is to understand market behavior, uncover trends, and develop a model capable of predicting future closing prices.

The project demonstrates practical skills in data science, Python, financial analytics, and machine learning—structured to meet professional standards for portfolio and internship applications.

Repository Structure

tsla-5year-stock-analysis
│
├── notebook/
│   └── tsla_analysis.ipynb
├── images/
│   ├── price_trend.png
│   ├── volume.png
│   ├── moving_averages.png
│   └── actual_vs_predicted.png
│   

Project Objectives

Clean and prepare five years of TSLA historical stock data.

Perform exploratory data analysis to identify major price trends, volatility, and market behavior.

Engineer features including daily returns and moving averages.

Build and evaluate a Random Forest regression model for future price prediction.

Interpret results and highlight model strengths and limitations within a financial context.

Dataset

Source: Yahoo Finance (historical daily TSLA price data)

Period: 2018–2023

Columns used:

Date

Open

High

Low

Close

Volume

All missing values were checked and confirmed to be absent. The Date column was converted to datetime format, and additional features were created through feature engineering.

Exploratory Data Analysis (EDA)
1. TSLA Closing Price Trend

A long-term upward trajectory with significant volatility, reflecting Tesla’s rapid growth phase and subsequent correction periods.

(Image: closing_price_trend.png)

2. TSLA Daily Returns

Daily returns were calculated to capture short-term price behavior and measure volatility.

(Image: daily_returns_plot.png)

3. Trading Volume Over Time

Reveals rising liquidity and market interest, often confirming major price movements.

(Image: volume_plot.png)

4. Moving Averages (50-Day and 200-Day)

Technical indicators were computed to identify trend direction and momentum shifts.

(Image: moving_averages_plot.png)

5. Positive vs Negative Daily Returns

Daily returns were visualized with color differentiation for positive and negative movements.

(Image: daily_returns_positive_negative.png)

Machine Learning Model
Model Used

Random Forest Regressor

Feature Inputs

Previous day’s Close price

Moving averages

Daily returns

Volume

Train/Test Split

80% training

20% testing

Evaluation Metrics

RMSE

R² Score

Model Interpretation

The model effectively captures overall trends but struggles with abrupt turning points, which is expected for tree-based methods on volatile financial data. Regularization through hyperparameter tuning was applied to reduce overfitting.

(Image: actual_vs_predicted.png)

Key Findings

TSLA exhibits strong long-term growth with high short-term volatility.

Trading volume tends to validate major price movements.

Moving averages provide meaningful trend indicators useful for feature engineering.

The Random Forest model performs well in trend following but naturally underperforms during sudden reversals.

This project demonstrates applied knowledge in financial EDA, technical indicators, and practical machine learning workflows.

Tools and Libraries

Python

Pandas

NumPy

Matplotlib

Scikit-learn

Google Colab / Jupyter Notebook

How to Run

Clone the repository:

git clone https://github.com/yourusername/tsla-stock-analysis-ml.git


Install dependencies (optional if using Colab):

pip install -r requirements.txt


Open the notebook:

tsla_stock_analysis.ipynb


Run all cells in sequence.

Future Improvements

Incorporate LSTM or GRU deep learning models for sequence prediction.

Add more technical indicators (RSI, MACD).

Extend analysis to multi-stock comparison or multi-feature forecasting.

Deploy predictions through a simple dashboard.

Author

Daya Kumar https://www.linkedin.com/in/daya-kumar27/
Aspiring Data Scientist & Machine Learning Enthusiast
