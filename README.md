# Online-Retail-Store-RFM-Cohort-Analysis

## Problem Statement
We have to perform cohort and RFM analysis to understand the value derived from different customer segments. Further, we will divide customers in different clusters based on the analysis by using K-means algorithm.

## Dataset Description
This is a transnational data set which contains all the transactions that occurred between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique and all-occasion gifts.

### Variables	Description
- **InvoiceNo**	Invoice number. Nominal, a six digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation
- **StockCode**	Product (item) code. Nominal, a five digit integral number uniquely assigned to each distinct product
- **Description**	Product (item) name. Nominal
- **Quantity**	The quantities of each product (item) per transaction. Numeric
- **InvoiceDate**	Invoice Date and time. Numeric, the day and time when each transaction was generated
- **UnitPrice**	Unit price. Numeric, product price per unit in sterling
- **CustomerID**	Customer number. Nominal, a six digit integral number uniquely assigned to each customer
- **Country**	Country name. Nominal, the name of the country where each customer resides
