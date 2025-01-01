# Prediction-Currency-Exchange

Currency Exchange Prediction

Introduction

Predicting currency exchange rates is an important task for individuals, businesses, and governments. Exchange rates influence global trade, investment decisions, and financial strategies. This project aims to predict the EUR/USD exchange rate using financial data and machine learning techniques.

The project uses historical EUR/USD data to analyze trends and train predictive models. It includes models such as Random Forest Regression, Artificial Neural Networks (ANNs), and Long Short-Term Memory (LSTM) networks, which are particularly effective for time-series forecasting.
Features and Methods

This project includes exploratory data analysis (EDA), feature engineering, and the application of machine learning models. The data, spanning from 2019 to 2024, includes daily open, high, low, close, and adjusted close prices for the EUR/USD exchange rate.

The data is preprocessed to handle missing values and normalized for better performance. Key analysis techniques include time-series plotting, distribution analysis, and feature importance analysis.

Three models are implemented:

    Random Forest Regression: A decision tree-based ensemble model that performs well with structured data and avoids overfitting by using randomized features.
    Artificial Neural Networks (ANNs): Neural networks capable of modeling complex relationships in data. They use layers of interconnected nodes to capture patterns.
    Long Short-Term Memory (LSTM): A type of recurrent neural network designed to capture dependencies in sequential data, making it particularly effective for time-series forecasting.

Performance metrics used to evaluate the models include:

    Mean Absolute Error (MAE)
    Mean Squared Error (MSE)
    R² (coefficient of determination)

Installation and Usage

To run the project on your machine:

    Clone the repository:

git clone https://github.com/ivanamarijanovic/Prediction-Currency-Exchange.git
cd Prediction-Currency-Exchange

Install the required dependencies:

pip install -r requirements.txt

Open the Jupyter Notebook:

    jupyter notebook

    Run the notebook file Currency Exchange Prediction.ipynb to preprocess the data, train models, and generate predictions.

Results

The project demonstrated that machine learning models can effectively predict currency exchange rates with varying levels of accuracy:

    The Random Forest Regression model provided good baseline results and was computationally efficient.
    Artificial Neural Networks captured non-linear patterns in the data and performed better than the Random Forest model in terms of accuracy.
    The LSTM model produced the most accurate predictions by capturing temporal dependencies in the data. However, it required more computational resources.

The results were evaluated using MAE, MSE, and R², and visualizations were used to compare predictions against actual exchange rates.
