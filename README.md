# agricultural-price-forecasting
Forecasting Nigerian agricultural commodity prices using machine learning.
# Agricultural Commodity Price Forecasting in Nigeria

## Overview

This project explores the use of machine learning models to forecast agricultural commodity prices in Nigeria. It uses historical price data to examine price trends and generate predictions that can support a better understanding of agricultural market movements.

## Objectives

* Analyze historical agricultural commodity prices.
* Explore price trends and fluctuations over time.
* Train and compare forecasting models.
* Evaluate model performance using standard error metrics.
* Generate future price forecasts.

## Dataset

The project uses historical Nigerian agricultural commodity price records spanning 2002–2025.

The analysis focuses on ten commodities:

* Rice (Imported)
* Maize (White)
* Yam
* Gari (White)
* Beans (Red)
* Tomatoes
* Onions
* Oil (Palm)
* Sorghum
* Groundnuts (Shelled)

## Methodology

The workflow includes data cleaning, date conversion, chronological sorting, monthly aggregation, missing-value handling, model training, and evaluation.

## Models

Three models are compared:

* Linear Regression
* Support Vector Regression (SVR)
* Prophet

## Evaluation

Model performance is assessed using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* Mean Absolute Percentage Error (MAPE)

The models are evaluated on historical observations not used for training.

## Technologies

* Python
* pandas
* NumPy
* Matplotlib
* scikit-learn
* Prophet
* Jupyter Notebook
* Streamlit (for the interactive application)

## Project Structure

The repository contains the Jupyter Notebook used for data processing, analysis, model training, and evaluation.

## Limitations

Forecasts are based on historical patterns and may not capture unexpected events, policy changes, weather shocks, or other external factors that influence agricultural prices.

## Future Improvements

Potential improvements include adding more explanatory variables, testing model performance across different time periods, and improving the accessibility of the forecasting application.

## Author

LAWAL RIDWANULAHI OLAWALE.
