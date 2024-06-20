# Car Price Prediction using Linear Regression

## Overview

This project aims to predict car prices using a linear regression model. The dataset used contains various features of cars which are utilized to build the prediction model.

## Dataset

The dataset consists of various attributes related to cars, including but not limited to:
- Make
- Fuel type
- Horsepower
- Engine size
- Price

## Steps and Methodology

1. **Data Loading and Preprocessing**:
   - Importing the dataset using Pandas.
   - Handling missing values by filling them with mean or fixed values.
   - Encoding categorical variables using Label Encoding.

2. **Data Splitting**:
   - Splitting the dataset into training and testing sets using an 80-20 split.

3. **Model Building**:
   - Building a linear regression model using the training data.
   - Calculating performance metrics like R-squared, adjusted R-squared, and coefficients.

4. **Model Evaluation**:
   - Predicting car prices on both training and testing sets.
   - Calculating errors and evaluating the model using metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and Mean Absolute Percentage Error (MAPE).

## Performance Metrics

- **Mean Squared Error (MSE)**: 11,650,759.82
- **Root Mean Squared Error (RMSE)**: 3,413.32
- **Mean Absolute Percentage Error (MAPE)**: 18.87%
- **Accuracy**: 81.13%

## Conclusion

1. **Model Performance**:
   - The model explains 81.13% of the variance in car prices, indicating decent predictive power.
   - The RMSE of 3,413.32 suggests that the typical prediction error is around this value.
   - A MAPE of 18.87% implies the predictions are, on average, off by about 18.87% from actual values.

2. **Strengths**:
   - The model has a good accuracy level, making it a useful tool for predicting car prices.

3. **Areas for Improvement**:
   - The high MSE and RMSE indicate potential for reducing prediction errors.
   - Strategies like feature engineering, exploring other regression models, and hyperparameter tuning can enhance model performance.

4. **Recommendations**:
   - **Feature Engineering**: Add or transform features to capture more relevant patterns.
   - **Model Selection**: Explore models like Ridge, Lasso, or non-linear models (e.g., Decision Trees, Random Forests).
   - **Hyperparameter Tuning**: Optimize model parameters using techniques like grid search.

