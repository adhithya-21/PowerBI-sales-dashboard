# Food Waste Analysis Dashboard - Power BI

## Project Overview

This project was developed as part of the **SENG 31333 – Business Intelligence with Power BI** module at the University of Kelaniya.

The dashboard analyzes food waste, sales performance, and operational inefficiencies using Power BI. The project focuses on data cleaning, transformation, data modeling, DAX calculations, and interactive dashboard visualization to generate business insights and support decision-making.

---

## Objectives

* Analyze food waste trends across branches
* Identify major waste reasons and operational issues
* Measure financial impact caused by waste
* Forecast future waste patterns
* Build an interactive business intelligence dashboard using Power BI

---

## Dataset & Data Preparation

The project includes multiple datasets imported from Excel and CSV files.

### Data Cleaning Performed

* Corrected data types
* Removed duplicates
* Handled null values
* Trimmed and standardized text
* Reformatted date columns
* Validated revenue and cost values
* Cleaned branch and item information

### Tools Used

* Microsoft Power BI
* Power Query
* DAX (Data Analysis Expressions)

---

## Data Modeling

A **Star Schema** model was implemented for efficient analysis.

### Fact Tables

* WasteData
* SalesData

### Dimension Tables

* BranchData
* Calendar
* ItemMaster

### Relationships

* Calendar[Date] → WasteData[Date]
* Calendar[Date] → SalesData[Date]

---

## DAX Measures

Several DAX measures were created to calculate business KPIs.

### Key Measures

* Total Waste Quantity
* Total Waste Cost
* Total Revenue
* Waste Percentage vs Sales
* Worst Performing Branch
* Most Wasted Item
* Savings Opportunity
* Potential Revenue Lost

---

## Dashboard Pages

### 1. Executive Overview

* Total Waste Quantity
* Total Waste Cost
* Waste Percentage vs Sales
* Worst Performing Branch
* Most Wasted Item
* Waste Cost Trend by Month
* Waste by Branch
* Waste by Category

### 2. Root Cause Analysis

* Waste by Reason
* Waste by Shift
* Waste by Day of Week
* Top 5 Most Wasted Items

### 3. Profit Impact Dashboard

* Potential Revenue Lost
* Monthly Savings Opportunity

### 4. Forecasting & Planning

* 30-Day Waste Prediction Forecast

---

## Key Insights

* Identified branches with the highest waste generation
* Detected operational causes of food waste
* Measured the financial impact of waste on revenue
* Predicted future waste trends for better planning

---

## Repository Structure

```text
Food-Waste-PowerBI-Dashboard/
│
├── dashboard.pbix
├── dataset/
├── screenshot/
├── README.md
```

---

## Screenshots

Add dashboard screenshots inside the `screenshot/` folder and display them here.

Example:

```md
![Dashboard Preview](screenshot/dashboard.png)
```

---

## Academic Information

**University:** University of Kelaniya
**Module:** SENG 31333 – Business Intelligence with Power BI
**Academic Year:** 2024/2025

---

## Author

Adhithya Jayawardhana

---
