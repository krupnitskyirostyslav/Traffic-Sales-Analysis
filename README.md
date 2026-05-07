# Traffic-Sales-Analysis
Portfolio Project

Tools: SQL · Python · Pandas · BigQuery · 

## [Tableau Dashboard](https://public.tableau.com/views/BusinessPerformanceOverview_17775798601180/BusinessPerformanceOverviewSalesandTraffic?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Project Overview
This project analyzes traffic, user behavior, and sales performance of an e‑commerce platform using data extracted from Google BigQuery. It demonstrates end‑to‑end analytical workflow: from data extraction and cleaning to exploratory analysis, statistical testing, and dashboard creation.

The project was completed as part of a Data Analytics portfolio and showcases practical skills in SQL, Python, and Tableau.

## Project Structure
The analysis is organized into the following stages:

### 1. Data Extraction (SQL + BigQuery)
A custom SQL query was written to join multiple tables from the DA dataset and build a unified analytical dataset.
The final dataset includes:

- Session metadata (date, country, continent, device, browser, OS, language)
- Traffic source & channel
- User account attributes (verified, unsubscribed)
- Product information (category, name, price, description)

### 2. Dataset Overview
The notebook includes a structured overview of the dataset:

- Total number of columns
- Numeric, categorical, and datetime fields
- Number of unique sessions
- Time period covered
- Missing values analysis and causes

### 3. Exploratory Data Analysis (EDA)
General analysis includes:

- Distribution of sessions
- Sales patterns
- Top countries, continents, and product categories
- Device and traffic channel breakdown
- Registered vs. unregistered user behavior

### 4. Sales Dynamics Analysis
Time‑series analysis of:

- Daily total sales
- Seasonal patterns
- Sales trends across continents (America, Asia, Europe)
- Sales by traffic channels
- Sales by device types

Visualizations highlight differences in behavior across segments.

### 5. Pivot Tables
Pivot tables were created to summarize:

- Sessions by traffic channel × device
- Sales by top product categories × top countries
- Additional custom pivot tables for deeper insights

### 6. Statistical Analysis of Relationships
Correlation analysis includes:

- Sessions vs. sales per day
- Sales correlations across continents
- Sales correlations across traffic channels
- Sales correlations across top product categories

Each correlation is accompanied by statistical significance testing.

### 7. Statistical Analysis of Group Differences
Hypothesis testing was performed for:

- Sales differences between registered vs. unregistered users
- Session counts across traffic channels
- Share of organic traffic in Europe vs. America

Tests include t‑tests, non‑parametric tests, and proportion tests depending on data distribution.

### 8. Tableau Dashboard
A two‑page interactive dashboard was built in Tableau Public, visualizing:

- Sales dynamics
- Geographic performance
- Product category insights
- Device and traffic channel breakdown
- User behavior metrics

## Key Skills Demonstrated
SQL: complex joins, dataset construction, BigQuery querying

Python: Pandas, NumPy, Seaborn/Matplotlib, statistical testing

EDA: segmentation, pivot tables, trend analysis

Statistics: correlations, hypothesis testing, significance evaluation

Data Visualization: clear, business‑oriented charts

Tableau: interactive dashboards for executive‑level insights


## Summary
This project provides a complete analytical workflow for understanding e‑commerce performance. It combines SQL, Python, and Tableau to deliver actionable insights into traffic quality, user behavior, and sales patterns — demonstrating practical skills required for a Data Analyst role.
