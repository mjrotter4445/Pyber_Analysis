# PyBer Analysis
*Matplotlib Analysis for PyBer Ride-Share company*

## Project Overview 
### Purpose & Background

The purpose of this analysis is to perform data analysis for Ride-Share company *PyBer* and to tell a compelling story with data visualization. This analysis showcases the relationship between the type of the city -- urban, suburban and rural -- and their correlation between rides, drivers and fares, and congregates data from January to early May of 2019 and focuses on the following: 

-	The total number of rides for each city type. 
-	The total number of drivers for each city type.
-	The sum of the fares for each city type.
-	The average fare per ride for each city type.
-	The average fare per driver for each city type.
-	The total fares for each week by city type. 

### Overview the methods and code
The data is gathered in two different CSV files (the city data and the ride data). We then utilize **Jupyter notebook** and **Pandas Library** to inspect data, merge datasets,
perform calculations and create new data series and data frames to work with.  We are also using Python’s plotting library **Matplotlib** to make the more effective charts. 

### Resources
- Data Source: 
  - [PyBer_ride_data.csv](https://github.com/mjrotter4445/Pyber_Analysis/blob/main/Resources/PyBer_ride_data.csv)
  - [city_data.csv](https://github.com/mjrotter4445/Pyber_Analysis/blob/main/Resources/city_data.csv)
  - [ride_data.csv](https://github.com/mjrotter4445/Pyber_Analysis/blob/main/Resources/ride_data.csv)

## Results 
The first exercise in this challenge was to create a DataFrame with our combined data.  The new Pyber Fare Summary looks like this: 

![Pyber datafame](https://github.com/mjrotter4445/Pyber_Analysis/blob/main/Graphics/PyBer%20Summary%20DataFrame.png)
 
The next exercise was to build a pivot table to display the comparitive results. From the pivot table we were able to  
prdouce and display more meaningful data.  This multi-line chart tells the story in detail and is pleasant to read. 

1. The total number of rides for each city type. 
   - Here we see that total ridership in Urban cities and higher that Suburban and most significantly higher than 
   Rural cities - by 13 times higher.  
2. The total number of drivers for each city type.
   - We also know that total drivers in Urban cities is much higher that in rural cities.The number of drivers
   in Urban type is almost 31 times higher than Rural.  
3. The sum of the fares for each city type.
   - The fares in Urban cities is much higher than Suburban and Rural. In some cases, 9 times higher.  
4. The average fare per ride for each city type.
   - The average fare per ride is lower in Urban cities. The most economical ride is costs an average of $24.53 a ride
5. The average fare per driver for each city type.
   - Average fares are also lower in Urban cities than in Rural cities.  The average fare per driver is most economical
   at only $16.57 per driver
6. The total fares for each week by city type. The results below represent the total Fares by City type and the Urban, 
   Suburban, and Rural correlation between the average fares per week.    
   This data in the multi-line graph is from a period of time Jauary 2019 to May 2019.
   
 ![Multiple Line Chart Tot Fares by City Type](https://github.com/mjrotter4445/Pyber_Analysis/blob/main/Graphics/PyBer_fare_summary.png)

 
This data in the multi-line graph is from a period of time Jauary 2019 to May 2019.    


## Summary 
There are many noticeable differences between Urban, Suburban, Rural riders and drivers in terms of volume. The most obvious conclusions 
that can be drawn is that Rural environments have the least amount of riders and drivers while Urban environments have many more riders 
and drivers. Suburban enviroments fall right in between.  Urban cities, with their highest ride and rider count have the lowest aveage 
fare per driver.  It's most economical to ride in the city.  Also noticeable is the peak in the 3rd week of February for all 3 city types.    
