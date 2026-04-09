# Powerbi-adventureworks-sales-dashboard
Interactive sales analytics dashboard built in Power BI using AdventureWorks dataset
# 📊 Power BI AdventureWorks Sales Dashboard

🚀 An end-to-end **Business Intelligence (BI) dashboard** built using Power BI and the AdventureWorks dataset.  
This project covers **data cleaning, modeling, DAX calculations, and interactive reporting**.

---

# 🧠 Project Overview

This project demonstrates how raw data can be transformed into **meaningful business insights** using Power BI.

🔍 The dashboard helps analyze:
- Sales performance 💰
- Customer behavior 👥
- Product performance 📦
- Return trends 🔁

---

# 🛠️ Tools & Technologies

- 📊 Power BI Desktop  
- 🧮 DAX (Data Analysis Expressions)  
- 🗂️ AdventureWorks Dataset  

---

# 📌 Step-by-Step Implementation

---

## 🔹 STEP 1 — Data Cleaning & Transformation (Power Query)

✨ In this step, raw data was cleaned and prepared before loading into Power BI.

### 🔧 Tasks Performed:
- Removed unnecessary columns ❌  
- Renamed columns for clarity 🏷️  
- Created new columns:
  - 👤 Full Name  
  - 🎂 Birth Year  
- Checked and corrected data types 🔢  

👉 Tool Used: **Power Query Editor**

---

## 🔹 STEP 2 — Data Modeling

🔗 Built relationships between multiple tables to create a proper data model.

### 🔧 Tasks Performed:
- Connected tables using keys 🔑  
- Created relationships between:
  - Sales ↔ Product  
  - Product ↔ Subcategory  
  - Subcategory ↔ Category  
  - Sales ↔ Customer  
  - Sales ↔ Calendar  
- Ensured all relationships are active ✅  

👉 Result: **Star/Snowflake Schema Model**

---

## 🔹 STEP 3 — DAX Calculations

🧮 Created calculated columns and measures to generate insights.

### 📌 Calculated Columns:
- 📅 Day of Week  
- 🏖️ Weekend / Weekday  
- 👤 Customer Priority  
- 💰 Price Point  
- 🔢 Age Calculation  

### 📊 Measures Created:

#### Sales Metrics:
- 💰 Total Revenue  
- 📦 Total Orders  
- 📈 Quantity Sold  
- 🧾 Total Cost  
- 💵 Total Profit  

#### Time Intelligence:
- 📅 YTD Revenue  
- ⏮️ Previous Month Revenue  
- 🎯 Revenue Target  

#### Advanced:
- 🔁 10-Day Rolling Revenue  
- 📊 % of Orders  

#### Returns Analysis:
- 🔁 Total Returns  
- 📉 Return Rate  
- 🚴 Bike Returns  

👉 Used functions:
- `CALCULATE()`  
- `SUMX()`  
- `DATEADD()`  
- `DATESYTD()`  
- `IF()`  

---

## 🔹 STEP 4 — Dashboard & Visuals

📊 Built an **interactive Executive Dashboard** using visuals.

---

### 📌 Visuals Created:

#### 📊 Matrix Visuals:
- Total Orders by Subcategory  
- Category → Subcategory → Product hierarchy  

#### 🔍 Drill-through Page:
- Detailed Category Analysis  
- Enabled right-click navigation  

#### 📈 KPI Visuals:
- 💰 Monthly Revenue  
- 📦 Monthly Orders  
- 🔁 Monthly Returns  

#### 🎯 Card Visual:
- 🏆 Top Product by Orders (Top N Filter)

#### 🎛️ Filters & Slicers:
- 📅 Date Slicer (interactive filtering)  
- 🌐 Report-level filter  

---

# 📸 Dashboard Preview

![ExecSummary](screenshots/exec-summary.png)  
![Drillthrough](screenshots/category-drillthrough.png)

---

# 📊 Key Insights

- 📈 Revenue trends over time  
- 🏆 Best-selling products  
- 🔁 Return behavior analysis  
- 👥 Customer segmentation  
- 📦 Category-level performance  

---

# 📁 Project Structure


---

# 🎯 What I Learned

- 🔗 Data modeling and relationships  
- 🧮 Writing efficient DAX formulas  
- 📊 Building interactive dashboards  
- 🎛️ Using slicers, filters & drill-through  
- 💡 Turning data into insights  

---

# 👨‍💻 Author

**Sagar Sankhla **

---

# ⭐ If you like this project

Give it a ⭐ on GitHub!
