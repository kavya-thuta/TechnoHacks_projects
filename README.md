# TechnoHacks_projects

#  overview:

This repository documents a series of tasks completed as part of the Data Analyst Internship with TechnoHacks. The tasks focused on data cleaning, calculating summary statistics, and finding/removing duplicates for two different datasets: Titanic and Iris Species. Below is an overview of each task:
#  Task 1: Data Cleaning (Titanic Dataset)
In this task, we worked with the Titanic dataset using MS-Excel. The following steps were performed to clean the dataset:

1.Age: Average age was calculated for passengers based on class and sex, and missing values were filled accordingly.

2.Cabin: The first initial was extracted from the "Cabin" column, and 'M' was imputed for missing values.

3.Embarked: Mode was found and used to impute missing values in the "Embarked" column.

4.Title: Titles were extracted from the "Name" column and consolidated into categories (e.g., Mr, Miss, Mrs, Master, and Royalty) to reduce categorization.

5.Ticket: Only the alphabetical part of the "Ticket" column was extracted.

6.One-hot encoded variables were created for the categorizations of "Title," "Embarked," "Cabin," and "Ticket" columns.

# Task 2: Calculate Summary Statistics (Titanic Dataset)
Python functions like mean(), median(), mode(), and std() were utilized to calculate essential summary statistics for the Titanic dataset in a Jupyter Notebook.

# Task 5: Find and Remove Duplicates (Iris Species Dataset)
Although no duplicates were found in the Iris Species dataset, instructions for finding and removing duplicates from specific columns were provided using functions like duplicated() and drop_duplicates() in a Jupyter Notebook.

# Dataset Information:

Titanic Dataset:

Data Source: Kaggle
Tool Utilized: MS-Excel (Task 1), Jupyter Notebook (Task 2)
Dataset Name: Titanic - train
Iris Species Dataset:

Data Source: Kaggle
Tool Utilized: Jupyter Notebook (Task 3)
Dataset Name: Iris Species
