# PyBer with Matplotlib

## Overview of the Project

### Purpose

After having started work at PyBer, a ride-sharing app company, as a data analyst the assignment was to analyze the totality of the rideshare data from January to early May of 2019. After doing so it was also necessary to create visualizations to show the CEO of the company. The data analyzed was done so through the inspection of two different data sets, those of the city specific data and the ride specific data. These two were combined into one data frame and after inspection the data was analyzed. During the course of this work, the data analysis generating the overall summary contained the information for the summary of rides for each city type, the summary for each city type, and the summary for drivers for each city type. Tables showing this data were created, as well as differing charts to visualize and communicate the information.

### Challenge

For the PyBer Challenge, the final part of the assignment for the presentation to the CEO was to create two technical analysis  deliverables, along with this written report to present the results. The first of these tasks was to create a ride-sharing summary DataFrame by city type. This would contain by writing code to ascertain the total numbers of rides, total number of drivers, the total fares for each city type, the average fare per ride, and the average fare per driver for each city type. The second goal was to create a multiple-line chart of total fares for each city type. This was accomplished by creating such a chart that was informative and visually intriguing as well.


## Analysis

### Deliverable 1: PyBer Summary DataFrame

After creating the necessary code and running it for the first deliverable the following PyBer Summary DataFrame was created.

![This is and image](https://github.com/johnjphenom/week5_matplotlib_hw/blob/main/Resources/PyBer_Challenge_Deliverable_1.png)

This chart points out the stark difference between the ride sharing trends amongst the differing types of cities: Urban, Suburban, and Rural. When it comes to 'Total Rides' for the those in Suburban areas had five times amount of rides as the Rural areas and the Urban areas had thirteen times the amount of 'Total Rides' in the Rural areas. For the comparison of Suburban to Urban the latter was 2.6 times the former. This trend of increasing counts continues from Rural, to Suburban, to Urban when it comes to the 'Total Drivers' for each respective type of city. Now the inverse correlation when it comes to magnitude of the observed variable is present when looking at the 'Average Fare per Ride'. The cost for rides in Rural cities was 1.1 times that of that in the Suburban cities and the cost for rides in Rural cities was 1.4  times the cost of a ride in Urban cities. When it comes to the monetary value of 'Average Fare per Driver' the trend continues in the same direction. For this statistic the 'Average Fare per Driver' in a Rural city is 1.4 times that of and Suburban city and 3.3 times that in an Urban city.

### Deliverable 2: PyBer Multiple-Line Chart of Total Fares for Each City Type

Below is the multiple-line chart detailing the trends for 'Total Fares' for each city type. 

![This is and image](https://github.com/johnjphenom/week5_matplotlib_hw/blob/main/analysis/PyBer_fare_summary.png)

It shows the trend with regard to this variable for each city type of the time period of January 2019 through April 2019. Overall, the general shape of each line per city type follows the same trend. It is lower at the beginning of the year, peaks in late February, decreases slightly over the course of April. The more informative information from this visualization is the order of magnitude difference between the 'Total Fare by City Type' for each category. We start by noting that the 'Total Fare by City Type' is the greatest for Urban cities, then Suburban cities are next, and the lowest total value is from Rural cities. That of Urban cities is greater than the 'Total Fare' for Rural cities by an order around five. The 'Total Fare by City Type' is about 1.7 times greater when it comes to comparing Urban to Suburban cities.  


## Summary

After parsing through the data and examining the multiple-line chart some trends become clear and from this come recommendations can be made to the CEO. When it comes to Rural cities it is possible that additional drivers are needed to increase the availability of rides for customers. If the total count of rides can be increased by a good amount the 'Total Fares' for this type of city will increase at a good rate because the 'Average Fare per Driver' is much higher here. Rural areas are ripe for additional infrastructure to the service that will generate additional revenue. It can also be said that increasing the number of drivers in Urban areas would be advantageous because it appears the service is used more frequently in this type of city. The volume of rides can be increased here and it will add to the availability of the service to those that clearly want to use it. 

The best course of action would be to roll out the increase in drivers slowly in the Rural cities to first determine if the demand is wanted for the service and more rapidly in Urban cities where it have been proven that customers want to use PyBer. When it comes to Suburban cities a more conservative approach than that in Urban cities is needed, while still doing so more aggressively than in Rural cities. Overall, growth can be achieved in all sectors with investment but it would be most prudent to direct the majority of that investment into Urban cities.
