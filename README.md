# UK-Retail-Store-Dashboard
This is a transactional data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.

--

# UK Online Retail Transaction Dashboard

This project provides an interactive dashboard for analyzing transactional data from a **UK-based, registered non-store online retail company** that sells **unique all-occasion gifts**. The dataset includes **all transactions between December 1, 2010, and December 9, 2011**, capturing both individual and wholesale customers.
[Online Retail Store](https://archive.ics.uci.edu/dataset/352/online+retail)

---
![alt image](https://github.com/wolethomas78/UK-Retail-Store-Dashboard/blob/2d2224a81a0cb3db91c894ea19cc1d3a6ec2b98a/UKdashboard.png)
You can access the dynamic dashboard here: [Tableau dynamic Dashboard](https://public.tableau.com/app/profile/oluwole.fagbemi2492/viz/UKonlineRetailDashboard/Dashboard1?publish=yes)


## Dataset Overview

- **Time Span:** 01/12/2010 – 09/12/2011  
- **Business Type:** Non-store, online retail  
- **Customer Base:** Individual customers and wholesalers  

### **Data Fields**

| Field        | Type     | Description                                                                 |
|--------------|----------|-----------------------------------------------------------------------------|
| `InvoiceNo`  | Nominal  | Unique 6-digit transaction number. Invoices starting with `C` = cancellation |
| `StockCode`  | Nominal  | Unique 5-digit product identifier                                            |
| `Description`| Nominal  | Product name or item description                                             |
| `Quantity`   | Numeric  | Number of units sold per transaction                                         |
| `InvoiceDate`| Numeric  | Date and timestamp of transaction generation                                 |
| `UnitPrice`  | Numeric  | Price per unit of product (in sterling)                                       |
| `CustomerID` | Nominal  | Unique 5-digit identifier for each customer                                  |
| `Country`    | Nominal  | Name of the country where the customer resides                               |

---

## Dashboard Features

- **Sales Overview:** Total sales, revenue trends, and top-performing products  
- **Transaction Insights:** Purchase patterns and canceled invoices  
- **Customer Distribution:** Geographic view of customers and top purchasing countries  
- **Product Analysis:** Inventory movements and popular gift items  
- **Time-based Trends:** Seasonal sales peaks and daily transaction volumes  

---

## Tech Stack

- **Data Processing:** Python (Pandas, NumPy) You can access the Python code here [Pandas code](https://github.com/wolethomas78/UK-Retail-Store-Dashboard/blob/cb4d7b8c7fc9fa9ac13a83786eb6e672572d977b/Python_code)
- **Database:** SQL (Postgresql) You can access the Postgresql code here: [Postgresql Code](https://github.com/wolethomas78/UK-Retail-Store-Dashboard/blob/3b491545bf525d2d57c305ae573954f6c1562e0b/Postgresql_codes)
- **Visualization:** Tableau : [Tableau Dashboard](https://public.tableau.com/app/profile/oluwole.fagbemi2492/viz/UKonlineRetailDashboard/Dashboard1?publish=yes)

---

## Usage

- 1. Clone this repository  
- 2. Load the dataset into your preferred environment  
- 3. Run the dashboard script or open the BI tool  
- 4. Explore interactive charts and KPIs  

---

## License
This project is open-source and available under the [MIT License](LICENSE).


---


![alt image](https://github.com/wolethomas78/UK-Retail-Store-Dashboard/blob/2c744d517fc0d3a054ad240917d672e2f72a6d64/UkKpi.png)
## KPI Analysis Report
### 1. Chart Reference
The analysis shows a sharp increase in both Quantity and Revenue from Dec-2010 to Dec-2011.
Quantity increased from 341,038 to 4,821,464
Revenue rose from 746,723.61 to 8,979,283.34

### 2. Observation
Quantity Growth: +1314%
Revenue Growth: +1102%
Return Items: Increased from 20,056 to 462,461, with return rate rising from 5.88% to 9.59%
Total Customers: Increased by 347% (from 949 to 4,245)
Revenue per Customer: Increased from 786.85 to 2,115.26

### 3. Interpretation
The massive growth in quantity and revenue indicates a large sales spike, likely due to a campaign or seasonal demand.
Higher return rates suggest potential issues with product quality, fulfillment, or mismatched customer expectations.
Revenue per customer more than doubled, meaning each customer is spending more on average.

### 4. Impact
Positive
Significant revenue and customer growth, strengthening overall market reach.

### Negative
Sharp increase in returns (over 9%) could lead to additional costs and affect profitability and customer satisfaction.

### 5. Recommendation
Investigate the cause of high returns (e.g., product defects, sizing issues, delivery problems).
Enhance quality checks and improve product descriptions to reduce returns.
Leverage the surge in customers by launching loyalty programs to retain them.
Monitor scalability and fulfillment processes to handle spikes without affecting product quality.
Analyze which products or campaigns drove the spike to replicate success in future periods.

---

## Revenue Trend Report (2010–2011)
![alt image](https://github.com/wolethomas78/UK-Retail-Store-Dashboard/blob/4f83be0ec9b419b2de5a6c17ca1fa6e405df2cf8/UKlinetrend.png)
### Overview
This report visualizes monthly Revenue data for 2010 and 2011, highlighting a significant upward trend throughout 2011.

 ### Revenue Trend (Line Chart)

#### Observations
2010: No recorded revenue across all months.
2011: Consistent monthly revenue, averaging around $630K in early months.
Sharp growth from September to November, peaking at $1.46M.

### Interpretation
Strong upward trend in late 2011 suggests seasonal demand or successful marketing campaigns.
Sustained revenue across the year indicates improved market positioning compared to 2010.

### Impact
Marked year-over-year growth, with 2011 far exceeding 2010 results.
Significant Q4 sales surge could highlight holiday-driven performance boosts.

### Recommendations
Replicate successful strategies from September–November to maintain high revenue levels.
Optimize early-year campaigns to smooth out revenue fluctuations.
Strengthen inventory management and logistics for peak sales periods.

---

![alt image](https://github.com/wolethomas78/UK-Retail-Store-Dashboard/blob/ff6bdacd1bf07c9dc0da8661b577abcc905e4efc/uktop5.png)
## Top 5 Customers Report
 ### Overview
This report highlights the Top 5 customers based on total purchase amounts, including a category for Unregistered Customers.

### Customer Purchase Data
Rank	Customer ID / Type	Total Purchase in GBP
- 1	Unregistered =	1,447,488
- 2	14646	   =     279,489
- 3	18102	   =     256,438
- 4	17450	   =     187,322
- 5	14911	   =     132,459

### Observations
Unregistered customers contribute the largest share with 1.45M in purchases.
Registered customers 14646 and 18102 are the top-performing individuals.
The top 5 customers collectively account for a significant portion of overall revenue.

### Interpretation
Heavy reliance on unregistered users could indicate missed opportunities for customer profiling and retention strategies.
Registered high-value customers show strong loyalty and purchasing power.

## Impact
Lack of registration data may limit personalized marketing and long-term retention.
Strong individual customer purchases suggest potential for VIP loyalty programs.

## Recommendations
 Encourage unregistered customers to create accounts (offer incentives like discounts or points).
 Develop exclusive rewards programs for top customers to increase repeat purchases.
 Analyze purchasing behavior of top customers to identify cross-selling and upselling opportunities.

 ---

 ## Revenue Distribution Report (2010 vs 2011)
 ![alt image](https://github.com/wolethomas78/UK-Retail-Store-Dashboard/blob/944fb9995b05269080de66ed7335f762b6a13038/ukpie.png)
 
### Overview
This report shows the percentage of total revenue contributed by 2010 and 2011, visualized as a pie chart.

### Revenue Percentage Data
Year	Revenue Percentage
2010	7.08%
2011	92.32%

 Revenue Split (Pie Chart)

### Observations
2011 generated the majority of revenue (92.32%), while 2010 contributed only 7.08%.
Indicates rapid growth or a significant operational scale-up in 2011.

### Interpretation
Strong revenue dominance in 2011 suggests effective sales strategies or market expansion during that year.
The small share in 2010 may represent early operations or a pre-growth phase.

### Impact
The company saw a massive year-over-year increase, improving overall profitability.
This trend can influence future budget planning and investment decisions.

### Recommendations
 Analyze drivers of 2011’s success (products, campaigns, market conditions) to replicate growth.
 Use insights from 2011 to forecast and plan for upcoming years.
 Maintain focus on high-performing strategies while addressing 2010’s performance gaps.









