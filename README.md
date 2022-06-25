
# Exploratory on Bike Sharing data
### Data Source : UCI Repository : - [Bike Sharing dataset - Zip File](https://archive.ics.uci.edu/ml/machine-learning-databases/00275/Bike-Sharing-Dataset.zip)
## Problem Statement

###### Exploratory data analysis is performed on the mentioned dataset to find the following: -
        1. Which seasons has the maximum number of bikes being rented?
        2. At what duration of time in a day, the count of bike rent has tha maximum?
        3. When is the most bikes are rented during the holidays or no-holidays?

## Dataset Information: -

Bike sharing systems are new generation of traditional bike rentals where whole process from membership, rental and return back has become automatic. Through these systems, user is able to easily rent a bike from a particular position and return back at another position. Here, we have daily data for 2 years. The target variable is the total count of bikes rented during each day. The independent variables are various factors like humidity, temperature, windspeed, weathersituation, season etc.

## Attribute Information: -
Both hour.csv and day.csv have the following fields, except hr which is not available in day.csv

    - instant: record index
    - dteday : date
    - season : season (1:winter, 2:spring, 3:summer, 4:fall)
    - yr : year (0: 2011, 1:2012)
    - mnth : month ( 1 to 12)
    - hr : hour (0 to 23)
    - holiday : weather day is holiday or not (extracted from [Web Link])
    - weekday : day of the week
    - workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
    + weathersit :
        - 1: Clear, Few clouds, Partly cloudy, Partly cloudy
        - 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
        - 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
        - 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
    - temp : Normalized temperature in Celsius. The values are derived via (t-t_min)/(t_max-t_min), t_min=-8, t_max=+39 
             only in hourly scale)
    - atemp: Normalized feeling temperature in Celsius. The values are derived via (t-t_min)/(t_max-t_min), t_min=-16,
             t_max=+50 (only in hourly scale)
    - hum: Normalized humidity. The values are divided to 100 (max)
    - windspeed: Normalized wind speed. The values are divided to 67 (max)
    - casual: count of casual users
    - registered: count of registered users
    - cnt: count of total rental bikes including both casual and registered
## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/Kushagra7698) 

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kushagra-mohan-prasad-5175b2168/)
