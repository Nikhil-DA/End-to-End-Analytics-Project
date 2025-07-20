---

# 📊 Sales Dashboard Analytics Project

## 🔍 Overview

This project focuses on transforming raw sales data into a meaningful and interactive dashboard using **Python** for cleaning and **Power BI** for visualization. It provides a comprehensive overview of sales performance, customer behavior, regional trends, and product/channel performance.
![image alt](https://github.com/Nikhil-DA/End-to-End-Analytics-Project/blob/main/sales-%20problem%20statement.png)

---

## 📁 Project Structure

### ✅ Raw Data

* Source: Excel file with 6 sheets
 ![image alt](https://github.com/Nikhil-DA/End-to-End-Analytics-Project/blob/main/sales-%20raw%20csv.png)

### 🧹 Data Preparation (Python - Pandas)

* importing necessary libs
  ![image alt](https://github.com/Nikhil-DA/End-to-End-Analytics-Project/blob/main/sales-%20libs%20and%20visual%20setup.png)
* * Combined 4 sheets into a single dataset
* Cleaned nulls, renamed columns, standardized formats
  ![image alt](https://github.com/Nikhil-DA/End-to-End-Analytics-Project/blob/main/sales-%20clean%20and%20prep.png)
* Feature engineered fields (Profit Margin %, Revenue per Order etc)
  
* EDA for insights(some the many are shown below)
  ![image alt](https://github.com/Nikhil-DA/End-to-End-Analytics-Project/blob/main/sales-eda%20graph.png)
  ![image alt](https://github.com/Nikhil-DA/End-to-End-Analytics-Project/blob/main/sales-eda%20graph2.png)
* Exported cleaned file

### 📈 Power BI Dashboard

Created an interactive **4-page dashboard**:

1. **Page 1 – Summary (Home)**
   Overview of dashboard sections with navigation
2. **Page 2 – Executive Overview**
   Key KPIs: Revenue, Orders, Profit Margin %, RPO
   Monthly trends, top/bottom products, region-wise sales
3. **Page 3 – Product & Channel Performance**
   Deep dive into product performance and sales by channel
4. **Page 4 – Customer & Region Analysis**
   Customer count, behavior, and map-based regional sales insights

---


## 🧱 Project Workflow

```
Raw Excel Data (6 sheets)
       ⬇
Python (Pandas) Cleaning & Merging
       ⬇
EDA + Export Cleaned File
       ⬇
Power BI Dashboard (4 Pages)
```

---

## 🚀 How to Run the Project

1. **Download the Repository**

   * Clone the repo or download as ZIP
   * Locate the Power BI file: `SalesDashboard.pbix`

2. **Open in Power BI Desktop**

   * Double-click `.pbix` file
   * Wait for visuals to load

3. **(Optional) Run Python Script**

   * Python script `/scripts` folder
   * It reads the 4 Excel sheets → cleans → merges → outputs

4. **Interact with the Dashboard**

   * Filter by Region, Channel, Month, Year
   * Navigate across 4 dashboard pages

---


## 💡 Tools & Tech

* **Python** (pandas, matplotlib)
* **Power BI**
* **Excel**

---

## 🤝 Credits

Created by \Nikhil Chauhan as part of a portfolio project.
Inspired by real-world sales dashboard use cases 

---

## 📄 License

MIT License – free to use with attribution.

---

