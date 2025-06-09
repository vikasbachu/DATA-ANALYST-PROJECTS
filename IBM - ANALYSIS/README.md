#IBM HR Data Analysis using SQL
Project Overview
This project performs an in-depth analysis of the IBM HR dataset using structured SQL queries. The primary objective is to uncover valuable insights related to employee attrition, income trends, satisfaction levels, and departmental performance. The project demonstrates the application of SQL best practices including advanced querying, window functions, Common Table Expressions (CTEs), and stored procedures.

Key Features
Data Cleaning: Filtering out incomplete records using IS NOT NULL checks to ensure data integrity.
Attrition Analysis: Calculation of attrition rates and percentages across various dimensions.
Department and Role Insights: Average income, satisfaction scores, and employee distributions by role and department.
Employee Satisfaction Trends: Identifying high-risk employees based on low satisfaction and overtime.
Salary Ranking: Ranking employees within each department using RANK() window function.
Parameterized Procedure: Dynamic procedure to retrieve the top N earners in each department using a combination of CTE and window functions.
Age Group Distribution: Age segmentation for demographic analysis.
Work-Life Balance Insights: Detailed comparison of attrition rates across different work-life balance categories.

SQL Concepts Used
CREATE DATABASE, CREATE TABLE, CREATE VIEW
Aggregate functions: COUNT(), AVG(), SUM(), MAX(), MIN()
GROUP BY, ORDER BY, CASE for conditional aggregation
Window functions: RANK()
Common Table Expressions (CTE)
Parameterized Stored Procedure
Data Filtering: WHERE IS NOT NULL, BETWEEN, logical operators

Files Included
IBM HR DATA ANALYSIS.sql – Complete SQL script with all queries, views, CTEs, and stored procedures.

How to Run
Import the dataset into your SQL environment.
Run the provided SQL script sequentially.
Execute the stored procedure CALL GetTopEarners(N); to retrieve the top N earners per department.

