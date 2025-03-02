Beauty Salon Data Warehouse Project

Project Overview

This project is a Data Warehouse implementation for a Beauty Salon business. The goal was to design a relational database and an external data source (Excel sheet), then integrate them into a Data Warehouse using Microsoft SQL Server and Microsoft Visual Studio. This project demonstrates the ETL (Extract, Transform, Load) process and enables business intelligence reporting.

Technologies Used

Database Management System: Microsoft SQL Server

ETL Tool: Microsoft Visual Studio (SSIS - SQL Server Integration Services)

Data Sources: SQL Database & Excel Spreadsheet

Reporting Tools: SQL Server Reporting Services (SSRS)

Query Language: SQL

Project Components

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
