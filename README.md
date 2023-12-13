# Project Overview

This project has two parts that demonstrate the importance and value of data visualization techniques in the data analysis process.

- In Part I, Exploratory data visualization, you will use Python visualization libraries to systematically explore a selected dataset, starting from plots of single variables and building up to plots of multiple variables.
- In Part II, Explanatory data visualization, you will produce a short presentation that illustrates interesting properties, trends, and relationships that you discovered in your selected dataset. The primary method of conveying your findings will be through transforming your exploratory visualizations from the first part into polished, explanatory visualizations.
--
## Instructions

### Part 1 - Exploratory Data Analysis
In this first part, you will conduct an exploratory data analysis on a dataset of your choice. Use Python data science and data visualization libraries to explore the dataset’s variables and understand the data’s structure, oddities, patterns, and relationships.

The analysis in this part should be structured, going from simple univariate relationships to multivariate relationships, but it does not need to be clean or perfect. There is no single answer that needs to come out of a given dataset. This part of the project is your opportunity to ask questions about the data and make your discoveries. It’s essential to keep in mind that sometimes exploration can lead to dead ends and that it can take multiple steps to dig down to what you’re genuinely looking for. Be patient with your steps, document your work carefully, and be thorough in the perspective that you choose to take with your dataset.


### Part 2 - Explanatory Data Visualization
As you complete the part I of the project, document your findings in a the README.md file available in the template. Particularly, update these sections in the README.md file:

Dataset - Introduce your dataset and document its source. Summarise the steps you took in your data exploration.

Summary of Findings - Summarise your data exploration findings and reflect on the steps you took in your data exploration. Mention whether you plan to bring them into your explanatory presentation or not.

Key Insights for Presentation - Write about why/how you chose certain findings over others to put in your explanatory analysis. Highlight the key insights that you want to convey in your explanatory report as well as any changes to visualizations, or note new visualizations that will be created to bridge between your insights.


## Dataset

> Ford GoBike System Data Exploration and Findings Communication: This document explores a dataset with information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area in 2019
The data consists of information regarding 183,412 rides made in a bike-sharing system covering the greater San Francisco Bay area in 2019. The dataset includes 16 features ('duration_sec', 'start_time', 'end_time', 'start_station_id', 'start_station_name', 'start_station_latitude','start_station_longitude', 'end_station_id', 'end_station_name', 'end_station_latitude', 'end_station_longitude', 'bike_id', 'user_type','member_birth_year', 'member_gender', 'bike_share_for_all_trip'). The dataset can be found here


## Summary of Findings

> Male is most gender founded on our data and most of trips hadn't finished most ages between 1965 to 1995 and i removed impossible ages like 1880 and many likes it by using IQR method and dist of duration has also outliers and i handle them using logarithm method 
most of Participants is subscrible but most of finished trips  finished by customers ,most of trip between 6 to 9 and 15 to 19 hour and thursday has most number of trip bu monday has highest average duration cause it is weekend
most of trips happend on Market St at 10th St state


## Key Insights for Presentation

> Gender per duration and type
> Day of weeks per duration and type
> day has highest avg duration
