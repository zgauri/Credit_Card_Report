# Credit Card Financial Performance Dashboard

## Project Overview
This project is focused on developing a sophisticated Credit Card Financial Performance Dashboard that delivers weekly, real-time insights into crucial metrics and trends related to credit card operations. The primary goal of this dashboard is to empower stakeholders with the tools to effectively monitor, analyze, and make data-driven decisions to enhance credit card services.

## Key Features
- **Dynamic and Interactive Dashboard:** Developed using a combination of Power BI, Excel, DAX, Power Query, SQL, and Python, this dashboard provides an interactive user experience with the ability to drill down into specific metrics.
- **Real-Time Data Integration:** The dashboard integrates with live data sources, ensuring that all visualizations and reports reflect the most current information available.
- **Comprehensive Performance Metrics:** Tracks a wide range of performance indicators, including transaction volumes, delinquency rates, customer spending patterns, and credit utilization, offering a holistic view of credit card operations.
- **Customizable Views:** Users can tailor the dashboard to focus on specific metrics or time periods, enabling more targeted analysis.
- **Automated Data Processing:** Python scripts automate the process of data cleaning, transformation, and analysis, reducing manual effort and ensuring data accuracy.

## Tools and Technologies Utilized
- **Power BI:** Core tool for building interactive reports and dashboards, offering a rich set of visualizations and capabilities for real-time data exploration.
- **Excel:** Used for preliminary data manipulation, exploratory analysis, and as an additional reporting tool for ad-hoc analysis.
- **DAX (Data Analysis Expressions):** Employed for creating sophisticated data models, calculated columns, and custom measures within Power BI.
- **Power Query:** Handles the ETL (Extract, Transform, Load) processes, connecting to various data sources, cleaning data, and shaping it for analysis.
- **SQL:** Utilized for efficient data extraction from relational databases, allowing for complex queries to gather the necessary data.
- **Python:** Supports advanced data processing tasks, such as complex calculations, automation, and integration of external data sources.

## Included Files and Resources
- **cc_add.csv:** Supplementary dataset containing additional credit card transaction details.
- **credit_card.csv:** Primary dataset containing core credit card transaction data.
- **cust_add.csv:** Supplementary dataset with additional customer information.
- **customer.csv:** Main dataset with customer demographics and account information.
- **SQL_Query_Financial_Dashboard_Data.sql:** SQL script containing queries for extracting and preparing data from the database.
- **Credit_Card_Financial_Report.pdf:** Comprehensive report detailing the data analysis, findings, and insights from the dashboard.

## Getting Started Guide

### System Requirements
- **Power BI Desktop:** Ensure the latest version is installed.
- **Python Environment:** Python 3.x installed with necessary libraries such as pandas, numpy, and matplotlib.
- **SQL Database Access:** Ensure access to the SQL database containing the relevant credit card data.
- **Microsoft Excel:** For any pre-processing or additional analysis of the data.

### Installation and Setup
1. **Clone the Repository:**
   ```bash
   git clone <https://github.com/zgauri/Credit_Card_Report>
   ```
2. **Database Configuration:**
   - Access the SQL database and execute the provided SQL script (`SQL_Query_Financial_Dashboard_Data.sql`) to load and prepare the data.
   - Verify the data integrity and ensure all necessary tables are populated.

3. **Install Required Python Packages:**
   ```bash
   pip install pandas numpy matplotlib
   ```
   - Additional packages may be required depending on your specific needs.

4. **Load the Power BI File:**
   - Open Power BI Desktop and load the provided Power BI file.
   - Configure data sources and establish connections to the SQL database.

### How to Use the Dashboard
1. **Data Refresh and Synchronization:**
   - Regularly update the SQL database to ensure the data in Power BI is current.
   - Use Power Query within Power BI to refresh datasets and ensure all visualizations are updated.

2. **Dashboard Interaction:**
   - Navigate through the various tabs and visualizations within the Power BI dashboard.
   - Use filters, slicers, and drill-down features to explore specific data points and trends.

3. **Customization and Extension:**
   - Adjust DAX formulas to create new metrics or modify existing ones according to your analysis requirements.
   - Utilize Python scripts to automate complex data transformations or integrate additional data sources.
   - Update Excel files for any preliminary data analysis or reporting needs.

### Advanced Usage
- **Integrate Additional Data Sources:** Expand the dashboard by connecting to new data sources, such as external APIs or other SQL databases.
- **Automate Data Workflows:** Use Python or SQL to create automated data pipelines that streamline the data preparation process.
- **Enhance Visualization:** Leverage Power BI’s extensive visualization library to add more advanced charts, graphs, and reports that offer deeper insights.
