# PyBer Analysis

## Overview of Project
The general goal of this project is to perform exploratory analysis on the following datasets -- [city_data.csv](https://github.com/cgurbatri/PyBer_Analysis/files/6544026/city_data.csv)
and [ride_data.csv](https://github.com/cgurbatri/PyBer_Analysis/files/6544027/ride_data.csv)
-- to determine the relationships between total rides, total drivers, total fares, and average fare per ride and drive by city type. Note, that these files are also available in the Resources folder. 

The analysis and visualizations will ultimately help improve PyBer's access to ride sharing services and determine its affordability for underserved neighborhoods.

## Results
A summary dataframe is shown in **Challenge Table 1** below and also available in the analysis folder. 
<img width="554" alt="summary_df" src="https://user-images.githubusercontent.com/45336910/119691380-854f6e80-be18-11eb-94af-1b620477441c.png">

Table 1 suggests that urban cities have a greater number of total rides, total drivers, and total fares, while rural cities have the least. However, the inverse is true for average fare per ride and avergae fare per driver where those values are greatest in rural areas and least in urban cities. 

Specifically, the trend in total fares by city type can be resampled to explore only the months of January 2019 through April 2019, as shown in **Challenge Fig. 1** below. This analysis correlates with Table 1 above, suggesting that there rural cities generally  have lower total fares and urban cities have the highest total fares and suburban cities fall in between. Visualizing the data over months reveals that there is a consistent increase in total fares regardless of city type at the end of February. 

<img width="722" alt="Challenge_Fig  1" src="https://user-images.githubusercontent.com/45336910/119694163-fc860200-be1a-11eb-971a-f4b3f06e81b0.png">

Also included in the analysis folder are: 
Fig. 1 -- bubble chart of the number of rides per city and average fare
Fig. 2 -- box and whiskers plot of the number of rides per city type
Fig. 3 -- box and whiskers plot of the fares per city type
Fig. 4 -- box and whiskers plot of number of drivers and city type
Fig. 5 -- pie chart of % total fares by city type
Fig. 6 -- pie chart of % total rides by city type
Fig. 7 -- pie chart of % total drivers by city type

Major findings from the figures above include:
* There is one outlier in the urban ride count data (Fig. 2) -- this outlier was included in the analysis
* Average number of rides in rural cities is about 4 and 3.5 times lower per city than urban and suburban cities respectively (Fig. 2). **Ultimately, urban cities have the highest ridership demand.**
* Fig 5-6, provide a nice visualization of the summary Table 1, showing that a large percentage of total rides, total drivers, and total fares are from urban cities. 
* Urban cities have more drivers than suburban/rural cities
* Rural cities have the highest average fare per ride and per driver
* Urban cities have the greatest ratio of total drivers to total rides (perhaps a surplus of drivers), thus enabling a lower average fare per ride and fare per driver than seen in suburban and rural cities. 

## Summary
Based on the analysis above, the following three lerecommendations are suggested:
* The cost for PyBer is greatest in rural cities, which could discourage potential use of PyBer services. Based on analysis of driver to ridership rations, increasing the number of drivers in rural cities could potantially help lower these costs and ultimately increase ridership and revenue. 
* Additionally, placing a cap on the fare in rural cities could also address help maintain fare affordability.
* Drivers in urban cities are earning less than drivers in rural cities, which could discourage drivers from working in urban cities. Perhaps other driver incentives could be offered to encourage drivers to continue to work in urban cities. 
