# TIME SERIES MODELING WITH ARIMA FOR HOUSE MARKET IN HARRIS COUNTY, TX

![](images/houston.jpg)

## Introduction
 Real estate is an absolutely lucrative investment. However, without any logistic forecast and analysis, one can fall into dangerous traps easily. For instance, a company went bankrupt because they invested a large amount of funds into real estate just before the market crash caused by a recession. Therefore, this project's goal is to give a recommendation of Top 5 zip codes in Harris County, Texas to real-estate investment firms. Harris County's house market analysis was performed on time series dataset from Zillow Research Page - an American online real estate database company. The dataset consists of nearly 15,000 zip codes all around the U.S. and ranges from the year of 1996 to 2018. The evaluation of top models is based on the minimized Mean Squared Error (MSE) and the Return On Investment (ROI) yield. 

## Methodology
### 1) Data Preprocessing
  * Reshape from wide to long format
  * Check for Trend, Seasonality, and Residuals
  ![](images/trend_seasonal_noise.jpg)
  * Check for Stationarity
  ![](images/stationarity.jpg)

### 2) Data Exploration and Visualization
![](images/harris_value_over_time.jpg)

### 3) Time Series Analysis and ARIMA Modeling
  ### Based on MSE and ROI yields
  ![](images/model_77093.jpg)

### 4) Result Details of Top 5 Zip Codes in Harris County
![](images/top_5_value_over_time.jpg)


## Content
- <a href="https://github.com/linhmai19/housing_time_series_modeling/blob/master/zillow_data.csv">Dataset from Zillow Research Page</a> 

- <a href="https://github.com/linhmai19/housing_time_series_modeling/blob/master/time_series_modeling.ipynb">Time Series Modeling</a>

## Presentation
- Presentation Slides: <a href="https://github.com/linhmai19/housing_time_series_modeling/blob/master/time_series_presentation.pdf">Time Series Modeling Presentation</a>

- Oral Presenation: <a href="https://github.com/linhmai19/housing_time_series_modeling/blob/master/time_series_oral_pres.mp4">Time Series Modeling Oral Presentation</a>

- Blog Post: <a href="https://medium.com/@linhnp.mai/time-series-modeling-with-arima-for-house-market-in-harris-county-tx-289331a0971a">Time Series Modeling For House Market In Harris County, TX</a>




