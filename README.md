# Data-Scientist-Nanodegree---Project-1
This is the repository for files used and code programs written regarding Project 1 of Data Scientist Nano degree in Udacity

This project aims to utilize Airbnb data for certain regions (Boston and/or Seattle) and conduct an analysis which answers at least 3 questions derived from the data.

For this project I used Seattle data and tried to give insight in the following 3 topics:
1) What are the key drivers that categorize hosts and how that is revealed through the differences of services they offer?
2) What do reviews reveal for the services that are provided? Are there any associations or biases between ratings and some key characteristics ?
3) How can we predict the price of using Airbnb services in Seattle

In this repository 1 zip file exist with name CSV files.zip and this contains the following csv files:

1) calendar.csv
2) reviews.csv
3) listings.csv
4) df_list.csv

The first 3 files were provided by Udacity. They were store in the following kaggle web page:
https://www.kaggle.com/airbnb/seattle/data

Details of csv files:

First: Records of prices in 2016 for every host
Second: Detailed records of reviews.
Third: Structured information about properties of the spaces offered by each host
Fourth: Data derived from the third one. Generated and extracted in csv in order to be used in other *.ipynb files

Additionally, there are 4 python code files:
1) GettingKnowWithData.ipynb
2) Question 1 - Host Profile.ipynb
3) Question 2 - Can we trust ratings.ipynb
4) Question 3 - trying to estimate the cost.ipynb

In the first one there are some checks in the datasets provided by kaggle in order to understand better them.
The last 3 are the analysis for each corresponding question regarding this project.

Details of Python codes:

First: 3 before-mentioned csv files were uploaded and explored. Explored the kind of information they have, number of columns, number of rows, volumes of missing values in each variable, descriptive statistics of the 3rd DataFrame. Baes on the last one, a separate dataset was extracted (df_list), which contains structured variables that can be used for analysis.

Second: I tried to create a host's profile using the cancelation policy they follow. 

Third: I tried to extract valuable information from ratings seeking any association or bias betwwen ratings and key characteristics

Fourth: A linear model fitted to predict Prices for using Airbnb services in Seattle

