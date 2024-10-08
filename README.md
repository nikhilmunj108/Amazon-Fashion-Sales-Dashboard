# Amazon Fashion Sales Dashboard – Power BI

This repository contains a Power BI project that visualizes sales and performance data for the Amazon Fashion category. The dashboard is designed to help analyze overall sales, seller activity, and individual product performance across various cities and states. It was led by Shailaja Mishra, Grow Data Skills.

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
  
### DAX Measures:
- **All_Overall_Sales**: Ensures that the category filter does not impact the KPI card showing overall sales.
```DAX
All_Overall_Sales = CALCULATE([Filter Sale], ALL('amazon-fashion - YT'[Category]))
