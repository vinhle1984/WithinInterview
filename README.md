# Within Interview Project

Created by Vinh Le

**Project Objective:**

 - analyze the influence of market sentiment on stock price movement

 - predict stock price trends or volatility based on sentiment.


**Introduction**
To meet the objectives above, I decided to use the stock ticker NVDA for my analysis. In the following section I will show how you can use a stacked LSTM model to predict the closing price of NVDA. LSTM (Long Short-Term Memory) is a special type of neural network designed to handle sequential data, meaning data where order matters, like in our example stock prices over time. I also performed sentiment analysis of news headlines to see how it can affect price movement. 

**Project Outline**

1. Stock Pricing Model
   
   1.1 Import Libraries
   
   1.2 Load Data
   
   1.3 Exploratory Data Analysis
   
   1.4 Preprocessing
   
   1.5 Build & Train LSTM model
   
3. Sentiment Analysis
   
   2.2 Load Data
   
   2.3 EDA
   
   2.4 Preprocessing
   
   2.5 Extract Sentiment from Text
   
3. Adding Sentiment as a Feature to LSTM Model
   
   3.1 Create new Dataset with Sentiment
   
   3.2 Preprocessing
   
   3.3 Train model with new feature (Sentiment)
   
   3.4 Evaluate new Model with Sentiment
   
 4. Model Comparison
    
 5. Summary
