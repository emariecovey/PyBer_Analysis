# PyBer_Analysis

## Overview

This analysis is for PyBer, a ride-sharing app company. I performed an exploratory analysis on data and produced visualizations to look at relationships within the data. First, relationships between type of city (urban, suburban, rural) and the number of drivers, rides, and ride fares were analyzed. City type was also compared to percentage of total fares, riders, and drivers. Lastly, total fare by city type over time was examined. The analysis will be used to help PyBer increase access to ride-sharing services and determine avaliablity for underserved neighborhoods.

Python code was written in Jupyter Notebook and used pandas libraries to manipulate data. Visualizations, including line charts, pie charts, box and whisker charts, and bubble charts were created using matplotlib. 

## Results 

There were noticable differences between city types and corresponding data in the various plots: 

### City type vs. ride count, driver count, and ride fares

- Urban areas had more rides, more drivers, and lower fares, especially when compared to rural areas. 
- Suburban areas had fewer drivers and rides and higher fares than urban ares, but did have more drivers and riders and lower fares than rural areas. 
- Rural areas had the lowest amount of drivers and rides, and the highest fares.

The bubble chart below shows all of this in one chart, and the box plots below show city type with driver counts, ride counts, and ride fares per city in seperate graphs to see relationships in more detail. Average numbers of drivers, rides, and fares can be seen by the orange median line in the boxplots.

Overall Bubble Chart:

![bubble plot here](https://github.com/emariecovey/PyBer_Analysis/blob/main/Analysis/Fig1.png)

Driver Count Boxplot:

![driver count here](https://github.com/emariecovey/PyBer_Analysis/blob/main/Analysis/fig2.png)

Ride Count Boxplot:

![ride count here](https://github.com/emariecovey/PyBer_Analysis/blob/main/Analysis/fig3.png)

Ride Fare Boxplot:

![ride fare here](https://github.com/emariecovey/PyBer_Analysis/blob/main/Analysis/fig4.png)


### City Type vs. % of Total Drivers, % of Total Rides, and % of Total Fares

Total Drivers: 

- The vast majority (81%) of all drivers were from urban areas, while less than 3% of drivers were from rural areas. Suburban drivers made up 17% of the total

![total driver pie](https://github.com/emariecovey/PyBer_Analysis/blob/main/Analysis/fig7.png)

Total Rides:

- 68% of rides were in urban areas, 26% of rides in suburban areas, and 5% were in rural areas. 

![Total rides pie](https://github.com/emariecovey/PyBer_Analysis/blob/main/Analysis/fig6.png)

Total Fares:

- Most fares came from urban areas (63%), followed by suburban areas (31%). Rural areas produced 7% of total fares

![Total Fares pie](https://github.com/emariecovey/PyBer_Analysis/blob/main/Analysis/fig5.png)

### Total Fare by City type

Weekly total fares were charted throughout January - April 2019 by city type. Urban areas clearly have the highest amount of revenue from fares, followed by suburban and rural areas. Fares vary throughout the time period, and there don't seem to be any strong patterns over time. 

![total fare line](https://github.com/emariecovey/PyBer_Analysis/blob/main/Analysis/fig8.png)

## Summary

The goal of this analysis was to provide information to inform decisions on making ride sharing service availability more equitable throughout different types of cities. 

Here are three recommendations to help address disparities throughout the different city types:

1. Recruit more rural drivers. 

Only 2.6% of drivers were from rural areas, while 5.3% of rides were in rural areas. Average fare price is higher in rural areas. If there were more drivers in rural areas, perhaps the cost of rides in rural areas would decrease

2. Slightly increase prices in urban areas.

The average fare price in urban areas is more than $10 less than average price in rural areas, according to the ride fare data boxplot. Most rides are in urban areas, with just 5.3% of rides in rural areas. If a very slight surcharge was implemented in urban areas, that could offset discounts in rural areas to make prices more similar between the two areas. 

3. Advertise ride sharing services in rural areas. 

It is possible that the numbers of trips in rural areas is low because people in rural areas do not know about the availablity of ride sharing services. Additional advertising in rural areas could increase demand, potentially increasing the number of rides and drivers in rural areas, which could in turn drive down costs of rural rides. 