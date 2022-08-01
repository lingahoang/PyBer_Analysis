# PyBer_Analysis
An analysis of ridesharing data from the beginning of January 2019 to May 2019.

## Overview

### Purpose

## Result
At first, we joined data from city_data.csv and ride_data.csv for a full DataFrame displayed. After utilizing merged data from both of those files, we were able to delivered a ride-sharing summary by city type and a multiple-line chart of total fares for each city type.

### Deliverable 1: a ride-sharing summary DataFrame by city type
In other to pull together a summary, here are the numbers that we need beforehand:
  - Total rides for each city type
  - Total drivers for each city type.
  - Total fares for each city type.
  - Average fare per ride for each city type. 
  - Average fare per driver for each city type.

![PyBer_summary](https://user-images.githubusercontent.com/107448172/181309828-43a6ab68-865b-4bd1-b018-924e3174ea0b.png)

#### Total rides for each city type
![total_rides](https://user-images.githubusercontent.com/107448172/181332521-8a75b30c-f024-4a7b-906e-20b234d7df4a.png)

![Fig8](https://user-images.githubusercontent.com/107448172/181341665-c59bc7e3-5fc5-40dd-9336-848bd800dae4.png)

Data concluded number of rides in the urban area is twice more than the total number of rides from rural and suburban cities.

#### Total drivers for each city type.
![total_drivers](https://user-images.githubusercontent.com/107448172/181335832-ab51870a-6791-4d0f-8dad-1417d5208004.png)

![Fig9](https://user-images.githubusercontent.com/107448172/181341687-4826cade-7ddc-4199-a1e7-3aa14074fb9b.png)

Data concluded number of drivers in the urban area is four times more than the total number of drivers from rural and suburban cities.

#### Total fares for each city type.
![total_fares](https://user-images.githubusercontent.com/107448172/181336379-2aed4a01-e234-47f9-9ad4-f8892f04a942.png)

![Fig10](https://user-images.githubusercontent.com/107448172/181341700-6f721ebc-940b-4b67-ad2e-f9ec31b0c321.png)

Data concluded total fares in the urban area is 1.6 more than the total fares from rural and suburban cities.

#### Average Fare per Ride per city and average fare per driver per city.
While Urban has the highest number for all the previous analysis, this time, it has the lowest number, followed by Suburban and then Rural. As we can see:
  . Urban has the lowest fare of $24.53 per ride.
  . Suburban still stays in mid line between two cities, which has $30.97 per ride. 
  . But Rural claimed the has the highest rate at $34.62.

Fare per driver analysis also got a similar graph line, which placed Urban with the lowest fare per driver at $16.57, followed by Suburban in the midline which is $39.50 and Rural on the highest end of $55.48. 

### Deliverable 2: a multiple line plot that shows the total weekly of the fares for each city type

Resources: Python on Jupyter Notebook using Pandas and Matplotlib.

PyBer Fare Summary chart
![PyBer_fare_summary](https://user-images.githubusercontent.com/107448172/181341431-0709a957-0fc9-4601-8760-fc0258e2b01e.png)
 
The chart above captured the weekly total fare by city type in the four months period. During those period from January 1st, 2019 to April 28th, 2019; we can see some ups and downs trend but Urban still has the highest fare of all. 

## Summary. 

This analysis pulls data from three different type of city: urban, suburban, and rural. Which later concluded that urban has the highest number of total rides, total drivers, and total fares. Although, Rural seems to be the lowest city for those previous categories, the average fares per ride and per drivers placed Rural to the highest fare. 

Since we only have a small amount of data to analyze from, we can conclude the trend like above. However, the data didn't specify if those drivers had multiples rides or didn't complete any rides at all. So, there is nothing else we can concluded further. 


