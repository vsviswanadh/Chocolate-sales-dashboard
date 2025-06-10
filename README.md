# Chocolate-sales-dashboard
 ![image](https://github.com/user-attachments/assets/872a5de3-a8a2-41c1-9dfd-ee15eb12fe49)

 
# First Tableau Business Dashboard Project

## Overview
This project marks my initial exploration into data visualization with Tableau, created as part of my learning journey in business analytics. The dashboard provides a snapshot of a chocolate products company’s performance in 2022, focusing on sales metrics, geographical sales distribution, and individual salesperson contributions. It aims to transform raw sales data into actionable insights through visual storytelling.

## Dashboard Details
The dashboard is designed to highlight key business metrics and trends, featuring the following components:
- **Business Summary Metrics**:
  - **Total Sales**: ₹6,183,625 (converted from USD to INR for display purposes).
  - **Boxes Shipped**: 177,007 units.
  - **Count of Data Points**: 1,994 records.
- **Sales by Country**:
  - A bar chart visualizing sales amounts across six countries: Australia, UK, India, USA, Canada, and New Zealand.
  - Each country is color-coded for easy identification (e.g., Australia in blue, UK in green, etc.).
- **Sales by Person**:
  - A horizontal bar chart showcasing the top-performing salespersons based on their total sales.
  - Notable performers include Ches Bonnell and Oby Sorrel, who lead in sales contributions.

## Dataset
The data for this project is sourced from the file `sample-data-10mins (1).xlsx`, which contains sales records for a chocolate products company in 2022. The dataset includes the following columns:
- **Sales Person**: Name of the salesperson (e.g., Ches Bonnell, Oby Sorrel).
- **Country**: The country where the sale occurred (Australia, UK, India, USA, Canada, New Zealand).
- **Product**: Type of chocolate product sold (e.g., Peanut Butter Cubes, 85% Dark Bars, Organic Choco Syrup).
- **Date**: Date of the sale, ranging from January to August 2022.
- **Amount**: Sales amount in USD (e.g., $5,320).
- **Boxes Shipped**: Number of boxes shipped per sale (e.g., 180 boxes).

### Dataset Summary
- **Time Period**: January 2022 to August 2022.
- **Total Records**: 1,994 sales entries.
- **Countries Covered**: 6.
- **Products**: Various chocolate products, including 85% Dark Bars, Eclairs, and Manuka Honey Choco.

## Prerequisites
To interact with or recreate this Tableau dashboard, you’ll need:
- **Tableau Desktop** or **Tableau Public** installed on your system.
- The `sample-data-10mins (1).xlsx` dataset file to load the data into Tableau.
- Basic knowledge of Tableau for exploring or modifying the dashboard.

## How to Use
1. **Access the Dashboard**:
   - Open the Tableau workbook (`.twb` or `.twbx` file, not provided here) in Tableau Desktop.
   - Alternatively, view the dashboard on Tableau Public if published (link not provided).
2. **Interact with Visualizations**:
   - **Sales by Country**: Hover over each bar to see the exact sales amount for a specific country.
   - **Sales by Person**: Check the horizontal bars to identify top salespersons and their contributions.
   - Use any available filters (e.g., date, product, or country) to drill down into specific data subsets.
3. **Recreate or Modify the Dashboard**:
   - Import the `sample-data-10mins (1).xlsx` file into Tableau:
     - Go to `Connect` > `Microsoft Excel` > Select the file.
   - Create calculated fields if needed (e.g., converting USD to INR for the total sales display).
   - Drag and drop fields like `Country`, `Amount`, and `Sales Person` to build the visualizations.
   - Customize colors, labels, and formatting to match the original dashboard design.

## Key Insights
- **Geographical Performance**:
  - Australia is the top-performing country in terms of sales, followed closely by the UK and India.
  - New Zealand has the lowest sales among the six countries.
- **Salesperson Contributions**:
  - Ches Bonnell and Oby Sorrel are the top salespersons, each contributing significantly to the total sales.
  - Other notable performers include Madelene Upcott and Brien Boise.
- **Business Metrics**:
  - The company shipped 177,007 boxes across all sales, indicating strong distribution activity.
  - The total sales amount of ₹6,183,625 reflects robust revenue generation over the 8-month period.

## Limitations
- **Time Frame**: The dataset only covers January to August 2022, missing the last four months of the year.
- **Currency Conversion**: The dashboard displays sales in INR (₹), but the original dataset uses USD ($). Conversion rates are not specified in the dataset.
- **Interactivity**: This README context is static; full interactivity (e.g., tooltips, filters) is only available in Tableau.
- **Data Granularity**: The dataset lacks additional metrics like profit margins, costs, or customer demographics, limiting deeper analysis.

## Future Improvements
- **Expand Time Frame**: Include a full year of data to analyze annual trends and seasonality.
- **Add Filters**: Incorporate interactive filters for products, date ranges, and salespersons to enhance user exploration.
- **Deeper Analysis**: Add metrics like profit margins, sales growth rates, or product popularity to provide more comprehensive insights.
- **Visual Enhancements**: Include a trend line or time-series chart to visualize sales patterns over the months.
- **Comparative Analysis**: Add year-over-year comparisons if historical data becomes available.

## Acknowledgments
- A big thanks to the Tableau community for their tutorials and resources, which were instrumental in helping me learn the basics of data visualization.
- The dataset used in this project is a sample and does not represent real-world business data.

## Contact
I’d love to hear your feedback or suggestions! Feel free to connect with me on LinkedIn (add your LinkedIn profile link if desired) or reach out via email (add your email if desired).

*Created on Tuesday, June 10, 2025, at 07:29 PM IST*
