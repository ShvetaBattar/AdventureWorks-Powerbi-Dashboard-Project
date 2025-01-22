🤞GitHub project that outlines the details of your Power BI AdventureWorks project:
## AdventureWorks Power BI Dashboard Project
Power BI dashboard created to analyze and visualize sales performance data from the AdventureWorks dataset, spanning the years 2019 to 2022. The project used
a variety of data modeling techniques, DAX calculations, and visualizations to provide insights into sales, margins, and geographical performance across continents.

# Key highlights of the dashboard include:
1.Sales Performance (Line Chart)
2.Total Sales by Continent (Bar Chart)
3.Total Margin Percentage by Product (Bar Chart)
4.Sales Map

## Data Model
The data model is built using several tables sourced from the AdventureWorks dataset:
- **Product Table**: Contains details on products such as names, categories, and subcategories.
- **Sales Territory Table**: Includes data on the geographical locations where products are sold (continent, region, country).
- **Product Rollup Table**: Provides hierarchy levels for product categories and subcategories.
- **Customer Table**: Contains information about customers such as their IDs and demographics.
- **Sales Table**: Contains transactional data, including sales amounts and quantities.
- **Order Date Table**: A date table used for time-based analysis.

These tables are connected using relationships to provide a robust and coherent data model for reporting.
## Visualizations
The dashboard contains the following key visualizations:
1. **Sales Performance Line Chart**: - Shows the trend of total sales from 2019 to 2022.
2. **Total Sales by Continent (Bar Chart)**: - Displays total sales broken down by continent: Europe, North America, and Australia.
3. **Total Margin Percentage by Product (Bar Chart)**: - Highlights the margin percentages across various product categories.
4. **Sales Map**:- Visualizes sales performance geographically, with a focus on continent and country-level sales distribution.
5. **Tooltip with Country Sales Information(Pie Chart)**: - Hovering over pie chart displays a tooltip with detailed sales information for specific countries
   within a continent.
## Techniques Used
🤞Power BI techniques to ensure effective data analysis and visualization:
1.**Data Transformation & Cleaning**:Used Power Query to remove duplicates, handle missing values, and perform other data wrangling tasks.
2.**DAX Measures**: Used to create custom calculations like total sales, margin percentages etc.
3.**Calculated Columns**: Created to transform and add new columns to the data model based on business rules.
4.**Date Table**: An essential feature for time-based analysis, which enables users to perform trend analysis by year, quarter, month, and day.
5.**Row-Level Security (RLS)**: Implemented to restrict access to data based on user roles, ensuring data confidentiality for different user groups.
  
## RLS (Row-Level Security)
Row-Level Security (RLS) has been implemented to ensure that different users can only view data relevant to their assigned region. This feature is particularly useful for
organizations with multiple sales territories or regions.
👍**Download the AdventureWorks Dataset** from the official [Microsoft website](https://www.microsoft.com/en-us/download/details.aspx?id=8483).
