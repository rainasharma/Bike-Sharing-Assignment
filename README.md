# Bike Sharing Assignment
Build a model which identifies variables significant in predicting the demand for shared bikes.This will be used by the management to understand and manipulate the business strategy to meet the demand levels and meet the customer's expectations.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## General Information
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demand
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.<br>

<b>Bike Sharing dataset</b> : day.csv

## Conclusions
As per the final model, the top 5 predictor variables that influences bike booking are:

- Temperature (Temp)
    - It has the most significant impact on bike rentals
- Windspeed
    - This creates a negative impact on bike renting as people do not opt to take a bike when the windspeed is high.
- Light Rain & Snow (weathersit =3)
    - This creates a negative impact on bike renting as people do not opt to take a bike in such a weather.
- Year (yr)
    - Rental increase with every year
- Sep 
    - It is month with high rentals, so company should promote more advertisments in this month
    
- As high temperature and good weather positively impacts bike rentals, it is recommended that bike availability and promotions to be increased during summer months to further increase bike rentals.</b>
<b>
- It is recommended to give utmost importance to these variables while planning to achieve maximum bike rental booking.


## Technologies Used
- Python Libraries - Numpy, Pandas
- Data Visualization Libraries - Matplotlib and Seaborne
- Linear Regression model libraries - Sklearn, Statsmodels
