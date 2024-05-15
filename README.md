# airbnb-booking-analysis
![AirBnb](https://github.com/Kashifletslearn/EDA-of-Airbnb-Hotel-Booking/blob/main/air%20bnb.jpg)

This project aims to do exploratory data analysis of the listings on Airbnb. Airbnb has a global reach, and data analysis plays a crucial role in its operations. The project focuses on utilizing historical data of Airbnb listings in New York as it is highlighted as one of the most popular places for tourism and business.

## Table of Content
  * [Problem Statement](#problem-statement)
  * [Dataset](#dataset)
  * [Data Pipeline](#data-pipeline)
  * [Project Structure](#project-structure)
  * [EDA](https://github.com/Kashifletslearn/EDA-of-Airbnb-Hotel-Booking/blob/main/EDA_of_Airbnb_Hotel_Booking.ipynb)
  * [Conclusion](#conclusion)
  
  
## Problem Statement
Airbnb is a popular online marketplace connecting homeowners who want to rent out their homes with travelers seeking accommodations in a specific location. Airbnb offers people an easy, relatively stress-free way to earn some income from their property. New York City is highlighted as one of the most popular places for tourism and business. Since its launch in 2008, Airbnb has expanded the possibilities of travel and offers a unique and personalized way of experiencing the world. In this project, we are finding the followings:
  * Do the EDA of the given dataset using Numpy and Pandas, and find the relationship between different variables.
  * Find out features that are important for Airbnb from a business perspective.
  * Do the cost and revenue analysis and find out groups where Airbnb can focus to increase its profit.
  * Analyze the sentiment from ratings of the customers. Find out the relationship between price and user's rating if there is any.


## Dataset
The dataset describes the listing activity and metrics in NYC, NY for 2019. The data set includes over 48895 records and 16 attributes. This data file includes all needed information to find out more about hosts, geographical availability, necessary metrics to make predictions and draw conclusions. For more information on the dataset, please visit the Kaggle website at https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data


## Data Pipeline
  1. Analyze Data: 
      In this initial step, we attempted to comprehend the data and searched for various available features. We looked for things like the shape of the data, the 
      data types of each feature, a statistical summary, etc. at this stage.
  2. EDA: 
      EDA stands for Exploratory Data Analysis. It is a process of analyzing and understanding the data. The goal of EDA is to gain insights into the data, identify 
      patterns, and discover relationships and trends. It helps to identify outliers, missing values, and any other issues that may affect the analysis and modeling 
      of the data.
  3. Data Cleaning: 
      Data cleaning is the process of identifying and correcting or removing inaccuracies, inconsistencies, and missing values in a dataset. We inspected the dataset 
      for duplicate values. The null value and outlier detection and treatment followed. For the imputation of the null value we used the Mean, Median, and Mode 
      techniques, and for the outliers, we used the Clipping method to handle the outliers without any loss to the data.
      

## Project Structure
```
├── README.md
├── Dataset 
│   ├── [Airbnb NYC 2019 dataset.csv](https://github.com/Navneet2409/Airbnb-Booking-Analysis/files/10833240/Airbnb.NYC.2019.dataset.csv)
├── Problem Statement
│
├── Know Yoour Data
│
├── Understanding Your Variables
│
├── EDA
│   ├── Numeric & Categorical features
│   ├── Univariate Analysis
│   ├── Bivariate and Multivariate Analysis
│
├── Data Cleaning
│   ├── Duplicated values
│   ├── Missing values
│   ├── Skewness
│   ├── Treating Outliers
|
│   
├── Report
├── Presentation
├── Result
└── Reference
```
## Click [here](https://github.com/Kashifletslearn/EDA-of-Airbnb-Hotel-Booking/blob/main/EDA_of_Airbnb_Hotel_Booking.ipynb) to view the solution of Airbnb Bookings EDA Analysis!** 




## Conclusion
In this project, we tackled an Exploratory Data Analysis problem in which we had to explore and find the relationship between different variables to understand the business sense and let stakeholders make informed decisions. Through this Exploratory Data Analysis (EDA) we analyzed Airbnb Bookings Analysis using Pandas and used Seaborn and Matplotlib for the visualization. 
    - There were approximately 48895 records and 16 attributes in the dataset.
    - We started by importing the dataset, and necessary libraries to understand the variables.
    - We conducted exploratory data analysis (EDA) to get a clear insight into each feature by separating the dataset into numeric and categoric features. We did 
    Univariate, Bivariate, and even multivariate analyses.
    - After that, the outliers and null values were removed from the raw data and treated. Data were transformed to ensure that it was compatible with model building 
    and predictions if required.

  ### **Major Findings**:
    - With a total of 18 listings, the Hillside Hotel is the most listed in Newyork. Michael, David, and Sonder(NYC) are the 3 topmost listed hostnames.
    - Manhattan has the most number of listings followed by Brooklyn and Queens, while Staten Island has the least number of listings. 85% of listing on Airbnb come 
    from Manhattan and Brooklyn. Even with the high number of listings in Manhattan and Brooklyn, the average price of the hotel is also too high which indicates 
    that the demand in these two areas is massive.
    - Williamsburg, Bedford-Stuyvesant, and Harlem are the most popular and have the most listings in the neighbourhood. Astoria, GreenPoint, and Upper West Side are 
    the most costly neighborhoods in the dataset.
    - Staten Island listings are sparsely separated from each other. Manhattan listings are the densest in the dataset.
    - The entire home/apt is the most preferred room type in Airbnb and has the most number of listings. Due to the high demand for the entire home/apt it is the 
    most costly one too followed by a private room. In all the neighborhood groups entire home/apt is the most costly which indicates its high demand all over 
    Newyork.
    - Price of USD 100 and USD 150 for one night is highly preferred by customers. The price of all the listings ranges from 0 to 2000 USD. The price of the listed 
    properties varies from 0 to 10000 which indicated that there are many wrong entries and outliers in the price. (Assuming price cannot be zero)
    - Most customers prefer to stay for 1,2 or 3 nights. Manhattan has a maximum average length of stay which is over 8 nights followed by Brooklyn which is over 6 
    nights. The Bronx has a minimum length of stay. The entire home/apt has a maximum average length of stay followed by a shared room.
    - The top 3 most rated host names are Micheal, David, and John. Even though Manhattan has the maximum number of listings yet Brooklyn has the most number of 
    reviews.
    - The most common availability days in the data is 0 which indicates the wrong entry in the dataset. It makes no sense that the hotel is not available for any 
    day and still has customers listed. Hotels in Staten Island are most of the time available in an entire year. Shared Room is available for use the most number of 
    the days in the year.
    
    
    
    
