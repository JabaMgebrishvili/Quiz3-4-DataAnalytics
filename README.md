# Space Missions Data Analysis
This project analyzes the dataset "All Space Missions from 1957" available on Kaggle. The analysis includes data preprocessing, data transformation, visualization, and date manipulation using various Python libraries.

# Overview
This project involves the following tasks:
•	Data preprocessing
•	Data transformation and categorization
•	Data reshaping using various functions
•	Creating different types of visualizations
•	Working with dates using various date-related functions

# Dataset
The dataset used in this project can be found on Kaggle. It includes information about all space missions from 1957 to present - https://www.kaggle.com/datasets/agirlcoding/all-space-missions-from-1957

# Tasks
Task 1: Data Preprocessing
•	Imported the dataset using pandas.
•	Inspected the dataset for missing values and general information.
•	Split the 'Datum' column into separate 'Date' and 'Time' columns.
•	Filled missing values with 'Unknown'.
•	Dropped unnecessary columns.
Task 2: Data Transformation
•	Converted the 'Date' column to datetime format and extracted the year.
•	Categorized missions into 'old', 'new', and 'latest' based on the year.
Task 3: Data Reshaping
•	Used melt(), pivot_table(), stack(), and crosstab() functions to reshape the data.
Task 4: Data Visualization
•	Created different types of charts to visualize the data:
1.	Line Chart: Rocket values over time.
2.	Bar Chart: Mission count by company.
3.	Scatter Chart: Relationship between rocket values and mission success.
4.	Histogram: Distribution of rocket values for successful missions.
5.	Pie Chart: Distribution of mission statuses.
Task 5: Date Manipulation
•	Extracted month and day names from the 'Date' column.
•	Calculated the number of days since each mission to the current date.

# Results
The analysis results include various visualizations and insights about space missions over the years. The data has been cleaned, transformed, and reshaped to provide meaningful insights.
