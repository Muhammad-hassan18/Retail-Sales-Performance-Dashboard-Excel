# 📊 Retail Sales Performance Dashboard Excel

> **An end-to-end Microsoft Excel analytics project transforming raw retail transaction data into an interactive business intelligence dashboard.**

---

## Executive Summary

This project analyzes **1,000 plus retail transactions across 26 business attributes** to understand sales performance, customer behavior, product performance, regional trends, order channels, returns, and operational performance.

The project was completed entirely in **Microsoft Excel**, starting with raw transaction data and progressing through data validation, formula-based analysis, PivotTables, KPIs, and an interactive dashboard.

### Key Business Metrics

| Metric                  |         Result |
| ----------------------- | -------------: |
| Total Transactions      |      **1,001** |
| Total Sales Value       | **Rs. 80.73M** |
| Total Quantity Sold     |      **2,921** |
| Average Order Value     | **Rs. 80.65K** |
| Average Delivery Time   |  **5.47 days** |
| Average Customer Rating |   **3.00 / 5** |
| Return Rate             |     **49.85%** |
| Cancelled Orders        |        **246** |

---

## 🎯 The Business Problem

A retail business has transaction data containing information about:

* Orders and customers
* Products, categories, and brands
* Sales and quantities
* Discounts, taxes, and shipping costs
* Payment methods
* Sales channels
* Cities, states, and regions
* Delivery performance
* Returns and order status
* Customer ratings

However, raw transactional data alone does not provide an efficient way for management to answer important business questions.

The key questions were:

* How are sales performing over time?
* Which products and categories generate the most revenue?
* Which brands contribute the most sales?
* Which regions and states are performing best?
* Which sales channel generates more revenue?
* What is the return and cancellation situation?
* How efficient is the delivery process?
* Where are the biggest opportunities for improvement?

---

## 💡 The Solution

I built an **Excel-based Sales Performance Dashboard** that converts raw transaction-level data into actionable business insights.

The solution follows an end-to-end analytics workflow:

**Raw Data → Data Cleaning & Validation → Analysis → PivotTables → KPIs → Dashboard → Business Recommendations**

The dashboard provides a centralized view of sales performance and allows business users to explore different dimensions of the data rather than manually analyzing thousands of cells.

---

## 📈 Number Impact

The analysis revealed several important numerical insights.

### Sales Concentration

**Electronics** generated approximately **Rs. 57.01M**, making it the strongest category and accounting for roughly **70.6% of total sales**.

### Product Performance

The highest-revenue products included:

1. **Keyboard**  Rs. 10.28M
2. **Headphones**  Rs. 9.54M
3. **Watch**  Rs. 8.48M
4. **Shoes**  Rs. 8.32M

### Regional Performance

The **North region** generated approximately **Rs. 48.56M**, significantly higher than the other regions represented in the dataset.

### Sales Channel

Sales were relatively balanced between:

* **Mobile App:** Rs. 41.02M
* **Website:** Rs. 39.71M

The Mobile App generated approximately **50.8% of total sales**.

### Returns

The dataset contains **499 returned transactions**, representing approximately **49.85% of all transactions**.

This is a major business signal that should be investigated further.

### Operations

Average delivery time was approximately **5.47 days**, while the average customer rating was only **3.00/5**.

These metrics suggest potential opportunities for improving both fulfillment performance and customer experience.

---

# 🔬 Methodology

## 1. Data Understanding

The dataset contains **1,001 transaction records and 26 columns** covering sales, customers, products, geography, operations, and order outcomes.

Key fields include:

* Order ID
* Order Date
* Customer Information
* Product
* Category
* Subcategory
* Brand
* Quantity
* Unit Price
* Discount
* Tax
* Shipping Cost
* Total Amount
* Payment Method
* Order Channel
* City / State / Region
* Delivery Days
* Return Status
* Rating
* Order Status

---

## 2. Data Cleaning & Validation

Excel formulas and data-validation techniques were used to prepare the dataset for analysis.

The workflow included:

* Checking data structure
* Identifying potential missing values
* Validating fields and data types
* Checking transaction-level information
* Working with dates and numerical fields
* Preparing data for PivotTable analysis
* Using Excel formulas to validate and transform information

---

## 3. Data Analysis

