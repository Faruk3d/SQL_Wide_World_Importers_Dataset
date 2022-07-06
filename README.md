# SQL_Wide_World_Importers_Dataset
* Dataset link : [Download](https://docs.microsoft.com/en-us/sql/samples/wide-world-importers-dw-install-configure?view=sql-server-ver16#download)

### Question 1: 

Using the database WideWorldImporters, write a SQL query which reports the consistency between orders and their attached invoices.
The resultset should report for each (CustomerID, CustomerName)
 a. the total number of orders: TotalNBOrders
 b. the number of invoices converted from an order: TotalNBInvoices
 c. the total value of orders: OrdersTotalValue
 d. the total value of invoices: InvoicesTotalValue
 f. the absolute value of the difference between c - d: AbsoluteValueDifference
 
 The resultset must be sorted by highest values of AbsoluteValueDifference, then by smallest to highest values of TotalNBOrders and CustomerName is that order.
 
 Please note that all values in a & b must be identical by definition of the query, as we are observing orders converted into invoices.
We are looking for potential differences between c & d.
BUT, you must find them consistent as the data is clean in WideWorldImporters.
Resultset enclosed in Q1-Resultset_Corrected.csv 

### Question 3 & 4 ongoing

### Question 2: 
In the database SQLPlayground, write a SQL query selecting all the customers'
data who have purchased all the products AND have bought more than 50 products in total (sum of all purchases).
Resultset enclosed in Q5-Resultset.csv

### Question 5:
In the database SQLPlayground, write a SQL query selecting all the customers'
data who have purchased all the products AND have bought more than 50 products in total (sum of all purchases).
Resultset enclosed in Q5-Resultset.csv
