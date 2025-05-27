# Sales dashboard using Power Bi and Snowflake
<img src="/PowerBI-Log.png" width="50%" /> <img src="/snowflake-log.png" width="30%" />
  

Creating an end-to-end sales analytics model. Loading and transforming it in Snowflake, visualizing KPIs, trends, and product performance in Power BI.
Designed and developed a dynamic sales analytics dashboard using Power BI and Snowflake as the cloud data source. The project showcases key sales KPIs, regional performance, product category insights, and customer segmentation.

## Key Features:

📊 Interactive dashboard with modern visuals and slicers

🔄 Live connection to Snowflake cloud data warehouse

📈 Visuals include: Sales trends, Profit margins, Regional breakdown, Category analysis, and Top 10 products

🧮 DAX measures for KPIs: Total Sales, Profit, Quantity, and Profit Margin (%)

🧩 Segment filters for Region, Category and Segment

🎨 Light theme layout for clarity and professional appearance

## Skills Demonstrated:

Data modeling and transformation

DAX calculations

Power BI visual design and storytelling

Integration with Snowflake (cloud-based data platform)
![Dashboard](/Sales_analysis.png)
## To view the project, you can go to the following link: [Power BI](https://app.powerbi.com/view?r=eyJrIjoiMDA3MTUyOTctZmViYi00NTBmLTliNjMtODIzZmM5ZGEzNzFlIiwidCI6IjAzNjhiOGIxLThjZWEtNDMwYi1hNzMwLWI5MTZlNjA2MWY1OSIsImMiOjZ9)


# Snowflake

Snowflake is a cloud-based data platform designed to store, process, and analyze large volumes of data in a scalable and efficient way. Unlike traditional databases, Snowflake is built entirely for the cloud and is offered as a Software-as-a-Service (SaaS), removing the need for hardware or infrastructure management.

## Key features of Snowflake:

Separation of storage and compute: Enables independent scaling of resources for better performance and cost optimization.

Multi-cloud support: Operates on AWS, Microsoft Azure, and Google Cloud Platform.

Shared-data architecture: Multiple users can access the same data simultaneously without performance degradation.

Support for structured and semi-structured data: Handles formats like JSON, Avro, Parquet, and XML without requiring prior transformation.

Secure data sharing and collaboration: Allows data to be shared across Snowflake accounts without physically moving it.

Minimal maintenance: No need for index management, partitioning, or manual performance tuning.

## Common use cases:

Business intelligence (BI) and data analytics

Real-time data integration

Data science and machine learning

Data warehousing


## POWER BI
Power BI is a data analysis and visualization tool developed by Microsoft that enables users to transform raw data into clear, interactive, and insightful visual reports. It helps businesses make data-driven decisions by creating dashboards, reports, and visual analytics.

## Key features of Power BI:

Connectivity to multiple data sources: It can connect to databases, Excel files, cloud services (such as Google Analytics, Azure, Salesforce), and many other sources.

Data transformation and modeling: Through Power Query, users can clean, combine, and shape data without writing complex code.

Interactive visualizations: Offers a wide variety of customizable charts, maps, tables, and visuals.

DAX language: Uses DAX (Data Analysis Expressions) for creating advanced calculations, measures, and KPIs.

Publishing and collaboration: Reports can be published to the Power BI web service, shared with others, or embedded into apps like Teams or SharePoint.

Scheduled data refresh: Supports automatic data updates to ensure reports always reflect the latest data.

## Common use cases:

Creating executive dashboards to track key performance indicators (KPIs)

Analyzing sales, finance, marketing, or HR data

Real-time data visualization

Automating business reporting processes


## NOTES: 
Latest Versions – Power BI Desktop vs. Snowflake (as of May 26, 2025)

| Feature Area                   | **Power BI Desktop**                                                                                                           | **Snowflake**                                                                                                    |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------- |
| **Latest Version**             | 2.142.1277.0 (May 6, 2025)                                                                                                     | Version 9.11 (April 28 – May 2, 2025)                                                                            |
| **AI Features**                | - Copilot available on iPad & Android tablets<br>- Transparent Copilot explanations<br>- New "Explore" AI visualization tool   | - Debugging support for Native Apps<br>- Enhanced Snowpark Python support<br>- Async updates for failover groups |
| **Data Integration**           | - Improved Snowflake connector<br>- New support for Vertica DB (ODBC)<br>- OneLake catalog now in Microsoft Teams              | - General availability of Apache Iceberg™ tables in China<br>- Improved external table and catalog sync          |
| **Modeling & Performance**     | - Direct Lake mode semantic models with better performance<br>- Version history for semantic models                            | - Support for file writing in UDFs/UDTFs<br>- Variable binding in SQL `SHOW` commands                            |
| **Visualizations**             | - New custom visuals (e.g., Heatmap by Powerviz, accoMASTERDATA)<br>- Conditional formatting for visual calculations (preview) | N/A                                                                                                              |
| **Platform Changes**           | - 32-bit version support ends June 30, 2025                                                                                    | - Python 3.8 support removed                                                                                     |
| **Publishing & Collaboration** | - Enhanced semantic model monitoring<br>- Improved dashboard history tracking                                                  | - Enhanced replication features<br>- Greater outbound endpoint access in procedures/functions                    |
| **Business Impact**            | N/A                                                                                                                            | - Raised FY26 product revenue forecast to \$4.325B<br>- Q1 2025 product revenue: \$996.8M (above expectations)   |




