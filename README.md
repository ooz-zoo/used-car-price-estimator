# About

Model that predicts the price of used cars based on multiple features using the Random Forest Regressor algorithm.

## Technologies
- Python
- Pandas
- NumPy
- scikit-learn (Random Forest)
- Joblib (for model serialization)

## Project Overview
1. Load and clean raw car listings data.
2. Convert categorical features to numeric using `OrdinalEncoder`.
3. Train a `RandomForestRegressor` to estimate prices.
4. Predict prices for new car entries.
5. Compare predicted prices of different vehicle configurations.

## Features Used
- Year
- Odometer
- Fuel Type
- Gearbox
- Brand

## Sample Prediction

Example input:
```python
{'year': 2010, 'odometer': 150000, 'fuelType': 'diesel', 'gearbox': 'manuell', 'brand': 'ford'}

The predicted price for the car is: ($) XXXX.XX
