### Appliance-energy-consumption-data-challenge
This was my first data science challenge, where I tried to utilize the ML models to predict the energy consumption of Appliances in a household. The target value in this challenge was the "Appliances" column. 

The data was obtained from Kaggle - https://www.kaggle.com/loveall/appliances-energy-prediction.

There are 19735 rows and 29 columns - a timeseries column "date", a target value (dependent varibale) "Appliances", and 27 features (independent variables). The analysys showed that not all features were relevant to predict the target value. 

I split the original data set into two data sets - one involving the series data (all, excluding the "date" column) and
timeseries data (only "date" and "Appliances"). 

For the series data, I split the data into 80% train and 20% test. 
The ML models I trialed were: Linear Regression, LassoCV, RidgeCV, Random Forest, Extra Trees, and Gradient Boosting. The model that yielded the best score was Extra Trees. 


For the timeseries data, I attempted to forcast was SARIMA, though I intend to try with a different model as well. I aggregated the data by weeks and trained the model on the first 15 weeks, leaving the last 4 for testing. 


