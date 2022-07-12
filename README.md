# Ford Go-Bike Exploration
## by Ajibola Oyedeji


## Dataset

The dataset contains 183,411 bike rides with 16 variables on ride including ride 
duration, start and end latitude and longitude, user type, age and gender. Get 
the [dataset here](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv).

Feature engineering was done to calculate the trip distance in kilometers 
from the start and end latitudes and longitudes, age, and extract categorical
variables such as weekday, time of day and age group.


## Summary of Findings

In the data exploration, it was discovered that there was little to no relationship
between the distance, duration and ages of riders. During exploration, it was 
discovered that majority of the riders were middle-aged adults. While most rides took 
place during the morning and evenings generally, upon further exploration by days of 
the week, users most like likely commenced trips in the afternoon on weekends while 
all other days were during the mornings.

A time series plot shows a correlation between the total number of trips per day 
and the average distance covered. In addition, female gender rode for more distance
male users while only subscribers share rides.

## Key Insights for Presentation

For the presentation, I focus on duration of rides and distance covered looking 
at the distribution. there were high ranges of values and were transformed. The 
distribution of the categorical variables were introduced using barplots, box 
plots and violing plots.

Bivariate and multivariate explorations were thereafter carried out to see the 
relationship across measures and categorical variables.