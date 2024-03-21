# Attrition Analysis
This HR Analytics project aims to analyze various aspects of human resources within an organization from the pharmaceutical industry to improve employee performance, job satisfaction, and employee loyalty. Further the overall goal is the prediction of future attrition based on the given data. The dataset used for analysis contains detailed information about employees including demographic details, job-related factors and assessments.

Note: some text or visualisation titles may be in german because they were used for a presentation to a german audience

# Team Members
Johannes Fousse: [GitHub](https://github.com/j-fousse)

Pelin Öztürk: [GitHub](https://github.com/p-ozturk)

Simon Bolenz: [GitHub](https://github.com/SimonBalangan)

# Jupyter Notebooks
This project consists of one Jupyter Notebooks for serving different purposes:
- Data Cleaning and Preparation: This focuses on data cleaning and preparation tasks. It includes handling missing 
values, encoding categorical variables and removing duplicates.
- Exploratory Data Analysis (EDA): To explore the dataset to gain insights into various HR aspects of the company.
- Data Analysis and Modeling: This includes data analysis tasks such as identifying measures to increase job satisfaction and performance ratings and predicting future attrition.

# Installation and Setup
To set up the project locally, follow these steps:
 - Clone the repository: https://github.com/j-fousse/HR_Analytics_2024
 - Navigate to the project directory: cd your-repository
 - Download the HR Analytics dataset and place it in the your-directory.

# Dataset
The HR Analytics dataset contains various columns related to employee information such as age, gender, education, job role, salary, and satisfaction levels.

This Dataset can be obtained from this [link](https://www.kaggle.com/datasets/saadharoon27/hr-analytics-dataset?resource=download).

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

![Datenanalyse5](https://github.com/j-fousse/HR_Analytics_2024/assets/162298231/e6e8e919-a475-4f83-b041-86a137b7c0b0)
   
2. Employees who work overtime and/or have a bad work life balance exhibit a attrition rate way above the average.

![Datenanalyse2](https://github.com/j-fousse/HR_Analytics_2024/assets/162298231/267d275d-4e15-483a-8d3b-a343d7ed22a8)

![Datenanalyse4](https://github.com/j-fousse/HR_Analytics_2024/assets/162298231/11d3015f-7fa3-45eb-bad1-6258c8e0a5d4)

3. Employees with a low job involvement exhibit a attrion rate almost double the average attrion rate.

![Datenanalyse3](https://github.com/j-fousse/HR_Analytics_2024/assets/162298231/51e0fa6e-3221-4106-8898-ca10b64d20e4)

4. Certain job roles such as Sales Representatives and Laboratory Technicians exhibit a attrition rate way above the average.

![Datenanalyse1](https://github.com/j-fousse/HR_Analytics_2024/assets/162298231/55ddc0fd-e37f-4b85-ab17-a204ff4526ad)

5. The predicted attrition probability decreases as salary increases. 

![Datenanalyse6](https://github.com/j-fousse/HR_Analytics_2024/assets/162298231/f7729cea-43fa-4da2-acf5-a845e8e4e8a0)

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
