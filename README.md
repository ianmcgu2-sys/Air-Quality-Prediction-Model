# Air-Quality-Prediction-Model
First ML model designed to predict Air Quality Index (AQI) level through training with common pollutants (e.g. CO, NO2 and PM2.5).

This project uses **Random Forest Regressor** (with 100 estimators) which effectively predicts AQI from concentrations of key air quality pollutants by training (with 80% train/20% test splitting) on the Kaggle Dataset [global_air_pollution_data.csv]([url](https://www.kaggle.com/datasets/sazidthe1/global-air-pollution-data)).

**Key Results:**
The model has a R**2 Score of 0.9965 on prediction of AQI and a mean absolute error of 0.2786 (AQI points).
It concludes that **PM2.5** is the most significant predictor out of all pollutants accounting for nearly 100% of the model's predictive weight.

Made using:
Python (Pandas, Seaborn & Scikit-learn)
