# PyBer-Analysis
## Overview 
You work as a data analyst for a ride sharing app company named Pyber. As your first big project, you are given rideshare data to analyze patterns and trends from the first half of 2019 and to present visualizations to the CEO. The data set contains information of different cities, city types, ride fares, and driver counts. 

### Purpose
The purpose of this analysis is to create a summary DataFrame of the ride-sharing data by city type. Using your knowledge of Python, Pandas and Matplotlib you’ll create a multiple-line graph that shows the total weekly fares for each city type.

### Resources
ride_data.csv, city_data.csv

## Results: 

In the summary DataFrame, you will set the city type as the index on the left. Then, merge the two data sets together by city and calculate the total rides, total drivers, total fares, average fare per ride, and average fare per driver based on the type of city. 

The total rides based on city type is:

  -Rural: 125

  -Suburban: 625

  -Urban: 1,625
  
The total drivers based on city type is:

  -Rural: 78
  
  -Suburban: 490 
  
  -Urban: 2,405
  
The total fares based on city type is:

  -Rural: $4,327.93
  
  -Suburban: $19,356.33
  
  -Urban: $39,854.38
  
The average fare per ride by city type is:

  -Rural: $34.62
  
  -Suburban: $30.97
  
  -Urban: $24.53
 
The average fare per driver by city type is:

  -Rural: $55.49
  
  -Suburban: $39.50
  
  -Urban: $16.57
  
As shown below, you will see the completed DataFrame of the calculations found. This shows the same information as above. 

![Pyber summary DataFrame](https://github.com/sydney-chen95/PyBer-Analysis/blob/main/analysis/Pyber%20summary%20DataFrame.png?raw=true)

Based on the DataFrame, you will see that rural cities have less total rides and less total drivers hence a smaller total fare compared to an urban city. This might be due to population size hence less people are taking rides. You can also conclude that there is a negative relationship between number of rides with the average fare per ride. In rural cities, the number of total rides is less than those in urban and suburban cities therefore the average fare per ride and average fare per driver will be higher compared to that of urban and suburban cities.

Next, you will plot a multi-line chart that shows the total weekly fares for each type of city between the dates January 1, 2019 to April 29, 2019. The multi-line chart below has three lines which represents the three city types in this analysis. 

![PyBer_fare_summary](https://github.com/sydney-chen95/PyBer-Analysis/blob/main/analysis/PyBer_fare_summary.png?raw=true)


Based on the multi-line chart, you can conclude that all three cities have similar trend with a peak in the last week of February. 

## Summary: 

Based on the results, some disparities among the cities types can be accessibility, racial discrimination, and wealth discrimination. Accessibility can be addressed by having more drivers in rural cities and also improved wait times for passengers before a driver leaves the pick up spot. Racial discrimination can come into play in all city types when drivers choose not to pick up passengers of a certain race. One way to fix this problem is to promote an inclusive ride sharing app for all people. Improving the app interface can also promote better attraction for riders who use the app. Wealth discrimination is another concern to tackle. This occurs when drivers refuse to pick up passengers from certain areas and travel the distance if they deem that the trip will not be worth it. Drivers can also refuse to travel to certain areas of town if they are judgemental of citizens in these areas because they believe the rider will not tip very well. This issue can be addressed by offering a fair wage to drivers.  

