# Sales_Analysis
![image](https://github.com/user-attachments/assets/c6649a98-e4a0-4760-b6ce-ae86ff7e89f5)


# Sales Analysis Dashboard

# Objective:
The goal of this Power BI project is to create a dynamic and interactive sales dashboard that helps in analyzing sales, profit, and quantity across different products, regions, and time periods. The project also demonstrates strong data modeling practices using star schema, relationships, and DAX.

# Key Features & Concepts Covered:
1. Loading Data to Power BI Desktop
   
Data was imported from multiple sources (e.g., Excel or CSV files) into Power BI Desktop. These included transactional sales data and master data for products, dates, and regions.

2. Data Profiling and Data Transformations
   
Data cleaning and transformation steps were performed using Power Query Editor. This included:

Removing duplicates and null values

Splitting and merging columns

Changing data types

Formatting and creating date fields

3. Primary Key and Foreign Key

Relationships were built between tables using:

Primary Keys (e.g., ProductID, Date, CustomerID in dimension tables)

Foreign Keys in the Fact table

4. Cardinality

Correct cardinality (One-to-Many, Many-to-One) was applied between fact and dimension tables to ensure proper filtering and performance in the data model.

5. Star Schema

The data model was structured using a Star Schema, with:

A central Fact Table (Sales transactions)

Surrounding Dimension Tables (Product, Date, Customer, Region, etc.)

6. Data Modelling

Logical relationships between tables were created, and relationships were validated to enable correct aggregation and filtering in visuals. The model also used relationship management techniques like active/inactive relationships.

7. Filters

Slicers and page/report level filters were added to allow users to view the data by:

Region

Product Category

Time Period

Customer Segments

8. Top/Bottom Products by Sales, Profit, and Quantity

Visuals were created using DAX measures to dynamically display:

Top 5 Products by Sales

Bottom 5 Products by Profit

Highest and lowest Quantity Sold by product

9. Sales Trends Over Periods
Line and area charts were used to show trends in:

Monthly and yearly sales

Year-over-year and month-over-month growth

Seasonal performance trends using Time Intelligence functions

10. Changing Behaviours for Dimension Tables
DAX functions like USERELATIONSHIP() and CALCULATE() were used to manage inactive relationships and perform custom time-based analysis (e.g., using alternate date fields).

11. Dimension Tables and Fact Tables
The model clearly separates dimension tables (used for slicing and filtering) and fact tables (used for calculations and aggregations), following best practices for Power BI data modeling.
