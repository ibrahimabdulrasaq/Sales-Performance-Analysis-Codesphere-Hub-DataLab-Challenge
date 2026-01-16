# Sales-Performance-Analysis-Codesphere-Hub-Datalab-Challenge
End-to-end Excel sales analytics project showcasing data cleaning, modeling, and dashboard visualization for business decision-making.

## Project Overview

This project is an Excel Sales Performance Dashboard developed as part of the DataLab Challenge organized by CodeSphere Hub.
The objective was to transform raw sales data into actionable business insights using Excel’s data analysis, modeling, and visualization capabilities.

The dashboard provides a comprehensive view of sales trends, profitability, product performance, regional insights, and store performance to support informed, data-driven decision-making.

This project consists of two dashboards:

Dashboard 1: Sales Perfomance Analysis.
<img width="785" height="425" alt="Dashboard" src="https://github.com/user-attachments/assets/5707a864-3d19-41c4-9d34-53c6bc0e6b65" />

Dashboard 2: Overview (Dashboard + Key Insights + Actionable Recomendations).
<img width="1184" height="432" alt="Dashboard Overview" src="https://github.com/user-attachments/assets/34afeece-9d4c-4e28-98f8-2abe78c40a75" />

My goal was to go beyond simple reporting metrics and deliver actionable insights that support data-driven decision-making.

## Objectives

* Clean and transform raw sales data
* Analyze key business performance metrics
* Build an interactive and intuitive Excel dashboard
* Communicate insights clearly through visual storytelling

## Data Source
The dataset for this project was provided by CodeSphere Hub through their Data Lab community. You can access it here: https://drive.google.com/drive/folders/1jv61iiOIffYNEHbudoBa8ndPzwgTmMHY?usp=sharing

## Tools & Technologies

* Microsoft Excel
* Power Query (data cleaning and transformation)
* Pivot Tables & Pivot Charts
* Power Pivot (data modeling)
* DAX measures
* Wireframing
* Dashboard visualization

## Dashboard Features

* Interactive slicers for time-based filtering
* KPI cards with Month-over-Month (MoM) comparison
* Dynamic charts for trend and performance analysis
* Clean, business-focused dashboard layout

### Power Pivot & Data Model

1. Diagram View (Data Model): I built a data model showing relationships between tables, enabling seamless analysis without flattening the data. This allowed the dashboard to remain flexible, dynamic, and scalable 
while maintaining data integrity.
<img width="1032" height="588" alt="Data Model" src="https://github.com/user-attachments/assets/e87fc25c-cc7c-44dc-be86-209f1ac1f436" />

2. Data View (Sample Tables)
* Fact Table (Sample)
<img width="1014" height="600" alt="Fact Table" src="https://github.com/user-attachments/assets/050d1804-3d05-4bda-802f-e0561536cf88" />

* Customers Table (Sample)
<img width="685" height="599" alt="Customer Table" src="https://github.com/user-attachments/assets/b26848a0-e030-4c7d-ba3d-a3be068b3a34" />

* Products Table (Sample)
<img width="553" height="600" alt="Product Table" src="https://github.com/user-attachments/assets/28d47695-a42c-4dc4-8342-22ead519faa4" />

* Sales Persons Table (Sample)
<img width="564" height="247" alt="Sales Person Table" src="https://github.com/user-attachments/assets/d5bf5889-46c7-46e3-ba7c-e1c2e86ab109" />

* Date Table (Sample)
<img width="538" height="596" alt="Date Table" src="https://github.com/user-attachments/assets/f401d738-d727-413a-9703-d72b80d51dfe" />

3. DAX Measures I Created
<img width="486" height="394" alt="Dax Measures" src="https://github.com/user-attachments/assets/5e72e8de-aa05-4f9f-a18e-891bc16ae281" />

## Key Metrics I Tracked
* Total Sales / Revenue
* Cost of Goods Sold (COGS)
* Profit
* Quantity Sold
* Previous Month Sales
* Previous Month COGS
* Previous Month Profit
* Previous Month Quantity Sold
* Month on Month Sales, COGS, Profit, and Quantity Sold

