# Procurement-Perfromance-Supplier-Risk-Dashboard
## Project Overview
This project simulates a real-world Tier 1 automotive procurement environment, where the company supplies OEM customers and sources components from Tier 2 suppliers.
The dashboard focuses on supplier performance, cost control and risk identification, enabling data-driven decision-making within Procurement.

---

## About Me
I am a Data Analyst with a strong focus on SQL and Power BI, specializing in business‑oriented analytics and decision support. My work emphasizes clean data preparation, robust data modeling, and KPI development, transforming raw and often inconsistent data into clear, actionable insights. I enjoy working end‑to‑end — from data cleaning and analytical SQL logic to well‑structured Power BI dashboards designed for management and business users.

---

## Objective
The main goal of this dashboard is to:
- Provide full visibility over procurement KPIs
- Track supplier performance across cost, delivery, and quality
- Identify high-risk suppliers
- Monitor savings performance vs targets
- Support strategic sourcing decisions

---

## Business Context
- Company: Tier 1 Automotive Supplier
- Customers: OEMs (e.g. VW, BMW, etc.)
- Suppliers: Tier 2
- Scope:
  - Multiple suppliers
  - Multiple commodities
  - Multiple projects

---

## Data Model
A Star Schema model was implemented to ensure scalability and efficient data analysis.
### Fact Table
**Fact_ProcurementPerformance**
Contains transactional procurement data at the level of:
- Supplier
- Component
- Project
- Month
Key metrics:
- Spend
- Price
- Volume
- Savings
- Quality (PPM)
- Delivery performance
- Lead time
  
### Dimension Tables
- Dim_Supplier
- Dim_Component
- Dim_Project
- Dim_Location
- Dim_Date

### Relationship
All dimension tables are connected to the fact table using:
- One-To-Many relationships
- Single-direction filtering
---

## Power BI Dashboard
### Procurement Performance Overview
**Purpose**: Provide a high-level overview of procurement perfromance
**Visuals:**
1. KPI Cards
  - Total Spend
  - Savings Achievement %
  - Avg Supplier Rating
  - Avg On-Time Delivery
2. Top Suppliers by Spend
  - Identifies key cost drivers
3. Unit Price Trend
  - Shows price evolution over time
4. Savings vs Target
  - Compares plan vs execution
5. Supplier Rating Distribution
  - Shows overall supplier base quality

### Supplier Risk & Quality Analysis
**Purpose**: Identify risks and perfromance issues
**Visuals:**
1. Supplier Risk Matrix (Scatter)
  - Core decision-making visual
2. PPM Trend Over Time
  - Tracks quality perfromance
3. Lead Time vs Performance Score
  - Identifies inefficient suppliers
4. Top Suppliers by PPM
  - Highlights worst performers
5. Supplier Perfromance Table
  - Detailed view of decision-making

---

## Data Model & Assumptions
- Star‑schema model with Customers, Products, Orders, and Order Items
- Revenue calculated from transactional data
- Estimated Profit calculated using an assumed 30% gross margin, due to missing cost data
- The assumption is explicitly documented and used consistently
 
---

## Key Insights
This dashboard enables:
- Identification of high-risk suppliers
- Detection of quality issues (PPM trends)
- Monitoring of cost and savings performance
- Understanding of supplier contribution to total spend
- Comparison of suppliers using a composite performance score
 
---

## Tools & Techniques
- Power BI Desktop
- Data modeling (star schema)
- DAX measures for KPIs
- UX‑focused dashboard design
- Excel - data preparation

---

## Contact
- LinkedIn: https://www.linkedin.com/in/luka-milenkovic-74768a285
- Email: m.milenkovicluka@gmail.com 
- GitHub: https://github.com/lukamilenkovic25

---
