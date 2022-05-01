# Bikesharing

## Project Overview
The purpose of the project is to provide analysis of the August Citibike data to convince investors that the bike-sharing program in Des Moines is a solid business proposal.

## Resources
 * Tableau Public Application Software
 * Jupyter Notebook
 * Python, Pandas DataFrame
 * Files Citi Bike trip data: 201908-citibike-tripdata.csv.zip
	* 201908-citibike-tripdata.csv
	* NYC_CitiBike_Challenge.ipynb
	* citibike_data.csv (File with modified tripduration column using Pandas)
	  [NYC_CitiBike_Challenge.ipynb](https://github.com/timbialek/Bikesharing/blob/main/NYC_CitiBike_Challenge.ipynb)


## Results

Visualizations Created for this Tableau Story

Tableau Story Link: [Citibike Tableau Story](https://public.tableau.com/app/profile/timothy.bialek/viz/NYCBikeChallenge_16513578165240/CitibikeStory?publish=yes)

Rides and Gender Breakdown Dashboard:

This first graph shows the volume of riders and give a breakdown by Gender.  The majority of the riders are male and the most popular times the bikes are in user are between 8-9am and 5-9pm.
![](https://github.com/timbialek/Bikesharing/blob/main/Images/Dashboard.PNG)

Checkout Times by Users:

Shows the average trip duration by rider for the first 3 hours they have the bike with the average user having a 5-minute trip duration.
![](https://github.com/timbialek/Bikesharing/blob/main/Images/1-Checkout%20Times%20for%20Users.PNG)

Checkout Times by Gender:

Shows the average trip duration for riders by gender for the 1st 3 hours they have the bike.  The a with the majority of the male users having a 5-minute trip duration, female user having a 6-minute duration and Unknown genders having an 11-minute duration.
![](https://github.com/timbialek/Bikesharing/blob/main/Images/2-Checkout%20Times%20by%20Gender.PNG)

Trips by Weekday by Hour:

This visualization shows the most popular hours the bikes are in usage by day the day of the week.  Tee most popular times are between 5-6pm on Thursday evenings.  Generally speaking, the morning hours between 7-9am and the evening hours of 5-7pm get most of the usage during the week which would correspond to the commuter hours with the weekends being busy from late morning to early evening hours.
![](https://github.com/timbialek/Bikesharing/blob/main/Images/3-Trips%20by%20Weekday%20per%20Hour.PNG)

Trips by Gender - Weekday by Hour:

Shows the utilization break down by male, female and unknown genders.
![](https://github.com/timbialek/Bikesharing/blob/main/Images/4-Trips%20by%20Gender%20(Weekday%20per%20Hour).PNG)

User Trips by Gender and Weekday:

Here we can see that the numbers of users are Subscribers and Male. 
![](https://github.com/timbialek/Bikesharing/blob/main/Images/5-User%20Trips%20by%20Gender%20by%20Weekday.PNG)


## Summary

# Key Points:

	* Most common gender type is male
	* Most common user type is subscriber
	* Thursdays have the biggest spike in activity
	* Peak usage of the bikes is between 7-9am and 5-7pm which are common commuter times which suggests people are using the bikes to get to work.
	* Most users check out a bike for less than 30 minutes with a significant number check out the bikes for only 5 minutes

A couple of additional views to help understand the data would be look at age and gender together and to look at the check visualizations by distance traveled by bike instead of duration.  Since latitude and longitude are in the data file calculating the distance between the starting and ending locations would be possible.
