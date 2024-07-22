# power_bi
Adverse Event Reporting Analysis in the Food and Cosmetics Industry
This project provides a comprehensive analysis of the adverse events reported in the food, dietary supplements, and cosmetics industry, using the CAERS dataset. The analysis aims to identify patterns and trends, contributing to improved product safety surveillance and public health outcomes.

Table of Contents
Background
Objective
Data Source
Part 1: Data Cleaning, Modeling, and DAX in Power BI
Part 2: Dashboard Building
How to Run the Project
Contributing
License
Background
The CAERS database is a critical tool for the FDA, containing adverse event and product complaint reports related to foods, dietary supplements, and cosmetics. This dataset, covering the period from 2004 to the second quarter of 2017, includes detailed records of various products and associated adverse events. Each record is meticulously coded using the Medical Dictionary for Regulatory Activities (MedDRA) terminology, ensuring standardized reporting across different products. The data captures elements like report numbers, product roles, brand names, industry codes, patient demographics, adverse outcomes, and coded symptoms.

Objective
The primary objective of analyzing the CFSAN Adverse Event Reporting System (CAERS) dataset is to gain a comprehensive understanding of adverse events associated with foods, dietary supplements, and cosmetics as reported to the FDA. This analysis aims to identify patterns and trends in these events, including the distribution across different product categories, the demographic characteristics of those affected, and the types and severities of reported symptoms and outcomes. By exploring these aspects, the analysis seeks to contribute valuable insights for enhancing product safety surveillance, informing regulatory policies, and ultimately improving public health outcomes by identifying potential risks and areas for intervention in the industries of food, dietary supplements, and cosmetics.

Data Source
The dataset from the CFSAN Adverse Event Reporting System (CAERS) is a comprehensive collection of reports submitted to the FDA regarding adverse events and product complaints associated with foods, dietary supplements, and cosmetics. It spans from 2004 to the second quarter of 2017 and includes several key fields:

RA_Report #: A unique identifier for each adverse event report.
RA_CAERS Created Date: The date when the report was entered into the CAERS database.
AEC_Event Start Date: The date when the adverse event started.
PRI_Product Role: Indicates whether the product was a suspect or concomitant (present during the event but not necessarily the cause).
PRI_Reported Brand/Product Name: The name of the product reported to be associated with the adverse event.
PRI_FDA Industry Code & Name: Categorization of the product based on FDA industry codes and names, such as 'Bakery Prod/Dough/Mix/Icing', 'Ice Cream Prod', etc.
CI_Age at Adverse Event: Age of the individual experiencing the adverse event.
CI_Age Unit: Unit of measurement for age (e.g., years, months).
CI_Gender: Gender of the individual.
AEC_One Row Outcomes: Describes the outcomes of the event, such as hospitalization, ER visit, or non-serious injuries/illness.
SYM_One Row Coded Symptoms: Lists the symptoms reported in association with the adverse event.
The dataset can be downloaded from the following link: CAERS_ASCII_2004_2017Q2.csv

Part 1: Data Cleaning, Modeling, and DAX in Power BI
Data Importing and Preliminary Analysis
Import the dataset into Power BI and perform an initial examination. Identify any apparent inconsistencies or data quality issues.
Handling Missing Values
Investigate and address the missing values. Determine an appropriate strategy for handling these.
Data Type Standardization
Ensure that all data types are correctly identified and converted if necessary, particularly for dates and numerical fields.
Product Role Categorization
Categorize the products based on their role ('PRI_Product Role') and analyze the distribution of these roles in the dataset.
FDA Industry Analysis
Group the data by 'PRI_FDA Industry Name' and analyze the frequency of reports in each industry.
Age Group Analysis
Create age groups from 'CI_Age at Adverse Event' and analyze the distribution of adverse events across these age groups.
Gender-Based Analysis
Examine the distribution of reports by gender. Are there noticeable differences in adverse event reporting between genders?
Adverse Event Start Date Analysis
Analyze the distribution of 'AEC_Event Start Date' over time. Identify any trends or patterns.
Outcome Categorization
Categorize 'AEC_One Row Outcomes' into broader categories and analyze the distribution of these categories.
Symptom Frequency Analysis
Analyze the most frequently reported symptoms in 'SYM_One Row Coded Symptoms'.
Correlation between Age and Symptom Types
Use DAX to investigate if there's a correlation between age and types of symptoms reported.
Industry and Outcome Relationship
Examine the relationship between 'PRI_FDA Industry Name' and types of outcomes reported.
Time Series Analysis of Reports
Perform a time series analysis to identify any seasonal trends in report submissions.
DAX for Advanced Age Analysis
Utilize DAX to calculate the average, median, and mode of the ages at which adverse events occur.
Product Name Analysis
Use text analysis techniques to identify the most commonly reported products.
Geographical Distribution (If Applicable)
If the data includes geographical information, analyze the distribution of reports by region.
Advanced DAX: Report Frequency Calculation
Develop a DAX formula to calculate the frequency of reports per month or year.
Symptom Severity Index
Create a severity index for symptoms based on their frequency and association with serious outcomes.
Report Duplication Analysis
Identify and handle any duplicate reports in the dataset.
Predictive Modeling for Adverse Event Risk
Use DAX to create a predictive model estimating the risk of adverse events based on product type and demographic data.
Complex Symptom Pattern Analysis
Utilize nested functions in DAX to analyze the dataset and find patterns in the occurrence of symptoms.
Advanced Outcome Prediction Model
Develop an advanced predictive model using DAX that estimates the likelihood of severe outcomes based on multiple factors.
Part 2: Dashboard Building
Adverse Event Reporting Dashboard
Develop a comprehensive dashboard showcasing key metrics such as frequency of reports, common symptoms, product types, and demographic breakdowns. Include interactive filters for industry, product role, and age groups.
Dashboard Design and Accessibility
Focus on making the dashboard visually appealing, easy to navigate, and accessible to users with different levels of expertise.
Time-Based Reporting Trends
Incorporate a section in the dashboard to visualize trends in adverse event reporting over time, highlighting any notable patterns.
Industry and Outcome Correlation Visualization
Create an interactive visualization showing the correlation between different industries and reported outcomes.
Demographic Analysis Section
Implement a section in the dashboard dedicated to analyzing demographic data, including age and gender distributions.
Key Insights and Data Storytelling
Provide a section that summarizes key insights or trends identified in the data, using visual storytelling techniques to highlight important findings.
How to Run the Project
Data Preparation

Download the dataset from the provided link.
Import the dataset into Power BI.
Data Cleaning and Transformation

Follow the steps outlined in Part 1 to clean and transform the data.
Use DAX for advanced calculations and modeling.
Dashboard Creation

Build the dashboard as outlined in Part 2.
Use Power BI features to create interactive and visually appealing visualizations.
Analysis and Reporting

Analyze the data using the dashboard.
Generate insights and share findings with stakeholders.
Contributing
We welcome contributions to this project. If you have suggestions for improvements or want to contribute new analyses or features, please submit a pull request or open an issue.












ChatGPT can make mistakes. Ch
