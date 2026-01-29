# 🏠 House Market Overview 

## 📌 Project Overview
This project provides an analytical overview of the **Housing Market** using **Microsoft Power BI**, with data sourced from **Google Cloud Platform (GCP)**.  
The report focuses on understanding market trends, pricing behavior, and key influencing factors through interactive visuals.

---

## ☁️ Data Source
- **Platform**: Google Cloud Platform (GCP)  
- **Service**: BigQuery  
- Data queried and prepared using **BigQuery SQL**

---

## 🔍 Data Understanding & Preparation
- Initial data understanding and exploratory analysis
- Data transformation and cleaning using **BigQuery SQL**
- Handling missing values and inconsistent records
- Creation of derived fields to support analysis

---

## 🔗 GCP to Power BI Integration
- Connected **BigQuery** to Power BI using native connector
- Optimized queries for performance and refresh efficiency
- Loaded cleaned data into Power BI data model

---

## 📐 DAX Functions Used (Brief Explanation)
- `CALCULATE()` – modifies filter context for measures  
- `YEAR()` – extracts year from date fields  
- `MAX()` – identifies maximum values  
- `IF()` – conditional logic  
- `BLANK()` – handles missing or invalid values  
- `MEDIAN()` – calculates central tendency  
- `DISTINCTCOUNT()` – counts unique values  
- `QUARTER()` – extracts quarter from date  
- `DATESINPERIOD()` – time intelligence calculations  
- `SUM()` – aggregation of numeric values  
- `ALLEXCEPT()` – removes filters except specified columns  
- `TOTALYTD()` – year-to-date calculations  

---

## 🧮 Calculated Columns
- Created calculated columns for date-based analysis
- Derived indicators to support pricing and trend evaluation

---

## 📊 Visualizations
- Interactive charts and KPIs for market trends
- **Key Influencers visual** to identify factors impacting house prices
- Time-based and category-based comparisons

---

## 📈 Key Insights
- Identification of key factors influencing house prices
- Trend analysis across years and quarters
- Median price behavior across regions and categories
- Clear visibility into market movement and seasonality

---

## 📸 Screenshots

#### Snapshot of DAX expression used to calculate Measures and Calculated Column:
![HMO_M&CC] (https://github.com/prasannak2405/PowerBI_Dashboard_3/blob/44763c9fbae01636056d55f08e9c5073206a32d0/images/HMO_M%26CC.png)

---

## 📁 Repository Contents
- Power BI report file (`.pbix`)
- PDF report
- Screenshots
- README.md

---

## ✅ Conclusion


This project demonstrates end-to-end **data analytics using GCP, BigQuery, and Power BI**, highlighting market trends and key drivers influencing the housing market.
