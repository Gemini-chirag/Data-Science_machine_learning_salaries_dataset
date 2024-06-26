## Data Science and Machine Learning Salaries Dataset
## Overview
This repository contains an analysis of a dataset detailing the salaries of data science and machine learning professionals. The dataset includes various attributes such as experience level, job title, employment type, salary, remote work ratio, and more. The goal of this analysis is to provide insights into salary trends and patterns within the field.
## Dataset Details
The dataset includes the following columns:

work_year: The year the salary was paid.
experience_level: The experience level in the job during the year, with the following possible values:
EN: Entry-level / Junior
MI: Mid-level / Intermediate
SE: Senior-level / Expert
EX: Executive-level / Director
employment_type: The type of employment for the role:
PT: Part-time
FT: Full-time
CT: Contract
FL: Freelance
job_title: The role worked in during the year.
salary: The total gross salary amount paid.
salary_currency: The currency of the salary paid as an ISO 4217 currency code.
salary_in_usd: The salary in USD (FX rate divided by the average USD rate for the respective year via fxdata.foorilla.com).
employee_residence: Employee's primary country of residence during the work year as an ISO 3166 country code.
remote_ratio: The overall amount of work done remotely, with possible values as follows:
0: No remote work (less than 20%)
50: Partially remote
100: Fully remote (more than 80%)
company_location: The country of the employer's main office or contracting branch as an ISO 3166 country code.
company_size: The average number of people that worked for the company during the year:
S: Less than 50 employees (small)
M: 50 to 250 employees (medium)
L: More than 250 employees (large)

## Key Insights and Analysis
1. Salary Trends by Experience Level
Analyze how salaries vary across different experience levels (Entry-level, Mid-level, Senior-level, Executive-level).
2. Employment Type and Salary
Investigate the differences in salaries based on employment type (Full-time, Part-time, Contract, Freelance).
3. Remote Work and Salary
Explore the relationship between the remote work ratio and salaries.
4. Geographic Analysis
Examine salary trends based on employee residence and company location.
5. Company Size and Salary
Assess how company size impacts salaries.

## Analysis Steps

Data Preprocessing
Load the dataset and handle any missing values.
Convert categorical variables into numerical ones where necessary.
Exploratory Data Analysis (EDA)
Generate summary statistics for key features.
Visualize salary distributions and trends using bar charts, box plots, and histograms.
Statistical Analysis
Perform regression analysis to understand the impact of various factors on salary.
Use correlation analysis to identify relationships between different variables.
Visualizations
Bar charts showing salary trends by experience level and employment type.
Box plots comparing salary distributions across different remote work ratios.
Heatmaps illustrating geographic salary trends.
