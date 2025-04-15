# SQL Window Functions Assignment

**Group Name:** Big Leagues  
**Members:**  
- SINGIZA GIHOZO MACRINE (27677)  
- KARURANGA Christian (27541)  
**Instructor:** Eric Maniraguha  

## Overview

This repository contains SQL scripts for an assignment on SQL Window Functions, covering table creation, data insertion, and queries using functions like LAG(), LEAD(), RANK(), DENSE_RANK(), ROW_NUMBER(), and aggregate functions with PARTITION BY.

## Files Description

- **table_creation.sql:** Creates `employees` and `allowances` tables.  
  ![Table creation](/table_create.png)  
- **data_insertion.sql:** Inserts sample data into the tables for testing.  
  ![Data insertion](/insert.png)  
- **window_functions_queries.sql:** Includes queries for:  
  1. **Comparing Values:** Analyze salary trends using LAG() and LEAD().  
     ![Task 1 Output](/task1.png)  
  2. **Ranking Data:** Rank employees by salary within departments using RANK() and DENSE_RANK().  
     ![Task 2 Output](/task2.png)  
  3. **Identifying Top Records:** Fetch top 3 salaries per department using ROW_NUMBER().  
     ![Task 3 Output](/task3.png)  
  4. **Finding Earliest Records:** Retrieve first two join dates per department using ROW_NUMBER().  
     ![Task 4 Output](/task4.png)  
  5. **Aggregation:** Calculate maximum salary per department and overall using MAX().  
     ![Task 5 Output](/task5.png)  

## Collaboration

Both members contributed equally, and the instructor is added as a collaborator for evaluation.
