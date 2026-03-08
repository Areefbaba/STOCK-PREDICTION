# STOCK-PREDICTION

## Project Overview

This project predicts stock **closing prices** using multiple Machine Learning algorithms.
It performs **data preprocessing, feature engineering, model training, and model comparison** to determine which algorithm provides the best performance.

The project demonstrates how Machine Learning can be applied to **financial time-series data** for predictive analytics.


##  Features

* Data preprocessing and datetime feature extraction
* Multiple Machine Learning models comparison
* Feature scaling for improved model performance
* Model evaluation using MSE and R² score
* Interactive prediction using user input
* Visualization of actual vs predicted prices


##  Machine Learning Algorithms Used

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* Support Vector Regressor (SVR)
* K-Nearest Neighbors (KNN)

The best performing model is selected based on **highest R² score and lowest MSE**.


## Dataset

The dataset contains historical stock data with the following features:

* Open
* High
* Low
* Close
* Volume
* Year
* Month
* Day
* Hour
* Minute

The **Close price** is used as the target variable for prediction.


##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

##  Model Evaluation Metrics

The following metrics are used to evaluate model performance:

* Mean Squared Error (MSE)
* R² Score

These metrics help determine which algorithm predicts stock prices most accurately.

##  Example Prediction Input

Enter Open Price: 180
Enter High Price: 185
Enter Low Price: 178
Enter Volume: 3500000
Enter Year: 2024
Enter Month: 6
Enter Day: 10
Enter Hour: 10
Enter Minute: 30
```
Output:
```
Predicted Closing Price: 182.43
```
