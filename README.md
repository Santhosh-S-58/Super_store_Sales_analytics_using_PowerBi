# 📊 Task 8 – Simple Sales Dashboard (Data Analyst Internship)

## 🔍 Objective
The goal of this task is to create a basic interactive sales dashboard using Power BI. The dashboard visualizes sales performance by **product category**, **region**, and **month**, helping identify trends and top-performing segments.

---

## 📁 Dataset
**File:** `Superstore_Sales.csv`  
**Fields Used:**  
- Order Date  
- Sales  
- Region  
- Category  
- Product Name (optional)  

---

## 🛠 Tools Used
- **Power BI Desktop** (Data visualization and dashboard design)  
- **Python + Pandas** (for optional data cleaning)

---

## 📈 Dashboard Features

1. **Line Chart** – Sales trend over time (monthly)
2. **Bar Chart** – Sales distribution by region
3. **Donut Chart** – Category-wise sales contribution
4. **KPI Cards** – Total sales and total orders
5. **Table** – Product-wise sales breakdown with conditional formatting
6. **Slicer** – Interactive filter by region

---

## 🧠 Key Insights

- 🟢 *Sales peaked in November 2023, likely due to holiday season demand.*
- 🟢 *The West region contributed the highest sales across all months.*
- 🟢 *Technology category was the top-performing segment in terms of revenue.*
- 🟢 *Office Supplies showed the lowest average order size among all categories.*

---

## 🧹 Data Cleaning (Python Script)

Before importing into Power BI, the dataset was cleaned using a Python script to:
- Remove null and duplicate values
- Convert `Order Date` to datetime
- Create a new `Month-Year` column for trend analysis

**File:** `clean_data.py`

---

## 📸 Deliverables

- `Cleaned_Superstore_Sales.csv` – Cleaned data file
- `SalesDashboard.pbix` – Power BI dashboard file
- `Sales_Insights_Task8.txt` – 3–4 key insights summary
- `Dashboard_Screenshot.png` – Exported view of the dashboard

---

## ✅ How to View the Dashboard

1. Open `SalesDashboard.pbix` in Power BI Desktop
2. Use slicers to explore sales by region and category
3. Hover over visuals for detailed tooltips

---

## 🚀 Author

**Santhosh S**  
Intern – Data Analyst Track  
Elevate Labs Internship Program  

