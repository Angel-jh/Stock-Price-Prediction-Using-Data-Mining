# Stock Price Prediction Using Data Mining

## Overview
This project explores the application of data mining and machine learning techniques in predicting stock prices using historical financial market data. The study focuses on improving prediction accuracy and supporting data-driven investment decision-making in highly volatile stock markets.

The project combines Long Short-Term Memory (LSTM) and XGBoost into a hybrid prediction model to capture both time-series patterns and complex non-linear relationships in stock market data.


## Objectives
- Apply data mining techniques for stock price prediction
- Analyze historical stock market trends and patterns
- Compare traditional analysis with machine learning approaches
- Improve prediction accuracy using hybrid models
- Support faster and more efficient investment decision-making


## Dataset
The project uses historical stock market data from four major U.S. technology companies:

- Apple (AAPL)
- Google (GOOGL)
- NVIDIA (NVDA)
- Microsoft (MSFT)

### Features Used:
- Open Price
- High Price
- Low Price
- Close Price
- Trading Volume

The dataset was collected over a 2-month period and processed using a rolling time-series approach where the previous 5 days were used to predict the 6th day.


## Technologies & Libraries Used
- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- XGBoost
- Matplotlib


## Data Preprocessing
Several preprocessing steps were performed to improve data quality and model performance:

- Data cleaning
- Handling missing values
- Data integration
- Feature transformation
- Data normalization using MinMaxScaler
- Data reduction
- Time-series sequence preparation


## Methodology

### Hybrid LSTM-XGBoost Model
This project uses a hybrid machine learning architecture:

### LSTM
- Captures sequential and time-series patterns
- Learns stock price trends over time
- Suitable for volatile financial data

### XGBoost
- Captures complex non-linear relationships
- Improves prediction stability and accuracy
- Handles feature interactions efficiently

The output from LSTM is used as additional input for XGBoost to improve overall prediction performance.


## Model Workflow
1. Collect historical stock data
2. Clean and preprocess the dataset
3. Normalize and transform features
4. Create time-series sequences
5. Train the LSTM model
6. Use LSTM outputs as features for XGBoost
7. Predict future stock closing prices
8. Evaluate prediction performance using MSE


## Results
The hybrid model successfully learned stock price movement patterns and achieved a low Mean Squared Error (MSE) of approximately 0.02, indicating strong prediction performance and model stability.

The model was able to:
- Capture market trends
- Predict short-term stock price movements
- Reduce prediction errors
- Improve decision-making efficiency


## Key Insights
- Hybrid models can outperform traditional analysis methods
- Combining time-series learning with ensemble learning improves prediction quality
- Data preprocessing plays a critical role in financial forecasting accuracy
- Machine learning can support investors in analyzing large-scale market data efficiently


## Limitations
Despite strong performance, the model still faces several challenges:
- Market volatility
- Data noise
- Risk of overfitting
- Difficulty integrating external factors such as news and investor sentiment


## Future Improvements
Potential future enhancements include:
- Integrating financial news sentiment analysis
- Adding macroeconomic indicators
- Using larger historical datasets
- Hyperparameter optimization
- Real-time prediction systems

---

## Author
Angelica Julie Herliman
