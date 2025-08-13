# Swiggy-Analysis
Swiggy Data Analysis

--------------------------------------------
Swiggy Insights: Restaurant Data Analysis
--------------------------------------------

This project conducts an exploratory data analysis (EDA) on Swiggy's sales data, focusing on restaurant ratings, cost distribution, and popular cuisines. Utilizing pandas and numpy, the analysis uncovers key insights about the dining trends across different cities, helping inform data-driven decisions for Swiggy and restaurant owners.

----------------
About Data:
--------------

Dataset: Swiggy Data

The dataset contains information about various restaurants listed on Swiggy. The informations includes id, name, rating, cost, cuisine etc.

Table of Contents:

Importing Libraries

Data Exploration

Data Preprocessing

Exploratory Data Analysis

Conclusion

---------------------
Importing Libraries
----------------------

Importing required libraries:

pandas for data manipulation.

numpy for numerical operations.

Data Exploration

Loads a Swiggy dataset containing restaurant information (ID, name, city, rating, rating count, cost, cuisine, license number, link, address).

Provides a data dictionary for understanding each feature.

Analyzes basic statistics using head(), tail(), and info() methods.

--------------------
Data Preprocessing
--------------------


Handles missing values:

Removes rows with any missing values.

Fills missing "rating" values with -999.0 (alternative: median imputation).

Converts "cost" feature from string to numeric format by removing the rupee symbol.

Deals with the categorical count in "rating_count" (optional: Label Encoding).

---------------------------
Exploratory Data Analysis
---------------------------

Restaurant Distribution:

Determines the number of cities served by Swiggy.
Counts the total number of restaurants and unique restaurant names.
Identifies the most popular food chains based on name frequency.
Customer Reviews:

Analyzes the overall rating distribution of restaurants.

Visualizes the percentage of ratings for different rating categories.

City Performance:

Discovers the city with the highest number of restaurants.

Explores the city with the highest average rating (considering reliable rating counts).

------------------
Cost Analysis:
-----------------

Examines the cost distribution of restaurants through visualizations.

Explores the most expensive restaurants based on cost.

--------------------
Cuisine Popularity:
--------------------

Identifies the most common cuisine types among highly-rated restaurants (rating > 3.5).

Utilizes list comprehension and string manipulation to analyze cuisine data.


-------------
Tools Used:
-------------
Excel

Python

Power BI

-------------
Conclusion
------------

The analysis provides a comprehensive overview of Swiggy's restaurant data, including insights into ratings, cost, and popular cuisines. This can help Swiggy and restaurant owners to make data-driven decisions.

---------
About
---------

This project delves into Swiggy's restaurant data, exploring various aspects and trends using Pandas and exploratory data analysis techniques.

-------
Topics
-------

data-science exploratory-data-analysis data-visualizations restaurant-analysis food-tech sales-data-analysis swiggy-data-analysis
Resources
 
