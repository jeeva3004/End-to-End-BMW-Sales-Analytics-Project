# End-to-End-BMW-Sales-Analytics-Project
# 🚗 BMW Global Sales Performance Dashboard (2010 – 2024)

## 📌 Project Overview

This project presents an end-to-end **data analytics solution** analyzing BMW global sales performance across models, regions, fuel types, pricing, and time trends.

The dashboard is developed using **Power BI** based on a large Excel dataset containing **50,000+ records**, simulating real-world automotive sales data.

The project demonstrates the complete analytics workflow including:

* Python-based data cleaning
* Excel-based summary analysis
* Data modeling and DAX calculations
* Interactive dashboard design and storytelling

---

## 📊 Dataset Information

* Source: Excel Dataset
* Records: 50,000+ rows
* Time Period: 2010 – 2024
* Granularity: Model × Region × Year

### Key Columns

* Year
* Model
* Region
* Sales Volume
* Revenue
* Fuel Type
* Average Price

---

## 🐍 Python Data Cleaning & Preparation

Data preprocessing was initially performed using **Python (Pandas)** to ensure data quality and consistency before visualization.

### 🔹 Python Tasks Performed

* Handling missing values
* Data type conversions
* Removing duplicate records
* Column formatting and renaming
* Basic exploratory checks
* Exporting cleaned dataset to Excel for reporting

This step helped improve **data accuracy and dashboard performance.**

---

## 📊 Excel Data Preparation & Summary Analysis

Further analytical preparation was performed in **Microsoft Excel**.

### 🔹 Excel Techniques Used

* **VLOOKUP** – Data retrieval across summary tables
* **XLOOKUP** – Flexible dynamic lookup implementation
* **INDEX + MATCH** – Advanced lookup for optimized performance
* Creation of summary tables:

  * Model-wise Sales Volume
  * Region-wise Revenue
  * Fuel Type Distribution
  * Year-wise Sales Trends

This enabled better understanding of patterns before dashboard development.

---

## ⚙️ Tools & Technologies Used

* Power BI Desktop
* DAX (Data Analysis Expressions)
* Python (Pandas)
* Microsoft Excel
* Data Modeling (Star Schema)
* Conditional Formatting
* Drill-Through Navigation

---

## 📈 Dashboard Pages

### 🔵 1. Overall Dashboard

* Total Revenue KPI
* Total Sales Volume KPI
* Year-over-Year Growth %
* Average Selling Price
* Sales Trend Analysis
* Top Performing Models
* Regional Revenue Comparison
* Fuel Type Distribution

---

### 🔵 2. Model & Market Performance Analysis

* Regional Sales Heat Matrix
* Price vs Sales Scatter Analysis
* Region Contribution per Model
* Sales Performance Segmentation

---

### 🔵 3. Regional Market Performance & Trend Analysis

* Top Performing Region KPI
* Revenue Ranking by Region
* Regional Sales Trend
* Fuel Preference Distribution

---

### 🔵 4. Model Performance & Product Insights

* Top Selling Model KPI
* Model Revenue Ranking
* Model Sales Trend
* Fuel Preference by Model

---

### 🔵 5. Model Deep Dive (Drill Through)

* Model-specific Revenue
* Units Sold Trend
* Regional Contribution
* Average Selling Price

---

## ⭐ Key Business Insights

* Asia region contributes the highest overall revenue
* Certain premium models maintain strong pricing power
* Sales trends fluctuate significantly post-2020
* Fuel preferences vary by region indicating different market maturity
* Not all high-price models achieve high sales volume

---

## 🎯 Skills Demonstrated

* Python Data Cleaning
* Excel Advanced Lookup Functions
* Data Modeling & KPI Design
* DAX Measures & Time Intelligence
* Interactive Dashboard Design
* Drill-Through Analytics
* Business Storytelling

---

## 📁 Project Structure

BMW-Sales-PowerBI-Dashboard
│
├── BMW_Sales_Dashboard.pbix
├── BMW_Sales_Dataset.xlsx
├── README.md
└── screenshots

---

## 🚀 How to Use

1. Download the repository
2. Open the `.pbix` file in Power BI Desktop
3. Update Excel data source path if required
4. Use slicers and drill-through for interactive exploration

---

## 👨‍💻 Author

**Jeeva Nandham**
Aspiring Data Analyst focused on building data-driven business solutions.

⭐ If you found this project useful, feel free to star the repository.
