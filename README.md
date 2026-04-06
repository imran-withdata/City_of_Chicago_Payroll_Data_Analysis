# City of Chicago Payroll Data Analysis

## Project Overview
This project involves a comprehensive exploratory data analysis of the City of Chicago Payroll Data. The goal is to understand various aspects of the city's employee payroll, including salary structures, hourly rates, departmental distribution, and job title insights.

## Data Source
*   `City_of_Chicago_Payroll_Data.csv`

## Libraries Used
*   `pandas` for data manipulation and analysis.

## Key Analysis Performed
1.  **Data Loading and Inspection**:
    *   Loaded the dataset into a pandas DataFrame.
    *   Displayed the first five rows (`pay.head()`).
    *   Obtained a summary of the DataFrame including data types and non-null values (`pay.info()`).
    *   Identified and quantified missing values in each column (`pay.isnull().sum()`).
    *   Generated descriptive statistics for the dataset (`pay.describe(include='all')`).

2.  **Typical Hours Analysis**:
    *   Calculated the maximum, minimum, and average 'Typical Hours' of employees.

3.  **Employment Type Analysis**:
    *   Determined the number of employees on salary versus hourly basis.

4.  **Departmental Insights**:
    *   Identified the department with the maximum number of employees.
    *   Analyzed the salary vs. hourly employee distribution specifically within the Police Department.

5.  **Salary Analysis**:
    *   Cleaned and converted the 'Annual Salary' column to a numeric 'Salary' column by removing dollar signs and commas.
    *   Calculated the mean, maximum, and minimum salaries.
    *   Identified the employee with the maximum salary.
    *   Identified the employee with the minimum salary.

6.  **Hourly Rate Analysis**:
    *   Cleaned and converted the 'Hourly Rate' column to a numeric 'H_Rate' column by removing dollar signs.
    *   Calculated the mean, maximum, and minimum hourly rates.
    *   Determined the number of employees receiving the maximum hourly rate.
    *   Identified the employee receiving the maximum hourly rate.
    *   Counted employees earning less than the average hourly rate.

7.  **Job Title and Employee Status Analysis**:
    *   Counted employees who are paid hourly and work full-time.
    *   Identified full-time employees working at an hourly rate of $10.00.

8.  **Job Titles Overview**:
    *   Determined the number of unique job titles in the dataset.
    *   Found the average salary for employees in each department.
    *   Identified the job title of a specific employee ('AGAR, BULENT B').
    *   Found the top most common job titles.
    *   Counted how many people have the word 'officer' in their job title (case-insensitive).

9.  **Data Export**:
    *   Saved the final processed DataFrame to a CSV file named `store.csv`.
