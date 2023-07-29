## Introduction

## Who we are

The Smith Busters are a group of aspiring MSIS graduate students who are enthusiastic about data and want to emphasize the importance of data analytics in today's data-driven world. We are ready to apply and present the knowledge we have gained as data analysts both inside and outside of the University of Maryland in order to make a difference in the communities.

The SmithBusters are Rishikesh Baskaran, Yash Makadia, Satvik Narang, Anushka Ranjan, Shweta Salelkar, and Nahome Yeshitila.


## What we are doing


The Smithbusters will produce visualizations using data from the US Census to help us visualize where places require assistance in any of the characteristics specified, such as education, employment etc. We will make predictions about how the numerous criteria we investigate impact the income and livelihood of Americans in various ways. SmithBuster intends to answer the following question with this data.

In order to build this index, we will need to evaluate answers to the following questions:

1. What is the median household income in the United States? How does median income vary in different states and what is the distribution of type of employment of people in the states?
2. How does the distribution of education levels and employment of the population within a state impact the income?
3. Can there be a model which can be trained to understand the  effect of each factor on income and estimate the income for a given state based on these factors?
4. Based on the income predicted by the model, does a state have an opportunity to improve their median household income and what are the factors that can help in achieving this?



## Why these questions matter: 
#### Part 1
Learning which states are doing well and which fall short of the national average requires knowledge of the median income of American families and how it varies from state to state. Our research will focus on high-income states to learn the employment structure that has contributed to their success. With that, the states trailing behind automatically become our choice of interest to focus on in the later parts of our report.
#### Part 2
A popular belief is that better education will lead to more job opportunities and a higher income. We're here to find out if that's true by comparing the levels of education in the state with the most income and the state with the least. If their level of education and income are directly related, education would be a straightforward task to focus on.
#### Part 3
We will need a working model to put our analysis to use and know right away from the predicted income if a state has room for improvement.
#### Part 4 
When our model does show that there is room for change, we will need to know which factors to start working on right away and how important each one is so that organizations can decide what to work on first.


## How will we accomplish this? (Description of dataset)

Our data was obtained from the US Census data website (https://data.census.gov/). We have obtained information on the below factors for the year 2020:

Table Name -> Description  
DP03       -> Economic characteristics 
DP05       -> Demographic and housing estimates    
S1501      ->  Educational attainment   
S2506       Financial characteristics for housing units 


Each of these tables consists of data for zipcode of US. In order to join relevant columns from these tables, we use Zip code as the primary key to join the above tables to create a consolidated dataset.

The columns we chose for our analysis largely had to do with how they relate to our objective. We needed to understand what factors affected the income of an individual and how his income affects his living conditions. DP03 gave us data on the income and income characteristics for the population and DP05 was about population characteristics and ethnicity. We used S1501 to understand the levels of educational attainment and of how many people in a city were educated up to high school, college and undergrad level. S2506 gave us two columns that informed us the mortgaged houses and what the median value was. <br>
