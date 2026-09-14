# Chinook SQL Sales, Marketing & HR Analysis

## 📌 Project Overview

This project uses the **Chinook database** to perform SQL-based business analysis.
The analysis covers **sales performance, customer behavior, marketing trends, and employee relationships** using practical SQL queries.
The main goal is to understand how SQL can be used to analyze relational data and generate meaningful business insights.

---

## 📂 Data Source

The dataset used in this project is the **Chinook Database**, an open-source sample database containing information about customers, invoices, tracks, artists, albums, genres, and employees.

**Source:** https://github.com/lerocha/chinook-database

---

## 🎯 Business Questions

### Sales Analysis

1. Which countries bring in the most revenue?
2. Who are the top-spending customers?
3. What is the monthly sales trend?
4. Which employees have the highest sales?

### Marketing Analysis

5. Which tracks and artists sell the most?
6. Which genres perform best, and does performance vary by country?
7. Which customers have not purchased recently?

### HR Analysis

8. Who reports to whom among the employees?

---

## 🧹 Data Cleaning & Validation

The Chinook database is already structured and relational, so basic data validation and cleaning checks were performed.

The following checks were considered:

- Checked important columns for missing values
- Checked for duplicate IDs
- Checked invoice totals for invalid negative values
- Checked invoice-line quantities for invalid values
- Checked relationships between related tables
- Checked dates and text fields for consistency
- Kept meaningful `NULL` values where they represent valid information

For example, an employee with no manager can have a `NULL` value in the `ReportsTo` column.

---
