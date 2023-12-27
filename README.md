# FlightFlow-Air-Traffic-Analysis
Analysing and Forecasting Air Traffic Variations at San Francisco Airport (SFO) with Advanced Time Series Modelling and Forecasting.

Given the variations in the Air Traffic at airport, we chose the dataset of
Air Traffic at SanFrancisco Airport (SFO) from the year 2005 - 2018.
To study these variations , irregularities in the passenger count, correct time
series model(s) and techniques must be used. <br>
The report comprehensively covers the entire workflow, from data cleaning and preprocessing to model fitting and forecasting the possible Air Traffic values based on the historical data.

Objective of the above Time series data includes :
1. Data analysis and cleaning
2. Finding out trends in data
3. Checking for Seasonality
4. Smoothening the data
5. Identifying parameters of the model
6. Fitting the right model
7. Calculating accuracy matrix
8. Forecasting future prices
<br>


Conclusion : 
SARIMA model was used as the time-series model.

1. The Air Traffic data was not very volatile, since the use of ARCH/GARCH model.
2. Data was made stationary (NoUnitroots). Thus an AR/MA or ARIMA or CNN model can be fitted.
3. Seasonality was present in the data, therefore SARIMA model gave better results.

<img width="399" alt="Screenshot 2023-12-27 at 7 02 44 PM" src="https://github.com/dwishashah/FlightFlow-Air-Traffic-Analysis/assets/123867488/26dea486-ee49-42b4-ba81-0a35efec5dd4">

   
