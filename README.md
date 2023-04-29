<h1 align="center">Northwind-Database-SQL-Project</h1>

**Northwind Database is Excellent ERP Schema based DB where we will perform various SQL Operations to get the required data from the same.** 

Database used from SkilloVilla, accessible to Students only.

### About Project 👨‍💻

- The Northwind database is a database used as the basis for tutorials to teach SQL. The Northwind database contains the sales data for a company called “Northwind Traders,” which imports and exports speciality foods from around the world. The Northwind database is an excellent tutorial schema for a small-business ERP, with customers, orders, inventory, purchasing, suppliers, shipping, employees, and single-entry accounting.
  
- I have used PostgreSQL (pgAdmin) to Load the Database - Perform the Operations like: 
* Data Processing
* Data Analysis
* Extracted Entity Relationship Diagram
  
## Technologies used ⚙️

* <a href="https://www.postgresql.org" target="_blank" rel="noreferrer">PostgreSQL - pgAdmin <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgres" width="32" height="32"/></a>

### Problem Statements:
  
 * According to the products table, which category_ids have more than 500 units_in_stock?
  --> <code>[We used Sum(units_in_stock) and group by Category_ID](#)</code>
 * Create a query where the count of orders placed would be mentioned against every customer_id but only for customers having at least 10 orders.
  --> <code>[We used Having Count(*) >= 10 and group by Customer_ID](#)</code>
 * Company wants to give $5 cashback to every customer on the first order. Identify the order_ids and customer_ids which are eligible for getting the cashback. 
  --> <code>[Used CTE - Common Expression Table having Customer_ID & Order_ID along with the Rank()](#)</code>
 * What is the total quantity sold for product_name = 'chai'.
  --> <code>[Used Join Statement on Product_ID and where clause](#)</code>
  
## Entity Relationship Diagram:
 
  <picture><img align="center" width="1200" src="https://github.com/Pavan-Jadhav/Northwind-Database-SQL-Project/blob/main/Northwind_DB_Model_Diagram.png" alt="ER-diagram_NW"/></picture>
  
## Project Summary:
  
* We used various SQL statements to find out the required information from the database. 
* SQL Queries are not shared here as not allowed here.

## Project References: 🔗

|**Sr.No. 🔢**|**References 👨‍💻**| **Links :link:**|
|------|--------------------|---------------------|
|1| ** ER Diagram for DB ** | [Database](https://github.com/Pavan-Jadhav/Northwind-Database-SQL-Project/blob/main/Northwind_DB_Model_Diagram.png)|
  
## Related Projects:question: 👨‍💻 🛰️

<code>[Govind Sales Annual Report 2022 - Tableau Dashboard](https://github.com/Pavan-Jadhav/Govind-Store-Annual-Report-2022---Tableau-Dashboard)</code> 🗂️

<code>[Big-Billion-Day-Sales-Analysis-2022-With-Python](https://github.com/Pavan-Jadhav/Big-Billion-Day-Sales-Analysis-2022)</code> 📑

<code>[Food Delivery Time Prediction Using LSTM on Python](https://github.com/Pavan-Jadhav/Food_Delivery_Time_Prediction_Using_LSTM_Python)</code> 📊

<code>[Govind Sales Annual Report 2022 - Excel Dashboard](https://github.com/Pavan-Jadhav/Govind-Store-Annual-Report-2022)</code> 🗂️

<code>[UK Road Accidents Tableau Dashboard](https://github.com/Pavan-Jadhav/UK-Road-Accident---Tableau-Dashboard)</code> 📊
   
### Liked my Contributions:question:[Follow Me](https://github.com/Pavan-Jadhav/)

## For any queries/doubts 🔗 👇 

### [Pavan Jadhav](#)
<p align="left"> <a href="https://twitter.com/pavan061994" target="blank"><img src="https://img.shields.io/twitter/follow/pavan061994?logo=twitter&style=for-the-badge" alt="Pavan Jadhav" /></a> </p>

<a href="https://www.linkedin.com/in/pavanjadhav" target="blank"><img align="center" src="https://img.shields.io/badge/-PavanJadhav-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/Pavan-Jadhav/" alt="Pavan-Jadhav" height="20" width="100" /></a>
<a href="https://www.instagram.com/pavan061994" target="blank"><img align="center" src="https://img.shields.io/badge/-@pavan061994-D7008A?style=flat-square&labelColor=D7008A&logo=Instagram&logoColor=white&link=https://www.instagram.com/pavan061994" alt="pavan061994" height="20" width="110" /></a>
<a href="https://github.com/Pavan-Jadhav" target="blank"><img align="center" src="https://img.shields.io/github/followers/Pavan-Jadhav?label=Follow&style=social&link=https://github.com/Pavan-Jadhav/" alt="Pavan-Jadhav" height="20" width="90" /></a>
