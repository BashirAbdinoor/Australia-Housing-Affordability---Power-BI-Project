
# Australia Housing Affordability - Power BI Project

## Problem Statement

This dashboard helps Australian better understand the housing market and what had happened in the last decade. It allows them to compare the housing market in the different states and territories in Australia.

In Australian media, regularly we are told of the housing crisis in Australia. As a 24 year old Australian, I want to acheive the Australian dream of house ownership. Therefore, I want to find out if the claims about house affordability are true. 

In this project I set out to answer the following question "Are Australian houses more or less affordable now compared to a decade ago?". Housing affordability has two components personal income and house prices. Therefore in order to answer that question, we have to answer this question first, what is the relationship between average person income and median house price in Australia? As a result, the following metric will be used. using 100% of income how long will it take to buy a median house with an average income? 



### Steps followed 

- Step 1 : Download the following data from abs, the average earnings and the median houses in all of the different states and territories.
- Step 2 : Combine the data into one excel file and calculate how long it will take to buy a median house with an average salary.
- Step 3 : Load data into Power BI Desktop as an Excel file.
- Step 4 : Create a line chart for every state and territory stacked over one another, on the x-axis is time and the y-axis is the number of years it will take to buy the house.
- Step 5 : Create a filled map for every state and territory stacked over one another.
- Step 6 : Create a button for every state and territory which are not stacked over one another and each of them has the name of the state or territory as a text.
- Step 7 : Create the title of the dashboard as a button.
- Step 8 : create a bookmark for every state or territory consisting only of the buttons and that state's or territory's filled map and line chart.
- Step 9 : Link the button of every state or territory with the corresponding bookmark.


### Dataset

The following datasets were used from the Australian Bureau of Statistics (abs),
1. Average weekly earnings per person (seasonally adjusted) in Australia and all the states and territories which can be found here https://www.abs.gov.au/statistics/labour/earnings-and-working-conditions/average-weekly-earnings-australia/latest-release
2. Mean price of residential dwelling in the data named as "Table 1. Total value of dwellings, all series" which can be found here https://www.abs.gov.au/statistics/economy/price-indexes-and-inflation/total-value-dwellings/latest-release

### Methodology

All the required data was compiled into one excel sheet and the number of years to buy a median house with 100% of average income was calculated using the following equation (median house price)/(52*average weekly income).

### Snapshot of the Dashboard

![image](https://github.com/Theeprotagonist/Projects/assets/112685391/ed3f7a82-cc54-4ba9-a11a-756a63aa9bf2)

![image](https://github.com/Theeprotagonist/Projects/assets/112685391/34738e19-8271-4880-a009-698f5558668c)

![image](https://github.com/Theeprotagonist/Projects/assets/112685391/fdc2e6f3-b8bd-4cd7-82ce-890419dd3574)

![image](https://github.com/Theeprotagonist/Projects/assets/112685391/a6b8f9a5-e04a-49fb-9360-c3d0dd99c447)

### Insights
Except Western Australia and Northern Territories in the last decade housing affordability has fallen. It will take 3 to 5 more years to buy a median house with an average income citizen compared to a decade ago.

# Author
Bashir Abdinoor. 
