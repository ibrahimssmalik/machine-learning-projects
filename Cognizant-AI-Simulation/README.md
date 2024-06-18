# Cognizant AI Job Simulation

This repository documents a job simulation on the Forage platform, focusing on data science and machine learning tasks. The project involved predicting stock prices for a business client using sensor data.

## Problem Statement

The objective was to predict product stock levels hourly based on sales data and sensor data provided by the client. The goal was to optimize product procurement strategies from suppliers.

## Project Overview

The project utilized a RandomForestRegressor for stock predictions. It includes three main tasks:

### Task 1 - Exploratory Data Analysis

- `eda.ipynb`: Jupyter notebook for exploring data.
- `sample_sales_data.csv`: Sample sales data used in EDA.

### Task 3 - Model Building and Interpretation

- `modeling.ipynb`: Notebook for building and interpreting the machine learning model.
- `sales.csv`: Sales data used for model training.
- `sensor_stock_levels.csv`: Sensor data related to stock levels.
- `sensor_storage_temperature.csv`: Sensor data related to storage temperatures.

### Task 4 - Machine Learning Production

- `model.py`: Python module for deploying the machine learning model into production.

## Usage

To run the project:

1. Open the Jupyter notebooks (`eda.ipynb` and `modeling.ipynb`) to view and interact with the code and data.
2. Install dependencies using pip by referencing `requirements.txt`:
    ```bash
    pip install -r requirements.txt
    ```
3. Follow instructions in the notebooks to execute cells and reproduce results.

## Conclusion

This project showcases the application of machine learning in predicting product stock levels using historical data and RandomForestRegressor. By leveraging these techniques, businesses can improve decision-making, manage risks effectively, and enhance operational efficiency in inventory management.