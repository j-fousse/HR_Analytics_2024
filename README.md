# Attrition Analysis
This HR Analytics project aims to analyze various aspects of human resources within an organization to improve employee performance, job satisfaction, and employee loyalty. Further the overall goal is the prediction of future attrition based on the given data. The dataset used for analysis contains detailed information about employees, including demographic details, job-related factors, and assessments.

# Team Members
Johannes Fousse: [GitHub](https://github.com/j-fousse)

Pelin Öztürk: [GitHub](https://github.com/p-ozturk)

Simon Bolenz: [GitHub](https://github.com/SimonBalangan)

# Jupyter Notebooks
This project consists one Jupyter Notebook, for serving all purposes like:
Data Cleaning and Preparation: This focuses on data cleaning and preparation tasks. It includes handling missing 
values, encoding categorical variables, and scaling numerical features.
Exploratory Data Analysis (EDA): To explore the dataset to gain insights into various HR aspects of the company.

Data Analysis and Modeling: This includes data analysis tasks such as identifying measures to increase job satisfaction and performance ratings, predicting future attrition, and conducting hypothesis tests.

# Installation and Setup
To set up the project locally, follow these steps:
 - Clone the repository: https://github.com/j-fousse/HR_Analytics_2024
 - Navigate to the project directory: cd your-repository
 - Download the HR Analytics dataset and place it in the your-directory.

# Dataset
The HR Analytics dataset contains various columns related to employee information such as age, gender, education, job role, salary, and satisfaction levels.

This Dataset can be obtained from the following link: https://www.kaggle.com/datasets/saadharoon27/hr-analytics-dataset?resource=download

# EDA/Cleaning
During the exploratory data analysis (EDA) and cleaning process, the following steps were undertaken:
- Data types were converted to ensure consistency and compatibility across the dataset.
- 57 rows containing NaN values and 10 duplicate rows were removed to maintain data integrity and accuracy.
- The median was chosen as a robust metric for central tendency measures, ensuring resilience against outliers and extreme values.

# Used libraries and modules:
- pandas
- numpy
- matplotlip
- seaborn
- statsmodels

# Key Results
1. Younger and less experienced employees exhibit a attrition rate above average; from age 36 on the predicted attrition probability is lower than the average attrition rate.
2. Employees who work overtime and/or have a bad work life balance exhibit a attrition rate way above the average.
3. Employees with a low job involvement exhibit a attrion rate almost double the average attrion rate.
4. Certain job roles such as Sales Representatives and Laboratory Technicians exhibit a attrition rate way above the average.
5. The predicted attrition probability decreases as salary increases. 

# Suggestions to mitigate future attrition
1. Set incentives for younger employees
    - such as increasing vacation days in the initial years; extending vesting periods for stock options
    - also consider older applicants
2. Improve Work-Life Balance
    - Reduce overtime or offer compensatory time off for better work-life balance  
3. Enhance Job Involvement
    - Delegate individual responsibility to employees
    - Clarify the overall purpose of less relevant tasks
    - Provide concrete recognition
4. Survey Sales Representatives and Laboratory Technicians to identify specific issues
5. Pay employees appropriate salaries

# License
CC0: Public Domain