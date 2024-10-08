# Amazon Fashion Sales Dashboard – Power BI

This repository contains a Power BI project that visualizes sales and performance data for the Amazon Fashion category. The dashboard is designed to help analyze overall sales, seller activity, and individual product performance across various cities and states.

## Dashboard Features:

### Visualizations:
- **KPI Cards** for total sales and seller counts.
- **Bar Charts** displaying sales by city and state.
- **Line Chart** tracking sales trends over time.
- **Status Filter** to track different stages of seller orders, including pending, shipped, and canceled.
- **Interactive Product View** with images linked to product data and sales.
- **Sales by Date** with drillthrough for detailed product view.

### Power BI Techniques:
- **Split Column by Delimiter**: Used for cleaning data to ensure correct categorization.
- **Replace Values**: Data cleansing to handle missing or incorrect entries.
- **Custom Column**: For calculating seller statuses.
- **Adding Images to Slicer**: Displaying product images alongside data points.
- **Image Area Size Customization**: Adjusting slicer for proper visualization.
- **Page Navigation**: Seamless transitions between Overview, Products, and Product Views.

How to Use:
Download the .pbix file and open it with Power BI Desktop.
Explore the different views and filters in the dashboard to analyze the Amazon Fashion sales data.
Screenshots:
Amazon Fashion Sales Overview

Product Details View

Drillthrough to Individual Product

Key Features:
Dynamic Slicers: Select a particular chart based on slicer filters, such as calendar filtering.
Bookmarks: Navigate through different views of the dashboard using pre-configured bookmarks.
Area Chart as Tool Tip: Hover over a pie chart slice to reveal additional insights via an area chart.
Drillthrough: Click on specific data points to view detailed information on another page.
Advanced DAX Functions: Utilized DAX expressions like CALCULATE, ALL, CUSTOMTABLE, and SELECTEDVALUE.
Learnings:
Power BI Data Cleaning: Techniques like splitting columns, replacing values, and creating custom columns.
Visualization Techniques: Leveraged different chart types and visual interactions for a seamless user experience.
DAX Measures: Created advanced DAX calculations to ensure correct filtering and calculation for metrics like total sales and seller counts.
Credits:
Project developed during the Power BI Bootcamp by Shailja Mishra and Grow Data Skills.
