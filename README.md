Exploratory Data Analysis (EDA) on Job Salary Dataset

Project Overview
This project focuses on performing an Exploratory Data Analysis (EDA) on a dataset containing job role information and salary distributions. The goal is to uncover key insights about salary patterns across different job roles and industries. The analysis includes data cleaning, manipulation, univariate and bivariate analysis, and addressing key business questions.

Objectives
- Understand the dataset: Analyze the structure and characteristics of the dataset.
- Data cleaning: Handle missing values, remove duplicates, and standardize formats.
- Univariate analysis: Study individual variables to detect trends and anomalies.
- Bivariate analysis: Explore relationships between multiple variables for deeper insights.
- Business insights: Answer critical questions related to salary distribution and job roles.

 Dataset
The dataset consists of the following variables:
  - Job Title: Title or designation of the job role.
  - Industry: The industry the job belongs to (e.g., IT, Finance).
  - Salary: The annual salary for the job role.
  - Experience Level: The level of experience required for the job (e.g., Junior, Senior).

Steps Involved

1. Data Cleaning
- Handled missing values by using median imputation for salary data and removed rows with empty job titles.
- Removed duplicate entries to ensure data quality.
- Standardized job titles by fixing misspelled or inconsistent values.

2. Data Manipulation
- Created new features like salary ranges and experience groupings to aid analysis.
- Converted categorical variables such as job roles into numerical codes for easier analysis.
- Filtered out extreme outliers in salary data to focus on realistic salary distributions.

3. Univariate Analysis
- Analyzed the distribution of salaries across different job titles using histograms and box plots.
- Explored the spread of job titles and industry types using bar charts.
- Examined experience levels and their impact on average salary.

4. Bivariate Analysis
- Investigated the relationship between salary and job title using scatter plots and grouped bar charts.
- Explored salary variations across industries using box plots.
- Analyzed the interaction between experience level and salary to identify how experience impacts earnings.

Key Findings
- Insight 1: Senior roles, especially in IT, tend to offer significantly higher salaries compared to other industries.
- Insight 2: Job titles within the same industry can have large salary disparities, highlighting the importance of experience level and specialization.
- Insight 3: Entry-level positions show more salary consistency across industries compared to senior roles, which have a wider salary range.

Tools Used
- Programming language: Python
- Libraries: Pandas, NumPy, Matplotlib, Seaborn
- Platform: Jupyter Notebook

## Conclusion
This EDA project reveals important trends in job salaries across industries and experience levels. The analysis helps to understand key factors that influence salaries and provides insights that can assist both job seekers and employers in making informed decisions.
