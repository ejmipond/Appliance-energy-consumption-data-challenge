### Appliance-energy-consumption-data-challenge
This is my first data science challenge, where I tried to utilize the ML models to predict the energy consumption of Appliances in a household. The target value in this challenge was the "Appliances" column. 

The data was obtained from Kaggle - https://www.kaggle.com/loveall/appliances-energy-prediction.

I split the original data set into two data sets - one involving the series data (all, excluding the "date" column) and
timeseries data (only "date" and "Appliances"). 

For the series data, the ML models I trialed were: Linear Regression, LassoCV, RidgeCV, Random Forest, Extra Trees, and Gradient Boosting. The model that yielded the best score was Extra Trees. 


