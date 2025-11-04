# 🚗 Car Sales Insights Dashboard  
**PGDM (AI & Data Science) — Trimester II Project**  
**Author:** Akhilesh Kakarla  
**Tools Used:** Python (Pandas, Matplotlib), Power BI, SQL  

---

## 📘 Project Overview  
This project demonstrates a **data-driven sales analysis** pipeline — from raw data to business insights.  
Using the **Car Price Dataset**, we built an **end-to-end analytics system** integrating:
- Exploratory Data Analysis (EDA) in Python  
- SQL-based data querying  
- Interactive Power BI Dashboard for decision-making  

---

## 🎯 Objective  
To analyze and visualize **car pricing trends, sales performance, and customer insights** using real-world data.  
The dashboard provides a unified view of:
- Price variations by **make, model, and fuel type**
- **Yearly trends** in car prices
- **Condition-based** price distributions
- Top performing **brands and regions**

---

## 🧰 Tools & Technologies  
| Component | Tool | Purpose |
|------------|------|----------|
| Database | PostgreSQL / SQLite | Store and query raw sales data |
| Data Analysis | Python (Pandas, NumPy, Matplotlib, Seaborn) | EDA and trend analysis |
| Visualization | Power BI | Interactive dashboard & KPIs |
| Documentation | Markdown | README + project presentation |

---

## 🗂️ Folder Structure  
car_sales_insights_project/
│
├── car_price.csv # Original dataset
├── car_sales_insights.ipynb # Jupyter notebook (Python analysis)
├── car_price_dashboard.pbix # Power BI dashboard
├── avg_price_by_make.csv # Optional summary data
├── avg_price_by_year.csv # Optional summary data
├── condition_counts.csv # Optional summary data
├── sales_insights.sql # Optional SQL queries
├── README.md # Documentation (this file)
└── screenshots/ # Dashboard preview images
├── dashboard_overview.png
└── trend_chart.png


---

## 🔍 Data Description  
| Column | Description |
|---------|--------------|
| `Car_Name` | Car brand and model |
| `Year` | Year of manufacture |
| `Selling_Price` | Price at which the car was sold |
| `Present_Price` | Current market price |
| `Kms_Driven` | Total kilometers driven |
| `Fuel_Type` | Type of fuel (Petrol/Diesel/CNG) |
| `Seller_Type` | Dealer or Individual |
| `Transmission` | Manual/Automatic |
| `Owner` | Number of previous owners |

---

## 📈 Key Insights  
✅ **Average Price by Brand:** Luxury brands like BMW & Audi have the highest resale prices.  
✅ **Fuel Type Comparison:** Diesel cars show slightly higher resale value than Petrol ones.  
✅ **Condition Analysis:** Cars with fewer kilometers retain higher prices.  
✅ **Yearly Trend:** Overall selling price shows gradual depreciation with age.  
✅ **Seller Insights:** Dealers sell at slightly higher margins than individuals.  

---

## 📊 Power BI Dashboard Features  
**Visuals included:**
- KPI Cards → Total Sales, Average Price, Profit Margin  
- Bar Chart → Average Selling Price by Brand  
- Line Chart → Price Trend by Year  
- Donut Chart → Fuel Type Share  
- Table → Top 10 Most Expensive Cars  
- Filters → Transmission, Year, Seller Type  

---

## ⚙️ How to Run the Project  

### 🐍 Step 1: Python (Jupyter Notebook)
1. Open `car_sales_insights.ipynb`  
2. Run all cells to generate summary CSVs:
   - `avg_price_by_make.csv`
   - `avg_price_by_year.csv`
   - `condition_counts.csv`

### 🗄️ Step 2: SQL (Optional)
1. Import `car_price.csv` into PostgreSQL or SQLite  
2. Run `sales_insights.sql` to explore KPIs and regional trends  

### 📊 Step 3: Power BI Dashboard
1. Open **Power BI Desktop**  
2. Load `car_price.csv` as data source  
3. Create visuals using the above fields  
4. Save as `car_price_dashboard.pbix`  

---

## 🧠 Learning Outcomes  
- Applied **SQL joins, aggregations, and KPIs** for data summarization  
- Built **Python-based EDA** workflow with visualization  
- Designed **interactive Power BI dashboard** for decision support  
- Understood how to combine **data science + business analytics** effectively  

---

## 💡 Future Enhancements  
- Automate data refresh from SQL to Power BI  
- Add predictive model for car price estimation  
- Build web dashboard (Streamlit or Flask integration)  

---

## 📸 Dashboard Preview  
*(Add these screenshots in your `screenshots/` folder and link them below)*

![Dashboard Overview](screenshots/dashboard_overview.png)
![Trend Chart](screenshots/trend_chart.png)

---

## 🏁 Conclusion  
This project transforms raw automobile sales data into actionable insights for decision-makers.  
It demonstrates **end-to-end analytics workflow** — from SQL querying to Power BI storytelling — showcasing both **technical and business intelligence** skills.

---

## 👨‍💻 Author  
**Akhilesh Kakarla**  
PGDM (Artificial Intelligence & Data Science)  
Ashoka School of Business  
📧 [kakarlaakhilesh13@gmail.com]  
📍 India  

---
