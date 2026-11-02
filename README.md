# Flight Fare Prediction Using Machine Learning

## Project Overview

This project focuses on analysing flight fare data and developing machine learning models to predict flight ticket prices.

Flight prices can vary depending on factors such as airline, journey date, source, destination, departure time, arrival time, flight duration and number of stops.

## Project Objectives

- Perform Exploratory Data Analysis (EDA).
- Clean and preprocess the dataset.
- Identify patterns and relationships between flight features and prices.
- Apply feature engineering and categorical encoding.
- Build and evaluate multiple machine learning models.
- Compare model performance and identify the best-performing model.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Joblib

## Machine Learning Models

1. Linear Regression
2. Random Forest Regressor
3. XGBoost Regressor

## Model Evaluation

The models were evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

Random Forest Regressor achieved the best test performance among the three models, with an R² score of approximately 0.8995.

## Project Structure

```text
Flight-Fare-Prediction/
├── Flight_Fare_Prediction.ipynb
└── README.md
```

## Conclusion

This project demonstrates the use of exploratory data analysis and machine learning techniques to understand flight fare patterns and predict flight prices. Random Forest Regressor was the best-performing model among the models evaluated.
