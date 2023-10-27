# Stock-Predictions

## 1 - Introduction

Stock predictions are the cornerstone of financial markets, aiming to anticipate future price movements of individual stocks or broader indices. Through the analysis of historical data, market trends, and various economic factors, investors and analysts strive to make informed decisions about buying, selling, or holding stocks. These predictions play a crucial role in shaping investment strategies, risk management, and overall financial success. 
In this dynamic realm, accurate forecasting is both an art and a science, offering opportunities for gains and challenges in navigating market volatility.

## 2 - About this Project

Suppose our goal is to generate profits through stock trading while strictly avoiding short-selling. To achieve this, we will develop a machine learning model designed to forecast whether a stock's price will rise on the following day. If the model indicates an increase, we will make a purchase; otherwise, we will refrain from trading.

Our primary focus is on maximizing true positives, which represent occasions when the algorithm correctly predicts price increases. Therefore, we will evaluate the algorithm's performance using precision as our chosen error metric, calculated as true positives divided by the sum of false positives and true positives. This approach ensures that we minimize potential losses associated with false positives—instances where we purchase stock, but the price actually decreases.

In pursuing this strategy, we acknowledge that we may experience a significant number of false negatives—days when the algorithm predicts price declines, yet prices rise. However, our priority is risk mitigation over profit maximization.

## 3 - Content

1 - Importing Libraries

2 - Loading Data

3 - Data Visualization

4 - Preparing Data

5 - Spliting Data

6 - Training a Machine Learning Models
    
    A) - RandomForestClassifier

    B) - KNN Model
    
    C) QDA
  
7 - Validating Models

8 - Creating a Backtesting Engine

9 - Adding More Predictors

10 - Models Performance

12) - Saving Models

13) - Results























