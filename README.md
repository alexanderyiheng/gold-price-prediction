
Gold Price Prediction using LSTM
This project involves predicting the daily closing price of gold (XAUUSD) using Long Short-Term Memory (LSTM) neural networks. The script utilizes financial data, including historical gold prices and the Volatility Index (VIX), to train and evaluate the LSTM model.

Project Overview
The main components of the project include:

Data Preparation: The script begins by loading and preprocessing financial data, specifically daily gold prices (XAUUSD) and the Volatility Index (VIX). It handles missing weekend data and performs necessary data transformations.

Exploratory Data Analysis (EDA): The script provides a summary of the data using descriptive statistics and visualizations. It includes plots showing the historical trend of gold prices and VIX, as well as moving averages.

Correlation Analysis: The correlation between gold prices and VIX is explored through joint plots and a heatmap, revealing insights into the relationship between these two financial indicators.

LSTM Model Building: The LSTM model is constructed using TensorFlow and Keras. The script includes data preprocessing steps such as normalization and splitting the data into training and testing sets.

Training and Evaluation: The LSTM model is trained using historical gold price data. The script evaluates the model's performance by calculating the Root Mean Squared Error (RMSE) on the test set.

Visualization of Predictions: The script visualizes the predicted gold prices against the actual prices, showcasing how well the LSTM model captures the underlying patterns in the data.

Project Structure
Data Folder: Contains CSV files for daily gold prices (xauusd_daily.csv) and the Volatility Index (vix_daily.csv).
Scripts: The main script (gold_price_prediction.py) encompasses all the steps mentioned above, from data loading to LSTM model training and evaluation.
Output Folder: Stores visualizations generated during the EDA and model evaluation phases.
Requirements
Python 3.x
Libraries: Pandas, Polars, NumPy, Matplotlib, Seaborn, Plotly, TensorFlow, Scikit-Learn
Usage
Install the required libraries using pip install -r requirements.txt.
Ensure the data files (xauusd_daily.csv and vix_daily.csv) are in the correct location (../data/).
Run the script (python gold_price_prediction.py) to execute the entire workflow.
Review the generated visualizations and model performance metrics.
Results
The project provides insights into the historical trends of gold prices, correlation with the Volatility Index, and employs an LSTM model to predict future gold prices. The README serves as a guide for users to understand the project structure, dependencies, and how to reproduce the analysis.