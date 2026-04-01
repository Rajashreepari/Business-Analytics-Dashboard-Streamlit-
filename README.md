# 📊 Business Analytics Dashboard (Streamlit)

## 🚀 Overview
The **Business Analytics Dashboard** is an interactive web application built using **Streamlit** to analyze and visualize business data.

It provides powerful insights into:
- Revenue & Profit trends
- Regional performance
- Product analysis
- Statistical insights
- Outlier detection

This dashboard helps businesses make **data-driven decisions** efficiently.

---

## 🖥️ Dashboard Preview

### 📈 Trends Analysis
<img width="1893" height="843" alt="trends1" src="https://github.com/user-attachments/assets/e68b25d5-df32-453d-aa5c-00e4b84ce82f" />

<img width="1905" height="829" alt="trends2" src="https://github.com/user-attachments/assets/701f5821-b9f4-4240-9655-6968fef8de2d" />


### 🗺️ Regional Insights
<img width="1887" height="831" alt="region1" src="https://github.com/user-attachments/assets/3d14ad18-f0ec-45c3-bf05-b093676175cd" />

<img width="1881" height="840" alt="region2" src="https://github.com/user-attachments/assets/cb7cd12b-bcc8-4ffb-90a4-f46968717d10" />


### 📦 Product Analysis
<img width="1882" height="845" alt="products1" src="https://github.com/user-attachments/assets/71e4c9a6-aff4-4c6f-9bcd-e59ef6cc18e6" />

<img width="1892" height="835" alt="products2" src="https://github.com/user-attachments/assets/398b4cd0-317b-4645-b987-f2905039ff18" />


### 📦 Deep Dive Analysis
<img width="1892" height="831" alt="deepDive1" src="https://github.com/user-attachments/assets/88a57e09-ce6e-4e06-b252-5a55f8b67ac1" />

<img width="1893" height="841" alt="deepDive2" src="https://github.com/user-attachments/assets/16e7193d-b35a-41cf-87d9-5ddab37ae33e" />

<img width="1895" height="853" alt="deepDive3" src="https://github.com/user-attachments/assets/cac4feab-95d4-4fd4-91b8-fbb171397d14" />


### 📦 Anomalies
<img width="1887" height="829" alt="Anomalies1" src="https://github.com/user-attachments/assets/e88c042b-54b6-4aff-afe3-bfa482c5aafb" />

<img width="1890" height="789" alt="Anomalies2" src="https://github.com/user-attachments/assets/a08ef31a-0554-4e20-a7f2-217053b68fb3" />


### 📦 Export
<img width="1917" height="701" alt="exports" src="https://github.com/user-attachments/assets/dbc0d286-82cb-4c93-b17c-8720fcd9aa98" />


---

## 🎯 Key Dashboard Modules

### 📊 KPI Dashboard
- Total Revenue 💰  
- Total Profit 📈  
- Units Sold 📦  
- Average Profit Margin 📉  
- Total Orders 🛒  
- Average Order Value 🧾  

---

### 📈 Trends Dashboard
- Monthly Revenue Trend
- Monthly Profit Analysis
- Quarterly Performance
- Revenue by Day of Week

---

### 🗺️ Regional Dashboard
- Revenue share (Pie Chart)
- Revenue vs Profit comparison
- Profit Margin Heatmap

---

### 📦 Product Dashboard
- Revenue by product
- Units vs Profit Margin
- Monthly trends

---

### 🔬 Deep Dive Dashboard
- Price distribution
- Profit margin distribution
- Correlation matrix
- Regression analysis

---

### ⚠️ Anomaly Detection Dashboard
- IQR Method
- Z-Score Method
- Outlier visualization

---

### 📥 Export Dashboard
- Download filtered data
- Download summary report

---

## 📊 Dataset

The dataset contains business transaction records with the following key columns:

- **Order_ID** → Unique order identifier  
- **Order_Date** → Date of transaction  
- **Product** → Product category/name  
- **Region** → Sales region  
- **Units_Sold** → Quantity sold  
- **Price** → Selling price  
- **Cost** → Cost price  

### 🔧 Data Processing
- Converted date into:
  - Year, Month, Quarter, Week, Day
- Handled missing values using median
- Created new features:
  - **Revenue = Units_Sold × Price**
  - **Profit = (Price − Cost) × Units_Sold**
  - **Profit Margin (%)**
  - **Cost Ratio**

---

## 📌 Key Insights

### 💰 Business Performance
- Revenue and profit show **monthly growth trends**
- Some months show **profit dips despite high revenue**, indicating cost issues

### 📦 Product Insights
- Certain products generate **high revenue but low margins**
- High-margin products contribute less volume but more profitability

### 🗺️ Regional Insights
- Few regions dominate overall revenue contribution
- Profit margins vary significantly across regions

### 📈 Trend Insights
- Sales show **seasonality patterns**
- Weekday vs weekend sales variations observed

### 🔬 Statistical Insights
- Strong correlation between **Revenue and Units Sold**
- Moderate relationship between **Price and Profit**

### ⚠️ Anomaly Insights
- Outliers detected in:
  - Price
  - Profit
  - Revenue
- These may represent:
  - Bulk orders
  - Pricing errors
  - Exceptional transactions

---

## ⚙️ Features
- 🔍 Interactive filters
- 📊 Dynamic visualizations
- 📈 KPI tracking
- 📉 Statistical analysis
- ⚠️ Outlier detection
- 📥 Export functionality

---

## 🛠️ Tech Stack
- Python
- Streamlit
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
