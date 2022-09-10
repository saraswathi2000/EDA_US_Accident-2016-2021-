# EDA_US_Accident-2016-2021-

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


More number of mssing values were in column "Number".

3. #### Exploratory Data Analysis

I performed analysis on columns like City, State, Temperature, start_time, and Start_Lat, Start_Lng.

- Top 20 cities by accident

More number of accidents were observed in Miami city.

- Distribution of cities by accident

The number of accidents is most number of cities is low (0-2000) and in few cities the number of accidents are more.

- hist plot showing more accidents occur on which day of the week.
More Accidents were observed on weekdays and less number of accidents on weekends.

- Distribution of accidents on weekends
on Weekends the peak accidents took place between 12 pm and 4 pm.

- Distribution of accidents according to Month.
More number of Accidents were observed in December Month.

I Used Folium library to locate the accidents on world map using the Start_Lat and Start_Lng columns.
- HeatMap of accidents on map
