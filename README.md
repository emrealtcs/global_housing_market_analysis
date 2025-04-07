# Global Housing Price Prediction

Predicting country-level housing price trends using feature-engineered time series data, clustering, and XGBoost regression.

# Overview
This project explores global housing price trends using machine learning. 

- Built a time-aware regression pipeline with XGBoost
- Engineered temporal and country-specific features
- Used KMeans clustering to capture regional patterns
- Predicted house price indices for 20 countries from 2021–2024

# Results
- Test RMSE: 23.77
- Cross-Validation RMSE (Avg): 29.01
- Model accuracy: ~82% (based on scaled error vs. index range of 80–180)
- Predicted trends closely match actuals across most countries

# Techniques Used
- Time Series Feature Engineering
- KMeans Clustering on Country Embeddings
- XGBoost Regressor
- Cross-Validation & Performance Metrics
- Matplotlib + Seaborn for Visualizations
