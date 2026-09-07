# Retail Sales Performance Analysis

## Project Overview

This project analyzes retail sales data to evaluate revenue performance, customer purchasing patterns, product demand, and sales activity across different periods and customer segments.

The analysis was conducted to identify key sales trends, high-performing product categories, customer segments, and sales patterns that can support data-driven decisions related to inventory planning, marketing, promotions, staffing, and overall sales performance.

---

## Business Problem

How can a retail business use sales data to understand revenue performance, customer purchasing patterns, and product demand in order to identify opportunities for improving sales performance?

---

## Objective

To analyze retail sales data to identify revenue trends, high-performing product categories, customer purchasing patterns, and key factors contributing to sales performance.

---

## Business Questions

The analysis was guided by five key business questions:

1. How does revenue change over time?
2. Which product categories generate the most revenue?
3. How does revenue differ by gender?
4. Which days of the week generate the highest sales?
5. Which product categories and customer segments (age group × category) contribute most to overall revenue?

---

## Dataset

The dataset contains **1,000 retail transactions** covering a 12-month period.

The data includes transaction-level information such as:

* Transaction ID
* Date
* Customer ID
* Gender
* Age
* Product Category
* Quantity
* Price
* Total Revenue
* And other transaction-related fields

### Data Quality

The dataset was validated before analysis to ensure data reliability.

The following checks were performed:

* No missing values were identified.
* No duplicate transactions were identified.
* Revenue calculations were validated across all 1,000 transactions.
* Total Revenue was confirmed as **Quantity × Price** for each transaction.

---

## Data Cleaning and Preparation

The raw dataset was initially provided with multiple fields combined into a **single semicolon-delimited column**.

For example:

`1;2023/11/24;CUST001;Male;34;Beauty;3;50;150;...`

**Power Query** was used to transform the raw data by splitting the semicolon-delimited records into **16 properly structured columns**.

The revenue field was renamed from **Total Amount** to **Total Revenue** to provide a clearer business interpretation and was formatted as currency.

After transformation and validation, the cleaned dataset was used for analysis in Microsoft Excel.

---

## Methodology

The project followed the following analytical process:

1. Imported the raw retail sales dataset.
2. Cleaned and transformed the dataset using Power Query.
3. Split the semicolon-delimited data into structured columns.
4. Validated missing values, duplicate transactions, and revenue calculations.
5. Renamed and formatted the revenue field.
6. Created PivotTable analyses to answer the business questions.
7. Used charts to visualize key findings.
8. Interpreted the results from a business perspective.
9. Developed recommendations based on the findings.

---

## Key Performance Indicators

| KPI                      |                     Result |
| ------------------------ | -------------------------: |
| Total Revenue            |               **$456,000** |
| Total Quantity Sold      |            **2,514 units** |
| Total Transactions       |                  **1,000** |
| Unique Customers         |                  **1,000** |
| Highest-Revenue Category | **Electronics — $156,905** |
| Lowest-Revenue Category  |      **Beauty — $143,515** |

---

## Key Findings

### 1. Revenue Trend Over Time

Total revenue reached **$456,000** across the 12-month period.

Revenue fluctuated considerably throughout the year rather than following a consistent upward or downward trend.

* **Highest monthly revenue:** May — **$53,150**
* **Lowest monthly revenue:** September — **$23,620**

Strong revenue performance was also observed in October and December, while March and September recorded relatively weaker performance.

The fluctuations indicate that the business may be experiencing seasonal or month-to-month variations in customer demand.

**Visualization:** Line Chart

---

### 2. Revenue by Product Category

**Electronics** generated the highest revenue at **$156,905**, followed closely by **Clothing at $155,580**.

**Beauty** generated the lowest revenue at **$143,515**.

Despite Electronics being the highest-performing category, the relatively small difference between the three categories indicates that revenue was fairly balanced across the product portfolio.

**Visualization:** Clustered Column Chart

---

### 3. Revenue by Gender

Revenue was relatively evenly distributed between male and female customers.

