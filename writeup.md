# Exploratory Data Analysis:Vending Machine installation in stations
Pramila Chaudhary

# Abstract
The purpose behind this analysis is to find the Ideal station which has maxmimum Total traffic (Maximum number of people entering and exiting the station), and find the ideal day of week and time duration in which the Vending Machine can refilled before the peak traffic hour starts. I Identified the peak traffic hour through visualization  for all the top 10 potential station in order to determine the best time of the day and similarly found the peak traffic week day to identify the best days of week.

# Design
These analysis are designed for Mr and Mrs Copper who are planning to install the vending machines at popular and most used MTA station in order to sell the maximum  number of the product.Analysis includes all the potential station names and their peak hour and days pf week.

# Data Set
3 months of data from MTA Turnstile Data : http://web.mta.info/developers/turnstile.html

# Algorithms
  1. Data Loading: using sqlalchemy
  2. Data cleaning: Removed non required columns, records with missing values, null values, duplicate rows
  3. calculated total traffic (actual Enteries + actual Exits )for each date and time 
  4. Created two new columns Weekday and hour in order to check the traffic in particular hour and on which day of a week
  5. again cleaned the data for abornomalities in the data set like outlier, negative values
  6. calculated total traffic(Sum) for each station
  7. created a function which accepts the list of the top 10 station names  and plots the graph for each of them with hourly average traffic
  8. created another similar function for ploting the graph for each station  with average traffic Vs day of week

# Tools
Python: Defing functions
SQLAlchemy: link Pandas datasets to a SQLite database
Matplotlib: For data visualization
Pandas: For data cleaning and organization and analysis

# Communication

![]


