# Zillow_TimeSeries_Prediction

### Zliiow Ocala Zipcode Prediction -A Time Series Project

![](Images\Map_Ocala.png)		

#### Overview:

**Case**

To do analysis--by utilizing Zillow's housing data and suggest the best real estate zip codes to invest in Ocala Florida today.

**Goal** : 

To Predict the best ZIPCODES to invest to have assured returns

**Assumption:**

•The invertor has a minimum of $125,000 to deploy upfront.

•The duration of staying invested is Minimum 3years and Max 10 years

•You seek to maximize growth potential by tapping into home value appreciation in“ Horse Capital of the World" OCALA

**Why OCALA:**

- Ocala is one of only five cities (four in the US and one in France) permitted under Chamber of Commerce guidelines to use the title, "Horse Capital of the World", based on annual revenue produced by the horse industry
- In the last decades of the twentieth century, the greater Ocala area had one of the highest growth rates in the country for a city its size.
- There are 30 elementary, ten middle and ten public high schools in Marion County

**Exploratory Data Analysis**

The Data is from Zillow :

•14723 Zip codes overall

•9 unique Zip Codes are there in Ocala

•The data time line is monthly from 1996-Apr to 2018 Apr 

•5 unique Zip Codes shortlisted based on largest mean

•The data time line is monthly from 1996-Apr to 2018 Apr 

#### The Process followed Post Basic EDA for each of the 5 Zipcodes

- Dickey Fuller test for testing stationary
- Log Transformation
- Dickey Fuller test for testing stationary post log transformation
- Differencing
- Dickey Fuller Test on Test Data
- Seasonal Decompose
- Auto Correlation
- Partial Auto Correlation
- Grid Search Auto Arima
- 3 ARIMA model with orders (0,2,0) (3,2,2) & (1,1,1)  for each Zip code
- Test Data Prediction to find Best RMSE
- 1 SARIMAX model (2,1,1) for each Zip code 
- 1 SARIMAX model (2,1,1) with Seasonal Order (2,1,1,12) for each Zip code 

