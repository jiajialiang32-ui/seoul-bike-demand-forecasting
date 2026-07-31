# Urban Micro-Mobility Demand Forecasting and Feature Importance Analysis: A Case Study of Seoul Bike Sharing

Short one-sentence description: This project predicts Seoul bike-sharing demand and identifies the key factors driving demand variation using ARIMA/ARIMAX and Random Forest analysis.

## Summary
This project explores demand dynamics in the Seoul public bike-sharing system by combining time-series forecasting with machine learning feature importance analysis. It aims to understand how historical demand patterns and external conditions such as temperature influence future bike demand.

## Features
- Daily demand forecasting using ARIMA and ARIMAX models
- Feature importance analysis through Random Forest regression
- Exploratory data analysis on Seoul bike-sharing usage patterns
- Project report and reusable notebook workflow

## Tech Stack
Frontend:
- N/A

Backend:
- Python

Database:
- CSV-based dataset (`SeoulBikeData.csv`)

Other tools and libraries:
- pandas
- numpy
- matplotlib
- statsmodels
- scikit-learn

## Demo
Insert screenshot or gif link here.

## Background and Problem
Seoul bike-sharing demand is strongly affected by environmental and temporal factors, making accurate forecasting difficult for planning and operations. This project addresses the need for demand prediction and interpretable feature analysis to support better resource allocation and service management.

## Architecture
The workflow begins with data loading and preprocessing, followed by time-series forecasting using ARIMA/ARIMAX and predictive modeling with Random Forest. The notebook structure separates data preparation, model fitting, result visualization, and feature ranking into distinct analysis sections.

## How to Run
```bash
git clone https://github.com/username/repository.git
cd project-folder

# install dependencies
pip install -r requirements.txt

# start program
python main.py
```
