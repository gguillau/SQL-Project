# <p align='center'> Chicago Ride Share Analysis </p>
<p align='center'>
  <img src="https://github.com/giova22i/Data-Science-Portfolio/blob/main/images/ridecover.jpg" />
    </p>


## Objective
Data Analysis on Chicago taxicab rides and weather reports to advise hypothetical ride-sharing company Zuber. What affects a taxi ride in Chicago? The goal of the project is to understand passenger passenger preferences and the impact of external factors on rides. Working with the database, we will analyze data from competitors and test a hypothesis about the impact of weather on ride frequency.


**Skills Used: Data Collection and Storage (SQL)**

## Data Description
A database with info on taxi rides in Chicago:

**neighborhoods table: data on city neighborhoods**

* name: name of the neighborhood
* neighborhood_id: neighborhood code

**cabs table: data on taxis**

* cab_id: vehicle code
* vehicle_id: the vehicle's technical ID
* company_name: the company that owns the vehicle

**trips table: data on rides**

* trip_id: ride code
* cab_id: code of the vehicle operating the ride
* start_ts: date and time of the beginning of the ride (time rounded to the hour)
* end_ts: date and time of the end of the ride (time rounded to the hour)
* duration_seconds: ride duration in seconds
* distance_miles: ride distance in miles
* pickup_location_id: pickup neighborhood code
* dropoff_location_id: dropoff neighborhood code

**weather_records table: data on weather**

* record_id: weather record code
* ts: record date and time (time rounded to the hour)
* temperature: temperature when the record was taken
description: brief description of weather conditions, e.g. "light rain" or "scattered clouds"

## Insights
After analyzing a public data sample of taxicab trips from November 2017 and weather reports, the following insights were discovered:
* Confirmed that weather conditions significantly influence the average ride duration, with bad weather leading to changes in duration.
* Identified downtown areas as popular drop-off locations based on the analyzed data.
* Observed a higher number of rides on days with good weather conditions.
* Suggested incentivizing drivers to participate during days with favorable weather conditions to capitalize on the increased demand.
* Discovered that most trips in Chicago end in the Loop area or downtown, suggesting Zuber could target this area for competition or focus on attracting customers outside this heavily serviced region.
* Proposed considering pricing strategies to account for weather effects, such as implementing a "bad weather" surcharge or pricing based on trip duration to reflect increased demand during inclement weather.

## Libraries Used
     Pandas
     Matplotlib.pyplot
     seaborn
     scipy.stats
     numpy
     Beautiful Soup
     Requests
     PySpark

## Background
This project is part of the Data Scientist training program from Practicum by Yandex. More info in link below:

https://practicum.yandex.com/data-scientist

