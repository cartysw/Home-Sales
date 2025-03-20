Hello

## Overview

This is a repository for the Module 22 Big Data challenge from the UofM Data Analytics Bootcamp course. The dataset being used concerns various recorded information about homes that have been sold from 2019 to 2022, including information such as selling price, number of bedrooms/bathrooms, etc. The main objective was to perform some light analysis/aggregation of the dataset and read in/cache a temporary view table into parquet to try and lower the execution time of queries. I opted to write my queries through pyspark's sql module. Some examples of queries that were performed are:

  * Finding the average price for a 4-bedroom house sold per year, rounded to 2 decimal places
  * Finding the average price for a 3-bedroom, 3-bathroom home with 2 floors, and a square footage of at least 2000 square feet
  * Finding the average price of a home for each recorded buyer view count, where the selling price of the home is at least $350,000
    * To note, the caching and parquet tests were performed using this query

I hope the analysis found here proves to be helpful and insightful. This script was created using Google Colab, which can be found here: https://colab.google/

## Installation Instructions
  * Download project files or clone the repository to your local machine
  * Open script file in your code editor of choice (As noted above, this script was created using Google Colab. However, if you have spark set up on your local machine you can simply run it in whatever program you prefer.)
  * Run the individual cells or the entire script at your discretion
