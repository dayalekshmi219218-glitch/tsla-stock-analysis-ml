# TSLA 5-Year Stock Analysis & Predictive Modeling

This project explores Tesla (TSLA) stock data over the last five years, analyzing trends in price, trading volume, and technical indicators. Additionally, it uses a Random Forest model to predict future closing prices. The project demonstrates skills in exploratory data analysis (EDA), feature engineering, visualization, and predictive modeling on financial time-series data.

---

## Project Summary

- Conducted a five-year analysis of TSLA historical stock data  
- Performed comprehensive exploratory data analysis to uncover trends, volatility, and market behavior  
- Engineered technical features including moving averages, momentum indicators, and volume-based signals  
- Built and evaluated a Random Forest model for predicting closing prices  
- Achieved strong model performance (R²: 0.94, RMSE: 21.46)  
- Included multiple visualizations to support insight and interpretation  

---

## Full Project Details

<details>
<summary><strong>Click to expand</strong></summary>

---

## 1. Exploratory Data Analysis (EDA)

The EDA examines:

- Price trends and patterns over time  
- Volatility spikes and corrections  
- Trading volume trends and market participation  
- Short-term and long-term moving averages  
- Momentum shifts and trend reversals  

These analyses reveal TSLA’s high-growth periods, correction phases, and general market sentiment. Understanding these patterns helps contextualize the machine learning predictions.

---

## 2. Feature Engineering

Key features created for the predictive model include:

- 20-day and 50-day Simple Moving Averages (SMA)  
- Momentum indicators capturing price changes  
- Volume-based signals to indicate market strength  
- Lag features and shifted targets for supervised learning  

Feature engineering allows the model to detect meaningful patterns and relationships in the data, improving predictive accuracy.

---

## 3. Predictive Modeling

A Random Forest Regressor was trained and evaluated on historical stock data.

**Model Performance**

| Metric | Value |
|--------|-------|
| RMSE (tuned model) | 21.46 |
| R² Score | 0.94 |

The model captures long-term trends effectively but naturally struggles with sudden spikes or reversals, which is common in financial time-series. Hyperparameter tuning focused on generalization to reduce overfitting while maintaining predictive strength.

---

## 4. Visualizations

The project includes visualizations such as:

- Price trend over time  
- Daily trading volume  
- Moving averages highlighting trend direction  
- Actual vs predicted closing prices  
- Additional supporting charts  

These plots help interpret the data and communicate insights clearly.

---

## 5. How to Run the Notebook

1. Clone the repository:  
   ```bash
   git clone https://github.com/dayalekshmi219218-glitch/tsla-stock-analysis-ml.git
2. Install required dependencies

3. Open the notebook in Jupyter or VS Code

4. Run all cells to reproduce the analysis


If you would like to connect, collaborate, or discuss data science, feel free to reach out
[LinkedIn](https://www.linkedin.com/in/daya-kumar27/)

