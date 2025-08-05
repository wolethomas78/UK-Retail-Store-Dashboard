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

- **Data Processing:** Python (Pandas, NumPy) [Pandas code](https://github.com/wolethomas78/UK-Retail-Store-Dashboard/blob/cb4d7b8c7fc9fa9ac13a83786eb6e672572d977b/Python_code)
- **Database:** SQL (Postgresql) You can access the Postgresql code here: [Postgresql Code](https://github.com/wolethomas78/UK-Retail-Store-Dashboard/blob/3b491545bf525d2d57c305ae573954f6c1562e0b/Postgresql_codes)
- **Visualization:** Tableau 

---

## Usage

1. Clone this repository  
2. Load the dataset into your preferred environment  
3. Run the dashboard script or open the BI tool  
4. Explore interactive charts and KPIs  

---

## License







This project is open-source and available under the [MIT License](LICENSE).

