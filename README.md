# Exploring Customer Behaviour Through SQL

## Objective
The *Exploring Customer Behaviour Through SQL* project focuses on analyzing customer data from an online retail database to uncover insights into sales trends, user activity, and membership patterns.  
The goal is to understand customer behavior, identify top-selling products, and support business decisions related to loyalty programs and personalized marketing strategies.

---

## Introduction
As a data analyst, one of the most intriguing aspects of analysis is uncovering insights about customer behavior through database exploration.  
In this case study, multiple interconnected tables were analyzed using SQL to gain a deeper understanding of customer activity for a popular online retailer.

### Database Structure
The database consists of **five tables** *Sales, Product, Goldusers_Signup, Users,* and *User_Name* each containing key information used to build a comprehensive view of customer interactions.

- **Sales Table:**  
  Contains transaction details including Sale Date, Product Sold, Price, and User ID.  
  → Helped identify top-selling products and most active customers.

- **Product Table:**  
  Includes Product ID, Product Name, and Price.  
  → Enabled analysis of product pricing and performance.

- **Goldusers_Signup Table:**  
  Tracks customers enrolled in the premium membership program.  
  → Used to identify customer demographics and interest in premium offerings.

- **Users Table:**  
  Contains customer details such as Name and Signup Date.  
  → Helped analyze customer growth and engagement trends.

- **User_Name Table:**  
  Maps UserID with corresponding User Names.  
  → Used as a linking table for joins and relationship building across datasets.

---

## Problem Statement
The client wanted to analyze customer data to answer key business questions, including:
- What are the most popular and frequently purchased products?  
- Who are the most active and high-value customers?  
- How much money has each customer spent?  
- Which customers are likely to join or benefit from the loyalty program?  

By gaining these insights, the company aimed to:
- Enhance customer engagement and retention.  
- Personalize marketing strategies.  
- Optimize loyalty program expansion based on customer behavior.

---

## Approach
The project used **SQL queries** to extract, clean, and analyze data across all tables.  
Key steps included:
1. Data exploration and table joins using common keys (e.g., UserID, ProductID).  
2. Aggregation and grouping to identify trends in sales and customer behavior.  
3. Calculation of total spending, frequency of visits, and membership status.  
4. Creation of query-based datasets for visualization and business review.  

---

## Insights & Outcomes
- Identified **top-selling products** and **most profitable categories**.  
- Recognized **most active and loyal users** based on transaction history.  
- Discovered **customer segments** most likely to enroll in premium programs.  
- Provided actionable insights for **marketing, retention, and sales optimization**.  

---

## Tools & Technologies
- SQL (Structured Query Language)  
- Database: Relational SQL-based system (e.g., MySQL / PostgreSQL)  
- Data Analysis & Reporting  

---

## Deliverables
- SQL Script: `Exploring Customer Behaviour Through-SQL.sql`  
- Project Documentation: `Exploring Customer Behaviour Through-SQL.pdf`

---

## Additional Info
Developed By: **Swetha K**  
LinkedIn: (https://www.linkedin.com/in/swethak2002/)

**Use Case:** Suitable for SQL learners, data analysts, and portfolio demonstration projects involving database analysis and customer insights.
