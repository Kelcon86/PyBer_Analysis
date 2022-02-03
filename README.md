# PyBer_Analysis

## Overview 
The CEO of PyBer, a ride-sharing app company, has asked that all of the rideshare data from January to early May of 2019 be analyzed and that visualizations be created to display the data. 

## Results
The data from our city_data and ride_data CSV's were combined to create a single dataset. Using the GroupBy function I got a count of the total rides and drivers for each city type, the total amount of fares for each city type and the average fare per ride and per driver for each city type. The results can be seen in the graph below. The data showed that the number of rides was far greater in urban areas with 1,625 compared to rural city types with only 125 rides. The number of drivers was also far higher in urban areas with 2,405 drivers compared to only 78 drivers in rural areas. Suburban areas fell in the middle in both categories with 625 rides and 490 drivers. Fares in rural areas were the highest on average at $34.62 and subsequently rural drivers had the highest average fares at $55.49. In comparison drivers in suburban areas had average fares of $39.50 and drivers in urban areas made the least with average fares of only $16.57. 

<img width="609" alt="Screen Shot 2022-02-03 at 12 47 28 PM" src="https://user-images.githubusercontent.com/60076980/152409144-3ddd0cc7-595d-4faa-9748-d49bb5cf9bb4.png">


A new dataframe was then created to show the total weekly fares for each type of city, which can be seen in the graph below.  

<img width="266" alt="Sum_By_Week" src="https://user-images.githubusercontent.com/60076980/152409857-89e133be-52d0-4b52-93bf-9ddd601ffc60.png">


<img width="979" alt="Total_Fare_By_City_Type" src="https://user-images.githubusercontent.com/60076980/152407593-e3d4d21a-c3ae-4cce-b6d2-5f7c4c5ab2a8.png">


## Summary: Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.
