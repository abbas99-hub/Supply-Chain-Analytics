# Supply-Chain-Analytics
![logistics-supply-chain-01](https://github.com/abbas99-hub/Supply-Chain-Analytics/assets/60792939/460d9bdc-a266-41e1-9f10-922871aa5a6a)

# Overview
This data analytics project focuses on analyzing and visualizing the supply chain data of a fashion and makeup product company. The dataset used in this project contains various features related to the supply chain process, including product information, sales, revenue, customer demographics, stock levels, lead times, shipping details, supplier information, and more.

The project workflow includes three main stages: Extract, Transform, and Load (ETL) the data using Python, loading the transformed data into Snowflake, and finally creating a dashboard in Power BI for data visualization.

# Dataset Overview
The dataset comprises the following features related to the fashion and makeup product supply chain:

* Product Type: The category of the product (e.g., clothing, accessories, makeup).
* SKU: Stock Keeping Unit, a unique identifier for each product.
* Price: The price of the product.
* Availability: The current availability status of the product.
* Number of Products Sold: The number of products sold for a given period.
* Revenue Generated: The total revenue generated from product sales.
* Customer Demographics: Information about the customers, such as age, gender, location, etc.
* Stock Levels: The quantity of each product available in the inventory.
* Lead Times: Time taken for an order to be fulfilled from the supplier's end to the customer's end.
* Order Quantities: The number of products ordered in each transaction.
* Shipping Times: Time taken for shipping products to customers.
* Shipping Carriers: The company responsible for shipping the products.
* Shipping Costs: The cost incurred for shipping each product.
* Supplier Name: The name of the supplier providing the products.
* Location: Location of the supplier.
* Production Volumes: The volume of products manufactured.
* Manufacturing Lead Time: Time taken for the manufacturing process.
* Manufacturing Costs: The cost incurred during the manufacturing process.
* Inspection Results: The results of quality inspection for products.
* Defect Rates: The percentage of defective products.
* Transportation Modes: The modes of transportation used to deliver products.
* Routes: The transportation routes taken for delivery.
* Costs: Various costs associated with the supply chain process.

## Project Steps
###  Step 1: Extract, Transform, and Load (ETL)

* Data Extraction: The dataset will be sourced from a specific location or file, such as a CSV or Excel file.

* Data Cleaning and Transformation: Python will be utilized to clean the data and handle missing values. Data transformation will be performed to make it suitable for analysis.

* Data Integration: Data from different sources or files will be integrated into a single cohesive dataset for further analysis.

* Data Loading into Snowflake: The transformed and integrated dataset will be loaded into the Snowflake data warehouse for efficient storage and processing.

### Step 2: Data Visualization with Power BI
* Data Connection: Power BI will connect to the Snowflake data warehouse to access the transformed dataset.

* Dashboard Creation: A comprehensive dashboard will be created in Power BI, showcasing various supply chain metrics and KPIs. The dashboard will include interactive visualizations like charts, graphs, tables, and maps.

* Data Insights: The Power BI dashboard will allow users to gain valuable insights into the supply chain process, identify trends, and make data-driven decisions to optimize operations.

## Project Structure
The project repository will have the following structure:

- |-- README.md
- |-- data/
- |-- processed/
- |   |-- processed_data.csv
- |-- raw/
- |   |--supply_chain_data.xlsx
- |-- src/
- |   |-- ETL.py
- |   |-- snowflake_utils.py
- |-- power_bi/
- |   |-- supply_chain_dashboard.pbix

## Getting Started
* Clone the repository to your local machine.

* Ensure you have Python and the required libraries installed.

* Run the ETL script (ETL_script.py) to perform the data extraction, transformation, and loading into Snowflake.

* Connect Power BI to Snowflake using the provided connection credentials (snowflake_connection_credentials.json).

* Open the Power BI file (supply_chain_dashboard.pbix) to explore the supply chain dashboard.

## Conclusion
This data analytics project demonstrates how ETL can be used to process and load supply chain data into Snowflake, followed by creating an interactive and informative dashboard using Power BI. The dashboard will empower users to analyze the supply chain metrics effectively and make informed decisions to enhance the overall efficiency of the supply chain process.
