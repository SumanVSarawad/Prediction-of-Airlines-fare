# Prediction-of-Airlines-fare: Project Overview

## About Dataset
### INTRODUCTION
The objective of the study is to analyse the flight booking dataset obtained from “Ease My Trip” website and to conduct various statistical hypothesis tests in order to get meaningful information from it. The 'Linear Regression' statistical algorithm would be used to train the dataset and predict a continuous target variable. 'Easemytrip' is an internet platform for booking flight tickets, and hence a platform that potential passengers use to buy tickets. A thorough study of the data will aid in the discovery of valuable insights that will be of enormous value to passengers.

Research Questions
The aim of our study is to answer the below research questions:
a) Does price vary with Airlines?
b) How the price changes with change in Source and Destination?
c) How does the ticket price vary between Economy and Business class?

### DATA COLLECTION AND METHODOLOGY
Octoparse scraping tool was used to extract data from the website. Data was collected in two parts: one for economy class tickets and another for business class tickets. A total of 300261 distinct flight booking options was extracted from the site. Data was collected for 50 days, from February 11th to March 31st, 2022.
Data source was secondary data and was collected from Ease my trip website.

### DATASET
Dataset contains information about flight booking options from the website Easemytrip for flight travel between India's top 6 metro cities. There are 10684 datapoints and 11 features in the cleaned dataset.

### FEATURES
The various features of the cleaned dataset are explained below:
1) Airline: The name of the airline company is stored in the airline column. It is a categorical feature having 6 different airlines.
2) Date of Journey: The date of journey the flights take.
3) Source: City from which the flight takes off. It is a categorical feature having 6 unique cities.
4) Destination: City where the flight will land. It is a categorical feature having 6 unique cities.
5) Route: The route the flight follows from source to destination.
6) Departure Time: This is a derived categorical feature obtained created by grouping time periods into bins. It stores information about the departure time and have 6 unique time labels.
7) Arrival Time: This is a derived categorical feature created by grouping time intervals into bins. It has six distinct time labels and keeps information about the arrival time.
8) Duration: The total duration of the flight takes.
9) Total Stops: A categorical feature with 3 distinct values that stores the number of stops between the source and destination cities.
10) Additional Information: The infomation of other details like meals included, layover etc.
11) Price: The price of the flight in INR.
12) Class: A categorical feature that contains information on seat class; it has two distinct values: Business and Economy.
13) Duration: A continuous feature that displays the overall amount of time it takes to travel between cities in hours.
14) Days Left: This is a derived characteristic that is calculated by subtracting the trip date by the booking date.
15) Price: Target variable stores information of the ticket price.

### Code and Resources Used
Python Version: 3.11 Packages Used:Pandas, Numpy, Sklearn, Seaborn

### Exploratory Data Analysis
After looking at the distribution of the data and the value counts for various categorical variables. Below are few highlights:
![image](https://github.com/SumanVSarawad/Prediction-of-Airlines-fare/assets/118813644/cbf8540c-2481-49dc-b039-69061321943f)

![image](https://github.com/SumanVSarawad/Prediction-of-Airlines-fare/assets/118813644/d6797381-e07c-4793-8ecd-0b965ef01651)

![image](https://github.com/SumanVSarawad/Prediction-of-Airlines-fare/assets/118813644/a4bef0bd-8bca-48b2-8279-1f27ee50f8ef)

### Results
• Successfully performed data cleaning for airline fare prediction, employing Python libraries and tools to eliminate missing data and outlier errors, resulting in a significant 30% reduction in data inconsistencies.<br>
• Utilized feature extraction techniques to identify the most influential features from the dataset, achieving an impressive accuracy of 90.47 % in airline fare prediction using Random Forest Regression.

