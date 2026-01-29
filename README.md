# Online Furniture Sales Analytics
### Excel Dashboard Project | Retail Analytics

---

## Executive Summary
This project analyzes **online furniture sales transactional data** using **Microsoft Excel** to derive actionable business insights related to **revenue performance, delivery efficiency, customer satisfaction, and operational costs**.

The analysis is presented through an **interactive Excel dashboard** designed to support **executive-level decision-making**.

---

## Business Problem
The online furniture retailer faces challenges in understanding:
- Which product categories and brands drive the most revenue
- How delivery performance affects customer satisfaction
- Whether value-added services (assembly) improve revenue and ratings
- How shipping costs, assembly costs, and payment methods impact overall performance

Due to limited visibility, decisions related to **logistics, pricing, services, and customer experience** are not fully data-driven.

---

## Project Objectives
- Analyze sales and revenue performance across categories and brands  
- Evaluate delivery success rates and identify operational bottlenecks  
- Understand customer satisfaction using ratings analysis  
- Measure the impact of assembly services on order value and ratings  
- Analyze shipping and assembly cost contribution  
- Identify preferred payment methods for high-value orders  
- Build an interactive Excel dashboard for stakeholders  

---

## Stakeholders
- **Business Leadership** – Strategic decision-making  
- **Sales & Marketing Teams** – Revenue drivers and promotions  
- **Operations & Logistics Teams** – Delivery performance  
- **Customer Experience Teams** – Ratings and service quality  
- **Finance Teams** – Cost contribution and profitability  

---

## Dataset Description
The dataset contains **transactional-level order data** with the following fields:
- Order ID, Customer ID  
- Product Category, Brand  
- Total Amount (Order Value)  
- Delivery Status, Delivery Window  
- Customer Rating  
- Assembly Service Requested (Yes/No)  
- Shipping Cost, Assembly Cost  
- Payment Method  

One order may contain **multiple rows**, representing individual order line items.

---

## Data Preparation & Cleaning
The dataset was cleaned and prepared in Excel using the following steps:
- Removed duplicate records  
- Handled missing numerical values by replacing them with 0  
- Replaced blank and `Unknown` ratings with **“Not Rated”**  
- Identified and corrected data errors in the **Total Amount** column  
- Standardized column names and formats  
- Ensured numeric fields were correctly typed  

### Derived Columns Created
- **Order Value Bucket:** Low / Medium / High  
- **Delivery Window Bucket**  
- Excluded “Not Rated” values from average rating calculations  

The cleaned dataset was structured to support **pivot table analysis**.

---

## Methodology
The analysis was performed entirely in **Microsoft Excel** using:
- Pivot Tables for aggregation and segmentation  
- Calculated KPIs for business metrics  
- Pivot Charts for visualization  
- Slicers for interactivity  

**Total Orders** were calculated using **Distinct Count of Order ID** to avoid double counting.

---

## Key Performance Indicators (KPIs)
The following KPIs were displayed as dashboard cards:
- **Total Revenue** – Sum of total order amount  
- **Total Orders** – Distinct count of Order IDs  
- **Average Order Value (AOV)** – Revenue / Total Orders  
- **Average Customer Rating** – Mean of customer ratings  
- **Delivery Success Rate** – Delivered orders / Total orders  
- **Total Shipping Cost** – Sum of shipping cost  

---

## Analysis & Insights

### Sales & Revenue Analysis
- Bedroom and Living Room categories generate the highest revenue  
- A small group of brands contributes a large share of sales  
- Medium-value orders dominate total transactions  

**Insight:**  
Revenue is concentrated in core home categories and mid-range pricing.

---

### Delivery Performance Analysis
- Overall delivery success rate is relatively low  
- Short delivery windows (0–5 days) have higher failure rates  
- Large furniture categories face more delivery issues  

**Insight:**  
Aggressive delivery timelines negatively impact delivery performance.

---

### Customer Experience Analysis
- Customer ratings vary significantly by category  
- Office and Living Room categories receive lower ratings  
- Orders with assembly service receive higher ratings  

**Insight:**  
Delivery experience and service offerings strongly influence satisfaction.

---

### Assembly Service Impact
- Assembly service orders have higher AOV  
- Assembly costs are low compared to revenue uplift  

**Insight:**  
Assembly service is a profitable value-added offering.

---

### Cost Contribution Analysis
- Shipping costs form a significant portion of order value  
- Assembly costs contribute a smaller share  

**Insight:**  
Shipping is a major cost driver and a key optimization area.

---

### Payment Method Analysis
- High-value orders primarily use **Credit Card** and **EMI**  
- Cash and wallet payments dominate low-value orders  

**Insight:**  
Customers prefer flexible and secure payment options for expensive purchases.

---

## Dashboard Design
The interactive Excel dashboard includes:
- KPI cards at the top  
- Sales, delivery, customer, cost, and payment visuals  
- Slicers for:
  - Product Category  
  - Delivery Status  
  - Assembly Service  
  - Delivery Window  

The dashboard allows stakeholders to **dynamically explore performance** across segments.

---

## Recommendations
- Improve delivery timelines for bulky furniture  
- Focus marketing and inventory on top revenue categories  
- Strengthen partnerships with high-performing brands  
- Promote assembly services as a premium add-on  
- Optimize shipping operations to reduce costs  
- Improve quality and delivery experience for low-rated categories  
- Enhance EMI and card payment options for high-value orders  

---

## Tools & Skills Used
- Microsoft Excel  
- Pivot Tables & Pivot Charts  
- Excel Tables  
- Slicers & Filters  
- KPI Reporting  
- Dashboard Design  
- Business & Data Analysis  
- Conditional Formatting  

---

## Conclusion
This Excel-based analytics project demonstrates how **transactional data** can be transformed into **actionable business insights**.  
While the business shows strong revenue performance, delivery efficiency and logistics present clear improvement opportunities.  
Data-driven insights enable better decisions across **pricing, operations, services, and customer experience**.

---

## 👤 Author
**Harisha Thoparapu**  
Data Analyst | Excel | SQL | Power BI | Python | Data Analytics
