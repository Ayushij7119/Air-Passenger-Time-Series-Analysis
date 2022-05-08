# Air-Passengers-Time-Series-Analysis-
Object:
This Project is developed to Analysis the changes in Number of Air Passengers travel per day and what may be the estimated 
rise or increase in thier numbers.


Models Used:
1)ARIMA
2)SARIMAX

Description:
(Step-by-step execution)
1) Import all Necessary libraries.They are-Pandas , Numpy, Matplotlib, Seaborn.
2) Load Air Passenger Dataset which is a CSV file.
3) Describe() function is used to get details of dataset.
4) Do Data cleaning of loaded Dataset, we use following functions-
    a. Nunique(): This function is used to identify unique value in a dataset.
    b. Isnull():  This function is used to to identify null values if present in a dataset.
5) Use set_index() function and visualize the passenger using plot().
6) Import adfuller from statsmodels.tsa.stattools Library(To check whether data is stationary or not).
7) Import autocorrelation_plot from pandas.plotting.
8) Import plot_acf,plot_pacf from statsmodels.graphics.tsaplots.
9) Import statsmodels.api as sm.
10) from statsmodels.tsa.arima_model import ARIMA
    ARIMA model is used for univariate Time Series Forecasting.
11)model_fit.summary() is use to display detail result of model.
12)then use SARIMAX model to get more accurate forcasting.
Display the result by graph using plot() function.

    
    
    
    

