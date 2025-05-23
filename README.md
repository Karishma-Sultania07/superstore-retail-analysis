# Retail Performance Overview Dashboard
This Tableau dashboard provides an interactive analysis of retail sales and profitability using superstore dataset. It helps uncover patterns across regions, categories, and time to support better business decisions.


## Objective
To visualize key retail metrics and enable users to interactively explore sales, profit trends, and customer segments, with filtering capabilities for deeper insights.


## Dataset Details
- **Source**: [Kaggle – Superstore Dataset Link](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final/data)
- **Format**: CSV  
- **Contents**: Orders, sales, profit, product categories, regions, customer segments, and time-based data  
- After downloading, renamed the file to: `Superstore.csv`


## Tools Used
- **Tableau Public Desktop** – for designing and building the dashboard  
- **Tableau Public Online** – for publishing and sharing the dashboard online  
- **GitHub** – for version control and documentation

## Dashboard Structure

### Top Metrics Displayed
- Total Sales  
- Total Profit  
- Profit Margin  
- Total Orders

### Visual Components
1. **Sales & Profit Over Time** – line chart 
2. **Sub-Category Breakdown** – horizontal bar chart 
3. **Sales by State** – map view
4. **Segment-wise Sales** – treemap chart

*Hover over any chart to get tooltip*


## Interactivity & Filters
All charts (excluding the time trend) can be clicked to filter other visuals on the dashboard.

To access more filtering options, click the filter icon:

<p align="left">
  <img src="Icons/filter-icon.png" alt="Filter Icon" width="40"/>
</p>

### Filter Panel Contents:
- Top N States by Sales  
- Top N Sub-Categories by Profit  
- Region Selector  
- Product Category Filter  
- Year Selector


## Dashboard Snapshots

### Filter Panel Hidden  
![Filter Closed](Dashboard-Screenshots/Dashboard%20(Filter%20Closed).png)


### Filter Panel Open  
![Filter Open](Dashboard-Screenshots/Dashboard%20(Filter%20Open).png)


## Key Insights
*Dynamic filters allow users to generate their own insights.*
### Depending on selected filters and chart interactions, the dashboard can help answer questions like:
- How does sales and profit vary across years?
- What sub-categories are underperforming?
- Which states contribute the most to sales?
- Which customer segments are most valuable?


## Repository Contents
- **README.md** → Project documentation
- **Superstore.csv** → dataset file
- **Icons/** → filter icon & Sales icon
- **Superstore-Dashboard.twb** → Tableau workbook
- **Dashboard-Screenshots/** → Dashboard images


## View Dashboard Online
- 🔗 **[Click here](https://public.tableau.com/views/Superstore-Dashboard_17479456534070/RetailDashboard?:language=en-US&:sid=02B731CF11CF494C9652C2D7D12AEEEE-0:0&:redirect=auth&:display_count=n&:origin=viz_share_link)** to view Dashboard on Tableau public online.  

**Note**: Designed for desktop view – best at **1200x800** resolution
