# U.S. Retail Sector Opportunity Analysis Dashboard

## Author
 Raye Oji, Aditi Shukla  

---

# Project Overview

This project analyzes retail sector performance across the United States using state-level economic indicators and sector-level retail growth data from **2023 to 2025**.

The objective was to build a business intelligence dashboard that helps identify:

- Which states offer the strongest retail opportunities  
- Which retail sectors are growing the fastest  
- How unemployment impacts retail performance  
- Which sector leads in each state  
- Time trends of top-performing sectors  

This project combines **Python for data engineering** and **Tableau for dashboard visualization**.

---

# Problem Statement

Retail businesses and investors often face uncertainty when expanding into new markets.

Important questions include:

- Which U.S. states have the best business environment for retail growth?  
- Which sectors are currently outperforming others?  
- Does lower unemployment support higher retail growth?  
- Which states are best suited for specific retail sectors?  

This project addresses these questions using a data-driven dashboard.

---

# Dataset Details

Two datasets were used in this project:

## 1. State Retail Growth Dataset

Included:

- FIPS code  
- State abbreviation  
- NAICS sector code  
- Retail Year-over-Year Growth (%)  
- Monthly / Quarterly time periods  

## 2. State Unemployment Dataset

Included:

- State name  
- Date  
- Unemployment Rate (%)  

These two datasets were cleaned, transformed, and joined into one final analytics dataset.

---

# Phase 1 of the Project (Initial Version)

The project initially focused only on **state-level retail analysis**.

This phase analyzed:

- Retail growth by state  
- Unemployment by state  
- Geographic performance differences  
- High-growth and low-growth states  

This helped understand overall state-level economic performance.

---

# Phase 2 of the Project (Advanced Version)

The project was later enhanced by introducing **sector-level analysis using NAICS codes**.

This improved the project significantly by allowing:

- Leading retail sector by state  
- National sector growth comparison  
- State × Sector opportunity analysis  
- Sector trend analysis over time  
- More realistic business decision-making insights  

This transformed the project from a simple regional analysis into a full business intelligence dashboard.

---

# Data Cleaning and Data Join Process (Python)

Python was used to build the final analytical dataset.

## Key Steps Performed:

### Retail Data Transformation

Retail data was originally in wide format and converted into long format for easier analysis.

### State Mapping

State abbreviations such as TX, CA, NY were converted into full state names for mapping and joins.

### NAICS Mapping

NAICS codes were translated into real retail sector names such as:

- Clothing Stores  
- Health & Personal Care Stores  
- Electronics Stores  
- Food & Beverage Stores  
- Motor Vehicle & Parts Dealers  
- Miscellaneous Retailers  

### Unemployment Cleaning

Date fields and unemployment values were standardized and cleaned.

### Final Dataset Join

Retail growth data was joined with unemployment data using:

- State  
- Date  

This created one unified dataset.

### Additional Features Created

Several business-focused calculated columns were added:

- **Opportunity Score** = Retail Growth − Unemployment Rate  
- Year  
- Month  
- Leading Sector by State  
- Leading Sector Growth Value  
- Leading Sector Opportunity Score  
- Is Leading Sector Flag  

These features were used directly in Tableau dashboards.

---

# Final Dashboard Charts

## Chart 1: Leading Retail Sector by State

U.S. map showing the highest-performing retail sector in each state.

## Chart 2: National Retail Sector Growth Comparison

Bar chart comparing average retail growth across sectors nationwide.

## Chart 3: Retail Growth vs Unemployment by State

Scatter plot analyzing the relationship between labor market strength and retail growth.

## Chart 4: State × Sector Opportunity Heatmap

Heatmap highlighting strong retail opportunities by state and sector combination.

## Chart 5: Time Trend Line of Top 5 Sectors

Line chart showing sector growth trends from 2023 to 2025.

---

# Dashboard Summary

The dashboard combines KPIs and visual analytics to present:

- Best performing sector nationally  
- Best state for retail opportunity  
- Lowest unemployment state  
- Highest growth state  
- Geographic and sector insights  
- Trend analysis over time  

This allows businesses to make better expansion and investment decisions.

---

# Key Insights

- Health & Personal Care Stores emerged as one of the strongest sectors  
- South Dakota showed strong opportunity and low unemployment  
- Nevada showed strong retail growth  
- Sector leadership varies across states  
- Lower unemployment often supports stronger retail performance  