* **Female:** $232,840 (**51.1%**)
* **Male:** $223,160 (**48.9%**)

Female customers generated slightly more revenue, with a difference of **$9,680** compared with male customers.

The relatively small difference suggests that both customer groups are important contributors to overall sales performance.

**Visualization:** Clustered Column Chart

---

### 4. Sales Volume by Day of the Week

Sales volume varied across the days of the week.

* **Highest:** Tuesday — **397 units**
* **Lowest:** Thursday — **301 units**

Tuesday accounted for approximately **15.8%** of total units sold, while Thursday accounted for approximately **12.0%**.

The variation suggests that customer purchasing activity was not evenly distributed throughout the week.

**Visualization:** Clustered Column Chart

---

### 5. Revenue by Product Category and Age Group

The strongest individual customer-product segment was:

**Clothing × Age 25–34 — $41,640**

Other strong combinations included:

* Electronics × Age 55–64 — **$38,210**
* Electronics × Age 35–44 — **$36,460**

When age groups were considered overall:

* **45–54:** $97,235 — highest overall
* **25–34:** $97,090
* **35–44:** $96,835
* **55–64:** $90,190
* **18–24:** $74,650 — lowest overall

These findings show that customer age and product category interact to influence revenue performance.

**Visualization:** Clustered Column Chart

---

## Recommendations

Based on the findings, the following recommendations are proposed:

### 1. Investigate Revenue Fluctuations

The business should investigate the factors behind high-performing months such as May, October, and December and weaker months such as March and September.

Understanding whether these differences are driven by promotions, product demand, seasonality, or customer purchasing behaviour could help improve revenue planning.

### 2. Maintain Support for High-Performing Categories

Electronics generated the highest revenue and should continue to receive appropriate inventory and marketing support.

However, because revenue was relatively balanced across Electronics, Clothing, and Beauty, the business should avoid becoming overly dependent on a single category.

### 3. Use Customer Segmentation

The retailer can use age-group and product-category insights to create more targeted marketing campaigns and promotions.

For example, Clothing promotions could be targeted toward customers aged 25–34 based on the strong performance of this segment.

### 4. Optimize Inventory and Staffing

Higher-volume days such as Tuesday should have sufficient inventory and staffing to meet customer demand.

The business could also investigate lower-volume days such as Thursday and test targeted promotions to determine whether sales can be increased.

### 5. Analyze Customer Purchasing Behaviour Further

Since revenue was relatively balanced between male and female customers, marketing strategies should continue to consider both groups.

Further analysis of purchasing frequency, product preferences, quantity purchased, and average transaction value could provide deeper insights into customer behaviour.

### 6. Investigate the Lower Revenue Contribution of Younger Customers

The 18–24 age group generated the lowest overall revenue.

Further analysis could determine whether this is related to purchasing power, product preferences, transaction frequency, or other customer behaviour and identify potential strategies for increasing sales from this segment.

---

## Tools Used

* **Microsoft Excel** — Data analysis, PivotTables, calculations, and visualization
* **Power Query** — Data cleaning, transformation, and validation

---

## Project Outcome

The analysis demonstrates how retail transaction data can be transformed into actionable business insights.

The findings provide the retailer with a clearer understanding of revenue trends, product category performance, customer demographics, purchasing patterns, and differences in sales activity across the week.

These insights can support more informed decisions around **inventory management, marketing, promotions, staffing, customer targeting, and sales strategy**.

---

## Conclusion

The Retail Sales Performance Analysis generated **$456,000 in total revenue from 1,000 transactions and 2,514 units sold**.

The analysis found that Electronics was the highest-revenue product category, female customers contributed slightly more revenue than male customers, Tuesday recorded the highest sales volume, and customers aged 25–34 purchasing Clothing represented the strongest individual customer-product segment.

Overall, the results show that retail sales performance is influenced by **time, product category, customer demographics, and purchasing patterns**. Using these insights to develop targeted strategies and improve operational planning can help the business identify opportunities to improve and stabilize sales performance.
