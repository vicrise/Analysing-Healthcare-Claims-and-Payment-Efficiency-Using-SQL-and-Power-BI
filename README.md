# Healthcare Insurance Analytics Using Power BI & SQL
### PROJECT OVERVIEW
This project focuses on analysing healthcare claims and payment patterns by integrating and evaluating data from patients, providers, claims, and payment systems.
 Using SQL for data extraction and transformation, and Power BI for visualisation, the goal is to uncover trends in claim approval rates, provider efficiency, patient demographics, and payment recovery performance.
 The insights generated will support healthcare administrators in optimising claim processing, identifying high-performing providers, and reducing financial leakage in the system.
### PROBLEM STATEMENT 
In the healthcare industry, inefficient claims management can lead to delayed payments, increased operational costs, and provider dissatisfaction. 
Organisations often lack clear visibility into claim outcomes, payment accuracy, and provider-level performance. With large volumes of patient and claim data, manual analysis becomes infeasible. 
This project addresses the challenge of integrating disparate datasets and delivering interactive, data-driven insights to monitor and optimise the financial performance of claims processing workflows.
### BUSINESS QUESTIONS
1.	What is the overall claim approval rate across all providers and patients?
2.	Which providers have the highest approval rates?
3.	Which patient demographics (age, gender, location) are associated with the highest claim amounts or frequencies?
4.	Are there any seasonal or monthly patterns in claims and payments?
5.	What is the recovery rate (payment vs. claim amount
6.	Which providers specialise in high-cost or high-volume claim areas?
7.	Who are the top 10 most frequent claimants, and how do they impact total expenditures?
8.	Are claims from certain specialities (e.g., cardiology, surgery) more likely to be approved or paid promptly?
9.	Is there a correlation between claim amount and approval likelihood?
### METHODOLOGY
#### TOOL USED: SQL and Power BI
#### DATA CLEANING PROCESS AND TRANSFORMATION: 
- I ensured that there were no duplicates, inconsistencies or errors, and I ensured the datatypes were correct  
-	I removed the phone number column because it is not necessary for my analysis 
-	I imported the database into Power BI for visualisation
### DATA ANALYSIS USING SQL
- [SQL QUERY](https://github.com/vicrise/Analysing-Healthcare-Claims-and-Payment-Efficiency-Using-SQL-and-Power-BI/blob/main/HOSPITAL%20CLAIM%20SCRIPT.sql)
### DATA ANALYSIS USING POWER BI
- DAX FUNCTION
- Claim Approval Rate (%) = 
- DIVIDE(
    [Total Approved Claims],
    [Total Claims],0)
- Total Claims = COUNTROWS(Claims)
### KEY INSIGHTS
-  The Claim Approval Rate is around 70.28%, which is relatively good, but it needs improvement. The Rejection Rate is nearly 20% and 1%, suggesting potential issues with claim quality or documentation.
- $3.39bn in Total Payouts indicates high financial throughput.
- Most patients are male, and the average age is 53.4 years, pointing toward a middle-aged demographic focus.

- The monthly claims show fluctuations, with peak periods in March 
and October, which vary across different years
- Some providers have lower-than-average recovery rates despite a high approval rate, indicating possible underbilling or delayed follow-up.
-  Claim trends by month suggest seasonality or operational cycles.

- The monthly payment pattern varies across different years, with peaks in March and July.
- Young adults and middle-aged patients generate the most claims, and females account for a higher proportion of claims.
- A visible positive correlation between claim count and payment amount.
- [DASHBOARD 1](https://github.com/vicrise/Analysing-Healthcare-Claims-and-Payment-Efficiency-Using-SQL-and-Power-BI/blob/main/Screenshot%20(160).png)
- [DASHBOARD 2](https://github.com/vicrise/Analysing-Healthcare-Claims-and-Payment-Efficiency-Using-SQL-and-Power-BI/blob/main/Screenshot%20(161).png)
- [DASHBOARD 3](https://github.com/vicrise/Analysing-Healthcare-Claims-and-Payment-Efficiency-Using-SQL-and-Power-BI/blob/main/Screenshot%20(162).png)
### RECOMMENDATION
- Audit rejected claims to identify root causes (e.g., incomplete submissions, provider errors).
- Improve patient education or provider training to reduce rejection rates.
- Offer additional support or audits to low-performing providers.
- Adjust resource allocation during peak claim months.
- Use the claim recovery rate as a performance KPI for contract negotiations.
- Develop health education campaigns for high-utilisation age groups to manage costs.
- Customise healthcare services by gender to optimise satisfaction and outcomes.

 - [INTERACTIVE DASHBOARD](https://app.powerbi.com/groups/me/reports/c10a7a51-bb33-444e-bf12-de90568a5f27/fb729d1c2025ea5d5208?experience=power-bi)
### CONCLUSION
- The dashboard supports data-driven decisions for cost control, provider optimization, and targeted patient care—making it a powerful tool for strategic healthcare management.



