# MDM-AIML-03
# Regression Models and Gradient Descent for Linear Regression

## AIML Practical Assignment

This practical implements Regression using Linear Regression for a real-world student performance prediction problem and implements Gradient Descent optimization for Linear Regression.

## Problem Statement

1. Develop a Regression Model for predicting student marks based on the number of hours studied and evaluate its performance using appropriate metrics.

2. Implement and analyze Gradient Descent optimization for Linear Regression.

## Objectives

- To implement Linear Regression for predicting student marks.
- To evaluate the regression model using MAE, MSE, RMSE and R² Score.
- To implement Gradient Descent for optimizing Linear Regression parameters.
- To analyze the convergence of Gradient Descent using Mean Squared Error.

## Dataset

The dataset contains two variables:

| Feature | Description |
|---|---|
| Hours_Studied | Number of hours studied by a student |
| Marks | Marks obtained by the student |

### Dataset

| Hours Studied | Marks |
|---:|---:|
| 1 | 35 |
| 2 | 40 |
| 3 | 45 |
| 4 | 50 |
| 5 | 55 |
| 6 | 60 |
| 7 | 65 |
| 8 | 72 |
| 9 | 80 |
| 10 | 88 |

## Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

## Algorithms Used

### 1. Linear Regression

Linear Regression is used to model the relationship between study hours and student marks.

The equation of Linear Regression is:

y = mx + b

where:

- `y` = predicted marks
- `x` = hours studied
- `m` = slope
- `b` = intercept

### 2. Gradient Descent

Gradient Descent is an optimization algorithm used to minimize the Mean Squared Error of the Linear Regression model.

The algorithm repeatedly updates the slope and intercept using the calculated gradients until the cost function converges.

## Performance Metrics

The Linear Regression model is evaluated using:

### Mean Absolute Error (MAE)

Measures the average absolute difference between actual and predicted values.

### Mean Squared Error (MSE)

Measures the average squared difference between actual and predicted values.

### Root Mean Squared Error (RMSE)

Represents the square root of the Mean Squared Error.

### R² Score

Measures how well the regression model explains the variation in the target variable.

## Project Structure

```text
Regression-Gradient-Descent/
│
├── regression.py
├── gradient_descent.py
├── dataset.csv
├── README.md
└── screenshots/
    ├── regression_output.png
    ├── regression_graph.png
    └── gradient_descent_graph.png
