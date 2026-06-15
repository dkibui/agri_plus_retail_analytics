# AgriPlus Kenya Retail Analytics

A data analytics portfolio project built around a fictional agricultural input retail chain operating across five towns in Kenya.

The project follows the complete analytics lifecycle:

* Data generation
* Data cleaning and preparation
* Data modeling
* SQL analysis
* Data visualization
* Business insights and recommendations

## Business Scenario

AgriPlus Kenya is a fictional agricultural input retailer with branches in:

* Nairobi
* Nakuru
* Eldoret
* Kitale
* Meru

The company sells a variety of farm inputs including fertilizers, seeds, pesticides, animal feed, and farm tools.

Management would like to better understand:

* Sales performance across regions
* Product category trends
* Customer purchasing behavior
* Seasonal demand patterns
* Payment preferences
* Top-performing stores and products

## Objectives

This project aims to demonstrate practical data analytics skills by:

* Designing a relational database in PostgreSQL
* Building a star schema for analytical workloads
* Generating realistic synthetic business data
* Writing SQL queries to answer business questions
* Creating interactive Tableau dashboards
* Producing actionable business insights

## Technology Stack

* PostgreSQL
* Python
* Pandas
* Tableau
* Git
* GitHub

## Database Design

The project uses a star schema consisting of:

### Fact Table

* fact_sales

### Dimension Tables

* dim_store
* dim_product
* dim_customer
* dim_date

```
                dim_store
                    |
dim_customer — fact_sales — dim_product
                    |
                dim_date
```

## Example Business Questions

### Sales Performance

* Which store generates the highest revenue?
* Which product categories contribute the most sales?
* How do sales change throughout the year?

### Customer Insights

* How do commercial farmers differ from smallholder farmers?
* What is the impact of customer loyalty tiers?

### Geography

* Which towns have the strongest sales performance?
* How does demand vary by county?

### Seasonality

* How do long rains and short rains affect demand?
* Which products experience seasonal spikes?

### Payment Behaviour

* What proportion of transactions are made using M-Pesa?
* How do payment preferences vary across regions?

## Repository Structure

```
├── data/
│   ├── raw/
│   ├── cleaned/
│
├── database/
│   ├── schema.sql
│   ├── seed_data.sql
│
├── notebooks/
│
├── sql/
│   ├── exploratory_queries.sql
│   ├── business_questions.sql
│
├── tableau/
│
├── images/
│
└── README.md
```

## Project Status

This project is currently under development.

Upcoming stages:

1. PostgreSQL schema creation
2. Synthetic data generation
3. Data cleaning and preparation
4. Exploratory data analysis
5. SQL business analysis
6. Tableau dashboard development
7. Insights and recommendations

---

This repository is intended to showcase end-to-end data analytics skills through a realistic agricultural retail business scenario inspired by the Kenyan market.
