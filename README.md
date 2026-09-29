# Car Price Prediction with Machine Learning

## Project Overview

This project predicts car selling prices using Machine Learning.

The project includes data preprocessing, feature engineering, regression modeling, and model evaluation.

## Dataset

The dataset contains information about used cars, including:

- Car Name
- Present Price
- Driven Kilometers
- Year
- Fuel Type
- Selling Type
- Transmission
- Owner

The target variable is `Selling_Price`.

## Feature Engineering

The following features were created:

- Brand
- Car Age
- Log Driven Kilometers
- Kilometers Per Year

## Machine Learning Model

Random Forest Regression was used to predict car selling prices.

## Data Preprocessing

The project uses:

- Missing value handling
- One-Hot Encoding for categorical features
- Feature scaling
- Train-test split

## Model Evaluation

The model was evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Project Files

- `car_price_prediction.ipynb` — Complete Machine Learning workflow
- `car data.csv` — Dataset
- `requirements.txt` — Required Python libraries
