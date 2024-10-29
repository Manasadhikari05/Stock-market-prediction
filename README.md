
# Stock Market Prediction using Historical and Sentiment Analysis of News Data

## Project Overview
This project involves predicting stock prices using historical data and sentiment analysis of news headlines. The model combines numerical stock market data with textual sentiment data to improve prediction accuracy. The approach leverages LSTM (Long Short-Term Memory) networks to forecast future stock prices.

## Dataset
### News Dataset
This dataset contains approximately 3.6 million historical news events from the Indian subcontinent, spanning from early 2001(2001-01-02) to Q1 2022(2022-03-29). It includes three columns: publish_date (date in yyyyMMdd format), headline_category (event category in ASCII), and headline_text (text of the headline in English). The data, sourced from the Times of India, provides insights into societal trends, priorities, and issues over time. This dataset is also available on Kaggle for further exploration and analysis. 
- Source: https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DPQMQH

### Historical Dataset
Historical stock price data for the project is sourced from Yahoo Finance (y-finance). This data includes daily stock prices and trading volumes, which are used to analyze and predict stock market trends. The dataset covers various features such as opening price, closing price, high, low, and volume.
- Source: https://pypi.org/project/yfinance/

## Libraries Used
- pandas
- numpy
- scikit-learn
- warning
- yfinance
- nltk
- matplotlib
- metrics
- keras

## Methods

### News Data Analysis
- Pretrained Model: NTLK VADER (Valence Aware Dictionary and sEntiment Reasoner).

### Numerical Data Analysis
- Model Type: LSTM (Long Short-Term Memory)
- Architecture: Three LSTM layers with 100 units each. Dropout layers to prevent overfitting. Dense output layer for price prediction.
- Activation Function: tanh
- Optimizer: Adam
- Loss Function: Mean Squared Error (MSE)

## Result
- R2 Score: 0.9920
- Explained Variance Store: 0.9936

## License
This project is licensed under the MIT License. See the [LICENSE](https://github.com/UjjawalGusain/Stock_Market_Prediction/blob/main/LICENSE) file for details.

# Actual Close Price vs Predicted Close Price

![Predictions](https://github.com/user-attachments/assets/ec898e64-0cf2-4ec4-a11f-fa9c7e99c57b)
