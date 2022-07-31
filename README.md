# PyBer_Analysis
Analysis of rideshare data utilizing Python, Pandas, Matplotlib, and Jupyter Notebook

## Overview of PyBer Analysis
The purpose of this project is to utilize Python, Pandas, Matplotlib and Jupyter Notebook to automate the task of analyzing ride-sharing data across city types to improve access and determine affordability for underserved neighborhoods. Two datasources are merged to provide the final output of fare metrics by city type.  One source contains driver count by city and city type and the other contains ride details including date, city, and fare.  
The data utilized for the analysis can be accessed through the following links: ![city_data.csv](https://github.com/dschul01/PyBer_Analysis/blob/main/Resources/city_data.csv) and ![ride_data.csv](https://github.com/dschul01/PyBer_Analysis/blob/main/Resources/ride_data.csv)

## Results
The table below shows the metrics formulated from the PyBer data sources. 

![PyBer_Metrics.png](https://github.com/dschul01/PyBer_Analysis/blob/main/analysis/PyBer_Metrics.png)

The PyBer metrics indicate multiple disparities across city types:

* Urban cities have the highest demand for rides; 260% more than suburban cities, 1,300% more than rural cities
* Urban cities have most drivers of all city types; 491% more than suburban cities, 3,083% more than rural cities
	- Urban driver count exceeds total rides by 68%
	- Suburban and rural driver counts are below total rides
* Urban cities have the highest revenue, yet lowest average fares per ride and driver
* Rural cities have the lowest revenue, yet highest average fares per ride and driver

There could be multiple root causes driving the high variances of metrics between city types.  The summary below describes the need for more data in order to make more educated decisions. 


## Summary
I recommend the following actions take place in order to address the disparities among the city types

1. Research incentive opportunities and drivers' interest in accepting rides in the other city types.  The total drivers in urban cities is much higher than demand so drivers might be willing to pick up passengers in neighboring suburban and rural cities.

2. PyBer needs to start collecting more data such as time and distance of ride and city population densities.  These factors most likely have impacts on the significant ranges of average fares.  Higher fares might be preventing rural customers from utilizing PyBer's services and that can't be determined without more data.

3. Determine factors driving the lower and higher fares during the year.  The chart below shows mutiple points in time where there were peaks and dips for all city types (ex. late Feb peak, early Mar dip).  Additional data is needed to determine if more or less drivers are needed during those times.  Marketing incentives for customers could be implemented to increase demand as well as bring on more drivers if necessary.

![PyBer_fare_summary.png](https://github.com/dschul01/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)
 