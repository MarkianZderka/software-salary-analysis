# Software Salary Analysis (India)

## Overview

This project presents an exploratory data analysis (EDA) of a dataset containing salary information for software professionals in India. The dataset was originally posted on [Kaggle](https://www.kaggle.com/datasets/whenamancodes/software-professional-salary-dataset?resource=download), and the data was collected from Glassdoor.

At first glance, the dataset appeared to represent international data. However, upon closer inspection during the analysis phase, it became evident that it contains only 10 unique locations — all Indian cities. Therefore, this analysis reflects the software job market in India.

## Goal

The main objective of this project was to better understand the salary structure, most common roles, and the connection between employment types and salary among software professionals. The project is also intended to showcase core data analytics skills through a structured, well-documented analysis pipeline.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Git + GitHub

## Key Insights

### Salary Distribution

- The salary distribution is highly variable, but several clear peaks were identified.
- These "peaks" may reflect common salary bands offered by companies.

### Employment Types

- Full-time employees generally earn more than interns, which is expected.
- Contractors had salaries quite close to full-time employees in many cases.

### Popular Positions

- We identified the most common job titles and examined how average salary varies by role.
- There was no strong correlation between how popular a position is and how well it pays.

### Company Ratings vs Salaries

- We selected the top 10 most represented companies in the dataset and compared their average salaries and average ratings from employees.
- The analysis showed no clear correlation between company rating and average salary.
  - For example, *Fresher* had the highest average rating but one of the lowest average salaries.
  - On the other hand, *Infosys* had a much higher average salary but the lowest rating among the top 10.

## Final Thoughts

This project helped uncover insights about how software salaries vary in India based on job role, employment type, and company. It also demonstrated how real-world data can be messy and full of surprises (e.g., geographic limitations, outliers, and unclear column definitions).

Overall, the project illustrates a typical data analysis workflow, including:

- Data cleaning
- Exploratory data analysis
- Visualizations
- Interpretation of trends and anomalies

## Dataset

[Software Professional Salary Dataset on Kaggle](https://www.kaggle.com/datasets/whenamancodes/software-professional-salary-dataset?resource=download)
> **Note:** This project uses the version of the dataset named `Salary_Dataset_with_Extra_Features.csv`, which contains additional columns such as `Employment Status` and is better suited for deeper analysis.
