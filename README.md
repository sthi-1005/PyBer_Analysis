# PyBer_Analysis

## Overview
Data analysis will be performed on raw data provided by 'PyBer', a ride-sharing company. The has been provided in 2 csv's: 1 containing information about the ride, and the 2nd containing information about cities PyBer is active in. The analysis will focus mainly on the differentiating between different 'City Types' (i.e. Rural, Urban, and Suburban).


## Results

### Total Fare

| Overview | Pie Chart Composition |
| ------------- | ------------- |
| ![Graphical Representation](analysis/PyBer_fare_summary.png) | ![](analysis/Fig5.png) |

- Total Fares by City Types is highly consistent; Urban cities provide the highest total fare, and Rural cities provide the lowest.
- During the period of analysis (January 2019 through April 2019, month-ended) Ubran cities account for nearly one-third of PyBer's Total Fares.

### Total Rides
| Box&Whisker | Pie Chart Composition |
| ------------- | ------------- |
|![](analysis/Fig2.png) | ![](analysis/Fig6.png) |

<p align="center">
  <img width="500" height="300" src="analysis/Fig1.png">
</p>
<p align="center">
<i>Note: Circle size correlates with driver count per city.</i>
</p>

- At first glance, the pie chart shows that the % composition of Total Rides per City Type resembles very closely to that of Total Fares.
- However, when looking at the Box and Whisker plot, the Urban cities have a much larger spread that Rural cities. This suggests that there is a possibility that performance in Urban cities may be harder to predict.
- It can also be observed in the scatter-plot that there is a correlation in Suburban and Ubran cities that as the total number of rides increase in the x-axis, the number of drivers (cirlce sizes) also increase.


### Total Drivers

| Box&Whisker | Pie Chart Composition |
| ------------- | ------------- |
|![](analysis/Fig4.png) | ![](analysis/Fig7.png) |

- Similar to the box and whisker plot of Total Rides, the Total Drivers for Urban city types are highly unpredictable as the spread is significant.
- The % composition of Drivers does not relate well in comparison to the other two above composition pie charts.



### Fare Breakdown
<b>Overview</b><br>
![](analysis/Fig3.png) 
| City Type  | Avg. Fare per Ride | Avg. Fare Per Driver |
| ------------- | ------------- | ------------- |
| Rural | 34.62 | 55.49 |
| Suburban | 30.97 | 39.50 |
| Urban | 24.53 | 16.57|

- It is seen that the average fare is significantly higher both per ride and per driver in Rural areas than Urban areas.

# Summary
Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.
- There is a statement summarizing three business recommendations to the CEO for addressing any disparities among the city types. (4 pt)
