# KPMGTrainingCamp2024

Me and my team reached the second place in a 3-days Training Camp organised by our Master Course in Data Science and KPMG Italy. In these 3 days, we took lectures from KPMG experts about Time-Series Forecasting and we had a competition where we had to solve a forecasting problem.

## The challenge

We had to forecast the amount of snacks sold from 05/2020 to 08/2020, by leveraging Time-Series forecasting techniques. After some preprocessing, we tried many different models like ARIMA (and its variants - SARIMAX), LSTM, tree-based regressor (RandomForestRegressor or XGBoost regressor), but we got the best result with Prophet. Moreover, the real key part of our solution was to take the logarithm of the Series to reduce noise: such decision allowed us to get improvements on all of our models. In the end, we also tried NeuralProphet but the obtained results were slightly worse than Prophet's.
