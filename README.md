Overview:
This project uses Power BI to analyze sales data and segment customers based on their spending patterns. The project involves data extraction, transformation, and analysis through DAX calculations, providing insights into sales performance and customer behavior.

Task 1: Analysis of Project Requirements
In this task, we analyzed project requirements to identify the necessary datasets, transformations, and calculations needed. This laid the foundation for accurate and insightful data analysis.

Task 2: Dataset Collection
The following datasets were gathered to meet analysis requirements:
Sales Orders
Customer Information
Product Details
Each dataset was verified and prepared for import into Power BI.

Task 3: Sales Data Extraction and Transformation
Data Source Identification
Import raw datasets, including Sales Orders, Customer Information, and Product Details, typically in CSV format.
Data Loading with Power Query
In Power BI, go to Home > Get Data and import each dataset using Power Query.
Combining and Merging Datasets
Use Append Queries and Merge Queries in Power Query to combine tables:
Example: Join Sales Orders with Product Category by Product ID to create a unified dataset.
Data Transformation
Apply transformations to clean and structure the data, such as:
Filtering to remove unnecessary rows.
Renaming columns and adjusting data types.
Applying Transformation Logic
Implement additional logic for filtering data and creating meaningful data relationships.
Use Merge and Append Queries as needed to establish relationships between tables (e.g., joining Sales Order with Product Category).
DAX Calculations
Total Sale = [Quantity] * [Price]
Average Order Value = [Total Sales] / [Order Count]

Task 4: Customer Segmentation using DAX Data Transformation
Data Source Import
Import the customer sales dataset, which includes Customer ID, Customer Name, Transaction Dates, Sales Amount, and Product Categories.
Transforming Data
Load the customer transaction data and, if necessary, create new columns in Power Query Editor.
DAX Calculations for Customer Segmentation
This segmentation allows for targeted marketing strategies by identifying high-value customers (e.g., Platinum tier) and creating personalized engagement approaches for each segment.
