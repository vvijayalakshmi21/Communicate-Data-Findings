# Communicate-Data-Findings

### Project Overview
This project has two parts that demonstrate the importance and value of data visualization techniques in the data analysis process. 
* The first part uses Python visualization libraries to systematically explore a selected dataset, starting from plots of single variables and building up to plots of multiple variables. 
* The second part will focus on producing a short presentation that illustrates interesting properties, trends, and relationships that are discovered in the dataset. 

The primary method of conveying the findings will be through transforming the exploratory visualizations from the first part into polished, explanatory visualizations.

### Dataset 
Flights data from http://stat-computing.org/dataexpo/2009/the-data.html will be used for analysis. The original repository is enormous. So for this project, only a few months of data will be considered (January, February and March 2020).

### Summary of Findings
In the exploration, I found that the most common reason for flight cancellations was Security with a whooping 84% followed by Carrier with a very small value of 8%. The departure delays are higher than arrival delays.


The top 5 carriers who had most diversions as well as most cancellations are 'United Airlines', 'Delta Airlines', 'American Airlines', 'Southwest Airlines', 'SkyWest Airlines' although each of the carriers differ in terms of numbers of cancellations/diversions. 

On eyeballing the data in the scatterplot there appears to be a negative relationship between Air time and Departure delays although the relationship appears to be slight to none - as most of the data shows no relationship and there appears to be a positive relationship between arrival and departure delays. Also, the delays seem to reduce towards the end of the month of every month.

### Key Insights for Presentation

For the presentation, I focus on the factors that affect arrival and departure delays of flights. The main consideration is on factors such as flight duration, day of month, day of week and also some insights on cancellations and diversions. I start by first plotting a pie chart for identifying the reasons for cancellation then highlight the top five carriers that have the most number of flight cancellations/diversions

Afterwards, I plot the origin cities having the most number of cancellations. I corroborate this fact by providing the list of busiest airport cities as per wikipedia. Then comes the analysis of day-wise data where I present the worst day of the month as well as week to travel based on the available data using bar plots. Finally I plot relationships between arrival and departure delays with the entire dataset and then the mean delays are plotted for every carrier as a scatter plot.



