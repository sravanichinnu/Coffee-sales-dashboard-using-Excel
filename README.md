# Coffee sales dashboard using Excel
This dashboard showcases a comprehensive sales dashboard created in Excel to analyze and visualize coffee sales performance. The dashbaord provides insights into sales across regions and products, with key metrics including **Total sales**, **growth trends**, and **top5 customers**.

## Features
- **Dynamic Data Integration**: Consolidates data from multiple source worksheets into a single "main sheet".
- **Advanced Formulas**: Utilized 'Excel's powerful XLOOKUP and INDEX-MATCH functions for data retrieval.
- **Interactive Visualizations**: Combined pivot tables and slicers for customizable insights.

## Data Ingestion:
### Source Dtaa
- Extarcted and consolidated data from multiple source worksheets into a central **main sheet**.
- Ensured that all relevant information is dynamiclaly updated and integrated.

### Key steps
1. **Identify Unique keys**:
   - 'CustomerId' for customer data.
   - 'ProductId' for coffee products data.
2. **Formula Implementation**:
   - Used **XLOOKUP** to retrieve customer data based on 'CustomerId'.
   - Used **Index-MATCH** to fetch product details based on 'ProductId'.

## Data Processing and Transformation
To prepare the data for analysis, the following transformations were applied:
1. Standardized the formar of 'Order Date' to a common format across all regions.
2. Added the unit 'kg' to the 'Size' column values.
3. Added the currency units to 'Unit Price' and 'Sales' columns.
4. Expanded product details using **IF** formulas:
   - Added a **Coffee Type Name** column based on abbreviations.
   - Added a **Roast Type Name** column based on abbreviations.

## Data Visualization
- **Pivot Tables**: Created a sumamrize data and provide actionable insights.
- **Interactive Dashbaord**: Includes:
  - Bar and line charts to visualize total sales over time, and growth trends.
  - Filter slicers for drill-down analysis by region, roast type, and customer.
  - A summary of top 5 customers and their contribution to sales. 
