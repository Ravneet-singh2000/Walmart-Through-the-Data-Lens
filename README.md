# Walmart-Through-the-Data-Lens

# Power BI Project: Walmart Dashboard


## Data Sources

* **SQL Server Database:** This serves as the primary source for raw sales data. It encompasses essential information such as:
    * **Sales Amounts:** Total revenue generated from each transaction.
    * **Product Categories:** Classification of products sold (e.g., Electronics, Furniture, Appliances).
    * **Profit Margins:** Profitability levels associated with each product or category.
    * **Transaction Details:** Time-stamped records of sales transactions.

* **Excel Spreadsheet:** This supplementary data source provides additional context and details, including:
    * **Product Information:** Detailed specifications and descriptions for each product.
    * **Delivery Times:** Recorded duration of product delivery to customers.
    * **Regional Data:** Information related to sales locations and customer regions.

## Tools Used

* **SQL Server Management Studio (SSMS):** This powerful tool was instrumental in:
    * **Data Extraction:** Querying and retrieving the necessary sales data from the SQL Server database.
    * **Data Manipulation:** Transforming and cleaning the raw data to ensure accuracy and consistency.

* **Microsoft Excel:** This versatile spreadsheet application played a crucial role in:
    * **Data Wrangling:** Cleaning, transforming, and enriching the data from the Excel spreadsheet.
    * **Data Analysis:** Performing initial data analysis and calculations.

* **Power BI Desktop:** This robust business intelligence tool was the foundation for:
    * **Dashboard Design:** Creating the interactive and visually appealing dashboard.
    * **Data Modeling:** Building the data model that underpins the dashboard's functionality.
    * **Visualization Development:** Designing and implementing the various visualizations (charts, graphs, maps).

## Project Structure

## Dashboard Features

* **Sales Overview:** This section provides a high-level summary of sales performance, including:
    * **Total Sales:** The overall revenue generated across all years.
    * **Total Profit:** The net profit earned across all years.
    * **Total Quantity Sold:** The total number of units sold across all years.
    * **Average Delivery Time:** The average time taken to deliver products to customers.

* **Sales by Category:** A pie chart visually represents the distribution of sales across different product categories, enabling quick identification of top-performing categories.

* **Profit by Product:** A pie chart highlights the profitability of individual products, allowing for easy comparison and identification of high-margin products.

* **Profit by State:** A bar chart illustrates the profit generated from each state, revealing regional variations in profitability and identifying areas for improvement.

* **Loss by State:** A bar chart specifically focuses on states with negative profit margins, enabling a targeted analysis of underperforming regions and potential corrective actions.

* **Average Delivery Time:** A map visualization displays the average delivery time across different regions, providing valuable insights into delivery performance and potential logistical bottlenecks.

## Usage

1. **Data Preparation:**
    * **Restore the Database:** Restore the `SalesData.sql` file to a SQL Server database instance.
    * **Data Cleaning:** Clean and transform the `ProductInfo.xlsx` spreadsheet as necessary to ensure data quality and consistency.

2. **Power BI Report:**
    * **Open the Report:** Open the `SalesAnalysis.pbix` file in Power BI Desktop.
    * **Refresh Data:** Refresh the data connections to the SQL Server database and Excel spreadsheet to ensure the dashboard displays the latest information.
    * **Explore and Interact:** Explore the interactive dashboard visualizations, filter data, and drill down into specific details to gain deeper insights.

## Additional Notes

* **Customization:** This project serves as a foundation for further customization. You can enhance the dashboard with additional features, such as:
    * **Interactive Filters:** Allow users to filter data dynamically based on various criteria.
    * **Drill-Down Capabilities:** Enable users to explore data at different levels of detail.
    * **More Complex Visualizations:** Incorporate advanced visualizations like treemaps, waterfall charts, and scatter plots.

* **Data Source Flexibility:** The data sources can be easily modified to accommodate different data structures and requirements.

* **Continuous Improvement:** The dashboard can be continuously improved and refined based on user feedback and evolving business needs.

**Feel free to reach out via the issue tracker on this repository if you have any questions or suggestions.**

**Author:** Ravneet Singh
**Date:** 2024-12-14
