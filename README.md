# Retail-Store-Analysis

## Problem Statement
Data Attached is a typical data of an e-commerce website. Please do the analysis and optimize it for storage area (i.e. storage area is expensive so we want to keep the products which give us the best revenue). Please keep in mind that fast delivery is also critical so we like to help the retailer by predicting the amount of sold product.
There are missing values in the data, please optimize it by doing the analysis.

## Data Dictionary
<li>Invoice No: Integer
<li>StockCode: String
<li>Description: String
<li>Quantity: Integer
<li>InvoiceDate: DateTime
<li>UnitPrice: Float
<li>CustomerID: Integer
<li>Country: String 
  
The data seems to be from a UK retail store as 91% transactions are from UK.


## Business Object
Analyzing past retail store data to help owner with inventory management so that he/she is better prepared for the upcoming year.

## Approach
We were given the invoice timestamp from which we extracted the month and aggregated the data on month level. We calculated total sales of each product in each month.Lastly, we created three separate categories of items as per their sales - (0-1000,100-3000,>3000)GBP. These ranges can vary as per the retail owner.
We also generated an interactive plot on tableau through which retail owner can easily see which are top priority items for each month.

## Tools Used
![alt text](https://github.com/sahil0094/Retail-Store-Analysis/blob/master/tools.jpg?raw=true)
