# PyBer_Analysis
## Overview of the analysis
We were given an assignment to analyze the total weekly fares for each city type using the data from a ride-sharing app, Pyber. We were tasked to create a multiple-line graph that shows the total weekly fares for each city type as well as compared the total fares. We then used the pivot function and resample function to create a new data set based on new criteria that we calculated, including the sum of the total rides by city type, the sum of the total drivers by city type, the sum of the total fares by city type, the average fare per ride by city type, and the average fare per driver by city type. We then used this data set to create the multiple-line graph. 

## Results: Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.
The first chart that we calculated shows: the total rides, total drivers, total fares, average fare per ride, and average fare per driver, as seen below.

![screenshot](https://user-images.githubusercontent.com/102992388/179813746-63bbfd94-8844-488e-abd9-9fdf09499d5e.png)

We then created a pivot table to get the total fares for each city type between the dates, 2019-01-01 and 2019-04-29. We then created a new dataFrame by  using the "resample()" function by week 'W' to get the sum of the fares for each week. 

![screenshot2](https://user-images.githubusercontent.com/102992388/179814284-c8b9174f-fc6b-434a-b9de-891e68b40f72.png)

As expected, the total fares for each city type is greatest for urban cities, followed by suburuban cities, then rural cities. This was visualized using a multiple-line graph.

![screenshot3](https://user-images.githubusercontent.com/102992388/179815065-51be2086-d7d2-4c1f-af79-fe3d413fa817.png)

## Summary: Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.

The demand for rides is highest in larger urban cities, however the rides in rural areas have the highest average fares per ride and driver. The rides in rural areas seem to be the most profitable. However, this can be a function of there being little need for drivers in the rural areas. This dataset doesn't consider consumer sentiment of how long the app takes to match them a driver. This can be something to consider investigating in the future to see if any city type is oversaturated with drivers. The ratio between total drivers and total rides is very disparate among the 3 city types. There are between 1 and 1.5 drivers per ride in rural and suburban areas, but this ratio drops in urban areas. Nonetheless, if the demand is being met, the CEO can consider increasing prices in urban areas, where demand is high to provide a higher average per ride and per driver as well. Demand seems to surge in all areas in the middle to the end of February, so the CEO may consider adding more drivers at this time to meet demand. In addition, in suburban areas, demand seem to surge in mid-April as well, so the CEO should consider increasing drivers to meet the demand. The CEO might also consider implementing surge pricing in these months to meet demand.
