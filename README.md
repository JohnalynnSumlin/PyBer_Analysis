# PyBer_Analysis

## Background

V. Isualize has given you and Omar a brand-new assignment. Using your Python skills and knowledge of Pandas, you’ll create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, you’ll create a multiple-line graph that shows the total weekly fares for each city type. Finally, you’ll submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

## What You're Creating/Overview

This new assignment consists of two technical analysis deliverables and a written report to present your results. You will submit the following:
* Deliverable 1: A ride-sharing summary DataFrame by city type
* Deliverable 2: A multiple-line chart of total fares for each city type
* Deliverable 3: A written report for the PyBer analysis (README.md)

## Results

For this analysis, we were provided with a dataset for city data and a dataset for ride data. The city information had information on city name, the number of drivers in the particular city, and the city type(urban, suburban, rural). The ride dataset has information on the city name, date and time of the rides, the fare of the ride, and the ride ID. Looking at our datasets, city name was one data that they both had in common, so we were able to combine them through the city name. From there, we performed calculations to find the total rides, total drivers, and total fare for each city type. This information was then used to calculate the average fare per ride and the average fare per driver. Then we were able to join all of the calculations into a new summary dataframe.
![1](https://user-images.githubusercontent.com/94920551/166937749-da6390b7-d4b1-4e41-b744-6b1da634ca9d.png)
The next item for our analysis is to create a multi-line graph for total weekly fares by each city type. Going back to our combined dataset, we were able to use a method called pivot.(), which is similar to creating a pivot table in Excel, to essentially create a pivot table within Jupyter Notebook. We resampled the data into weeks, then we created the graph that V. Isualize asked us to create.
![1](https://user-images.githubusercontent.com/94920551/166937933-77b1e708-f923-43c5-b180-7f524b25cbb5.png)

From our analysis, we can see that there are differences in values between the different city types of our data. Though rural areas have the least number of total rides and drivers, but they yield higher average fare per ride and average fare per driver when compared to suburban and urban city types. This could be because the length of each ride is longer and/or further compared to suburban or urban areas, which would increase the fare of each ride. The same could be true for why there might be lower total rides and total drivers because the distance between destinations are further, thus would increase the fare for each ride and people would shy away from taking Pyber due to the higher cost of the ride. This could also be a contributor to why there are less drivers overall in rural areas.

## Summary

* The urban city rides make more revenue than the rural area but rural city rides are more profitable than the urban area.
      * So, it would be great to focus on improvising the plan to make urban cities rides more profitable.
* Also, it would be great to focus on drivers count, though urban cities have less rides than the drivers count.
* Increase the per mile charges in urban cities because there are more short trips and Average fare per driver is less.
* To increase the drivers count , they can charge more to drivers who is consistence in their work.
