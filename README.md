
# Airbnb Price Prediction for Los Angeles

## Project Overview
This project builds a machine learning model to predict the price of Airbnb listings in Los Angeles. By utilizing data on property features like location, number of bedrooms, amenities, and host details, the model aims to provide accurate price estimates for new Airbnb listings. 

## Data
The dataset includes information on 19,230 Airbnb listings in Los Angeles with features such as:
- Property details: bedrooms, bathrooms, beds, etc.
- Location: latitude, longitude
- Host details: host response rate, whether they are a superhost, total listings count
- Other features: cleaning fees, number of reviews, and review scores

## Model
The project uses several machine learning models to predict prices:
- **Linear Regression**
- **Ridge Regression**
- **Lassso Regression**
- **Desicion tree Regressor**
- **Random Forest Regressor**
- **XGBoost Regressor**
- **MLP Regressor (Neural Network)**

The performance of each model is evaluated using:
- **RMSE** (Root Mean Squared Error)
- **R²** (Coefficient of Determination)
- **MAE** (Mean Absolute Error)

The **XGBoost Regressor** was found to be the best-performing model, balancing both accuracy and generalization.
