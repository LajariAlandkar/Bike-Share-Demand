# Bike-Share-Rental
Predicting rental count for bike

# Introduction

Bike sharing systems are a means of renting bicycles where the process of obtaining membership, rental, and bike return is automated via a network of kiosk locations throughout a city. Using these systems, people are able rent a bike from a one location and return it to a different place on an as-needed basis. Currently, there are over 500 bike-sharing programs around the world.

In this project, we would combine historical usage patterns of bike with weather data in order to forecast bike rental demand in the Capital Bikeshare program in Washington, D.C.

# Problem Statement
Predict the total count of bikes rented during each hour covered by the test set, using only information available prior to the rental period.

# About data
Data Fields
 * datetime - hourly date + timestamp
 * season - 1 = spring, 2 = summer, 3 = fall, 4 = winter
 * holiday - whether the day is considered a holiday
 * workingday - whether the day is neither a weekend nor holiday
 * weather - 1: Clear, Few clouds, Partly cloudy, Partly cloudy 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
 * temp - temperature in Celsius
 * atemp - "feels like" temperature in Celsius
 * humidity - relative humidity
 * windspeed - wind speed
 * casual - number of non-registered user rentals initiated
 * registered - number of registered user rentals initiated
 * count - number of total rentals
    
    
Important Notes:
 
 * Hourly Data for two years
 * Training Set: First 19 days of each month Test Set: 20th to end of month



