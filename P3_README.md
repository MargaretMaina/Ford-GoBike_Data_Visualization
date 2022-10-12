# Bike Share Analysis of the Ford GoBike System
## by Margaret Maina


## Dataset

The Ford GoBike System is a transportation system that is an integral part of the Bay Area- San Fransisco, East Bay and San Jose. Launched by Ford in 2017, the product was designed to be comfortable and easy to ride. Subscribers can pick or rent a bike from one station and drop it off at another when they subscrie to the service. However, the bikes are also available for any other customers too.

This dataset contained 183412 observations and 16 features from 2019.
After cleaning, I ended up with 174952 observations and 16 columns which I used for analysis and visualizations.
The columns are as follows:
* duration_sec
* start_time 
* end_time 
* start_station_id
* start_station_name 
* start_station_latitude
* start_station_longitude
* end_station_id
* end_station_name
* end_station_latitude 
* end_station_longitude 
* bike_id
* user_type 
* member_birth_year
* member_gender
* bike_share_for_all_trip

## Prerequisites
Before running the codes, you will need to install the following libraries:

Python
Pandas
Numpy
Matplotlib
Seaborn
Date


## Summary of Findings

1. The average bike trip duration for the Ford GoBike system was 10 minutes. Subscribers took way more bike trips than walk-in customers. More males than females and other took the trips over the dataset period.
2. The start location did not seem to affect the trip duration by much as more popular stations had a high trip average of up to 1000 minutes per trip while others had less than 20 minutes.
3. Customers(walk-ins) spent more time per trip than Ford GoBike subscribers.
4. Most users did not utilize the bike_share_for_all feature.
5. Overall, the majority of bikes were hired by users aged 25 to 45.

## Key Insights for Presentation

For the presentation, I will analyze the distribution of my main variable- trip duration in minutes.
I will also look at how a couple of factors influence the trip duration with my features being the age, gender and bike_share_for all.
Lastly, I will look for any intersections between age, trip duration and gender.