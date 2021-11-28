# Pyber_Analysis

As a Data Analyst at Pyber you will use your Python skills and knowledge of Pandas, create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, you’ll create a multiple-line graph that shows the total weekly fares for each city type. 

---

# Overview of Analysis

The goal of this analysis is the create a multi-line graph that shows the total weekly fares for each city type.  PyBer operates in 3 types of cities: urban, suburban, and rural.  For this analysis we calculated the total rides, total drivers, total fares, average fare per ride, and average driver fare for each city type.  This data created a summary data frame to help better understand ride-sharing by city type.

# Results

From the summary data frame, we can see that there is a trend between how populated a city is and the total number of rides, which directly affects the total number of drivers, total fare, and average fares by ride and driver.  Based on the summary data the total number of rides, drivers, and fares decrease as the cities become further from urbanized areas, the average fare per ride and per driver seems to increase.  This can be explained by the accessibility of PyBer in rural areas.  Having less drivers in rural areas could lead to higher average fares per ride.

|          |'Total Rides' | 'Total Drivers' | 'Total Fares' | 'Average Fare per Ride' | 'Average Fare per Driver'|
|'Rural'   |125           |78               | $4,327.93     | $34.62                  | $55.49                   |
|'Suburban'|625           |490              | $19,356.33    | $30.97                  | $39.50                   |
|'Urban'   |1,625         |2,405            | $39,854.38    | $24.53                  | $16.57                   |

With the multiple-line chart, we can compare total fares by city type over a period of five months. The number of rides peak at the end of February and fluctuates during the month of March. All the graphs tend to follow the same trend throughout these months, except for the trend in suburban cities, where we see a sharper increase during the month of April. 

https://github.com/MicheleS3/Pyber_Analysis/blob/main/analysis/PyBer_fare_summary.png?raw=true