After preparing the data, PivotTables were created to analyze sales across multiple dimensions.

The analysis included:

* Monthly sales
* Product performance
* Brand performance
* Category performance
* Payment methods
* Order channels
* Regional performance
* State-level performance
* Return status
* Order status
* Delivery performance
* Customer ratings

---

## 4. KPI Development

Key performance indicators were created to provide a high-level overview of the business.

The dashboard focuses on metrics such as:

* Total Sales
* Transaction Count
* Quantity Sold
* Average Order Value
* Average Delivery Days
* Average Rating
* Return Performance
* Order Status

---

## 5. Dashboard Development

The final dashboard uses **PivotTables and charts** to transform the analysis into an easy-to-understand visual report.

The dashboard is designed to help users quickly identify:

* Sales trends
* Top-performing products
* Strong categories and brands
* Regional opportunities
* Channel performance
* Operational issues
* Return-related problems

---

# 🛠️ Skills Demonstrated

### Microsoft Excel

* Data Cleaning
* Data Validation
* Excel Formulas
* Logical Functions
* PivotTables
* Pivot Charts
* KPI Development
* Dashboard Design
* Data Visualization
* Business Analysis

### Analytical Skills

* Exploratory Data Analysis
* Trend Analysis
* Sales Performance Analysis
* Regional Analysis
* Customer/Order Analysis
* Business Insight Generation
* Data-Driven Decision Making

---

# 📊 Results & Business Recommendations

## 1. Investigate the High Return Rate

Almost **50% of transactions are marked as returned**.

This is the most significant issue identified in the dataset.

### Recommendation

Investigate return reasons by:

* Product
* Category
* Brand
* Region
* Customer segment
* Order channel

The business should determine whether returns are caused by product quality, incorrect expectations, delivery issues, or other operational problems.

---

## 2. Prioritize Electronics

Electronics contributes approximately **Rs. 57.01M**, representing the majority of sales.

### Recommendation

Continue investing in high-performing electronics products while monitoring inventory, pricing, and customer satisfaction to protect this important revenue stream.

---

## 3. Investigate the North Region

The North region generates approximately **Rs. 48.56M**, making it the strongest region in the dataset.

### Recommendation

Analyze what is driving this performance and determine whether successful products, customer segments, pricing strategies, or marketing approaches can be replicated in weaker regions.

---

## 4. Strengthen the Mobile App

The Mobile App contributes approximately **Rs. 41.02M**, slightly outperforming the Website.

### Recommendation

Continue improving the mobile shopping experience and analyze customer behavior to identify opportunities for increasing conversion and repeat purchases.

---

## 5. Improve Customer Experience

The average rating is approximately **3.0/5**, indicating significant room for improvement.

### Recommendation

Combine rating information with product, return, delivery, and channel data to identify the main drivers of poor customer satisfaction.

---

## 6. Monitor Delivery Performance

Average delivery time is approximately **5.47 days**.

### Recommendation

Analyze delivery performance by region, state, product, and order channel to identify areas where logistics improvements could increase customer satisfaction and potentially reduce returns.

---

# 🚀 Next Steps

This project can be extended into a more advanced analytics solution by:

1. Adding **profit and margin analysis** rather than focusing primarily on sales value.
2. Creating **customer segmentation** based on purchasing behavior.
3. Analyzing **return reasons** if that information becomes available.
4. Building **monthly and year-over-year growth metrics** with a larger historical dataset.
5. Adding automated data refresh functionality.
6. Rebuilding the dashboard in **Power BI** for more advanced interactivity.
7. Using SQL/Python to automate the data preparation pipeline.

---

# 📁 Project Structure

```text
Excel-Sales-Dashboard/
│
├── Excel Project 1 Sales Dashboard.xlsx
└── README.md
```

### Workbook Structure

| Sheet                  | Purpose                                  |
| ---------------------- | ---------------------------------------- |
| **Master Data**        | Raw transaction-level dataset            |
| **Data Check**         | Data validation and checking             |
| **KPIs**               | KPI calculations and PivotTable analysis |
| **Dashboard Creation** | Dashboard visualization workspace        |

---

 
### ⭐ If you found this project useful

Feel free to explore the workbook and review the dashboard, calculations, and analysis workflow.
