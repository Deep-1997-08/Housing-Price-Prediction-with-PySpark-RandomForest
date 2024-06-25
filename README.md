# Housing Price Prediction with PySpark RandomForest

## Project Overview

This project aims to predict housing prices using the PySpark library and the RandomForest algorithm. The dataset used for this project is the California Housing Prices dataset, which includes various features such as the median income, total rooms, total bedrooms, population, households, and ocean proximity.

## Project Structure

The project is structured as follows:

1. **Data Loading**: The dataset is loaded into a PySpark DataFrame.
2. **Data Preprocessing**: This includes handling missing values, feature scaling, and encoding categorical variables.
3. **Feature Engineering**: Creating new features or transforming existing features to improve the model's performance.
4. **Model Training**: Training a RandomForest model to predict housing prices.
5. **Model Evaluation**: Evaluating the model's performance using various metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R-squared.

## Installation

To run this project, you need to have PySpark installed. You can install it using pip:

```sh
!pip install pyspark
