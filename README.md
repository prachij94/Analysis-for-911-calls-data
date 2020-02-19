# Analysis-for-911-calls-data

This repository contains a jupyter notebook on the data analysis about the calls that were made to the emergency (911) services like Fire, Traffic, EMS for Montgomery County, PA. This dataset is hosted on [Kaggle](https://www.kaggle.com/mchirico/montcoalert).

It contains the following fields about the call:
- lat:Latitude
- lng:Longitude
- desc:Description of Emergency
- zip:ZIP Code
- title:Title of Emergency
- timeStamp:Date and time of the call
- twp:Town
- addr:Address


To derive interesting and meaningful insights from the dataset, data analysis has been performed using Python data exploratory tools like **Pandas** and **Matplotlib, Seaborn** for visualization.

Few of the inferences drawn about the calls made are:
- The top 5 zipcodes
- The top 5 townships 
- The most common Reasons out of *Fire, Traffic, EMS* for a 911 call and their distributions with respect to each other
- All reasons' distribution on each day of the week
- All reasons' distribution on each month of the year
- Linear fit for the number of calls made per month
- The count of calls made on different dates for each of the reasons
- The heatmap and clustermap for count of calls made on the day of the week and the hour of the day
- The heatmap and clustermap for count of calls made on the day of the week and the month of the year

# Requirements:
- numpy
- pandas
- matplotlib
- seaborn
