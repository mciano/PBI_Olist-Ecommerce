#Olist E-commerce Analytics

Data Analytics project focused on transforming raw marketplace data into actionable business insights through interactive dashboards and advanced metrics.

This project analyzes the Olist Brazilian e-commerce marketplace, integrating sales, logistics, customer, and payment data to generate insights about business performance, customer behavior, and operational efficiency.

The final solution was delivered as an interactive Power BI dashboard designed to support data driven decision making.

Business Problem

Modern e-commerce platforms generate massive volumes of transactional data, but organizations often lack clear visibility into operational performance.

The Olist marketplace faces several analytical challenges:

Sellers distributed across different geographic regions

High volume of daily orders

Limited visibility of customer behavior

Multiple payment methods impacting financial analysis

Lack of operational performance indicators

Without proper analytics, it becomes difficult to identify inefficiencies, optimize logistics, and improve customer retention.

Project Objectives

The goal of this project is to transform fragmented marketplace data into a structured analytics solution capable of answering key business questions.

Main objectives include:

Analyze marketplace revenue and sales performance

Identify high value customers through segmentation

Monitor logistics efficiency and delivery performance

Evaluate seller performance across the platform

Identify operational bottlenecks affecting business growth

Analytical Areas

The dashboard is structured into four analytical domains.

Orders Analysis

Sales volume by category

Monthly revenue trends

Gross Merchandise Value analysis

Year over Year comparisons

Payments and Financial Analysis

Revenue distribution by payment method

Payment installment analysis

Impact of cancellations on revenue

Cash flow insights

Logistics and Operations

On Time Delivery (OTD)

Freight cost impact on orders

Delivery lead time analysis

Cancellation monitoring

Customer Analytics

RFM customer segmentation

Customer Lifetime Value

Customer satisfaction analysis

Seller performance ranking

Key Metrics (KPIs)
Sales Metrics

Total Revenue

Gross Merchandise Value (GMV)

Average Order Value

Revenue Growth YoY

Logistics Metrics

On Time Delivery Rate (OTD)

Average Freight Cost

Delivery Lead Time

Customer Metrics

Customer Lifetime Value (LTV)

Net Promoter Score (NPS)

RFM Segmentation

Operational Metrics

Cancellation Rate

Seller Ranking

Order Processing Time

Key Insights

The analysis revealed several important insights.

Revenue is concentrated among a small number of sellers

High value customers generate a significant portion of total GMV

Credit card payments dominate marketplace transactions

Logistics performance maintains a high delivery success rate

Freight costs can significantly impact average order value

These insights support strategic decisions related to logistics optimization, seller management, and customer retention strategies.

Data Sources

The project uses a relational dataset stored in SQLite, containing marketplace transactional data.

Main tables include:

Table	Description
orders	Order lifecycle and timestamps
order_items	Products sold per order
order_payments	Payment method and payment value
order_reviews	Customer satisfaction ratings
customers	Customer information
sellers	Marketplace sellers
products	Product catalog
geolocation	Geographic information
Technology Stack
Technology	Purpose
Power BI	Data visualization and dashboard
SQL	Data querying and transformation
SQLite	Data storage
DAX	Business metrics and calculations
DBeaver	Database exploration
Data Model

The analytical model follows a star schema design, enabling efficient analysis and scalable reporting.

Fact tables store transactional information while dimension tables provide descriptive attributes.

Main relationships include:

Orders → Customers

Orders → Sellers

Orders → Products

Orders → Payments

Orders → Reviews

Dashboard Preview

Below are examples of the dashboard views developed in this project.

Executive Overview

This page provides a high level overview of revenue, orders, customer metrics, and logistics performance.

Sales and Revenue Analysis

Analysis of revenue trends, category performance, and geographic sales distribution.

Customer Segmentation

RFM segmentation and Lifetime Value analysis to identify high value customer groups.

Logistics Performance

Delivery performance, cancellation rates, and freight impact analysis.

