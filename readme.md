Analysis of Jail Deaths in U.S. 
===========

Clarissa Chan,
Yuxi Jiang,
Louise Li, 
Yichu Chen,
Zhongwen Liang


## Intension
-Our intension in this assignment is to explore the conditions of jails in the U.S. and explore all the possible influences on deaths in jail. Throughout this project, we will compare the followings: the death rate, suicide rate,  causes of death in each state, the number of deaths around the country each year, time of death, the trend of the average daily inmate population, and the relationship between different methods of deaths in different years.


## Data background
-Our data comes from the website "https://www.reuters.com/investigates/special-report/usa-jails-graphic/" created by journalists 
-we are using the "all_deaths.csv" and "all_jails.csv" files to access jail death information for 50 states
-"reuters-jail-deaths-codesheets.xlsx" is an excel file that contains the meaning of each variable in the two files listed above


## Access to the file
-You should see a folder called "Notebook" above this Readme file
-open it and there will be a folder called "data" and a notebook called "141B_Final"
-"data" folder consists of all of the data that we will be using in the notebook which include "all_deaths.csv", "all_jails.csv", and "141B_Final" is the notebook that consist of all of our code.
-Make sure your terminal has install all of the following tools: numpy, pandas, plotnine, matplotlib, sqlalchemy, plotly, seaborn
  $ pip install numpy
  $ pip install pandas
  $ pip install plotnine
  $ pip install matplotlib
  $ pip install sqlalchemy
  $ pip install seaborn
  $ pip install geopandas==0.3.0
  $ pip install pyshp==1.2.10
  $ pip install shapely==1.6.3
  

## Summary
Our group has selected 5 of the 7 categories that are presented in our report which includes 1.Project organization, writeup readability, and overall conclusions, 3. Scientific programming, custom algorithms, and numpy use, 4. Data munging, 5. Data visualization, and 7. Data storage.

In our final project, we explored the jail deaths in the US with two datasets including ‘all_jails.csv’ and ‘all_deaths.csv’. We have looked at the number of inmate population from 2008-2019 with its highest, average, and total inmate population in each state by year. The highest-ranking of the inmate population is relatively stable. we have also used the pie chart to analyze the percentage of the cause of death. Based on the pie chart, we can conclude that illness/natural death is the first leading cause of jail death which contributes to around 50-55% of total jail deaths in each year while the unnatural death rate consists of another 40% of jail deaths. By using the heatmap, we have visualized the percentage of the causes of death for each state and the counties in California. In addition, we have examined the average percentage of jail deaths in all States and the counties in California. We can conclude that Washington DC has the highest death rate at nearly 0.25%. San Diego and Kern have the highest number of death in jail at around 0.33% in California. Based on the pie chart of the racial distribution of jail deaths in each year, we discover that White inmates make up the largest proportion of jail deaths in all years, followed by Black and Hispanic inmates.

