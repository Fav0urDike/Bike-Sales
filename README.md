# 🚴‍♂️ Sprocket Central Pty Ltd – Customer & Bike Purchase Analysis

![](https://github.com/Fav0urDike/Bike-Sales/blob/main/bicycles-for-sale-in-sports-store-photo.jpg)
---
## 🧠 Objective

To analyze a new customer dataset and determine which **wealth segment** Sprocket Central Pty Ltd should target, using demographic, tenure, and purchasing behavior data.

---

## 📁 Dataset Overview

- **Source**: Shared via WhatsApp by a friend  
- **Sheets**:  
  - `Title`  
  - `New Customer List` (1,000 rows × 23 columns)
- **Contains**: Customer demographic info, purchase history, job industry, tenure, and wealth segments

---

## 🛠️ Tools & Skills Used

| Tool | Description |
|------|-------------|
| Microsoft Excel | Initial cleaning, table creation, column removal |
| Power Query | Data transformation, custom column creation |
| Power BI Desktop | Dashboard development, visualization, and analysis |

---

## 🔍 Problem Statements Addressed

1. Total number of customers  
2. Total number of bikes purchased  
3. State with the most bike purchases  
4. Age category that should be prioritized  
5. Job industry with the most customers and purchases  
6. Tenure group contributing most to bike purchases  
7. Gender with highest bike purchase  
8. **Primary Wealth Segment** to target for marketing

---

## 🧼 Data Cleaning & Transformation Steps

- Converted raw data to Excel Table format  
- Removed non-relevant columns  
- Imported into Power Query for transformation  
- Created custom columns:
  - **Birth Year** from Date of Birth
  - **Age** = 2025 - Birth Year
  - **Age Groups** based on WHO standards
  - **Tenure Groups** using nested IF logic (`<6 months`, `6–9 months`, `9+ months`)
- Replaced missing values with `"Not Specified"`

|Dirty Data    | Power Query       | Clean Data|
|--------------|-------------------|-----------|
|![](https://github.com/Fav0urDike/Bike-Sales/blob/main/Unclen.png)         |![](https://github.com/Fav0urDike/Bike-Sales/blob/main/power%20query.png)              |![](https://github.com/Fav0urDike/Bike-Sales/blob/main/clen.png)

---

## 🧱 Data Modeling

- No complex modeling needed; single flat table used for analysis.

---

## 📊 Key Insights

| Metric | Result |
|--------|--------|
| **Total Customers (Cleaned)** | 983 |
| **Total Bikes Purchased** | 49,000 |
| **Top State** | New South Wales |
| **Top Age Group** | Pre-retirees (46–60) |
| **Top Wealth Segment** | Mass Segment |
| **Top Job Industry** | Financial Industry |
| **Top Tenure Group** | 9+ Months tenure purchased more bike |
| **Top Gender** | Female |

## 📸 Dashboard Preview
![](https://github.com/Fav0urDike/Bike-Sales/blob/main/Dashboard.png)
![](https://github.com/Fav0urDike/Bike-Sales/blob/main/Dashboard%20High%20Net%20Worth.png)
![](https://github.com/Fav0urDike/Bike-Sales/blob/main/Dashboard%20%20Affluent.png)
![](https://github.com/Fav0urDike/Bike-Sales/blob/main/Dashboard%20Mass%20Customer.png)

---

## 🎯 Recommendation

Sprocket Central Pty Ltd should focus marketing and retention efforts on:

- **Wealth Segment**: Mass  
- **Age Group**: Pre-retirees (46–60)  
- **Tenure Group**: 9+ months  
- **Job Industry**: Financial Industry  
- **Gender**: Female  
- **Location**: New South Wales  

This segment shows the highest engagement, purchase activity, and long-term value.

---

## ✅ Conclusion

Using Excel, Power Query, and Power BI, customer data was successfully transformed and analyzed. Based on the findings, the **Mass wealth segment of pre-retiree females in the financial industry living in New South Wales** represents the most profitable audience for future sales and marketing initiatives.

---


---

## 📂 Project Files

- [📥 Download Power BI Report (.pbix)](https://github.com/Fav0urDike/Bike-Sales/raw/main/Prj%204.pbix) – Power BI dashboard file  
- [📥 Download Cleaned Excel File (.xlsx)](https://github.com/Fav0urDike/Bike-Sales/raw/main/KPMG_VI_New_raw_data_update_final.xlsx) – Excel data transformation

  
---

## 🗂️ Author

**Favour Dikejiorah Tochukwu**

---

![](https://github.com/Fav0urDike/Bike-Sales/blob/main/thank-you-words-on-notepad-and-office-supplies-free-photo.jpg)
