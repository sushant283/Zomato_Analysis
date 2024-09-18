                                                    Zomato Restaurant Analysis
This repository contains a data analysis project focused on Zomato Restaurants. It includes a Jupyter Notebook that analyzes restaurant data from Zomato using a provided CSV dataset.

Project Overview
The project aims to explore and visualize various aspects of restaurants listed on Zomato, such as ratings, online ordering, and table booking options. Python libraries such as Pandas, Matplotlib, and Seaborn are used for data manipulation, visualization, and analysis.

Files in the Repository 

1) Zomato data .csv
This file contains the dataset used for the analysis. The dataset includes information about restaurants, such as:
Name: The name of the restaurant.
Online Order: Whether online ordering is available (Yes/No).
Book Table: Whether table booking is available (Yes/No).
Rate: The rating of the restaurant.
Votes: Number of votes received.
Approx Cost (for two people): Average cost for two people dining.
Listed In (type): The type of listing (e.g., Delivery, Dine-out, Cafes).

2) ZomatoAnalysis.ipynb
This Jupyter Notebook contains the Python code used to perform the analysis. The notebook includes:
Data Loading: Loading the dataset into a Pandas DataFrame.
Data Cleaning: Handling missing values, converting data types, and ensuring data consistency.
Exploratory Data Analysis (EDA):
Visualizing the distribution of ratings and average cost.
Analyzing the relationship between ratings, cost, and listing types.
Mapping restaurant locations and clustering based on ratings.
