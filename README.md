# forecast-energy-consumption
Forecasting energy consumption can be cruicial to have a sense of how much energy/power needs to be produced. The objective of this work is to predict future monthly energy consumption from time series data. The data includes hourly enerergy consumption of different states in the US collected by a regional transmission organization - PJM. Different exploratory data analysis are performed on the data to detect the daily, weekly, monthly and yearly trends. To predict future energy consumption, several models (ARIMA, PROPHET, LSTM) are trained on the time series data. Finally, the performance of different models are compared to predict monthly energy consumption. 

• EDA has been performed to discover daily, monthly, yearly energy consumption from the time series. 
• PROPHET with & without hoildays are trained (R2: 0.84, MAPE: 3.5%).
• SARIMAX 


<img src="graph.PNG" width="80%">
<img src="performance.PNG" width="50%">

