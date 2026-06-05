# E-Commerce-Return-Rate-Investigation


## Project Overview

Product returns are a major challenge in the e-commerce industry. High return rates increase logistics costs, create inventory management issues, and reduce profitability. This project aims to investigate the factors influencing product returns using statistical analysis and data visualization techniques.

The objective is to identify return patterns, understand customer behavior, and provide business recommendations to reduce unnecessary returns.

---

## Problem Statement

E-commerce companies experience significant losses due to product returns. Business teams need to understand:

* Why customers return products.
* Which product categories have higher return rates.
* Whether discounts increase returns.
* Whether delivery delays influence return behavior.
* Which customer groups contribute most to returns.

This project performs statistical and exploratory data analysis to answer these questions.

---

## Dataset Description

The dataset contains e-commerce transaction records with the following attributes:

| Column Name       | Description                                           |
| ----------------- | ----------------------------------------------------- |
| InvoiceNo         | Invoice Number                                        |
| StockCode         | Product Code                                          |
| Description       | Product Description                                   |
| Quantity          | Quantity Purchased (Negative values indicate returns) |
| InvoiceDate       | Date of Transaction                                   |
| UnitPrice         | Product Price                                         |
| CustomerID        | Customer Identifier                                   |
| Country           | Customer Country                                      |
| Customer Rating   | Customer Satisfaction Rating                          |
| Discount Percent  | Discount Offered                                      |
| Delivery Duration | Delivery Time in Days                                 |

---

## Tools and Libraries Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy

---

## Project Workflow

### Phase 1: Data Understanding

* Loaded dataset
* Checked dataset dimensions
* Identified missing values
* Removed duplicate records
* Calculated total orders
* Calculated total returns
* Computed return percentage

---

### Phase 2: Descriptive Statistical Analysis

Calculated:

* Mean
* Median
* Standard Deviation
* Quartiles
* Distribution Analysis

Analyzed:

* Average Delivery Duration
* Average Product Price
* Average Customer Rating

Visualizations:

* Histograms
* Distribution Plots

---

### Phase 3: Return Pattern Investigation

Investigated relationships between:

* Category and Return Rate
* Price and Return Rate
* Delivery Duration and Return Rate
* Discount and Return Rate
* Customer Rating and Return Rate

Visualizations:

* Bar Charts
* Box Plots
* Scatter Plots
* Heatmaps

---

### Phase 4: Outlier Analysis

Detected unusual observations using:

* Box Plots
* Interquartile Range (IQR)
* Z-Score Method

Investigated:

* High Return Customers
* Extremely Delayed Deliveries
* High-Priced Returned Products

---

### Phase 5: Hypothesis Testing

Performed statistical hypothesis testing.

**Null Hypothesis (H₀):**
Delivery delay has no impact on return behavior.

**Alternative Hypothesis (H₁):**
Delivery delay significantly impacts return behavior.

Test Used:

* Independent T-Test

Decision Rule:

* p-value < 0.05 → Reject H₀
* p-value > 0.05 → Fail to Reject H₀

---

### Phase 6: Customer Segmentation

Created customer segments:

* High Return Customers
* Discount Driven Customers
* Premium Customers
* Delayed Delivery Customers
* Low Rating Customers

Purpose:

* Identify customer groups requiring intervention.
* Improve customer retention strategies.

---

### Phase 7: Business Insights

Key Findings:

* Certain product categories showed higher return rates.
* High-return customers contributed significantly to overall returns.
* Discounts influenced return behavior in some cases.
* Customer ratings provided useful insights into dissatisfaction.
* Delivery delay impact was evaluated using hypothesis testing.

---

## Visualizations Included

* Return Rate Analysis
* Category-wise Return Distribution
* Price vs Return Analysis
* Delivery Duration Analysis
* Discount Impact Analysis
* Customer Segmentation Charts
* Correlation Heatmap
* Outlier Detection Boxplots

---

## Business Recommendations

1. Improve product descriptions and images.
2. Monitor high-return customers.
3. Review return-prone product categories.
4. Optimize discount strategies.
5. Improve customer satisfaction through feedback monitoring.
6. Strengthen delivery performance monitoring.
7. Develop predictive models for return prevention.

---

## Future Scope

* Machine Learning-based Return Prediction
* Customer Churn Analysis
* Product Recommendation Systems
* Real-Time Return Monitoring Dashboard
* Advanced Customer Segmentation Models

---

## Conclusion

This project successfully analyzed e-commerce return behavior using statistical techniques and data visualization. The analysis identified important return patterns, customer segments, and business factors that influence product returns. The findings can help e-commerce businesses reduce return rates, improve customer satisfaction, and optimize operational efficiency.
