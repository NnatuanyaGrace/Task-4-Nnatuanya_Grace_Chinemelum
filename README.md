# E-Commerce Orders Analysis and Performance Dashboard 

## Dashboard Preview

<img width="782" height="442" alt="Ecommerce Orders Dashboard__" src="https://github.com/user-attachments/assets/9d412e78-0fc5-46ca-8906-26099bdad2b7" />

## 1. Project Overview

This project analyzes 1,200 e-commerce order records to evaluate sales performance, product performance, order fulfillment, and referral-source contribution.

An interactive, one-page dashboard was developed using Microsoft Power BI to consolidate key performance indicators (KPIs) and visualizations into a single reporting interface. The analysis covers monthly sales trends from January 2023 to June 2025 and examines order distribution across five order statuses and five referral sources.

The findings reveal fluctuations in monthly sales, differences in product sales performance, a substantial proportion of cancelled and returned orders, and variations in order volume across referral sources. These insights provide a basis for investigating operational challenges and identifying opportunities to improve business performance.

## 2. Business Objectives

The analysis was designed to address the following business questions:

* What is the overall order volume and recorded sales value?
* How does sales performance change over time?
* Which products contribute the most to recorded sales?
* How are orders distributed across different statuses?
* What proportions of orders are cancelled and returned?
* Which referral sources generate the highest order volumes?

## 3. Tools and Technologies

* **Microsoft Power BI:** Dashboard development and data visualization.
* **DAX (Data Analysis Expressions):** KPI calculations and measures.
* **Power Query:** Data preparation and transformation.
* **Microsoft Excel:** Source dataset.

## 4. Key Performance Indicators

The dashboard tracks six key performance indicators:

| KPI                   |   Value |
| --------------------- | ------: |
| Total Recorded Sales  |   1.26M |
| Total Orders          |   1,200 |
| Delivered Order Value | 242.60K |
| Delivered Orders      |     231 |
| Cancellation Rate     |  20.83% |
| Return Rate           |  20.58% |

**KPI interpretation:** Total Recorded Sales represents the recorded value across all orders, while Delivered Order Value represents the recorded value of orders with a delivered status. The latter is an operational measure and should not be interpreted as accounting net revenue or profit.

## 5. Key Findings and Observations

### 5.1 Monthly Sales Performance

The monthly sales trend examines recorded sales from January 2023 to June 2025.

**Key observations:**

* Monthly sales fluctuate throughout the reporting period.
* June 2024 recorded the highest monthly sales value of approximately 68,068.54.
* April 2023 recorded the lowest monthly sales value of approximately 27,751.71.
* The trend does not show a consistent upward or downward movement throughout the entire period.

**Business implication:**

The fluctuations indicate an opportunity to investigate the factors influencing monthly sales performance. Reviewing seasonal demand, promotional activities, pricing changes, and product demand could help explain the observed peaks and declines.

The data identifies when sales varied, but further investigation is required to establish why those variations occurred.

### 5.2 Product Sales Performance

The dashboard compares recorded sales values across seven products.

| Product | Recorded Sales |
| ------- | -------------: |
| Chair   |        195.62K |
| Printer |        195.61K |
| Laptop  |        192.13K |
| Tablet  |        186.57K |
| Monitor |        175.65K |
| Desk    |        167.46K |
| Phone   |        151.72K |

**Key observations:**

* Chair recorded the highest sales value at approximately 195.62K.
* Printer followed closely at approximately 195.61K.
* Laptop ranked third at approximately 192.13K.
* Phone recorded the lowest sales value at approximately 151.72K.
* The difference between the highest- and lowest-performing products was approximately 43.90K.

**Business implication:**

Chair and Printer recorded the strongest sales values, while Phone had the lowest. Further investigation into quantities sold, pricing, customer demand, and product costs would help determine what drives these differences.

Sales value alone does not establish profitability or justify changes to inventory levels.

### 5.3 Order Status and Fulfillment Analysis

The order-status analysis examines the distribution of all 1,200 recorded orders.

| Order Status | Number of Orders | Percentage |
| ------------ | ---------------: | ---------: |
| Cancelled    |              250 |     20.83% |
| Returned     |              247 |     20.58% |
| Pending      |              237 |     19.75% |
| Shipped      |              235 |     19.58% |
| Delivered    |              231 |     19.25% |
| **Total**    |        **1,200** |   **100%** |

**Key observations:**

* Cancelled orders represent the largest status category, with 250 orders.
* Returned orders account for 247 orders.
* Pending orders account for 237 orders.
* Shipped orders total 235.
* Delivered orders account for 231 records.

Cancelled and returned orders combined account for 497 orders, representing **41.42% of all recorded orders**.

**Business implication:**

The proportion of cancelled and returned orders warrants further investigation. Examining cancellation reasons, return patterns, delivery experiences, and potential product-related issues could help management identify opportunities to improve order fulfillment and customer experience.

