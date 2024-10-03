# LITA_CLASS_DOCUMENTATION
Documentation of my first project while learning Data Analysis with the Incubator Hub

### Project Title: ABC Sales Analysis

### Project Overview
This project aims at bringing awareness to the company in respect to the progression of their sales activity over the past years. The analysis will indicate overall state of past sales and proffer better solution based on adequate and reasonable decision for optimum results of sales in the coming years.

### Data Sources
The primary source of Data is Data.csv and other source like kaggle and Fred.

### Tools Used
-Microsoft Excel [Download Here](https//www.microsoft.com)
 1. for Data Cleaning
 2. for Data Analysis
 3. for Data Validation
    
-SQL: Structured Query Language
 1. for querying
 2. for updating affected fields and records:
``` UPDATE table 1
     set location= 'Abuja'
     where SalesID= 'Ab201'
 3. for selecting affected fields and records:
``` SELECT p.ProductID, p.ProductName
    FROM Products p
    LEFT JOIN Sales s ON
    p.ProductID= s.ProductID
    WHERE s.ProductID is NULL
-GitHub for building portfolio

### 
