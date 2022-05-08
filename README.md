# Py_Ber-Analysis
## Overview 
We were tasked to report visualizations for PyBer on ride share data. If used effectively, this will help leadership at PyBer determine how to best approach ride-sharing in upcoming markets by affordability factors. 

The study provided the proper CSVs to hold all PyBer data on three city region types: Urban, Suburban, and Rural. 

For each city type, we attempted to uncover the necessary information amongst the following: 
1. Total rides
2. Total drivers
3. Total fares
4. Average fare per ride or driver 
5. Total fare by specific city type 

To do all of our visualizations, we imported the matplotlib and pandas dependencies. 
In reference to our CSVs, we had access to both the city_data and ride_data files, which were then merged into one source. 
We created our merged dataframe as pyber_data_df. 
Here are the first five outputs: 
![image](https://user-images.githubusercontent.com/102266450/167278089-72465073-4ddf-4b05-b46b-7e658c430791.png)


## Results

### First Deliverable
As mentioned, by leveraging Pandas via the Python file in our Jupyter Notebook; we were able to create key dataframes for the categories above. 

Initially, we had the PyBer_Analysis file to look through these dataframes. 
We then created the challenge file in hopes to present the "Total Fare by City Type" figure (seen below). 
![image](https://user-images.githubusercontent.com/102266450/167278023-c467435f-c279-4a12-9305-57a28958c958.png)

To get this chart, we first looked at the 3 city types, and found the total rides for each.
![image](https://user-images.githubusercontent.com/102266450/167278137-c559d592-05f8-46e2-a2dd-fcbc06d2602e.png)

We then found the total drivers in each city type:
![image](https://user-images.githubusercontent.com/102266450/167278145-beae5879-8885-486b-a109-71bb08267206.png)

We replicated similar steps for total amount of fares by city type, average fare per ride, and average fare per driver. Respectively, here are the outputs for each series: 
![image](https://user-images.githubusercontent.com/102266450/167278207-f5bffda4-1562-4d86-9877-ae8c9dc5ef51.png)
![image](https://user-images.githubusercontent.com/102266450/167278209-035770a3-52bb-4e94-afb1-f61fd8d684dd.png)
![image](https://user-images.githubusercontent.com/102266450/167278211-d1fd291e-a6c8-411d-b3b6-1fa4010a6029.png)

Upon finding each of these, we then created the pyber_summary dataframe. 
![image](https://user-images.githubusercontent.com/102266450/167278229-c633a59f-579c-4812-b0a6-1a05266991b1.png)

## Second Deliverable
By created the summary dataframe, we then turned our attention towards having a sum of fares dataframe, and using the pivot table function. 

We ultimately found a dates dataframe, per the request of using the loc method between two specific dates. 
In doing so, we found the following: 
![image](https://user-images.githubusercontent.com/102266450/167278291-9376ae8d-bc6c-4648-a9fe-a8572e0b929d.png)

## Chart 
Once again, although the previous two deliverables led to the creation of our chart, here are the steps we took to ensure the plot was formatted correctly: 
![image](https://user-images.githubusercontent.com/102266450/167278303-5fd02187-add7-4bfc-9e8c-e2258f194a86.png)

## Summary
Here are three recommendations we hold according to our data: 
1. We need to question if this data would hold true if the study were larger. The city types of suburba, urban, and rural are a good start in terms of categorization---but it would still benefit PyBer for more sample data. 
2. However, we must also yield caution in focusing too much on the current city types. We recommend putting more resources in densley populated areas, as they are likely most underserved, and in need of the ride-sharing solutions than the rural locations. 
3. We recommend increasing the number of riders in all locations. Currently, there are only 78 total drivers in the rural bucket, with 125 total rides accounted for. For suburban areas, we see that 625 rides are served by only 490 drivers!
