Day 1: Data Exploration and Preprocessing
Objective:
On my first day as a data analytics intern, I worked on downloading a dataset from Kaggle, loading it into Jupyter Notebook, and performing basic preprocessing steps to prepare the data for analysis.

Tasks Completed:
Dataset Download and Loading:

Downloaded the CSV file from Kaggle.
Loaded the dataset into Jupyter Notebook using pandas to begin data exploration.
Column Names Representation:

Displayed all the column names in the dataset to understand the structure and identify columns that needed further processing.
Date and Time Separation:

The date column was split into two separate columns:
Date: Contained the date values.
Time: Contained the time values.
This was done to better analyze trends over time and simplify any future time-based analysis.
Category Alias Column Splitting:

The category_alias column, which contained both the type and category information, was split into two new columns:
Type: Representing the broader category type.
Category_Alias: Representing the specific category under that type.
This step was important for better segmentation and more detailed analysis of product categories.
Tools and Libraries Used:
Python
Jupyter Notebook
pandas for data loading and manipulation