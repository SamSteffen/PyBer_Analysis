# PyBer_Analysis

## Overview
To better understand ridesharing service accessibility for passengers in various city types (urban, suburban and rural) an analysis of two datasets ("city_data.csv" and "ride_data.csv") of 2019 rideshare data was performed using Python, Pandas, Jupyter Notebooks, and MatPlotLib.

An initial analysis of the merged datasets revealed the following:
- Comparing the average number of rides between each city type, the average number of rides in the rural cities is about 3.5 and 2.5 times lower than urban and suburban cities, respectively.
- There is one outlier in the urban ride count data (the city of West Angela has the highest rider count). 
- The average number of rides in the rural cities is about 4- and 3.5-times lower per city than the urban and suburban cities, respectively.

![Fig3](https://user-images.githubusercontent.com/104729703/178143053-f56c640f-9353-4e27-93ce-7f2098a71ce5.png)

- From the combined box-and-whisker plots of 2019 Ride Fare data (above), we see that there are no outliers. However, the average fare for rides in the rural cities is about $11 and $5 more per ride than the urban and suburban cities, respectively. 
- The average number of drivers in rural cities is nine to four times less per city than in urban and suburban cities, respectively. 

While the above analysis revealed discrepancies among rideshare revenue according to city type, to better understand the spending trends among rideshare users within different city types over time, further analysis was necessary. 

## Results
To visualize the spending trends among rideshare users within different city types (urban, suburban, rural) by week, a summary DataFrame of the ride-sharing data by city type was created that showed the total rideshare fares for each city type by week:

<img width="154" alt="fares_summary_df" src="https://user-images.githubusercontent.com/104729703/178143317-0822110d-987b-4168-80ac-3d79ee08af21.png">

From the above dataframe, a multiple-line graph was made using matplotlib to show the total weekly fares for each city type. 


# Challenge_Instructions
Use your repository README file to write your analysis of how to address any disparities in the ride-sharing data among the city types.

The analysis should contain the following:

# Overview of the analysis: 
- (Explain the purpose of the new analysis.)
The purpose of the new analysis is well defined. (3 pt)

# Results: 
- Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.
There is a description of the differences in ride-sharing data among the different city types. Ride-sharing data include the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type. (7 pt)

# Summary: 
- Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.
There is a statement summarizing three business recommendations to the CEO for addressing any disparities among the city types. (4 pt)

Deliverable 3 Requirements
Structure, Organization, and Formatting (6 points)
The written analysis has the following structure, organization, and formatting:

There is a title, and there are multiple sections. (2 pt)
Each section has a heading and subheading. (2 pt)
Links to images are working and displayed correctly. (2 pt)
Analysis (14 points)


