HR Attrition Analysis - Data Analytics Mini Project

Excel for data cleaning and transformation, Power BI for the report and dashboard.

Objective

Find out which employees are most likely to leave a company and which factors are linked to attrition, using an HR employee dataset.

Original Dataset Source
Dataset: Human_Resources.csv (employee records from a fictional company)
Dataset link: https://data.mendeley.com/datasets/smypp8574h/1
DOI link: https://doi.org/10.17632/smypp8574h.1
Platform: Mendeley Data
Contributor: Abdelrahim Aqqad
Published: 1 November 2023 (Version 1)
Licence: CC BY 4.0
Project Files
File	Description
Human_Resources.project.csv.xlsx	Cleaned dataset with calculated columns and pivot tables
Power Bi Dashboard.pdf	Power BI report exported as PDF
HR_Project_Screenshots_and_Insights.pdf	Project screenshots followed by the insights page
README.md	This file
Data Cleaning and Transformation (Excel)
Loaded Human_Resources.csv into Excel and converted it to a Table.
Checked for blank cells and handled them in the cleaned file.
Removed columns that were not needed for the analysis.
Created calculated columns with formulas: Age Group, Income Band, Tenure Band and Attrition Flag.
Built pivot tables on separate sheets for Descriptive, Diagnostic, Predictive and Prescriptive analysis, plus salary and performance comparisons.
Power BI Report

Two dashboard pages:

Attrition Dashboard: attrition by department, age group, overtime and tenure band, with cards for employee count and attrition rate.
Salary and Performance Dashboard: monthly income by department, gender, job role and performance rating.
Four Types of Analysis
Type	Question	Example
Descriptive	What happened?	Attrition rate for each department
Diagnostic	Why did it happen?	Attrition for overtime vs non-overtime employees
Predictive	What may happen?	Highest-risk groups by tenure and income band
Prescriptive	What should we do?	Retention plan for current high-risk employees
Key Insights
Overall attrition is 16.1%: 237 of 1,470 employees left.
Overtime doubles the risk: 30.5% of overtime employees left, against 10.4% of others.
Sales has the highest department attrition (20.6%), against 13.9% in Research & Development. Sales Representatives are highest at 39.8%.
New joiners leave most: 34.9% attrition in the first 0-1 years, falling to 10.4% after 10 years.
Low pay and young age raise risk: 28.7% attrition in the low income band, and 27.9% for employees under 30.
Action needed: 69 employees work overtime and have 0-1 years of service. 55.1% of them left, and 31 are still employed and should be prioritised for retention.

Note: these figures were calculated before cleaning the blank cells, so small differences are possible after cleaning. The dataset is fictional and has no dates, so the predictive analysis is a risk estimate from past patterns, not a time forecast.

Tools

Microsoft Excel, Power BI Desktop