Table Summary for Key Metrics:

  | Metric            | Current Period | Previous Month (PM) | Month-over-Month (MoM) |
| ----------------- | -------------- | ------------------- | ---------------------- |
| **Total Sales**   | $5.4M          | $5.0M               | ▲ 8.8%                 |
| **COGS**          | $3.1M          | $2.9M               | ▲ 9.1%                 |
| **Profit**        | $2.3M          | $2.1M               | ▲ 9.0%                 |
| **Quantity Sold** | $606.1K        | $556.0K             | ▲ 9.0%                 |

## Key Insights & Findings

**1. Monthly Sales Performance Overview**
* May and July recorded the strongest sales performance
* February, April, June, and December experienced notable declines
* The year ended with a downward trend, suggesting seasonal fatigue or market saturation

**2. Top Products by Sales Volume**

*	Soft Drinks consistently dominated sales, peaking at $1.2M across the full period
*	Water, Sports Drink, and Coffee showed strong and consistent performance
*	Tea and Juice had fluctuating demand, with Tea peaking in July and Juice in March

Recommendations:
* Focus inventory and marketing efforts on Soft Drinks, Water, and Coffee.
* Introduce promotions or bundling strategies for Juice and Tea during slower months.

**3. Regional Performance Highlights**

*	Michigan, Virginia, California, and Texas were consistently top-performing states
*	Washington, Illinois, and Georgia showed strong mid-tier performance
*	Indiana, Wisconsin, and North Carolina recorded lower but stable sales

Recommendation:
* Expand promotional efforts in mid-tier regions and replicate success factors from top-performing states.

**4. Top Performing Stores**

*	Barron-Fleming, Myers-Lopez, Miller, Novak PLC, and Valdez frequently ranked among top performers
*	Lopez and Martinez showed strong performance in specific months

Actionable Insight:
* Use high-performing stores as benchmarks to improve performance across other outlets.

**5. Sales by Week Trends**
*	Week 2 and Week 5 consistently recorded peak sales
*	Week 1 and Week 6 were typically slower

Actionable Recommendation:
* Align promotions, campaigns, and product launches with Weeks 2 and 5 to maximize impact.

## Overall Recommendations
Recommendations

1. Prepare for seasonal dips in Q2 and Q4 through targeted campaigns.
2. Focus on high-performing products, particularly Soft Drinks, Water, and Coffee.
3. Apply insights from top-performing states to improve underperforming regions.
4. Enable high-performing stores to share best practices with others.
5. Leverage weekly sales cycles with targeted promotions and loyalty programs.

## Limitations

This dashboard uses historical sales data, so it may not predict future trends accurately. It does not include detailed customer or transaction-level information, which limits deeper insights. The analysis depends on the accuracy of the source data, and mistakes in the data can affect the results. Also, because it is built in Excel, it may not handle very large datasets or real-time updates as well as specialized BI tools.

## Conclusion

In this project, I demonstrated how raw sales data can be transformed into actionable insights using Excel. By building a data model with relationships between tables, I enabled seamless analysis without flattening the data, improving flexibility and scalability. The dashboard highlights monthly performance, top products, regional trends, store-level insights, and weekly sales patterns, providing a solid foundation for data-driven business decisions.

## Impact

The dashboard supports strategic decision-making by clearly visualizing key sales metrics. It helps identify top-performing products, stores, and regions, enabling more targeted marketing and operational optimization. By highlighting seasonal trends and weekly sales patterns, it informs planning for promotions and inventory management. Additionally, this project showcases practical skills in data modeling, Power Query, Pivot Tables, and dashboard design, reinforcing proficiency in Excel analytics for professional growth.

### Connect With Me Here

LinkedIn: https://www.linkedin.com/in/ibrahim-abdulrasaq/

Email: ibrahimabdulrasaqademola2017@gmail.com
