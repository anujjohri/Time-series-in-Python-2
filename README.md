# Time-series-in-Python-2

In this code, we will implement ARIMA models

ARIMA - AutoRegressive intergrated moving avg technique


AR - auto regressive

parameter - p  - how many pervious time periods that needs to be considered(known as lags)

The value of current time period is obtained depending upon the values of previous time periods 



MA - moving avg - works on error term on each lags

parameter - q - number of lags

The value of current time period is obtained depending upon the error terms of previous time periods 


ARMA

parameter - p , q - combination of both

better model because we consider both the observation value and the error terms

ARMA not suitable when we have trend and seasonality in data



ARIMA

works well when we have trend 

parameter- d - order of diff used to remove the trend component from the data 

parameter - p, q 

if d=0 , it becomes ARMA



SARIMA

works well when we have trend and seasonality 

(p,d,q) - trend

(P,D,Q) - seasonality 

will take 2 set of parameters
