# BikeRental_RegressionProblem
It is a Forecasting problem where we need to predict the total rental count of each datetime.

### Dataset:

Input Features:<br>
['season', 'holiday', 'workingday', 'weather', 'temp', 'atemp', 'humidity', 'windspeed', 'year', 'month', 'day', 'dayofweek','hour']<br>
       
Target:<br>
['count']<br>

Objective:

You are provided hourly rental data spanning two years. 
    
For this competition, the training set comprises the first 19 days of each month, while the test set is from the 20th to the end of the month. 
You must predict the total count of bikes rented during each hour covered by the test set, using only information available before the rental period

