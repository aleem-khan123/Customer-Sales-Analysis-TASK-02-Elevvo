# Customer-Sales-Analysis-TASK-02-Elevvo
#  Customer Sales Analysis (Task 02)

## ** Project Overview**
This project is part of the **Elevvo Pathways Platform Internship 2025**, which provided me the opportunity to apply data analytics skills in real-world scenarios.  

The task focuses on **Customer Sales Analysis** using transaction-level sales data.  
The objective was to **explore, clean, and analyze customer behavior**, identify sales patterns, and apply **RFM (Recency, Frequency, Monetary) analysis** for customer segmentation.

---

## ** Objectives**
- Explore customer sales and purchasing behavior.  
- Analyze trends across **countries, products, and months**.  
- Perform **RFM Analysis** to segment customers.  
- Provide **visual insights** for better business decision-making.  

---

## ** Dataset**
- **Source**: Online Retail Dataset  
- **Key Fields**:  
  - `InvoiceNo` → Transaction number  
  - `StockCode` → Product code  
  - `Description` → Product description  
  - `Quantity` → Number of items purchased  
  - `InvoiceDate` → Date of transaction  
  - `UnitPrice` → Price per unit  
  - `CustomerID` → Unique customer identifier  
  - `Country` → Country of transaction  
  - `TotalSales` → Revenue (`Quantity × UnitPrice`)  
  - `Year, Month, Week` → Extracted for trend analysis  

---

## ** Data Preparation & Cleaning**
- Removed records with **missing CustomerID values**.  
- Removed **duplicate invoices**.  
- Added **TotalSales** column for revenue calculation.  
- Extracted **Year, Month, Week, YearMonth** for time-series analysis.  
- Removed records with **negative quantities or zero values**.  

---

## ** Exploratory Data Analysis (EDA)**
- **Top Countries by Sales** → Identified revenue-contributing countries.  
- **Monthly Sales Trends** → Observed growth, decline, and seasonality.  
- **Product-Level Analysis** → Top-selling and most profitable products.  
- **Customer Segmentation** → Applied RFM analysis to group customers.  

---

## ** RFM Analysis (Customer Segmentation)**
- **Recency (R)** → How recently a customer purchased.  
- **Frequency (F)** → How often they purchased.  
- **Monetary (M)** → How much revenue they generated.  

**Key Findings:**  
- **Loyal Customers** → Low Recency, High Frequency.  
- **At-Risk Customers** → High Recency, Low Frequency.  
- **High-Value Customers** → High Monetary value.  
- **One-Time Buyers** → Large group with single transactions.  

---

## ** Data Visualization**
- **Bar Charts** → Sales by country & top-selling products.  
- **Line Charts** → Monthly sales trends.  
- **Histograms** → Distribution of R, F, M values.  
- **Heatmaps** → Correlation between sales metrics.  
- **RFM Graphs** → Segmentation visualization.  

---

## ** Insights & Conclusion**
- A **few countries dominate** total sales revenue.  
- **Monthly sales patterns** show clear seasonality and peaks.  
- A **small group of loyal, high-value customers** drives most revenue.  
- Large portion of customers purchase **only once** → retention opportunity.  
- Findings can support **marketing campaigns, customer retention strategies, and product decisions**.  

---

## ** Project Structure**
📁 Customer-Sales-Analysis  
- 📄 Raw_Data.csv — Original dataset  
- 📄 Cleaned_Data.csv — Processed dataset  
- 📄 Task 2 Report (Customer Sales Analysis).pdf — Detailed report  
- 📄 Visualizations/ — Graphs & charts  
- 📄 RFM_Segmentation.ipynb — Notebook with RFM analysis  
- 📄 README.md — Project documentation  

---

## ** How to Use**
1. Clone this repository  
   ```bash
   git clone https://github.com/aleem-khan123/Customer-Sales-Analysis.git
   Navigate into the project folder

cd Customer-Sales-Analysis


Open RFM_Segmentation.ipynb in Jupyter Notebook to view analysis.

Review Task 2 Report.pdf for detailed insights.

Explore Visualizations/ folder for graphs and charts.

## Results

Clear understanding of customer purchasing behavior.

Segmentation of loyal, at-risk, and one-time buyers.

Identification of top-performing countries & products.

Actionable insights to improve retention and revenue growth.

 ## Author

- Aleem Shoukat
- Gmail- iamaleemmm@gmail.com
- Linked in-www.linkedin.com/in/aleem-shoukat-9bb3b6356

⭐ If you found this project useful, feel free to star this repository!
