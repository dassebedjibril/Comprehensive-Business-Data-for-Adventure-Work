# AdventureWorks Comprehensive Business Data Analysis


## Overview


This Power BI project aims to transform raw data into actionable insights through dynamic reports and dashboards. This assists the management team in monitoring Key Performance Indicators (KPIs), comparing regional performance, analyzing product-level trends, and identifying high-value customers.

![Image](https://github.com/dassebedjibril/Comprehensive-Business-Data-for-Adventure-Work/assets/56389559/4bf27f2f-3fa0-4a3f-9324-09eee39754fd)


### Dashboard Access

View the interactive dashboard here: **AdventureWorks Business Dashboard** ( https://drive.google.com/file/d/1rlK1-yutVG6LEBMsN0U3ARL0oKeBahSr/view?usp=sharing)


## Project Workflow

The project was executed following a structured workflow, utilizing various data sets:





### Step 1: Data Connection and Preparation

#### Objective: 
Efficiently connect to and prepare the data for analysis.

#### Data Files:
- Calendar Lookup
- Customer Lookup
- Territory Lookup
- Product Categories Lookup
- Product Subcategories Lookup
- Product Lookup

#### Activities:
- Use Power Query for connecting to the above data sources.
- Apply data profiling tools to assess data quality and structure.
- Perform transformations to clean and structure data effectively.





### Step 2: Data Modeling

#### Objective: 
Build a robust data model to support complex analytical queries.

#### Activities:
Design relational data models emphasizing normalization and efficient filter flow.
Establish relationships with proper cardinality using lookup tables.
Create a star schema centered around Sales Data as fact tables.





### Step 3: DAX Calculations

#### Objective: 
Develop calculated columns and measures to provide in-depth and dynamic analysis capabilities.


#### Activities:
- #### Add Calculated Columns: 
Enhance the data model by adding calculated columns that support further analysis, such as Full Name *(Customer Detail)* for combining first and last names.



- #### Develop Measures for Real-Time Analytics:
#### Rolling Calculations: 
Compute rolling totals to capture trends over specific periods, such as `10-days Rolling Revenue` and `90-day Rolling Profit`.

#### Sales Analysis: 
Measures like `Bike Sales`, `Bulk Orders`, and `Total Orders (Customer Detail)` offer insights into different aspects of sales performance.

#### Customer Analytics: 
Track `Total Customers`, `Average Revenue per Customer`, and analyze specific metrics like `Total Orders (Customer Detail)`.

#### Profitability and Cost Measures: 
Determine financial health through `Total profit`, `Total Cost`, `Profit Target`, and `Profit Target Gap`.

#### Return Metrics: 
Analyze return rates and quantities with `Bike Return Rate`, `Quantity returned`, `Total returns`, and `Return Rate`.



- #### Implement Advanced DAX Formulas and Functions:

#### Target vs. Performance: 
Calculate gaps between targets and actuals with measures such as `Order Target Gap`, `Profit Target Gap`, and `Revenue Target Gap`.

#### Historical Comparisons: 
Utilize measures like `Previous Months Orders`, `Previous Months Profit`, `Previous Months Returns`, and `Previous Months Revenue` to compare current performance against historical data.

#### Year-To-Date and Aggregate Measures: 
Analyze year-to-date performance with `YTD Revenue` and aggregate order details with `All Orders`, `Total Orders`.





### Step 4: Data Visualization and Dashboard Creation

#### Objective: 
Design interactive visuals and dashboards that effectively simplify and convey complex data insights.

#### Activities:

- **Develop Comprehensive Visuals**:
#### Executive Dashboard: 

Assemble high-level KPIs and metrics in a consolidated view to offer executives a quick snapshot of overall business health.

#### Geographical Insights: 
Use the `Map` page to visualize data geographically, highlighting regional sales performance, customer distribution, and territory coverage.

#### Product and Customer Insights:
*`Product Details:`* Provide deep dives into product performance, inventory levels, and profitability by category and subcategory.

*`Customer Detail:`* Offer insights into customer behavior, segmentation, and value, enhancing targeted marketing strategies.


- **Advanced Analysis Tools**:
#### Q & A: 
Natural language querying enables users to ask questions directly and receive insights without traditional report navigation.

#### Decomposition Tree: 
Utilize this tool on the Décomposition Tree page to break down data dynamically, exploring different dimensions and discovering root causes of performance metrics.
#### Key Influencers: 
Analyze the Key influencers page to identify which factors most significantly impact KPIs, aiding in predictive analysis and strategic planning.



-  **Customize Visual Formats and Interactivity**:

#### Enhance User Experience: 
Tailor chart and visual formats to enhance readability and user engagement. Manage the interactions between report elements to create a coherent narrative across pages.

#### Dynamic Navigation: 
Employ filters and bookmarks to navigate through the data dynamically, enabling users to customize views and drill down into specific areas of interest.






### Step 5: Performance Optimization

#### Objective: 
Optimize the performance of Power BI reports and dashboards.

#### Activities:
Employ optimization techniques to enhance report responsiveness.
Optimize DAX queries and review report configurations for efficiency.




### Data Files Specifics

#### Annual Sales Data:
Sales Data 2020
Sales Data 2021
Sales Data 2022

#### Returns Data:
Analyzed to integrate customer satisfaction and product quality insights into the reports.


## Conclusion
This Power BI project demonstrates the detailed process of converting extensive raw data into meaningful insights that facilitate strategic decision-making within AdventureWorks. The dashboards serve as crucial tools for ongoing business assessment and strategy development.

