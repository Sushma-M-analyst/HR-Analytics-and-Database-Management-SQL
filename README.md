# HR Analytics and Database Management System using SQL

## Project Overview

The HR Analytics and Database Management System is a comprehensive SQL project designed to manage and analyze employee-related data within an organization. The project focuses on employee management, department analysis, salary reporting, job allocation, location tracking, and dependent management using SQL.

The system demonstrates database design principles and advanced SQL concepts to generate meaningful business insights from HR data.

---

## Business Problem

Organizations generate large volumes of employee data across departments, locations, jobs, and reporting structures. Managing and analyzing this information is critical for workforce planning, performance evaluation, compensation management, and organizational decision-making.

This project aims to build an HR database that enables efficient employee management and analytical reporting using SQL.

---

## Objectives

* Manage employee information efficiently.
* Analyze workforce distribution across departments.
* Evaluate salary structures and compensation trends.
* Track employee-manager relationships.
* Monitor department performance.
* Generate business reports using SQL.
* Demonstrate advanced SQL concepts and database operations.

---

## Database Tables

### Employees

Stores employee details including salary, department, manager, and hire date.

### Departments

Stores department information.

### Jobs

Stores job titles and job details.

### Locations

Stores office location information.

### Countries

Stores country information.

### Regions

Stores regional information.

### Dependents

Stores employee dependent details.

---

## SQL Concepts Covered

### Data Definition Language (DDL)

* CREATE TABLE
* ALTER TABLE
* ADD COLUMN
* DROP COLUMN
* FOREIGN KEY Constraints

### Data Query Language (DQL)

* SELECT
* DISTINCT
* ORDER BY
* TOP N Queries

### Filtering and Conditions

* WHERE Clause
* IN
* BETWEEN
* LIKE
* IS NULL
* EXISTS

### Joins

* INNER JOIN
* LEFT JOIN
* SELF JOIN
* FULL OUTER JOIN
* CROSS JOIN

### Aggregations

* COUNT()
* SUM()
* AVG()
* MIN()
* MAX()

### Advanced SQL

* GROUP BY
* HAVING
* CASE Statements
* Subqueries
* Correlated Subqueries
* UNION
* INTERSECT

### Data Manipulation

* UPDATE Statements

---

## Key SQL Tasks Performed

### Employee Analysis

* Employee records retrieval
* Employee salary reporting
* Employee hire date analysis
* Employee phone number validation

### Salary Analysis

* Highest salary employee identification
* Second highest salary calculation
* Average salary comparison
* Salary categorization using CASE statements

### Department Analysis

* Employee count by department
* Department salary expenditure
* Department performance analysis
* Department headcount reporting

### Manager Analysis

* Manager and direct report identification
* Reporting hierarchy analysis
* Manager performance evaluation

### Workforce Analysis

* Employees with dependents
* Employees without dependents
* Department workforce distribution
* Location-based employee analysis

---

## Business Insights

### Workforce Distribution

* Identified departments with the highest employee count.
* Analyzed workforce allocation across business units.

### Salary Insights

* Determined salary ranges across departments.
* Identified high-performing and highly compensated employees.

### Organizational Structure

* Analyzed reporting relationships between managers and employees.
* Evaluated management span of control.

### HR Reporting

* Generated department-level and employee-level reports.
* Improved visibility into employee demographics and compensation structures.

---

## Technologies Used

* SQL
* MySQL / SQL Server
* Relational Database Management System (RDBMS)
* Database Design
* Data Analysis

---

## Entity Relationship Diagram (ERD)

The database consists of seven interconnected tables:

- Regions
- Countries
- Locations
- Departments
- Jobs
- Employees
- Dependents

### Key Relationships

- One Region can have many Countries.
- One Country can have many Locations.
- One Location can have many Departments.
- One Department can have many Employees.
- One Job can be assigned to many Employees.
- One Employee can have multiple Dependents.
- One Employee can manage multiple Employees (Self Join Relationship).

ER Diagram is available in the Documentation folder.

## Skills Demonstrated

* SQL Query Writing
* Database Design
* Data Analysis
* Workforce Analytics
* Salary Analysis
* Department Performance Analysis
* Reporting and Dashboard Preparation
* Relational Database Management

---

## Conclusion

The HR Analytics and Database Management System demonstrates the practical application of SQL in managing and analyzing employee data. The project covers fundamental and advanced SQL concepts including joins, subqueries, aggregate functions, set operators, CASE expressions, and database constraints. It provides meaningful workforce insights and supports data-driven HR decision-making.

---

## Author

Sushma M

Business Analyst | SQL | Power BI | Excel | Python

Bengaluru, Karnataka
