# Strava-Fitness-Data-Analysis
Unlocking New Growth Opportunities through Smart Device Data Insights

Note: Please refer to the files in this repository to find all of the data/code/graphs/tables found in this report and much more.

Power Bi visualization: <a href="https://github.com/madhuripingle/Strava-Fitness-Data-Analysis/blob/main/STRAVA%20FITNESS%20DATA%20ANALYSIS.pbix">Click here</a>

## Preparing data for analysis

For this project, I've used the 18 datasets dated from 03/12/2016 - 05/12/2016 provided on kaggle. Click on this FitBit Fitness Tracker Data (CC0: Public Domain, dataset made available through Mobius) to access the website and download the datasets provided as .csv files. This data set contains personal fitness data from 30 fitbit users on minute-level output for physical activity, heart rate, and sleep monitoring. It also includes information on daily activity, steps, and heart rate that can be used to explore users’ habits. Thirty Fitbit users consented to the submission of personal tracker data and the data provided in this website is made available to access to the public.

Or you could access and download the data from this repository named as "Raw Data".

I am using Microsoft SQL Server Management Studio in this part of the project to help process and analyze the datasets. Also using Python to analyze the data and Using Power Bi to crate an interactive dashboard.

First make sure to import all of the dataset as a .csv file to the database server. In order to solve this business task, only 6 of the given 18 datasets was used. Many of the files are either redundant, is not essential, or relevant, or lacking sufficient data to perform an analysis upon.

## Processing of Data

Here, I will be transforming and organizing data by adding new columns, extracting information and removing bad data and duplicates.

In order to get accurate analysis, validate and make sure the dataset does not include any bias, incorrect data, and duplicates.

<a href="https://github.com/madhuripingle/Strava-Fitness-Data-Analysis/blob/main/STRAVA%20FITNESS%20DATA%20ANALYSIS.sql">SQL File</a>

<a href="https://github.com/madhuripingle/Strava-Fitness-Data-Analysis/blob/main/STRAVA%20FITNESS%20DATA%20ANALYSIS.ipynb">Python File</a>

## Conclusion

After performing the collection, transformation, cleaning, organisation and analysis of the given datasets, we have enough factual evidence to suggest answers to the business-related questions that were asked.

We can infer that the duration and the level of intensity of the activities performed are greatly in dependence to the amount of calories burned. METs provide a great insight on the intensity of activities performed and the amount of calories burned per minute. While most of the consumers attain adequate amounts of sleep, it is noticed that a small fraction of the users either oversleep or undersleep.

In order to design new marketing strategies to better focus on unlocking new growth oppurtunities and develop the business, we have to refer to the analysis provided above and keep those facts in mind. The recommendations I would provide to help solve this business-related scenario is shown below.

## Top Recommendations to Marketing Strategists:

1.Highlight the MET tracking feature on the smart devices as a marketing strategy and create awareness on MET values. For it allows users to track their level of intensity of activities and provide a real time insight on how much calories they burn every minute.</br>
2.Consumers seem to spend most of their time inactive and live a sedentary lifestyle.</br>
3.Provide app notification for users to remind them to get sufficient sleep every day and implement new sleep measurement features or products such as tracking Rapid Eye Movement (REM) sleep.</br>
4.Consider setting daily/weekly calorie challenges and award points to users based on the top performers. Where the points can be accumulated and redeemed as a discount for their next product purchase.
