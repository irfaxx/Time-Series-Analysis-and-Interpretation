**Description**

This project aims to predict traffic volume using Explainable Machine Learning techniques. It utilizes a dataset containing information about traffic, weather conditions, and time-related features.

**Prerequisites**

Python 3.x
Required Python packages: pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost, statsmodels



**python traffic_volume_prediction.py**

This script performs the following tasks:

**Data preprocessing:** 

Cleaning, feature engineering, and visualization.
**Model training:**

XGBoost and RandomForestRegressor models are trained for traffic volume prediction.
**Evaluation:**

Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R²) are calculated to evaluate model performance.
**Feature Importance:**

Feature importance analysis using XGBoost.
**Seasonal Decomposition:**

Trend, seasonal, and residual components of the traffic volume time series data are decomposed using statsmodels.
**Decision Tree Visualization:**

Decision Tree Regressor is trained and visualized.
**File Descriptions**

traffic_volume_prediction.py: Main script containing code for data preprocessing, model training, evaluation, and visualization.
Metro_Interstate_Traffic_Volume.csv: Dataset containing traffic volume and related features.
README.md: This file.


Credits
The dataset used in this project is obtained from the UCI Machine Learning Repository: Metro Interstate Traffic Volume Data Set.
License
This project is licensed under the MIT License - see the LICENSE file for details.
