# Wrangling and Analyzing WeRateDog's Twitter Data

## Introduction
In this project, I will be wrangling twitter archive data obtained from the Twitter user [@dog_rates](https://twitter.com/dog_rates), also known as WeRateDogs. The interesting part of this project is the fact that it appropriately depicts how data analysts often collect data and clean it to make it ready for analysis.

## Data Wrangling
This section describes all efforts to gather, validate/assess, and finally clean the data to make it ready for analysis.
### I. Data Gathering
Here I collected the three datasets using different techniques. While two of the datasets were readily available, the other had to be queried from the Twitter API.
### II. Data Assessment
I performed both visual and programmatic assessments on the data and identified issues that needed to be addressed in order to have the correct and proper data ready for analysis.
### III. Data Cleaning
Here, I cleaned the data and appropriately rectified the data **quality** and **tidiness** issues earlier encountered during its assessment.

## Analysis and Conclusion
After cleaning the data and saving it to a new file, I decided to investigate the following questions:
1. What are the most common ratings in this data? The five most common ratings were 12, 10, 11, 13, and 9, respectively.
2. Does a dog's rating affect how Twitter users interact with the tweet in terms of the number of likes? In short, yes. Beginning from a rating of 8 out of 10, the average number of likes saw an increase up to a rating of 14 out of 10.  
3. What's the strength of the relationship between the number of retweets and its number of likes? There's a strong positive correlation of 0.93.

## Notes
In case you might be interested in replicating this project, you would need to do the following to ensure the code does not break (apart from having the necessary libraries installed):
- Create a directory named "data" which will house all the data files. Links to download the starter data files are in the wrangle_act notebook.
- Have a twitter developer account and obtain your access and customer keys.
