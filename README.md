# Olist E-commerce Analytics

![Power BI](https://img.shields.io/badge/PowerBI-Dashboard-yellow?logo=powerbi)
![SQL](https://img.shields.io/badge/SQL-Data%20Analysis-blue?logo=postgresql)
![Data Analytics](https://img.shields.io/badge/Data-Analytics-green)
![Customer Analytics](https://img.shields.io/badge/Customer-Analytics-purple)
![Logistics Analytics](https://img.shields.io/badge/Logistics-Analytics-orange)

Data Analytics project designed to transform marketplace transactional data into **strategic insights for sales performance, customer behavior, and logistics operations**.

The project analyzes the **Olist Brazilian e-commerce marketplace**, integrating sales, payments, logistics, and customer data into a unified analytics model visualized through **Power BI dashboards**.

---

# Business Case

E-commerce marketplaces generate large volumes of operational data, but many organizations lack the analytical structure needed to transform this data into actionable insights.

The Olist marketplace faces several operational and analytical challenges:

- Sellers distributed across multiple regions
- High volume of daily orders
- Limited visibility of customer purchasing behavior
- Multiple payment methods impacting financial analysis
- Lack of standardized operational performance metrics

This project aims to solve these problems by building a **data-driven analytics solution** capable of providing operational visibility and supporting strategic decision making.

---

# Project Objectives

The project focuses on answering key business questions through data analytics:

- How revenue is distributed across categories and sellers
- Which customers generate the highest value for the platform
- How logistics performance impacts customer satisfaction
- Which operational factors drive cancellations
- How payment methods influence revenue and cash flow

---

# Analytical Framework

The dashboard is structured around four main analytical areas.

## Sales Performance

- Revenue trends
- Category performance
- Gross Merchandise Value
- Year over Year growth

## Financial Analysis

- Revenue by payment method
- Payment installment behavior
- Cancellation financial impact
- Cash flow indicators

## Logistics Analytics

- On Time Delivery (OTD)
- Freight cost impact
- Delivery lead time
- Logistics bottleneck identification

## Customer Intelligence

- RFM segmentation
- Customer Lifetime Value (LTV)
- Customer satisfaction analysis
- Seller performance evaluation

---

# Key Metrics

## Sales KPIs

- Total Revenue
- Gross Merchandise Value (GMV)
- Average Order Value
- Revenue Growth YoY

## Logistics KPIs

- On Time Delivery Rate (OTD)
- Average Freight Cost
- Delivery Lead Time

## Customer KPIs

- Customer Lifetime Value
- Net Promoter Score (NPS)
- RFM Segmentation

## Operational KPIs

- Cancellation Rate
- Seller Ranking
- Order Processing Time

---

# Key Business Insights

The analysis identified several strategic insights.

### Revenue Concentration

A small percentage of sellers accounts for a large portion of total revenue, indicating marketplace dependency on key partners.

### High Value Customer Segments

Customers classified as **RFM Champions** represent a significant portion of the platform's GMV.

### Payment Behavior

Credit card transactions dominate the platform's revenue stream.

### Logistics Efficiency

Delivery performance maintains a high success rate, demonstrating strong operational efficiency.

### Freight Impact

Freight cost significantly influences order value and purchasing behavior.

---

# Data Sources

The analysis is based on a relational dataset stored in **SQLite**, containing transactional marketplace data.

Main tables include:

| Table | Description |
|------|-------------|
| orders | Order lifecycle and delivery timestamps |
| order_items | Products sold per order |
| order_payments | Payment information |
| order_reviews | Customer satisfaction ratings |
| customers | Customer information |
| sellers | Marketplace sellers |
| products | Product catalog |
| geolocation | Geographic mapping |

---

# Technology Stack

| Tool | Purpose |
|-----|--------|
| Power BI | Data visualization |
| SQL | Data querying |
| SQLite | Data storage |
| DAX | Business metrics |
| DBeaver | Database exploration |

---

# Data Model Architecture

The analytical model follows a **star schema architecture**.

Fact tables store transactional metrics while dimension tables provide descriptive attributes.

Core relationships include:

- Orders → Customers
- Orders → Sellers
- Orders → Products
- Orders → Payments
- Orders → Reviews

This structure enables scalable analytical queries and optimized reporting performance.

---

# Dashboard Preview

## Executive Overview

![Overview](images/dashboard_overview.png)

High level business performance indicators including revenue, orders, logistics metrics, and customer insights.

---

## Sales Analysis

![Sales](images/dashboard_sales.png)

Revenue trends, category analysis, and geographic sales distribution.

---

## Customer Segmentation

![Customers](images/dashboard_customers.png)

RFM segmentation and customer lifetime value analysis.

---

## Logistics Performance

![Logistics](images/dashboard_logistics.png)

Delivery performance, cancellation rates, and freight cost analysis.

---

# Project Structure
