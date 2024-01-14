# EDA
The script includes various exploratory data analysis techniques:

**Initial Exploration:** The shape of the DataFrame and its columns are explored, and the first few and last few rows are displayed. This is typically done to get an initial understanding of the dataset's structure and the type of data it contains.

**Data Types and Summary Statistics:** The .info() and .describe() methods are used to examine the data types of each column and to get summary statistics for numeric columns, respectively. This helps in understanding the kind of data each column holds and its distribution.

**Missing Value Analysis:** The script calculates the number of missing values in each column using df.isnull().sum(). This is crucial for data cleaning and preparation.

**Duplicate Row Analysis:** The script checks for duplicate rows in the dataset, which is an important step to ensure the data's integrity.

**Group By Analysis:** The script includes a plan to answer five questions using the groupby method. These questions involve understanding the distribution of clinical trials based on various factors like status, condition, sponsors, study type, and funding.

**Conditional Analysis:** It also plans to answer five questions using conditional statements. These questions are more specific and involve filtering the data based on certain

conditions, such as trials conducted in France, enrollment numbers for COVID-19 trials, and specific characteristics of the trials like age group and funding source.

**Duration Calculation for Trials:** The script calculates the duration of the clinical trials by subtracting the start date from the completion date. This calculation is done separately for COVID-19 related trials and other conditions to compare the average durations.

This README text provides a comprehensive overview of the initial steps in data analysis, focusing on understanding the dataset's structure, identifying missing values and duplicates, and extracting specific insights using groupings and conditional statements. The analysis seems to be a part of a larger study or project related to clinical trials, particularly focusing on COVID-19.
