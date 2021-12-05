# Stock Target Price Predictor
Metis Classification Module 4 Project

### ABSTRACT

I developed a classification pipeline that takes in a stock’s price data from the TD Ameritrade API, transforms the data using a series of custom functions and evaluates that stock relative to a trading system known as The Strat. The classification problem is: what is the probability that a stock will hit its target price using The Strat trading system? I trained the data on five models to find the model that best predicts on the test data. The model with the best performance was a tuned Random Forest, which predicted with a .74 accuracy on the test data. I then used this model to predict stock performance for the month of September, which returned a .80 accuracy score and 80% success rate on the top five stocks with the highest probability of success.

### Install
 The following libraries are required for this project:
 
  - NumPy
  - Pandas
  - Requests
  - Json
  - SQLite
  - SQLAlchemy
  - Scikit-learn
  - XGBoost
  - Pickle

### Data
  - [TD Ameritrade API](https://developer.tdameritrade.com/apis)
