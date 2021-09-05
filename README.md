# Kickstarter Challenge
Performing analysis on Kickstarter data to uncover trends 
# Kickstarting with Excel

## Overview of Project
The objective of the project is to help Louise analyze Kickstarter data, make it more readable and gain insights from the historical and on-going Kickstarter campaings. The objective also entails creating data visualizations that will help in summarizing the analysis completed.

### Purpose
Throughout the project, the purpose was to compare the influence of several variables on the outcome of Kickstarter campaigns. Variables such as category, country and average donations. In order to help understand how and when a successful Kickstarter campaign may take place.

## Analysis and Results

### Analysis of Outcomes Based on Launch Date
![Outcomes Based on Launch Date](https://user-images.githubusercontent.com/88692025/132140495-81dfc3e4-06ea-4f0c-a147-84b747f08ea9.png)
* An analysis was created to help Louise our client understand the link between the outcome of a Kickstarter campaign and the time of year or date that it was launched. This is an important correlation to conclude from as the weather and seasons play a role in poeple's deicision making and propensity to spend money. The data gave a clear indication that the most successfull campaings occurred in May and June. The Spring/Summer seasons contains more succesffull ccmpaaings than the Falll/Winter seasons. This can help Louise drive decision making with the information that the summer season will likely yield a more successfull result than the other seasons. A second conclusion is that the time of year has little to no effect on whether or not a campaign will fail, as the data on failed campaings is spread out quite evenly throughout the year. It can also be conlcuded that there are many more cmapaings during the Spring and Summer season and as a result might be a driver to the higher number of successes. 

### Analysis of Outcomes Based on Goals
![Parent Category Outcomes](https://user-images.githubusercontent.com/88692025/132140663-9a886da1-8eaf-44ba-a79a-2cc4a01657f0.png)
* An analysis was created to determine thew correlation between a campaing's goal amount and the percentage of it's success, failure and cancelatrion. Between 0 and 34999 here is a clear conclusiona nd trend. The higher the goal set for a Kickstater campaign the higher the pertcenrtage of failure comapred to success. Initially, on the lower end of the goal range the success percentage is quite high near 80%, and this beings to decrease to aroung 55% as the goal increases from less tahn 1000 dollars to betweeen 15000 - 19999. We can conclude that it is more likely to be successfull and smaller goal ranges with regards to plays specifically. 

## Challenges and Recomendations 
### Excel Challenges
1. One of the challenges while performing this analysis was a bottleneck presented by the COUNTIFS function, it was quite tedious and ineffeceient to manually input the various ranges of the Kickstarter campaign. In a scenario where there more than for example 40 ranges, it would have taken hoours to inout the ranges in 5000 increments, especially with the <> signs and ending the rangfes at the 999 or 000 increment. This would present a large chance of typos or erros.
* A potential reccomendation to imrpove on this process would be to create a range trhough another table with a formula and then using the COUNTIFS fucntion to read the ranges and categories from that table.
### Dataset Limitations
1. One of the potenital limitations of the analyis is the fact that the dataset included variables that might be irerelvant or inconclusive. Variables that were not utilized in the analysis should be inlcuded in later stages is a potential fix.
2. A second potential limitation of this data set is the outcomes and goals of larger campaings are not as prevalant. Meaning anything above a certain range of around 35000 dollars has only a few cmapaings to conclude from. This could cause an inaccuratre conclusion wehn looking at larger campaigns as there is not enough data to conclude from.
### Further Analysis
* There are many further variable correlations and analyses that can be created from this Kicktarter cmapign dataset, for example we could take a look at the average donation and the link of success, we could also make an analysis based on subcatregory and country and see if certain countries prefer certain categories. Another one could be the link between number of backers, goal and outcome. A graph could be created to measure the correlation between number of backers and the outcome of the campaign.  
