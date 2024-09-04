# Bike Sharing Assignment
> 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis. It is required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.
Data set used is day.csv


## Conclusions
- Total significant independent variables are 8: ['year', 'holiday', 'temp', 'windspeed', 'season_2', 'season_4', 'month_9', 'weather_condition_3']

Inferences of significant independant variables
temp coefficient is (0.5682) high and +ve shows registrations are more in high temperatures due to clear weather.
Bike sharing total count is increased from 2018 to 2019 (year coefficient 0.2334) after Covid-19. People are preferred to use bikes than public transport.
Next significant variable is weather condition 3(coefficient -0.2535): Light Snow, Light Rain + Thunderstorm + Scattered clouds causes for low registrations.
Next significant variable is windspeed (coefficient -0.1455): -ve shows bike riding is difficult hence registrations are reduced.
