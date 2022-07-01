## Bikesharing

## Overview of the analysis


The purpose of this project is to analyze NY CitiBike, to get results that might be useful for analyzing the viability of opening a bike-share system in Des Moines, Iowa.
For this analysis, Pandas would be used to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, a set of visualizations would be created to:
Show the length of time that bikes are checked out for all riders and genders. Show the number of bike trips for all riders and genders for each hour of each day of the week. Show the number of bike trips for each type of user and gender for each day of the week.
Finally, these new visualizations would be added to the one created in this module for the final presentation and analysis to pitch to investors.


## Resources


Tableau, Jupyter Notebook, Visual Studio Code


## Results


## Deliverable 1:
Using Python and Pandas functions, convert the "tripduration" column from an integer to a datetime datatype to get the time in hours, minutes, and seconds (00:00:00). After converting the "tripduration" column to a datetime dataytpe, export the DataFrame as a CSV file to use for the trip analysis.



![image](https://user-images.githubusercontent.com/96086671/176773459-ac1635bf-b930-424d-a402-122a78ca56c8.png)



 
## Deliverable 2:
Create Visualizations for the Trip Analysis:



![image](https://user-images.githubusercontent.com/96086671/176773851-0c2577a1-86bc-469b-b07c-1fb61ba9062d.png)



 
1.	There is a line graph displaying the number of bikes checked out by duration for all users, and the graph can be filtered by the hour.




![image](https://user-images.githubusercontent.com/96086671/176773935-cef9a639-8e8d-4917-8021-ca78aa65cbf0.png)


 

2.	There is a line graph displaying the number of bikes that are checked out by duration for each gender by the hour, and the graph can be filtered by the hour and gender.


 
 ![image](https://user-images.githubusercontent.com/96086671/176774045-4896e344-16f3-4ae2-a47b-9b7c3e8bc2d6.png)

 
 

3.	A heatmap is created showing the number of bike trips for each hour of each day of the week.

 
 
 ![image](https://user-images.githubusercontent.com/96086671/176774151-2ce065d4-e2a8-4712-b29c-97ab1fda774e.png)

 
 

4.	A heatmap is created showing the number of bike trips by gender for each hour of each day of the week, and the heatmap can be filtered by gender.

 
 
 
 ![image](https://user-images.githubusercontent.com/96086671/176774248-07b38a9e-7eb9-4d50-acf8-de683d4ad9f7.png)

 
 
 
 
5.	A heatmap is created showing the number of bike trips for each type of user and gender for each day of the week, and you can only filter by user and gender.



## Deliverable 3:

In Tableau, create a new Story using visualizations that will support the key findings you want to show.

1.	Use the five visualizations.



![image](https://user-images.githubusercontent.com/96086671/176774680-3456e487-199c-4c62-b68c-988926e1192d.png)


 

2.	Use at least two visualizations that you created in this module.



![image](https://user-images.githubusercontent.com/96086671/176774816-8b305e3d-5715-4464-a5ca-475538be3519.png)



 
# Checkout Times by Gender

This image shows a graph of gender and time of day that the bike share is utilized and how long of a trip the user took. Aside from the much higher number of male users, the graph shows a sharper increase in ride duration by males than females.

# Checkout Times for Users

This figure looks at the time that the bikes were ridden between subscribers and customers. According to the graph, subscribers are utilizing the bike share more during commuting hours where customers are opting to utilize the bike share more during weekends and non-peak commuting hours.

# Summary

This analysis helped to get an idea of what the Des Moines bike share program would look like by using data from New York City in August as the basis for the analysis.
The analysis shows there is a higher user base among males than females and subscribers primarily use the bike share program to commute to work during mornings and afternoon hours. Customers tend to utilize the program on weekends more throughout the day.

In the future, I would focus also on age-related data vis-a-vis the ages of subscribers versus customers.


https://public.tableau.com/app/profile/kofi.borsah/viz/Book3_16566806319550/AugustPeakHours?publish=yes
