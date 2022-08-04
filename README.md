# PyBer Ride Share Analysis

### Analysis Overview

The purpose of this analysis was to generate a summary dataframe from gathered PyBer ride share data and reformat the data to show the average ride fare per week
by city type. Then we assesses changes over time using Matplotlib to look at ride fares from Urban, Rural, and Suburban cities between 2019-01-01 and 2019-04-29.

### Analysis
_____________________________
#### Results

The summary dataframe for PyBer ride share data can be seen in Fig. 1 below. The summarized data shows that most rides are given in Urban cities (1625) where the least are given in Rural cities (625) and suburban cities being the middle (625). The total number of rides and the average fare per ride positively correlate with the total number of drivers, with the least amount of drivers being in Rural cities which also produce the lowest average fare and the most drivers in Urban cities which produce the highest average fare. Interestly, these data negatively correlate with the average fare per ride and the average fare per driver.  While rural cities have the lowest total rides, total drivers, and average fare produced, they have the highest fare per ride ($34.62) and highest average fare per driver ($8.06). Conversely, while urban cities have the highest total rides, total drivers, and average fare, they have the lowest average fare per ride ($24.53) and average fare per driver ($0.67). 
_____________________________
**Fig. 1: PyBer Ride Share Summary**

![ride_share_by_city](https://user-images.githubusercontent.com/108199140/182748344-efcabc1a-cb01-4636-8dbf-8ed3e69cb2ab.PNG)
_____________________________

This data was reformatted to visualize the sum of ride fares per week between the dates 2019-01-01 and 2019-04-29 (Fig. 2 & 3). While the data shows that the total fare by city type between Jan 2019-April 2019 does not fluxuate significantly over time, it shows that urban cities consistently produce the highest total fares and rural cities produce the lowest toal fares. Overall this data suggests that while rural cities are the most profitable for PyBer drivers having the highest fare per ride and fare per driver, urban cities are the most cost effective for PyBer ride share consumers having the lowest fare per ride.

_____________________________

**Fig. 2: Average Ride Fare per Week by City Type** 

![fare_by_week](https://user-images.githubusercontent.com/108199140/182749565-dadfb33c-4601-4b8b-8002-c23e7b0ba79c.PNG) 

**Fig. 3: Average Ride Fare Jan 2019-April 2019**

![ride_share_per_week](https://user-images.githubusercontent.com/108199140/182749652-667fe965-23b0-4623-9500-6f33f7784ce8.PNG)

_____________________________

### Summary

Based on this data, it could be recommended for PyBer to expand the radius of PyBer driver pings to reach more rural cities or remote areas to increase ride numbers in rural cities. Another recommmendation could be to lower the fare of rural city rides to make them more affordable and amenable to more of the rural city population. Lastly, incentivise drivers to driver in rural cities with bonus payments to increase the number of drivers in these areas to boost ride numbers. 






