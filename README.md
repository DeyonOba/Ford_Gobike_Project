# Ford_Gobike_Project

![image](https://i2.wp.com/www.dailycal.org/assets/uploads/2017/07/bikes_deborahchen_staff-copy-900x580.jpg)

## Introduction
This data set includes information about 183,400 individual rides made in a bike-sharing system covering the greater San Francisco Bay area.
The data set contains information regarding:
+ Duration – Duration of trip
+ Start Date – Includes start date and time
+ End Date – Includes end date and time
+ Start Station – Includes starting station name and number
+ End Station – Includes ending station name and number
+ Bike Number – Includes ID number of bike used for the trip
+ Member Type – Indicates whether user was a "registered" member  or a "casual" rider.
+ Start and End Coordinates - Includes the longitude and latitude of each start and end station.
+ Bike id.

From a similar dataset website [Capital Bikeshare](https://ride.capitalbikeshare.com/system-data) these are some question posed about the bike sharing system.

+ Which stations are most popular?
+ What days of the week are most rides taken on?
+ How long does the average trip take?

These Project would try to answer these questions and more.

## Installations
The Python modules used for this project are:
1. Numpy
2. Pandas
3. Matplotlib
4. Seaborn
5. Datetime
6. Folium

## Conclusions

These project successfully analized different features from the data set. I analized the popularity of different categorical variable with the result been that the most popular:
- Member gender are Males with a popularity of over 70 percent.
- Day of the week is Thursday.
- Hour of the day to start a ride is at 5 pm.
- Period of the day are during evenings.
- Age group are adults.

One relationship i found fascinating while investigating this data set is that, the categories that were least represented had higher average time duration than the most popular categories.

## Project Limitations

These are some limitations that could be further reasearched on.

1. No predictive algorithms was used in these project.
2. While clean the missing station names, a better approach could have been implimented by finding the nearest know station cooridinate to that location and then matching the station name to the missing stations, instead i droped all missing values.
3. The project could have explored more goegraphical maps e.g.(visualization of the top 10 stations with custom markers, and the most popular routes to take while taken in ride)

