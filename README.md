 <h1>EDA_US_Accident-2016-2021</h1>
<img align="right" alt="coding" width="400" src="https://cdn.dribbble.com/users/207059/screenshots/16573416/media/4f24405796465a71b2691f94f5e5d1f8.gif">

- The dataset is taken from kaggle. 
- The dataset includes information about accidents happend in US between 2016 to 2021
- It can be useful to prevent Accidents.

## Steps

1. #### Data Download

   The dataset has been downloaded from kaggle using opendatasets library.

   Link of dataset from kaggle : https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents

2. #### Data Cleaning and Preparation

   Data Preparation and Cleaning is all about understanding the data in the file and
   fixing missing or incorrect values.
   
   first i loaded the file using Pandas library. Using the pandas library, i got to know more information about the dataset, like the numerical columns, missing      values,statistical information..etc

- Bar plot of Missing values per Column

![](Screenshots/Bar%20plot%20of%20Missing%20values%20per%20column.png)

More number of mssing values were in column "Number".

3. #### Exploratory Data Analysis

I performed analysis on columns like City, State, Temperature, start_time, and Start_Lat, Start_Lng.

- Top 20 cities by accident

![](Screenshots/Top%2020%20cities%20by%20accident.png)

More number of accidents were observed in Miami city.

- Distribution of cities by accident

![](Screenshots/Distribution%20of%20cities%20by%20accident.png)

The number of accidents is most number of cities is low (0-2000) and in few cities the number of accidents are more.

- hist plot showing more accidents occur on which day of the week.

![](Screenshots/hist%20plot%20showing%20more%20accidents%20occur%20on%20which%20day%20of%20the%20week.png)

More Accidents were observed on weekdays and less number of accidents on weekends.

- Distribution of accidents on weekends

![](Screenshots/Distribution%20of%20accidents%20on%20weekends.png)

on Weekends the peak accidents took place between 12 pm and 4 pm.

- Distribution of accidents according to Month.

![](Screenshots/Distribution%20of%20accidents%20according%20to%20month.png)

More number of Accidents were observed in December Month.

I Used Folium library to locate the accidents on world map using the Start_Lat and Start_Lng columns.

- HeatMap of accidents on map

![](Screenshots/heatmap%20of%20accidents%20on%20map.png)

## Summary and Insights

- Miami is the city in US that has observed more number of accidents between 2016-2021.
- States wise Highest number of accidents were observed in california followed by Florida.
- The number of accidents is most number of cities is low (0-2000) and in few cities the number of accidents are more.
- Less than 5 percent of cities have more than 1000 accidents.
- most accidents are between 0-100 and over 1100 cities have just reported 1 accident.
- a high percentage of accidents took place more in between 1 pm to 7 pm and the next higher percentage of accidents in between 6 am to 8 am in a week.
- more Accidents were observed on weekdays and less number of accidents on weekends.
- on sundays the peak accidents take place between 12 pm to 4 pm.
- More number of Accidents were observed in December Month.
- More number of accidents were observed near coastal areas.


### Follow me on <a href="https://www.linkedin.com/in/saraswathi-pandit-806796183/" target="blank"><img align="center" src="https://img.shields.io/badge/-SaraswathiPandit-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/saraswathi-pandit-806796183/" alt="Saraswathi Pandit" height="20" width="120" /></a>
