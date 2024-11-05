# LITA_CLASS_DOCUMENTATION
---
## Project Title: Sales data Analysis
---
## Project overview:
---
This project is aimed at exploring the sales performance of a certain region or geaograpical area over a specific period of time. It helps to summarize these set of data, making it readable and interpretable. From these analysed set of data, we are able to draw meaningful conclusions and identify trends in sales data.

## Data Sources:
---
The primary source of data used here is an open source data tht can easily be downloaded in an online such as Data.gov, Kaggle, as well as other data source.

## Tools used:
---
- Microsoft excel [Download Here](https://www.microsoft.com)
1. For Data Cleaning
2. For Analysis
3. For Data Visualization

- Sql- Structured Query language for Querying of Data

- Github for Portfolio Building

- Power BI(Business Intelligence)- For Data visualization


## Data Cleaning and Formatting
---
This is the first phase of data analysis, and it involves:
1. Importing data
2. Data inspection
3. Transform data
4. Data formatting.
5. Validation of data etc.

## Explorative Data Analysis 

This involves exploring the given dataset to answer some questions about the data such as;

- What is the average subscription duration and the most popular subscription patterns?
- What is the summary of total sales by product. region and month?
- What is the average sales per product and total revenue per region?

## Data Analysis
---
This is the process of extracting insights and crucial information from a set of data, it helps to summarize the data and also interprete results;

```SQL

Select * from SalesData$

select [total sales], product from [dbo].[SalesData$]

select product, sum([total sales]) AS TOTALSALES FROM [dbo].[SalesData$]

GROUP BY Product

SELECT Region, count([Customer Id]) AS NUMBEROFSALES FROM [dbo].[SalesData$]

GROUP BY Region

select sum([total sales]) AS TOTALSALES, Product from [dbo].[SalesData$]

GROUP BY Product

ORDER BY 1 DESC

SELECT SUM ([total sales]) AS TOTALMONTHLYSALES FROM [dbo].[SalesData$]

WHERE EXTRACT(YEAR FROM OrderDate)=EXTRACT(YEAR FROM CURRENTDATE)

GROUP BY EXTRACT(YEAR FROM OrderDate)

EXTRACT(MONTH FROM OrderDate)

ORDER BY YEAR SALES, MONTH SALES

SELECT SUM([total sales]) AS TOTALMONTHSALES FROM [dbo].[SalesData$]

WHERE DATEPART(YEAR, OrderDate)=DATEPART(2023, GETDATE(04/11/2024)

SELECT TOP 5 [Customer Id], [total sales] FROM [dbo].[SalesData$]

order by [total sales] DESC

SELECT region, [total sales], ([total sales]/select sum([total sales]) from [dbo].[SalesData$])*100 as percentage of total sales from [dbo].[SalesData$]
group by region, [total sales]
```


## Data Visualization
---
![P1](https://github.com/user-attachments/assets/598d805e-cafd-4adb-bd4c-96403b1f5b2d)

![P2](https://github.com/user-attachments/assets/cdb5c184-45b9-49d9-93e4-649ddcea2f1e)

![P3](https://github.com/user-attachments/assets/fcb501c7-5924-441f-a1d6-8f6ca06ac3be)

![P4](https://github.com/user-attachments/assets/c7d6ee5f-45fa-4f41-ac0d-c6dd162916d8)

![P5](https://github.com/user-attachments/assets/afe68eab-4633-43c3-9f4f-f5344128243a)

![P6](https://github.com/user-attachments/assets/67bc0609-fa83-42b2-8394-14cb51e2666c)

![C1](https://github.com/user-attachments/assets/33ee2260-51bd-4d7e-ba3e-5bdf0e9bac7b)

![C2](https://github.com/user-attachments/assets/2d8f74e5-7033-4fa7-a404-eca723048895)

![C3](https://github.com/user-attachments/assets/0080a9b2-b261-4734-aa2e-0ed354213701)

![C4](https://github.com/user-attachments/assets/5400e88e-d71b-4c0a-88d5-6be9980d2e71)

![C5](https://github.com/user-attachments/assets/f499581d-4c40-414a-9eea-787ae8fe48bd)






