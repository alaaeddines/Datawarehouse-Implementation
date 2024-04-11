# Adventure Works Sales Data Warehouse

This project implements a data warehouse for the sales department of Adventure Works. The data warehouse is designed to store and analyze sales data from multiple sources, including reseller sales and internet sales. The data warehouse will provide the sales department with more visibility into their sales performance and help them make better decisions.

## Technical Specifications

__Data Warehouse Design__: Dimensional

__ETL Tools__: Microsoft SSIS

__Database Software__: Microsoft SQL Server

__OLAP Cubes__: Microsoft SSAS

__Reporting__: Microsoft Power BI

## Project Stages

__Design__: In the design stage, we defined the fact and dimension tables for the data warehouse.

__Implementation__: In the implementation stage, we used Microsoft tools to create the data warehouse:
* __SSMS__: We used SSMS to create the staging area and the data warehouse.
* __SSIS__: We used SSIS to extract data from the source systems to the staging area and then to the data warehouse.
* __SSAS__: We used SSAS to create OLAP cubes for data analysis.
* __Power BI__: We used Power BI to create reports for the sales department.
* 
## Design of the Data warehouse Schema
![](https://user-images.githubusercontent.com/76821291/195586553-7337402e-2bbb-4bc3-9aef-c4d3aacdd7bd.PNG)

This star schema might be used for data analysis:

* A sales analyst could look at sales trends over time (using the DimDate table) to see if there are any seasonal patterns.
* The analyst could also compare sales by product category (using the DimProduct table) to see which products are selling the best.
* They could also segment customers by demographics (using the DimCustomer table) to see which customer groups are most profitable.
![se3](https://user-images.githubusercontent.com/76821291/195586561-4eda7cae-b1f8-426e-b9e2-81fc3ed8df66.PNG)

This star schema might be used for data analysis:

* A sales manager could analyze sales trends over time (using the DimDate table) to identify seasonal buying patterns.
* They could compare sales performance across different sales territories (using the DimSales Territory table) to see which territories are performing well.
* The manager could also analyze sales by product category (using the DimProduct table) to identify top-selling products.
* They could investigate sales performance by individual employees (using the DimEmployee table) to assess their contributions.
* Analysing sales by reseller (using the DimReseller table) could help identify high performing resellers or regions

## Reporting using Power BI
![Generated Reports](https://user-images.githubusercontent.com/76821291/195586122-9243a2d4-505e-46b3-bf52-1ea53f3189b7.PNG)

