# Housing-Price-Analysis-using-Google-Big-Query-and-Power-BI
### Dashboard Link: https://app.powerbi.com/Redirect?action=OpenReport&appId=a6a927c2-3465-402c-905a-8ced8f5307af&reportObjectId=995d52e5-060f-49af-927b-e148a5cafbf3&ctid=ea8ae8e0-4ea9-4d36-801d-0eee370d9e5f&reportPage=43e986a7feb8232f2311&pbi_source=appShareLink&portalSessionId=4271acbf-57ff-4839-8d0e-a281c2f1b36a

# 🏠 Housing Market Analysis – Power BI Dashboard

## 📌 Project Overview
This project analyzes residential housing transaction data using **Google BigQuery** as the data source and **Power BI** for visualization.  
The objective is to uncover pricing trends, property characteristics influencing value, and regional market behavior to support data-driven decision-making in the housing market.

---

## 🎯 Problem Statement
The housing market is influenced by multiple variables such as property type, size, location, age, and macroeconomic indicators.  
However, these factors are often analyzed in isolation.

**This project aims to answer:**
- How do housing prices vary by **property type, region, and size**?
- Which regions command the **highest price per square meter**?
- What role do **property age and room count** play in pricing?
- How do **economic indicators** correlate with housing prices?

---

## 🗂️ Data Source
- **Primary Source:** Google BigQuery  
- **Dataset:** Housing transaction data  
- **Tooling:** Power BI Desktop (`.pbix`)  

**Key Data Fields Used**
- Purchase price  
- Square meters (sqm) and price per sqm  
- House type (Apartment, Villa, etc.)  
- Number of rooms  
- Year built  
- Region & city  
- Inflation rate, interest rate (macro indicators)

---

## 🔍 Data Analysis Steps
1. **Data Ingestion**
   - Connected Power BI directly to Google BigQuery.
   - Imported structured housing transaction data.

2. **Data Cleaning & Preparation**
   - Standardized column names and data types.
   - Handled missing values in macroeconomic indicators.
   - Derived calculated fields such as:
     - Price per square meter
     - Property age (current year – year built)

3. **Data Modeling**
   - Established relationships between transactional and regional attributes.
   - Created measures using DAX for:
     - Average price
     - Median sqm price
     - Regional comparisons

4. **Exploratory Analysis**
   - Price distribution across house types.
   - Regional price comparison.
   - Impact of size (sqm) and number of rooms on pricing.

5. **Dashboard Design**
   - Interactive slicers for region, house type, and year.
   - KPI cards for average price and sqm price.
   - Comparative bar and trend visuals.

---

## 📊 Key Insights from the Dashboard

### 1. Property Type Pricing
- **Villas consistently command higher average purchase prices** than apartments.
- Apartments show **higher price per sqm**, indicating premium pricing in urban locations.

### 2. Regional Trends
- **Capital and North Zealand regions** exhibit the highest average prices and sqm rates.
- Peripheral regions show lower absolute prices but better affordability per room.

### 3. Size & Room Impact
- Larger properties (higher sqm) increase total price but **reduce price per sqm**.
- Properties with **3–5 rooms** dominate transaction volume, indicating strongest demand.

### 4. Property Age Effect
- Newer properties generally achieve **higher price per sqm**.
- Older houses show greater variance, driven largely by location rather than age alone.

### 5. Economic Indicators
- Rising interest and inflation rates correlate with **price moderation**, especially in non-prime regions.
- Prime regions remain relatively resilient to macroeconomic fluctuations.

---

## 📈 Business Value
- Enables **buyers** to identify value-for-money regions.
- Assists **investors** in targeting high-yield property types.
- Helps **policy analysts** understand regional affordability gaps.
- Demonstrates end-to-end BI skills: BigQuery → Power BI → Insights.

---

## 🛠️ Tools & Technologies
- **Google BigQuery** – Data storage & querying  
- **Power BI** – Data modeling & visualization  
- **DAX** – Measures and calculations  

---

## 📁 Files Included
- `Big_Query_BI.pbix` – Power BI dashboard file  
- `Housing Data.csv` – Sample housing dataset  

---

## 🚀 Next Enhancements
- Time-series forecasting for price trends.
- Rental yield analysis (if rental data is added).
- Integration of demographic or income-level data.

---

**Author:** Aditya Vijay  
**Domain:** Data Analytics | Business Intelligence  
