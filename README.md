Apple Stock Price Prediction (Short-Term)
📌 Overview

This task aims to predict the next day's closing price for Apple (AAPL) using historical stock data.
The model uses regression techniques to learn from Open, High, Low, and Volume features.

🔧 Steps Performed

Retrieved Apple stock data using yfinance

Created a target column: Next Day Close

Selected features for modeling:

Open

High

Low

Volume

Trained a Linear Regression model

Compared actual vs predicted closing prices using a line plot

📊 Skills Practiced

Time-series data handling

API-based data loading

Regression modeling

Prediction visualization

Model evaluation

🛠️ Libraries Used

yfinance

pandas

matplotlib

scikit-learn

▶️ How to Run
pip install yfinance pandas scikit-learn matplotlib
