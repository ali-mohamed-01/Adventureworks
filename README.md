# Power BI Lab 5

## Overview
Power BI Lab 5 focuses on building insightful reports using the AdventureWorks sample database. This project aims to provide comprehensive insights into company performance, sales operations, and inventory management through well-structured and interactive Power BI dashboards.

## Data Source
The dataset used in this project is sourced from Microsoft's AdventureWorks sample database.

**Source Link:**  
[AdventureWorks Sample Database](https://docs.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver15&tabs=ssms)

**Conductivity Mode:**  
- Import Mode

## Data Model
### Tables Utilized:
The following tables are used to construct the data model:

- `vw_DimProducts` – Contains product-related information.
- `vw_DimSalesPersons` – Contains salesperson details and performance metrics.
- `vw_DimShipMethods` – Includes shipping methods and related attributes.
- `vw_DimStatuses` – Provides order status tracking.
- `vw_DimTerritories` – Covers geographical sales territories.
- `vw_FactOrderDetails` – Captures transactional order data.
- `DimDate` – A calculated DAX table used for date-based analytics.

### Key Measures:
A dedicated DAX table has been created to store the following key performance indicators (KPIs):

- **Orders by Order Date** – Tracks the number of orders based on order dates.
- **Orders by Ship Date** – Monitors order shipment timelines.
- **Orders by Due Date** – Analyzes orders based on due dates.
- **Total SubTotal** – Calculates the aggregated order subtotal.
- **Total Tax** – Computes total tax amount.
- **Total Freight** – Summarizes freight costs.
- **Total Due** – Represents the final amount due per order.

## Project Objectives
This Power BI report aims to deliver the following insights:

1. **Overall Company Performance:**
   - Provide a high-level overview of key business areas.
   - Evaluate sales performance across regions, products, and order trends.

2. **Operations Report:**
   - Analyze sales team performance.
   - Compare individual sales performance with peers.
   - Assess performance over previous months and quarters.

3. **Inventory Report:**
   - Monitor product stock levels.
   - Identify trends in product availability and sales velocity.

## Features and Functionalities
The report incorporates the following advanced Power BI features:

- **Clear and Organized Visuals:**  
  - Ensuring intuitive and meaningful visualizations for easy interpretation.

- **Filter Synchronization:**  
  - Applying filters across multiple pages to maintain consistency in analysis.

- **Cross-page Filtering:**  
  - Enabling filters to persist across different report pages for a seamless user experience.

- **Advanced Interactions:**  
  - Implementation of drill-down and drill-through capabilities for deeper insights.
  - Hierarchical structures to enable multi-level analysis.
  - Tooltips displaying sales values associated with order quantities.

- **Custom Color Theme:**  
  - A professionally designed color scheme exported as a JSON file for consistent branding.

## Implementation Steps
1. **Data Connection:**
   - Connect to the AdventureWorks SQL database in Power BI.

2. **Data Transformation:**
   - Perform necessary data cleaning and transformation using Power Query.

3. **Model Development:**
   - Create relationships, hierarchies, and calculated columns/measures.

4. **Report Design:**
   - Build visually appealing dashboards with intuitive navigation.

5. **Publishing & Sharing:**
   - Deploy reports to Power BI Service for accessibility and collaboration.

## Usage Instructions
1. Download the AdventureWorks database from the link provided above.
2. Open the Power BI report file and ensure the data source is correctly configured.
3. Navigate through the report pages to explore insights.
4. Use filters and drill-through features to analyze data effectively.

## Recommendations
For optimal experience, ensure the following:
- Use the latest version of Power BI Desktop.
- Refresh data periodically to keep reports up-to-date.
- Leverage Power BI Service to access the report across devices.

## License
This project is intended for educational and demonstration purposes only.

## Author
Ali Mohamed Ali
aliabdulwahed2003@gmail.com  
http://www.linkedin.com/in/ali-abdulwahed
