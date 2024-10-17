# Bitcoin Price Prediction

## Overview
This project aims to predict Bitcoin prices using machine learning models, particularly Long Short-Term Memory (LSTM) networks. The project leverages historical data and various Python libraries to perform data analysis, feature engineering, and visualization to provide insights into Bitcoin price trends.

## Project Features
- **Data Collection**: Historical Bitcoin price data sourced from [Kaggle](https://www.kaggle.com/datasets) or similar datasets.
- **Exploratory Data Analysis (EDA)**: Used **Pandas**, **Matplotlib**, and **Seaborn** to visualize trends, price distributions, and moving averages.
- **Feature Engineering**: Created new features such as moving averages and volatility indices to enhance model performance.
- **Machine Learning Model**: Implemented an LSTM model using **TensorFlow** to predict future Bitcoin prices.
- **Hyperparameter Tuning**: Optimized model accuracy through grid search and hyperparameter tuning.
- **Data Visualization**: Visualized predictions and actual prices using various graphs for investment insights.

## Key Libraries
- **Pandas**: For data manipulation and preprocessing.
- **NumPy**: For numerical computations.
- **Matplotlib & Seaborn**: For data visualization and graphical analysis.
- **TensorFlow/Keras**: For building and training the LSTM model.
- **Sklearn**: For data scaling and performance evaluation.

## Results
- Achieved a reasonable prediction accuracy for Bitcoin prices using the LSTM model.
- Visualized price predictions alongside actual prices to aid in investment decision-making.

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/msamil93/bitcoin-data-analysis
   ```
2. Navigate to the project directory:
   ```bash
   cd bitcoin-data-analysis
   ```
3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter notebook:
   ```bash
   jupyter notebook bitcoin_price_prediction.ipynb
   ```
## Future Work
- Implement additional models such as ARIMA and Prophet to compare performance.
- Explore more features for enhanced prediction accuracy.
- Integrate real-time data fetching using APIs.

## Project Link
You can view the project notebook [here](https://github.com/msamil93/bitcoin-data-analysis/blob/main/bitcoin_price_prediction.ipynb).

## Author
**Samil Tekinoglu**  
[GitHub](https://github.com/msamil93)
