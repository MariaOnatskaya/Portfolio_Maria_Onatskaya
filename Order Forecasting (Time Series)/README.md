# Taxi Order Demand Forecasting Model (Time Series)

## Description:
Developed and trained a model to forecast the number of taxi orders for the next hour based on a provided labeled dataset.

## Key Achievements:
- Built baseline forecasts (based on the mean value and previous value of the series) to assess model adequacy.  
- Trained six machine learning models, including LinearRegression, DecisionTreeRegressor, KNeighborsRegressor, LightGBM, XGBoost, and CatBoost.  
- Developed and trained a neural network to predict the number of orders.  
- Performed hyperparameter tuning using GridSearchCV for all models except linear regression.  
- Experimental results showed that the neural network achieved the highest forecasting accuracy.  

## Tools:  
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, PyTorch, LightGBM, XGBoost, CatBoost, Pipeline, GridSearchCV, TimeSeriesSplit.
