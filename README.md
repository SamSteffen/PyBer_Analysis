# PyBer_Analysis

## Overview
To better understand PyBer ridesharing service accessibility for passengers in various city types (urban, suburban and rural), an analysis was prepared comprised of two datasets ("city_data.csv" and "ride_data.csv") of 2019 rideshare data using Python, Pandas, Jupyter Notebooks, and MatPlotLib.

An initial analysis of the merged datasets revealed the following:
- Comparing the average number of rides between each city type, the average number of rides in the rural cities is about 3.5 and 2.5 times lower than urban and suburban cities, respectively.
- There is one outlier in the urban ride count data (the city of West Angela has the highest rider count). 
- The average number of rides in the rural cities is about 4- and 3.5-times lower per city than the urban and suburban cities, respectively.

![Fig3](https://user-images.githubusercontent.com/104729703/178143053-f56c640f-9353-4e27-93ce-7f2098a71ce5.png)

- From the combined box-and-whisker plots of 2019 Ride Fare data (above), we see that there are no outliers. However, the average fare for rides in the rural cities is about $11 and $5 more per ride than the urban and suburban cities, respectively. 
- The average number of drivers in rural cities is nine to four times less per city than in urban and suburban cities, respectively. 

While the above analysis revealed discrepancies among rideshare revenue according to city type, to better understand the spending trends among rideshare users within different city types over time, further analysis was necessary. To visualize the spending trends among rideshare users within different city types (urban, suburban, rural) by week, a summary DataFrame of the ride-sharing data by city type was created that showed the total rideshare fares for each city type by week.

## Results
Using the merged dataframe of the "city_data.csv" and "ride_data.csv" datasets, the following rideshare findings were collected:

### Ride Data by City Type
* Total Urban Rides: 1,625
* Total Suburban Rides: 625
* Total Rural Rides: 125

### Driver Data by City Type
* Total Urban Drivers: 2,405
* Total Suburban Drivers: 490
* Total Rural Drivers: 78

### Fare Totals by City Type
* Total Urban Fares: $39,854.38
* Total Suburban Fares: $19,356.33
* Total Rural Fares: $4,327.93 

### Rider Fare Averages by City Type
* Average Fare Per Urban Ride: $24.53
* Average Fare Per Suburban Ride: $30.97
* Average Fare Per Rural Ride: $34.62

### Driver Fare Averages by City Type
* Average Fare Per Urban Driver: $16.57
* Average Fare Per Suburban Driver: $39.50
* Average Fare Per Rural Driver: $55.49

The data above is summarized in the following dataframe:
<img width="625" alt="image" src="https://user-images.githubusercontent.com/104729703/178146456-9019c594-3f09-43ec-a750-a2a6f64888ca.png">

To visualize the spending trends among rideshare users within different city types (urban, suburban, rural) by week, the summary DataFrame of the ride-sharing data by city type was created that showed the total rideshare fares for each city type by week. This DataFrame is pictured below.

<img width="154" alt="fares_summary_df" src="https://user-images.githubusercontent.com/104729703/178143317-0822110d-987b-4168-80ac-3d79ee08af21.png">

From the above dataframe, a multiple-line graph was made using matplotlib to show the total weekly fares for each city type. Below is a line graph depicting the weekly fare summary for rideshares in each of the three city types, Rural, Suburban, and Urban:

![Pyber_fare_summary](https://user-images.githubusercontent.com/104729703/178145596-ec2b205e-be37-4775-842c-fd968120b358.png)

The above line-chart makes it easy to see several disparities in ride-sharing data among different city types:
* As would be expected, the total rideshare fares per week are highest for urban rideshares, lower for suburban, and lowest for rural.
* The above chart reveals slight discrepancies in the quantities of rideshares used on week-to-week basis. The end of Feburary proved to be consistently high across all three city types in terms of fares.
* As far as general trends, urban rideshare fares show a gradual increase between January and March, and a slight overall drop between March and May; suburban and rural rideshare fares fluctuate marginally. 
* The shape of these lines also indicate that there is a correlation between the fluctuation of rideshare fare accrual and city type; the more money accrued, the greater the fluctuation in accrual over time.
* All three city types show fairly consistent rideshare use between the months of January and May (that is, there do not appear to be outliers in this dataset).

# Summary: 
Based on the results described above, three business recommendations for addressing disparities among the city types can be made:
1. Supply and demand dictates that the rides are cheaper for riders in the city, but also earn drivers less money. While rides are more expensive for riders in rural areas, drivers in rural areas earn more money. To raise the number of drivers available in rural areas, incentives exist to recruit rural drivers through marketing and advertising campaigns that leverage higher wages available per ride, which, over time, could reduce the cost of rides in rural areas for rideshare users.
2. The end of February is consistently high in its fare accrual across the city types. The penultimate week in February represents the maximum fare for urban and suburban city types and the second-highest value for rural. This finding suggests that demand for rides around this time of year is high. This could be a good time to launch a marketing campaign to make customers aware of services and to recruit more drivers. 
3. It could also benefit this analysis to begin collecting data around ride-share destination categories (residential, airport, restaurants) to determine the cause of this uniform rise in rideshare use at the end of February. It is to be supposed that urban rides are cheaper because they are more frequent and potentially shorter than rides in rural areas, but we lack comprehensive data to say this for sure.
4. The end of March shows the highest fare for rural rideshares, while between January and March, there is a gradual increase in rideshare fare accrual for urban rideshares, the highest grossing city type. It could be of great benefit to this analysis to cross-check this data with weather data from each city to determine whether a correlation exists between increased use of rideshares and outdoor temperature.

