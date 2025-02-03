# Credit Card Approval Prediction Exploratory Data Analysis (EDA)
This repository contains exploratory data analysis (EDA) for understanding patterns and insights in credit card application data.

## Overview
Exploratory data analysis (EDA) is a crucial step in understanding the structure and characteristics of a dataset. In this project, we conduct EDA on a dataset containing information about credit card applicants. The goal is to gain insights into various factors that may influence credit card approval decisions.

## Dataset
The dataset used in this project is sourced from Kaggle. It contains [number of samples] samples and [number of features] features, including:

- CODE_GENDER: Gender of the applicant (e.g., Male, Female)
- FLAG_OWN_CAR: Whether the applicant owns a car (Yes/No)
- FLAG_OWN_REALTY: Whether the applicant owns real estate (Yes/No)
- CNT_CHILDREN: Number of children the applicant has
- AMT_INCOME_TOTAL: Total income of the applicant
- NAME_INCOME_TYPE: Type of income (e.g., Working, Pensioner)
- NAME_EDUCATION_TYPE: Level of education of the applicant
- NAME_FAMILY_STATUS: Family status of the applicant
- NAME_HOUSING_TYPE: Housing situation of the applicant
- DAYS_BIRTH: Age of the applicant in days (negative value)
- DAYS_EMPLOYED: Number of days the applicant has been employed (negative value)
- FLAG_MOBIL: Number of mobile applicant has 
- FLAG_WORK_PHONE: Number of work phone applicant has 
- FLAG_PHONE: Number of phone applicant has
- FLAG_EMAIL: Number of email applicant has 
- OCCUPATION_TYPE: Type of occupation of the applicant
- CNT_FAM_MEMBERS: Number of family members of the applicant
- MONTHS_BALANCE: Number of months since the last balance (e.g., -1 indicates the latest month)

## Repository Structure
- data/: This directory will contain the dataset files, application_record.csv and credit_record.csv, along with any other related data files used in the project.
- notebooks/: This directory will contain the Jupyter notebook titled Credit Card Approval Prediction EDA. This notebook will be used for exploratory data analysis (EDA), where you will analyze the application_record.csv and credit_record.csv datasets.
- README.md: This Markdown file will provide an overview of the project, including details about the datasets, project structure, usage instructions, results summary, and other relevant information.

## Results:
1. Demographic Insights:
- Gender Distribution: The dataset contains a balanced distribution of male and female applicants, with approximately equal proportions.
- Age Distribution: The age distribution of applicants ranges from 20 to 70 years, with the majority of applicants falling between 30 and 50 years old.
- Family Status: Most applicants are married or living together, followed by single applicants.
2. Financial Insights:
- Income Distribution: The income distribution of applicants varies widely, with the majority having incomes in the lower to middle range.
- Employment Status: A significant portion of applicants are employed, while a smaller percentage are retirees or unemployed.
- Housing Type: The majority of applicants own real estate, followed by those who rent.
3. Credit History Insights:
- Months Since Last Balance: The number of months since the last balance ranges from -60 to 0, with a peak around -1, indicating that many applicants have recent credit activity.
- Credit Status: A substantial number of applicants have a positive credit status, while a smaller percentage have a negative credit status.
4. Other Insights:
- Occupation Types: The dataset contains various occupation types, with the most common being laborers, sales staff, and core staff.
- Number of Children: The number of children per applicant varies, with a significant portion having no children and others having one or more children.
5. Correlation Analysis:
- Income vs. Education: There is a positive correlation between income and education level, with higher-educated individuals tending to have higher incomes.
- Age vs. Employment Duration: There is a negative correlation between age and the number of days employed, indicating that younger individuals tend to have longer employment durations.

These insights provide a deeper understanding of the characteristics of credit card applicants and their credit history. They can be valuable for informing future modeling efforts and decision-making processes related to credit card approval prediction.
