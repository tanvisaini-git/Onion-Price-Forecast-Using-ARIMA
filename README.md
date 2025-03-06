# Onion Price Prediction
Developed as part of a project for Statistics program at University of Delhi, Lady Shri Ram College. The project aims to forecast onion prices based on historical data, seasonality, and various factors influencing the price.

## Overview
The Onion Price Prediction project aims to predict the future price of onions based on past pricing data and various influencing factors, including seasonal patterns, weather conditions, and supply-demand dynamics. Using machine learning algorithms, this tool provides forecasts that could help vendors, retailers, and consumers make informed decisions on purchasing and selling onions.

## Motivation
Onion prices often fluctuate due to a variety of factors, including supply chain disruptions, seasonal harvests, and changing demand. Predicting these price changes can benefit farmers, retailers, and consumers, enabling better decision-making and cost management. This project provides a model that forecasts onion prices, aiming to reduce uncertainty in the market and optimize supply chain operations.

## Data Sources and Feature Engineering
The model uses historical onion price data and related factors such as:

* Price Data: Historical onion prices from various markets.
* Seasonality: Data on when onions are harvested during the year, including crop cycles.
* Weather Data: Weather conditions such as temperature, rainfall, and humidity, which can affect onion production.
* Supply and Demand: Data on market supply and demand, including production levels and consumption rates.
* Economic Indicators: Influences such as transportation costs, inflation, and import-export regulations.
### Feature Engineering Techniques:
* Temporal Features: Extracting time-related features such as day, month, and year to capture seasonality patterns.
* Lag Features: Including previous price data to account for historical trends.
* Weather Data: Integration of weather data to understand its impact on supply and production.
* Market Dynamics: Incorporating supply-demand data to help predict price shifts.
## Model Architecture
The model utilizes various machine learning techniques to forecast onion prices, including:

* Linear Regression: A basic regression model used as a benchmark.
* Random Forest Regressor: An ensemble method that can capture non-linear relationships between features.
* XGBoost: A gradient boosting algorithm that provides robust predictions, especially for complex data patterns.
The model evaluates and compares the performance of each algorithm, selecting the best performer based on accuracy and prediction reliability.

## Predicted Price Example
Given historical data, the model forecasts the future onion prices. For instance, the prediction might suggest that onion prices will rise in the coming month due to low production and high demand during the festive season.

## Future Developments and Directions
While the current model focuses on predicting onion prices based on available data, future advancements aim to expand the prediction model to consider:

* Regional Price Variations: Understanding how prices differ across different markets and locations.
* Supply Chain Disruptions: Including data on transportation strikes, infrastructure issues, or weather-related disruptions to further improve the model's accuracy.
* Market Insights: Incorporating consumer behavior data, such as purchasing trends, to fine-tune price predictions.

The goal is to develop a more comprehensive forecasting system that can predict onion prices with higher precision, providing valuable insights to all stakeholders in the onion supply chain.
