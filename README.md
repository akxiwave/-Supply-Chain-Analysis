# -Supply-Chain-Analysis
This project analyzes the end-to-end supply chain performance of a company using Power BI, Excel, and SQL.   The objective is to diagnose operational efficiency, identify revenue drivers, evaluate supplier performance, and provide improvement strategies based on data-driven insights.
## 📦 Project Overview

This study evaluates the company’s supply chain across three major product categories:

- **Skincare**  
- **Haircare**  
- **Cosmetics**

The analysis covers:

- Revenue performance  
- Stock turnover  
- Shipping performance  
- Supplier quality  
- Customer demographics  
- Defects & inspections  
- Lead times and logistics efficiency  

---

## 📊 Key Metrics (Dataset Overview)

- **Total SKUs:** 100  
- **Total Quantity Sold:** 46,099 units  
- **Total Revenue:** $577,604.82  
- **Total Profit:** $519,398.76  
- **Gross Margin:** ~89.92%  
- **Average Defect Rate:** 2.28%  
- **Average Shipping Time:** 5.75 days  
- **On-Time Delivery:** 83%  
- **Turnover Rate:** 965.02  

---

## 📂 Project Files

| File | Description |
|------|-------------|
| `CDACL-003-Supply Chain Analysis PPT.pptx` | Final presentation |
| `CDACL-003-Supply Chain Analysis_Project.pbix` | Power BI dashboard |
| `CDACL-003-Supply Chain Analysis_Project.pdf` | Full project documentation |
| `CDACL-003-Supply Chain Analysis_problemstatements.docx` | Problem statements |
| `supplychain_Data_Excelworking.xlsb` | Data cleaning & calculations |
| `Measures and Calculative columns.xlsx` | All DAX formulas |
| `Location_details_States Mapped for Mapchart.csv` | State-to-location mapping |
| `filter Image.jpeg`, `Image 1 for dashboard.jpg` | Dashboard preview images |

---

# 🧩 Problem Statement (From Project Document)

Using the given supply chain dataset, perform:

### ✔ **1. Complete Diagnostic Report**
- Evaluate end-to-end supply chain  
- Identify operational inefficiencies  
- Compare KPIs across products  
- Diagnose defects, delays, stock issues  
- Analyze supplier and shipping performance  

### ✔ **2. Create a Comparative Dashboard (Power BI)**
- Compare Cosmetics, Haircare, Skincare  
- Visualize shipping carriers, fulfillment, defects  
- Build actionable insights for leadership
- # 📑 Dataset Attributes (From Provided Document)

Includes:

- Product Type  
- SKU  
- Price  
- Availability  
- Units Sold  
- Revenue Generated  
- Customer Demographics  
- Stock Levels  
- Shipping Times & Carriers  
- Supplier Name  
- Manufacturing Lead Time  
- Defect Rates  
- Inspection Results  
- Transportation Routes & Costs  

---

# 📈 Dashboard Insights (Power BI)

### **1. Revenue Breakdown**
- **Skincare = Highest revenue ($241.6K → 42%)**  
- **Haircare = $174.4K**  
- **Cosmetics = $161.5K**  

### **2. Customer Demographics Issue**
- 29.97% revenue from **Unknown gender**  
👉 Major data quality problem

### **3. Logistics Performance**
- **Carrier B** handles most revenue & best delivery  
- **On-time delivery = 83%** → MUST improve  
- Average shipping time = 5.75 days  

### **4. Product Performance**
- Skincare: Strong performance, healthy stock turn  
- Haircare: Extremely high turnover (281x) — **possible data error**  
- Cosmetics: Lowest fill rate (73.08%) — **forecasting issue**  

### **5. Defects & Inspections**
- Highest defects from **Haircare (36.86%)**  
- Many inspections still **pending** → slow QC  
# 📌 Key Insights

- Skincare is the **growth engine**  
- Cosmetics is **leaking revenue** due to low fill rate  
- Carrier B is the **most reliable shipping partner**  
- Supplier 3 & 5 are **top performers with >90% margins**  
- 30% customer gender missing → **fix CRM immediately**  
 🛠 Recommendations / Action Plan

### ✔ Priority Fixes
- Clean the **‘Number_of_products_sold’** column  
- Make **Gender** mandatory in order system  
- Fix **Cosmetics** demand forecasting (target >92% fill rate)  
- Improve QC closure (max **48 hours**)  
- Enhance logistics → achieve **>90% on-time delivery**  

### ✔ Strategic Moves
- Invest more in **Skincare** (drives 42% revenue)  
- Shift 80% shipping volume to **Carrier B**  
- Allocate more business to **Supplier 3 & 5**  
- Set up monthly **data quality audits**
- 👨‍💼 Author / Contact

Akshath Shetty

📌 LinkedIn:
https://www.linkedin.com/in/akshath-shetty-updatedprofile/
