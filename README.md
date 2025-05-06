# 📊 Live Connection to Azure SQL Database - Power BI Report

This Power BI report uses **DirectQuery** to pull data from the **AdventureWorksLT SQL Database** hosted on Azure. The report includes key sales data from the **SalesLT.Product** and **SalesLT.SalesOrderDetail** tables, enabling real-time analytics.

## ✅ Tasks Completed

### 📡 Data Connection
- **Connected to the AdventureWorksLT SQL Database** using **DirectQuery**.
- Loaded the following tables:
  - **SalesLT.Product**
  - **SalesLT.SalesOrderDetail**

### 📊 Visualizations & Interactions
- Created a **Card Visualization** displaying sales data.
- Added **OrderQty** field to the chart.
- Created a **Slicer** with the **SellStartDate** field to filter data dynamically.
- Added a **Card Visual** to display **LineTotal** field.

### 📁 File
- `AdventureWorks_azure_report.pbix`: Power BI report file connected to Azure SQL Database

## 💻 How to Use
1. Open the **Power BI report** in **Power BI Desktop**.
2. Use the **Slicer** to filter data based on **SellStartDate**.
3. Interact with the **Card Visuals** to explore the **Order Quantity** and **Line Total** metrics.
