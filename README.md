# Data-analytics-airbnb-
Airbnb Data Analysis Project

**Project Overview
This project explores an Airbnb listings dataset using Python, Pandas, Matplotlib, and Seaborn. The goal is to clean the data, handle missing values, perform exploratory data analysis (EDA), and derive meaningful insights from the listings and reviews data.

**Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook

**Dataset
The dataset contains Airbnb listing information such as:
Listing ID
Name
Host Name
Neighbourhood Group
Room Type
Price
Service Fee
Reviews Per Month
Last Review Date
Availability and other listing details

****Data Cleaning Performed
****Checked for missing values.
****Removed duplicate records.
****Converted last review column to datetime format.
****Filled missing values in reviews per month with 0.
****Handled missing values in last review.
****Removed rows with missing listing names and host names.
****Removed currency symbols ($) and commas from price and service fee columns.
****Converted price-related columns to numeric data types.

**Exploratory Data Analysis Questions
1. What is the distribution of listing prices?
Used a histogram with KDE curve.
Analyzed how listing prices are distributed across the dataset.

2. How are listings distributed across different room types?
Used a count plot to visualize the number of listings for each room type.
Identified the most common accommodation type.

3. How are listings distributed across different neighbourhood groups?
Examined listing concentration across neighbourhood groups.
Compared popularity of different locations

4. What is the relationship between price and room type?
Used a box plot to compare price distributions across room types.
Identified variations in pricing among accommodation categories.

5. How have reviews changed over time?
Aggregated reviews by month.
Created a time-series visualization to observe review trends over time.
📈 Key Insights
Listing prices show variation across different price ranges.
Certain room types dominate the platform.
Listings are concentrated in specific neighbourhood groups.
Room type significantly influences pricing.
Review activity changes over time, indicating shifts in platform usage and demand.

**kills Demonstrated
Data Cleaning
Exploratory Data Analysis (EDA)
Data Visualization
Handling Missing Values
Time Series Analysis

