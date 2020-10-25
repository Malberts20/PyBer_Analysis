# PyBer Analysis

## Overview of the PyBer analysis

Perform an exploratory analysis of ride sharing data by creating visualizations using Pandas and Matplotlib libraries.  This analysis will be utilized to 
improve access to ride sharing services and determine affordability for underserved neighborhoods.

Resources - Data Source : city_data.csv, ride_data.csv; Software: Python 3.8.5; Jupyter Notebook 6.1.4; Libraries: Pandas, Matplotlib

## PyBer Results
Ride sharing data is below:

![Data_frame_summary](https://user-images.githubusercontent.com/71353552/97111297-acd43200-16a3-11eb-9357-1c65a17bcb5a.PNG)

![Pyber_fare_summary](https://user-images.githubusercontent.com/71353552/97111303-b198e600-16a3-11eb-91f8-35c4fddf2769.png)

Results:
1. Urban > Suburban > Rural for number of rides, driver count, and total fares
2. Normalizing on Rural data, Suburban has 5.0X the number of rides, 6.3X the number of drivers and 4.5X the Total Fares
3. Normalizing on Rural data, Urban has 13.0X the number of rides, 30.8X the number of drivers and 9.2X the Total Fares
4. Looking at the ratio of Avg Fare per driver/Avg Fare per ride; Rural is 1.6X, Suburban is 1.3X and Urban is 0.7X
5. Monthly data is pretty consistent with the exception of the last few data point that show increasing Fare revenue in Suburban with downward trends in both Rural and Urban.

## PyBer Summary

Based on the above results, recommedations would be to reduce the number of drivers in the Urban area and add drivers in the Suburban and Rural areas.  These driver changes will help in "flattening" the normailization ratios, particularly for the Rural and Urban areas:
  1. Add 50 drivers to Rural
  2. Add 100 drivers to Suburban
  3. Reduce 400 drivers in Urban
  4. Continue to measure results and adjust as needed 
  
