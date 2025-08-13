# Florida-Bike-Rentals---Demand-Prediction-Model
This project analyzes and predicts daily bike rental demand for a Florida rental service using historical usage data and external factors such as weather, seasonality, and holidays. The workflow included:

Data Cleaning & Preparation: Addressed missing values, standardized date/time formats, and encoded categorical variables for model readiness.
Exploratory Data Analysis (EDA): Visualized rental trends by temperature, humidity, wind speed, and seasonal effects; identified peak demand periods and unusual fluctuations.
Feature Engineering: Created new predictors like “is_weekend,” “is_holiday,” and rolling averages for weather metrics to better capture demand patterns.
Model Development: Implemented and compared multiple regression algorithms, including Linear Regression, Decision Tree Regressor, and Random Forest Regressor.
Model Evaluation: Achieved an R² score of 53.4%, indicating moderate predictive performance, and highlighted key demand drivers such as temperature and season.
Insights & Recommendations: Suggested strategies for inventory allocation and staffing adjustments based on predicted high- and low-demand periods.
Tech Stack: Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Jupyter Notebook
