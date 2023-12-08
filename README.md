# KPMG-AU-Data-Analytics-Job-Simulation
Welcome to the KPMG Data Analytics Virtual Internship for July 2023! In this simulation, you'll step into the shoes of a Data, Analytics and modeling team member at KPMG Australia. Your primary focus will be advising a client on customer targeting through data analysis. This README provides an overview of the tasks, findings, and recommendations made during the internship.

Overview
Task Summary
Completed a simulation advising a client on customer targeting.
Assessed data quality and completeness for analysis.
Analyzed data to target high-value customers based on demographics and attributes.
Developed dashboards to communicate findings with visuals.

Role: Data Analytics Intern, KPMG
Data Quality Analysis
Identified Errors and Mitigation Recommendations
Customer Demographic (Total records 4000)
DOB

01 record with an invalid date (1843)
87 records with blank values
last_name

125 records with blank values
Gender

88 records with 'U' (Undefined)
Inconsistencies in gender values (e.g., M, Male, F, Female, Femal)
job_title

506 records with blank values
job_industry

656 records mention 'N/A'
Default

3317 records with special characters, including null and blanks
Tenure

87 records with blank values
Mitigation Recommendations

Impute missing DOB values with the mode year.
Assign a uniform last name to records with missing values.
Standardize gender values and replace 'U' based on customer names.
Fill in tenure values with the mean of existing values.
Eliminate blank orders to remove fake orders.
Transactions (Total records 20000 - past 3 months)
Online_order

94 records with blank values
brand, product_line, product_class, product_size, standard_cost, product_first_sold_date

48 records with blank values in each field
Mitigation Recommendations

Address missing values in online orders.
Resolve blank values in brand, product line, product class, product size, standard cost, and product first sold date fields.
Next Steps
The KPMG Data Analytics Team recommends implementing the above mitigations to enhance data quality, leading to more accurate analytics and better results for your company. If you have any questions or need further clarification, please feel free to reach out.

Thank you for the opportunity to contribute to your data analytics journey.
