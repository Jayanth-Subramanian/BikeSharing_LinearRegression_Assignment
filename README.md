# BikeSharing_LinearRegression_Assignment
> Analyze the data set from the US bike-sharing provider "BoomBikes", find out Which variables are significant in predicting the demand for shared bikes using EDA and use linear regression techiques to find out how well those variables describe the bike demands using multiple linear regression techniques

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## General Information
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic.
- The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
- They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know: Which variables are significant in predicting the demand for shared bikes and How well those variables describe the bike demands

## Conclusions
- We can see that the equation for best fitted line is:
  cnt = 0.0750 + yr(0.2331) + workingday(0.0561) + temp(0.5499) - windspeed(0.1552) + season_summer(0.0886) + season_winter(0.1307) + mnth_Sept(0.0974) + weekday_Mon(0.0675) - weathersit_2(0.0800) - weathersit_3(0.2871)
- Demand for bikes increases with yr, workingday, temp, season_summer, season_winter, mnth_Sept, weekday_Mon.
- Demand for bikes decreases with windspeed, weathersit_2, weathersit_3

## Technologies Used
- Python
- Pandas, Numpy, Matplotlib and Seaborn
- statsmodel
- sklearn


## Contact
Created by [@Jayanth-Subramanian]