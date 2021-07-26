# Bikesharing

## Resources
- Software: Tableau Public, VS Code, Python 3.7.8
- Data: 201908-citibike-tripdata.csv, Citibike.cvs

<br/>
<br/>

## Overview
The purpose of this analysis was to create several visualizations to determine the statistics for Citi bike trip rides for the month of August 2019. Jupyter Notebook was used to edit the original CSV to convert some of the data types, and Tableau was used to visualize the data. The statitics for August 2019 were broken down by several parameters, in order to determine total number of rides, peak operating hours, rides by gender, and several others. Once the data was used to create visualizations with Tableau, interactive filters were also applied for additional functionality. 

<br/>
<br/>

## Results

### 1. August 2019 Breakdown
For the month of August in 2019, we were able to see that there were a total of 2.3 million Citi bike rides taken.
Additionally, we were able to determine that the peak operating hours were between 5 P.M. and 7 P.M, and 12 A.M. to 5 A.M. were the slowest hours. 
![ride_overview](https://user-images.githubusercontent.com/82389466/126927059-3bbcde3a-ec9f-4c4f-9726-df528e8f9765.png)
<br/>
<br/>

### 2. Number of Rides per Hour and Gender
Second, we broke down the trip durations for each trip starting hour, and further broke this down by gender.
We can see that the shortest trips were between 12 A.M. and 1 A.M., with men having the most start times in this hour. Throughout the rest of the day, a similar number of trips occurred throughout the hour, and had varying times between 10-60 minutes.
![rides_per_hour](https://user-images.githubusercontent.com/82389466/126927533-fddd73fe-bbba-41d3-be0f-78a5c65c8cda.png)

<br/>
<br/>

### 3. Trips by Hour of Weekday and Gender
Third, we created a visualization to determine the number of trips per hour for each weekday, and further broke this down by gender. 
We can see that the most trips occured on Monday, Tuesday, and Thursday, between the hours of 5 P.M. and 7 P.M.. 8 A.M. during the weekdays also saw a higher number of trips. 
We can also see that the majority of these rides during these hours and days were by male users.
![trips_by_hour_day](https://user-images.githubusercontent.com/82389466/126927694-46e899ba-cd6d-48bc-b980-36879ae0530d.png)

<br/>
<br/>

### 4. Trips by Gender, and Subscribers vs Users by Gender
Lastly, a visualization was created to determine the number of rides by gender, and the number of users vs subscribers by gender. 
We can see that the vast majority of rides were by males, at 65.28% of all rides, and females at 25.10%. 
Additionally, the majority of subscribers were male, and had the most rides during Monday, Tuesday, and Thursday.
![trips_by_gender](https://user-images.githubusercontent.com/82389466/126927852-0490f5e2-7971-4e15-99eb-60511ad2aeaf.png)

<br/>
<br/>

## Summary
Overall, we can see that August 2019 was a very busy month for Citi, with over 2.3 million trips taken. The most trips occurred on Monday, Tuesday, and Thursday, and the majority of trips and subscribers were male. 
A visualization to compare day of week to trip duration could be created, to see which days users get the most out of their bikes. Additionally, a visualization of the most used bikes could be created, to see which bikes may require the most maintenance.
