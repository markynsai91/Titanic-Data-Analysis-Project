# Titanic-Data-Analysis-Project


## Project Summary
This project explores the factors that influenced passenger survival during the Titanic disaster using data analysis and visualization in Python. The analysis focused on understanding how passenger class and age affected survival outcomes to draw insights that could inform fairer ship design and emergency planning. I cleaned and prepared the dataset using Pandas, handled missing values with mean imputation, and created an age_category column to group passengers into Children (0–14), Youth & Adults (15–64), and Seniors (65+). Visualizations were built to compare survival counts and rates across passenger classes and age groups. The findings showed a clear class-based disparity in survival rates, with first-class passengers having significantly higher survival chances. Children had a higher likelihood of survival compared to adults and seniors, revealing patterns of vulnerability that could inform better safety design in future maritime planning. Tools Used: Python (Pandas, NumPy, Matplotlib), Jupyter Notebook, Excel

## Project Goals

## Goal:
See if survival rate had anything to do with the passenger class, Also assess the age of the passengers within each class to identify vulnerable age categories.

## Data Preperation

The Titanic dataset is downloaded, cleaned, and prepared for analysis. The process begins by retrieving the dataset from Google Drive using the gdown library, then loading it into a Pandas DataFrame for inspection and preprocessing.

Next, the data is stored in a SQLite database, enabling the use of SQL queries directly within the Jupyter Notebook. By loading the SQL extension with %load_ext sql and connecting to the database using %sql, the environment allows for both Python-based and SQL-based data exploration.

This setup provides a structured and flexible workspace where Python and SQL can be used together to analyze, query, and visualize the Titanic dataset effectively in later stages of the project.
