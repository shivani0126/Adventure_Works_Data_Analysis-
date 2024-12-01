# Data Analysis of Bicycle Manufacturing Company Using Python, SQL and Power BI
 
## Overview

This project goes through the Production and Inventory Analysis of the Microsoft AdventureWorks Database. Adventure Works is a fictional bicycle manufacturing company, this database contains standard transactions data from an Enterprise Resource Planning System. It contains data from the following scenarios of the company: Human Resources, Product Management, Manufacturing, Purchasing, Inventory, Sales, and Admin. The objective of this project is to create an end-to-end sales analytic report based on AdventureWorks database. Which is an online transaction processing (OLAP) database sample based on a fictitious multinational bicycle manufacturing company named AdventureWorks.
This analysis focuses on the Manufacturing and Inventory part of the data. Microsoft Power BI has been used to create an interactive dashboard while pulling data from SQL Server.

## Data Source

[Data Source](https://docs.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver15&tabs=ssms)

## Data Model

Defining an effective data structure in a dashboard is important, incorporating a star schema model gives an efficient design and makes the data refresh faster. The image below shows the tables used in the process:-

<img width="620" alt="DataModel" src="https://github.com/user-attachments/assets/8c01945f-b234-496e-bcb6-c438f12a57e1">



### Tables used in the model: -

- Production Location - Has Production assembly data, 1.e. Parts used to manufacture each product are defined here with an assembly location category
- Production Product - Data related to products, their physical details, price, etc.
- Production ProductCategory - Products and their defined categories
- Production ProductSubcategory - Products and their subcategories
- Production ProductInventory - Inventory data of the produced products
- Production ScrapReason - Waste Data related to manufacturing
- Production WorkOrder - Production transactions and related data
- Production WorkOrderRouting - Production work order scheduling data and details
- Sales SalesOrderDetail - Transactional Sales Data

## Built With

•[Python](https://www.python.org/)
•[Power BI](https://powerbi.microsoft.com/en-us/)
•[SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)

## Analysis

### Main Page

This dashboard analyses manufacturing and inventory operations, the dashboard is made to have an app-like navigational interface. The main page includes leads to three areas namely Production Overview and Inventory Overview and Production Category Analysis. Each then breakdown details and KPIs on their own page afterward.

<img width="1024" alt="Main Page" src="https://github.com/user-attachments/assets/2cf71eb4-6182-4d59-86b0-d3aa7313fe97">

### Production Overview

<img width="1024" alt="Production Overview Page" src="https://github.com/user-attachments/assets/9b9dd220-5850-432b-af68-ffa45b7ecd06">


The dashboard is made according to the fiscal year terms, a custom date table was created using DAX, to automatically generate Fiscal year segregations. An assumption is made that the fiscal year starts on October 1st and ends on September 30th.  

This page gives information about the manufacturing overview of the company, Measures were created in Power BI in order to have custom KPIs. All the charts and KPIs are described below: -

<img width="1024" alt="Production Overview KPI" src="https://github.com/user-attachments/assets/8eb161d9-377f-4795-ad1a-263344a37b35">

### Production Category Analysis

After looking at the overview of the manufacturing department, one can navigate to the Product Category Page for a more detailed analysis. Which will help identify specific issues in the manufacturing system. 

This section consists of 4 charts that show an in-depth analysis of the Production components and help determine specific issues.

<img width="1024" alt="Production Category Analysis" src="https://github.com/user-attachments/assets/0a4bb266-603f-443a-b116-11f8176b09e8">


### Inventory Overview

Another major component of the dashboard is the Inventory overview, although there is no data regarding the distribution supply chain in the database this analysis is done assuming the is one location.

Main Page

The overview includes 3 KPI's, 3 Filters to slice the data, and 2 charts.

<img width="1024" alt="Inventory data overview" src="https://github.com/user-attachments/assets/d59c9b3b-805d-4706-aee5-0b54c56e2c94">


**KPIs**

<img width="1024" alt="Inventory data overview KPI" src="https://github.com/user-attachments/assets/66520321-771e-4705-8049-14a062ddef2f">




