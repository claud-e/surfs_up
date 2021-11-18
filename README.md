# Surf shop analysis

## Overview

An investor is looking to invest in a surf and ice cream shop in Hawaii, he has concerns about the weather and believes it could be a hindrance to the success of the business. This analysis is looking to find weather patterns based on observations provided by weather stations placed around the city of Oahu, specifically for the months of June and December. Pandas and SQLalchemy are the tools to be used in this analysis.

## Results

- We can Observe that June is somewhat warmer than December, which is to be expected, but the difference is not so large as to fall outside of the standard deviation.
- There are almost 200 observations more in June than in December. There might be a reason for that, it would be worth it to look into it.
- Minimun temperatures in December are lower than in June, which again is to be expected considering the time of year.


![December temperatures](/Challenge/Dec_temps.png)



![June temperatures](/Challenge/June_temps.png)


## Summary

One query that would be interesting to explore is grouping temperatures by the stations and looking into the average, then seeing if there are outliers and identify the best places to be.

Another possible query is to look into the averages for the different years and look for trends which might be correlated with CO2 emissions. 
