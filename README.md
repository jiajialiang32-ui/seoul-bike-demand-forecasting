# Urban Micro-Mobility Demand Forecasting and Feature Importance Analysis: A Case Study of Seoul Bike Sharing

## Project Overview
This project investigates the demand dynamics of the Seoul public bike-sharing system by combining Time Series Forecasting (ARIMA/ARIMAX) and Machine Learning Feature Importance Analysis (Random Forest).

## Repository Structure
* `/data`: Contains the raw `SeoulBikeData.csv` panel dataset (365 days, hourly records).
* `/code`: Includes Python scripts/notebooks for data preprocessing, Random Forest feature selection, and ARIMA/ARIMAX forecasting.
* `/report`: Contains the final academic project report document.

## Key Findings
* Temperature Dominance: Random Forest feature importance proves that temperature accounts for over 40% of demand variance.
* ARIMA vs. ARIMAX Trade-off: Highlights the methodological limitations of long-term exogenously driven time-series forecasting when future weather predictions are unavailable.
