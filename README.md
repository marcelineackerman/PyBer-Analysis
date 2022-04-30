# PyBer-Analysis

## Overview of the analysis

An analysis of rideshare data for the company PyBer, using Python, Pandas, and Matplotlib to create charts and visualizations by city type. Specifically:

###  A summary DataFrame by city type
- A chart showing the Total Rides, Total Drivers, Total Fares, Average Fare per Ride, and Average fare per driver, based on type of city (Urban, Suburban, or Rural).

### A multi-line chart of total fares by city type
- A multi-line graph that shows the weekly fare totals by city type (Urban, Suburban, or Rural) over the course of several months in 2019.

## Results

### Summary of Rideshare Data by City Type

-image here

As demonstrated here, despite the relative increase in price as the city types move from Urban to Suburban to Rural, the total rides has a greater impact on the revenue generated from rideshares. There are 5x as many rides in suburban cities as there are in rural, and roughly 2.5x as many rides in urban cities as there are in suburban, translating to a near 5x increase in revenue for suburban vs. rural, and a nearly 2x increase in revenue between suburban and urban.

Notably, the total number of drivers does *not* directly correlate to an increase in revenue. This is demonstrated most effectively by the urban data, where there are significantly more drivers than actual rides given. Rural drivers gave roughly 1.6 rides per driver, suburban 1.3 rides per driver, and urban only .7 rides per driver. This significantly reduces the average fare per driver as well, which is less than half of the suburban average.

### Weekly Fare Data by City Type

-image here

As shown above, each type of city remains relatively consistent in total fare throughout the span of January through May, with predictable spikes near the end of February. Urban fares tend to be more prone to spikes and dips, but the overall tendency remains consistently high compared to suburban and rural cities.

The beginning of April shows a spike in rural fares, a gradual increase in urban fares that dips back down by the end of the month, with a dip in suburban fares that spikes back up by the end of the month. This could be attributed to the warming weather, encouraging rideshare users to travel more, or by holidays near the beginning of April that bring in users who may not normally use rideshare services.

## Summary and Recommendations

To summarize, there are a few notable changes that could be made to increase profits for PyBer

### Recommendation 1:

- Either reduce the number of drivers in Urban cities, or increase advertising for PyBer in urban cities. While the proportion of drivers increases, the change is not reflected in revenue and actually lowers average fare per driver. A decrease in drivers means a decrease in competition for remaining drivers, and increase the average fare per driver, but also puts a large amount of people out of work. An increase in advertising instead could bring in more users and therefore fill the need for work among urban drivers.

### Recommendation 2:

- Increase fares for rural rides. The demand for rural rides is higher than suburban and urban rides, as demonstrated by higher proportion of rides-to-driver. The fares for rural rides are already 13% higher than suburban for an overall ~30% increase in rides per driver, which leaves room for growth in rural fare prices.

### Recommendation 3:

- Include mileage distance data in the data for a more accurate analysis. Urban cities tend to be more compact and rides are likely for shorter distances, whereas Rural cities are spread far and thin, increasing mileage for the average ride. This may account for the average fare increase between urban and rural cities, but would need further testing to confirm.