# Mercado Libre Growth Analysis Challenge
## Overview
As a growth analyst at Mercado Libre, the leading e-commerce platform in Latin America, this project aims to analyze search traffic data to understand its implications on the company's stock performance and overall growth strategies. By leveraging Google search trends and stock price data, we explore whether patterns in user interest can predict financial outcomes.

## Technologies Used
- Python
- Pandas for data manipulation.
- Matplotlib for visualizations.
- Prophet for time series forecasting.
- Google colab for cloud environment. 

## Setup Instructions
- Clone the repository: git clone https://github.com/priscillasp/prophet-challenge 
- Navigate to the repository: cd prophet-challenge
- Open the .ipynb in Google Colab to run the analysis.

## Analysis Summary
### Step 1: Unusual Patterns in Search Traffic
Analyzed Google search data for May 2020, correlating spikes in search trends with the release of quarterly financial results.
Calculations indicate an increase in searches during the month that MercadoLibre released its financial results.
### Step 2: Search Traffic Seasonality
Examined hourly, daily, and weekly search traffic patterns.
Identified peak times and days with the highest user activity, providing insights for targeted marketing campaigns.
### Step 3: Search Traffic and Stock Price Patterns
Combined search data with stock price movements to investigate correlations.
Analyzed the first half of 2020, revealing synchronized trends in increased search traffic and stock prices.
Introduced lagged search trends and calculated stock volatility and hourly returns, examining their interrelationships.
### Step 4: Time Series Forecasting with Prophet
Configured and estimated a Prophet model to forecast search popularity.
Provided forecasts and decomposed the time series to highlight key periods of interest and activity throughout the year. 
Analysis revealed that around 7-11pm daily search trends peak, Tuesday is the day of the week with the most traffic and the lowest point for searches is around late October. 

## Results
The analysis successfully linked Google search traffic with financial metrics, suggesting that higher user engagement on the platform can potentially be a precursor to positive stock performance. 
