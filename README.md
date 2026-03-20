ANN-Based Power Output Prediction

Overview

Features

* Predicts power output using
* Implemented using scikit-learn
* Handles real-world regression problem
* Includes model training and evaluation
* Saved trained model (`best_model.pt`)

Input Features

The model uses the following input variables:

AT → Ambient Temperature
V → Exhaust Vacuum
AP → Atmospheric Pressure
RH → Relative Humidity

Target Variable:
PE(Power Output)

 Dataset

* File: `powerplant_data.csv`
* Contains environmental features and corresponding power output
* Clean and structured dataset for regression

Results

* Model successfully predicts power output with good accuracy
* Suitable for real-world regression tasks
* Can be improved with hyperparameter tuning


Project Structure

├── ANN_regression.ipynb
├── powerplant_data.csv
├── best_model.pt
├── README.md
