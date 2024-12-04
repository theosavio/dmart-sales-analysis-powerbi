# D-Mart Sales Analysis Project Using Power BI

## Purpose
This project analyzes D-Mart's sales, customer behavior, and inventory data to derive actionable insights and improve operational efficiency.

## Objectives
- Gain insights into sales trends and customer purchasing patterns.
- Identify inventory gaps and optimize stock levels.
- Utilize Power BI to create dynamic dashboards for effective decision-making.

## Data Sources
- **Sales transaction data**
- **Customer feedback surveys**
- **Inventory reports**

Data was exported in **CSV** and **Excel** formats from D-Mart’s database.

## Data Preparation
- Cleaned and transformed data to ensure consistency.
- Removed duplicates, handled missing values, and standardized formats.
- Imported data into Power BI for integration and analysis.

## Data Modeling
- Designed relationships between **Order**, **Customer**, **Location**, and **Product** tables.
- Established one-to-many relationships for seamless data flow.
- Ensured proper key constraints for accurate aggregation and filtering.

## Visualizations Created
- **Gauge Meter**: Displays total discount price.
- **Pie Chart**: Represents order payments based on shipment types.
- **Line Graph**: Tracks inventory levels over time.

## Insights Derived
1. **Sales Performance**:
   - Identified peak sales months.
   - Recognized best-selling product categories.
   - Analyzed year-over-year trends and revenue distribution.
   
2. **Customer Insights**:
   - Derived regional preferences and purchase behaviors.
   - Gained insights into customer demographics.

3. **Operational Metrics**:
   - Highlighted underperforming inventory items.
   - Measured inventory turnover and shipment efficiency.

## Calculated Metrics
- **Selling Price (SP)**: Difference between MRP and Discount Price.
- **Total Profit**: Summed up from the Product table.
- **Total Order Value**: Calculated as Selling Price × Total Order Quantity.

## Challenges Faced
- Handling large datasets with inconsistent formatting and missing values.
- Establishing relationships between multiple tables with complex structures.
- Writing and optimizing DAX queries for accurate calculations and metrics.
- Designing visuals to balance aesthetics and clarity.

## Tools Used
- **Power BI** for data visualization and insights.
- **Microsoft Excel** for data cleaning and initial preparation.

## Future Enhancements
- Automating data updates for real-time dashboards.
- Including predictive analytics to forecast sales trends.
- Expanding the scope to include competitor analysis.

---

### How to Access
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/dmart-sales-analysis-powerbi.git
