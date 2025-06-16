# Data Science Job Analysis

This project analyzes a dataset of data science job listings to identify trends in required skills, job titles, and salary expectations.

## Project Overview

The goal of this project is to provide insights into the data science job market by examining key features such as job titles, required skills, and associated salaries. The analysis includes:

*   Identifying the most frequently requested skills.
*   Comparing the skills required for different job roles (e.g., Analyst vs. Scientist).
*   Analyzing salary distributions across different job titles.
*   Exploring the relationship between skill demand and median salary.

## Dataset

The analysis is based on a Dataset acquired from Kaggle titled indeed_uk_datascience_jobs_jan2024.

## Analysis Steps

The Colab notebook performs the following main steps:

1.  **Load Data:** Reads the `Cleaned_Dataset.csv` file into a pandas DataFrame.
2.  **Data Cleaning:** Removes or handles missing values and irrelevant columns (in this case the 'Date' column did
3.  not contain a date).
4.  **Skill Analysis:**
    *   Calculates the percentage of job listings mentioning each skill.
    *   Identifies the top skills overall and for specific roles (Analyst, Scientist).
    *   Visualizes skill percentages using bar charts.
5.  **Job Title Analysis:**
    *   Identifies the most common job titles.
    *   Analyzes salary distributions for the top job titles using box plots.
6.  **Skill Demand vs. Salary Analysis:**
    *   Calculates the demand percentage and median salary for each skill.
    *   Visualizes the relationship between skill demand and median salary using scatter plots.

## How to Run the Notebook

1.  Open the `Data Jobs analysis.ipynb` file in Google Colab.
2.  Upload the `indeed_uk_datascience_jobs_jan2024` file to the Colab environment.
3.  Run each code cell sequentially.

## Dependencies

The notebook uses the following Python libraries:

*   `pandas`
*   `seaborn`
*   `matplotlib`
*   `collections` (Counter)
*   `IPython` (for display and get_ipython)
*   `datasets` (although not explicitly used in the provided code snippets, it is imported)
*   `google.colab.files` (for file upload)

These libraries are standard in the Colab environment, so no additional installation should be required.

## Results

The analysis provides visualizations and tables showing:

*   Top skills by percentage of mentions.
*   Specific skills in demand for Analyst and Scientist roles.
*   Salary ranges for the most common job titles.
*   The correlation between skill demand and median salary, highlighting potentially valuable skills to acquire.
  
