Beauty Salon Data Warehouse Project

Project Overview

This project is a Data Warehouse implementation for a Beauty Salon business. The goal was to design a relational database and an external data source (Excel sheet), then integrate them into a Data Warehouse using Microsoft SQL Server and Microsoft Visual Studio. This project demonstrates the ETL (Extract, Transform, Load) process and enables business intelligence reporting.

Technologies Used

Database Management System: Microsoft SQL Server

ETL Tool: Microsoft Visual Studio (SSIS - SQL Server Integration Services)

Data Sources: SQL Database & Excel Spreadsheet

Reporting Tools: SQL Server Reporting Services (SSRS)

Query Language: SQL

Division into tasks (it was required due to the fact that it was an university project):
Task1 - Establishing buisness goals and processes as well as data sources
Task2 - Building database ( first source ) and filling it with generated data as well as excel sheet (second source) and filling it with generated data
Task3 - Developing document describing data warehouse according to the provided schema
Task4 - Establishing cube in MSVS
Task5 - Establishing ETL process in MSVS
Task6 - Conducting queries for the warehouse in MS SQL Server 2019 
Task7 - Report about the efficiency of the warehouse, comparing MOLAP, ROLAP and HOLAP
Task8 - Visualizing KPIs and queries using Power BI

Project Components:

1. Data Sources

Relational Database: Designed in SQL Server to store structured transactional data.

Excel Sheet: Contains additional beauty salon data.

2. Data Warehouse Schema

A star schema was designed with the following tables:

Fact Table: Appointment, Rating, Product Usage

Dimension Tables:

Customer

Employee

Service

Time

Product

Position

Date

Client

Junk

3. ETL Process

Extract: Data from SQL database and Excel sheet.

Transform: Cleaning, formatting, and integrating data into a structured format.

Load: Data stored in the Data Warehouse for reporting and analysis.

4. Data Analysis & Reporting

Queries were written to generate reports for:

Total revenue per month

Most popular beauty services

Customer visit frequency

Employee performance tracking

Peak booking times