The status distribution alone does not establish the causes of cancellations or returns.

### 5.4 Referral-Source Performance

The referral-source analysis compares order volumes across five acquisition sources.

| Referral Source | Number of Orders | Percentage |
| --------------- | ---------------: | ---------: |
| Instagram       |              259 |     21.58% |
| Email           |              250 |     20.83% |
| Google          |              241 |     20.08% |
| Facebook        |              228 |     19.00% |
| Referral        |              222 |     18.50% |
| **Total**       |        **1,200** |   **100%** |

**Key observations:**

* Instagram recorded the highest order volume, with 259 orders.
* Email ranked second, with 250 orders.
* Google accounted for 241 orders.
* Facebook generated 228 orders.
* Referral recorded the lowest order volume, with 222 orders.

The difference between the highest- and lowest-performing referral sources was 37 orders.

**Business implication:**

Instagram leads in recorded order volume, but order count alone does not establish which channel generates the most revenue or delivers the best return on marketing investment.

Comparing revenue contribution, conversion rates, customer acquisition costs, and marketing expenditure would provide a more complete assessment of referral-source effectiveness.

## 6. Business Recommendations

Based on the findings, the following actions are recommended for further investigation and consideration.

### 1. Investigate Cancellations and Returns

Examine the reasons behind the 250 cancelled orders and 247 returned orders. Identifying recurring causes could help management prioritize improvements to the ordering, fulfillment, and returns processes.

### 2. Monitor Monthly Sales Trends

Review periods of unusually high or low sales alongside available information on seasonal demand, promotions, pricing, and customer activity. This could help explain sales fluctuations and support better sales planning.

### 3. Evaluate Product Performance Beyond Sales Value

Investigate the factors contributing to the strong recorded sales of Chair and Printer and the lower sales value of Phone. Combine sales analysis with quantities sold, product costs, and inventory information before making product-level decisions.

### 4. Assess Referral-Source Effectiveness

Compare referral sources using revenue, conversion rates, acquisition costs, and marketing expenditure. This would help determine which channels provide the greatest business value rather than relying solely on order volume.

### 5. Strengthen Order Fulfillment Monitoring

Track order statuses regularly and investigate potential delays, cancellations, and returns. Additional information about fulfillment times and the reasons for unsuccessful orders would support more targeted operational improvements.

## 7. Dashboard Features

The interactive dashboard consolidates the analysis into a single page.

**KPI Cards**

* Total Recorded Sales
* Total Orders
* Delivered Order Value
* Delivered Orders
* Cancellation Rate
* Return Rate

**Visualizations**

* **Monthly Sales Trend:** Tracks recorded sales over time.
* **Orders by Referral Source:** Compares order volumes across acquisition channels.
* **Orders by Status:** Shows the distribution of orders across five statuses.
* **Sales by Product:** Compares recorded sales values across products.

**Interactive Slicers**

Users can filter the dashboard by:

* Product
* Order Status
* Date

These features support interactive exploration of the dataset and allow users to examine performance across different selections.

## 8. Limitations of the Analysis

The findings are based on the fields and records available in the supplied dataset.

* The analysis identifies sales fluctuations but does not establish their underlying causes.
* Product sales values do not establish product profitability.
* Order volumes by referral source do not establish marketing effectiveness or return on investment.
* The cancellation and return analysis identifies the scale of these outcomes but does not explain why they occurred.
* Delivered Order Value represents the recorded value of delivered orders and may not account for refunds, discounts, or other financial adjustments.

Additional financial, marketing, product-cost, and fulfillment data would be required to support more detailed business conclusions.

## 9. Conclusion

This project demonstrates how Microsoft Power BI can transform e-commerce order data into an interactive dashboard for business performance monitoring and analysis.

The analysis identified fluctuations in monthly sales, differences in product sales contributions, a substantial proportion of cancelled and returned orders, and variations in referral-source order volumes.

These findings highlight opportunities to investigate order fulfillment, understand changes in sales performance, evaluate product performance, and assess customer acquisition channels more comprehensively.

The dashboard brings these indicators together in a single reporting interface, allowing users to monitor performance and explore the data interactively. Further analysis using additional business information could help management investigate the underlying causes of the observed patterns and develop more targeted improvement strategies.

## 10. Skills Demonstrated

* Data Preparation and Transformation
* Microsoft Power BI
* DAX Measures and Calculations
* KPI Development
* Data Visualization
* Interactive Dashboard Design
* Business Performance Analysis
* Insight Development
* Business Recommendations
* Analytical Reporting

## 11. Project Deliverables

* Power BI dashboard file: Ecommerce Orders Dashboard.pbix
* Dashboard screenshot: Screenshot of the Dashboard
* Project documentation: `README.md` file
* Source dataset:Source dataset used for the analysis
