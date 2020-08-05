
# Module 2 Project  | Europe Migration

## Introduction

The goal of this project is to apply data analytics concepts that I have learned so far to a real-world data project. Up to this point I learned the following data analytics concepts:

- Data wrangling and cleaning with pandas
- API and web scraping
- Intermediate topics in Git, MySQL, and Python
- Data analysis using Pandas 
- Statistics & probability
- Exploratory data visual
- Storytelling through data visualization, business intelligence


## Project Description

This project looks into how migration in Europe affected the labour market using data from Eurostat migration database. The idea is to explore the relationship between nationals and foreigners and employed and unemployed for each of the EU country. National workers are those who have a citizenship in the residing country and foreign workers do not.

The project explored the following 3 stories: 

Story 1: Foreigners take jobs away from nationals.

Story 2: Foreigners migrate only when there are jobs available.

Story 3: There is no relation between migration rate and unemployment rate.

The following hypothesis was derived from story 3: 

H0: Migration rate is not related to unemployment rate.
H1: Migration rate is related to unemployment rate.


## Task

The task was to analyze all individual EU countries spanning over 10 years, but I found that focusing on a few provided more fruitful results. During my analysis I choose to focus on 3 countries: Netherlands, Germany and Spain.

## Action

Tools Used:
Python
Jupyter Notebook
Tableau

Skills Used:
Data Cleaning
Data Retrieval
Data Analysis
Statistics
Data visualisation

Steps Followed:
1) I extracted data for all 3 countries comparing unemployment rate nationals vs unemployment rate foreigners and plotted the tow lines side by side using Tableau.
2) I wanted to see relative net flow of immigrants compared with national unemployment rate. I extracted data for net inflow of active foreigners (as % of active population) and unemployment rate for nationals and plotted it using Tableau for all 3 countries.
3) I also derived correlation coefficient between unemployed nationals vs inflow/outflow of foreigners for all 3 countries.


## Result

I obtained the following results

1) Netherlands unemployment rate nationals & foreigners: The graph shows both lines are very similar, thus the Dutch market treats both national and foreign workers the same. 
2) Germany unemployment rate nationals & foreigners: The graph shows both lines are very similar, with a slight decrease of unemployment rate for nationals than foreigners starting from 2015.  
3) Spain unemployment rate nationals & foreigners: Once again the graph we see similarities in both lines and interestingly 2018 and 2019 unemployment rate for nationals and foreigners is the same.
4) Netherlands net inflow of active foreigners (as % of active population) and unemployment rate for nationals: The graph shows an unemployed rate for Dutch nationals changing from year to year and the net flow of immigrants as a % of last years total active population. The graph is measuring the impact on the changes of foreigners into the total active pool. The bars which are immigrant flows represent much smaller number than the line which represents unemployment rate for nationals and they do NOT move together. 
5) Germany net inflow of active foreigners (as % of active population) and unemployment rate for nationals: The graph showed that in 2016 the largest flow of immigrants measured at 1% came into the country and still unemployed rate is going down.
6) Spain net inflow of active foreigners (as % of active population) and unemployment rate for nationals: The graph showed that Spain has chronic high unemployment, where they reached about 25% in 2013. In this graph, we see foreigners leaving the country from 2011-2016 as unemployment rate increases. 

Results form Hypothesis:

H0: Migration rate is not related to unemployment rate.
H1: Migration rate is related to unemployment rate.

We are testing how far from the mean each of two variables are - the variables being unemployed nationals & change of active foreigners. Our p-value is small for Netherlands, Germany and Spain meaning we reject the null hypothesis that migration rate is not related to unemployment rate. In other words, we could say that migration rate is related to unemployment of nationals, however they don’t have to move in the same direction. 

A link to my public tableau with project's graphs

https://public.tableau.com/profile/viktoriya.shirochenkova#!/vizhome/Europe_Migration/NLUnemploymentRate?publish=yes






