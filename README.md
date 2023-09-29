# House Price Prediction

This repository contains code for a house price prediction project using Python and scikit-learn.

## Introduction

In this project, we aim to predict house prices based on various features. We utilize a Linear Regression model for this prediction task. The dataset used for this project is available in the file `ParisHousing.csv`.

## Prerequisites

Before running the code, ensure you have the following libraries installed:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install them using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/house-price-prediction.git
   cd house-price-prediction
   ```

2. Download the dataset file `ParisHousing.csv` and place it in the project directory.

3. Run the Jupyter Notebook or Python script to execute the code.

4. You can modify the code to experiment with different machine learning models or parameters.

## Code Explanation

- The code performs data analysis, including data visualization, correlation analysis, and handling categorical variables.
- It splits the dataset into training and testing sets using `train_test_split`.
- It applies a Linear Regression model to predict house prices.
- Model evaluation is done using Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R²).

## Results

The project evaluates the Linear Regression model's performance with the following metrics:
- MAE: 1497.143245542242
- MSE: 3648827.320395196
- RMSE: 1910.1903885202637
- R²: 0.9999995776276368# house-price-prediction
