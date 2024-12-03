## Erdos Data Science Bootcamp  

## SIGNS - Stock Insights from Global News Sentiments

This Project is a part of Erdos Institute Data Science BootCamp.
Authors : 

-- Hirak Bandyopadhyay

-- Kunal Mozumdar

-- Rishabh Bhardwaj

-- Yaman Sanghavi


### Objective:

The goal of this project is to predict whether stock prices will rise or fall based on sentiment analysis of financial and geopolitical news. The focus is on gathering sentiment data from news and social media platforms, analyzing relevant stock price factors, and building machine learning models to forecast stock price movements.

Accurate stock price prediction is crucial for investors and financial institutions which aid them in forming a more informed trading strategy. This project aims to study the historical behavior of markets and how various news events like financial news, geopolitical news of war and conflict, or even news or rumors about election results influence market behavior. By integrating this kind of sentiment analysis with financial data this project aims to optimize trading strategies by forecasting stock prices accurately. The following stakeholders would be benefactors of the project :  Financial analyst and Traders, Investment firms, Economist and Political Scientist and Individual investors. 

### KPIs

-- Prediction accuracy of future stock prices.

-- Correlations between market sentiment, specific global events, and stock prices.

-- Identify features that have a significant impact on stock predictions. 

### 

### Setting up the Environment

Check to make sure you have uodated conda by running the following in your command line interface :
```
conda --version
conda update conda
```

Set-Up environment : 

```
conda env create --file=SIGNS_env.yml
conda activate SIGNS_2024
```


### Data Collection and Preprocessing

-- Collected data on stock prices from Yahoo Finance - [yfinance](https://pypi.org/project/yfinance/)

-- Scrapped data for Stock news and Global News sentiments. 

-- Using tools like VADER and custom made lexicon we assigned sentiment scores to Financial News and Geopolitical News. 

### Feature Engineering and Modelling

-- Computed relevant target features to predcit : Next Day Closing Price, Next Day Standard Moving Average (SMA), Pecentage Change, Price Trend (Binary variable) and SMA Trend (Binary). Examined different features to understand which factors influence stock prices.

-- Models include : ARIMAX (Baseline Model), Linear Regression, Logistic Regression, Random Forest, Gradient Boosted Trees and XGBoost. 

-- Gradient Boosted Trees and XGBoost gave the best predictions. 






