# Seoul Bike Demand Forecasting and Feature Importance Analysis

This project predicts daily Seoul bike-sharing demand and identifies the key factors driving demand variation using ARIMA/ARIMAX time-series forecasting and Random Forest feature-importance analysis.

## Summary
This project studies urban micro-mobility demand in Seoul by combining forecasting with interpretable machine learning. It uses historical usage patterns and environmental variables to estimate future bike demand while highlighting the most influential predictors.

## Skills Applied
- Time-series forecasting with ARIMA/ARIMAX
- Python data analysis and visualization
- Machine learning with Random Forest regression
- Feature importance interpretation for urban mobility analytics

## Features
- Daily bike demand forecasting with ARIMA and ARIMAX
- Random Forest-based feature importance analysis
- Exploratory analysis of demand and weather-related patterns
- Reusable notebook workflow for reporting and model comparison

## Tech Stack
Frontend:
- N/A

Backend:
- Python

Database:
- CSV dataset (`SeoulBikeData.csv`)

Tools & Libraries:
- pandas
- numpy
- matplotlib
- statsmodels
- scikit-learn
- Jupyter Notebook

## Demo
ARIMA result


<img width="635" height="329" alt="截屏2026-07-31 下午1 26 42" src="https://github.com/user-attachments/assets/a91c2e77-82d7-4646-a495-d64e957b1c35" />


ARIMAX result


<img width="628" height="332" alt="截屏2026-07-31 下午1 27 52" src="https://github.com/user-attachments/assets/db124ef5-0b09-40f5-8ed7-fc1fc25948dd" />


Random forest result


<img width="638" height="327" alt="截屏2026-07-31 下午1 28 13" src="https://github.com/user-attachments/assets/2ee3029e-b6d9-4e16-9366-1239cd0dcfa3" />

## Background and Problem
Seoul bike-sharing demand is highly affected by weather, seasonal effects, and temporal usage patterns. Accurate prediction helps operators allocate bikes efficiently, reduce shortages, and support planning decisions. This project addresses the need for both accurate forecasting and model interpretability.

## Architecture
The workflow begins with loading the Seoul bike-sharing dataset, followed by preprocessing, exploratory analysis, and feature preparation. Forecasting is performed with ARIMA/ARIMAX models, while Random Forest is used to rank the variables contributing most strongly to demand prediction. The notebook outputs clean visualizations and comparative results.

## How to Run
```bash
git clone https://github.com/yourname/your-repo.git
cd project-directory

# install dependencies
pip install -r code/requirements.txt

# run the notebook workflow
jupyter notebook code/ARIMA.ipynb
```
