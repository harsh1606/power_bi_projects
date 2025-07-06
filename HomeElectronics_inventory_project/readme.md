# 📦 Home Electronics Inventory Dashboard (Power BI Project)

This repository contains a Power BI dashboard that helps visualize, monitor, and analyze inventory metrics across multiple SKUs and warehouse locations for a home electronics business. The insights generated from the dashboard assist stakeholders in maintaining healthy stock levels and optimizing product availability.

---

## 📁 Repository Structure

├── HomeElectronics_InventoryData_Dashboard.pbix # Power BI report file
├── data_model.png # Data model relationship diagram
├── data/
│ ├── HomeElectronics_InventoryData (1).xlsx
│ ├── Supplier_Data.xlsx
└── README.md # Project documentation



---

## 🎯 Objective

To build an interactive Power BI dashboard that provides visibility into:
- Inventory quantity by product, category, and warehouse
- Stock trends over time
- Reorder point monitoring
- Overall product availability across locations

---

## 📌 Key KPIs & Metrics

| KPI                     | Description                                         |
|------------------------|-----------------------------------------------------|
| **Quantity On Hand**   | Total units available across all products           |
| **Quantity Sold**      | Cumulative quantity sold                            |
| **Reorder Points**     | Sum of reorder thresholds across all products       |
| **Total Products**     | Unique products tracked                             |
| **Total Warehouses**   | Number of warehouse locations in the dataset        |

---

## 📈 Dashboard Visuals

- **Line Chart**: Quantity On Hand by Date (Jan–Dec 2024)
- **Pie Chart**: Quantity by Category (Smartphones, TVs, Tablets, etc.)
- **Bar Chart**: Quantity by Product
- **Bar Chart**: Quantity by Warehouse
- **Slicers**: Year, Month Number, Location, Category
- **KPI Cards**: Summary metrics at the top

---

## 🧠 Insights Enabled

- Identify top-performing or understocked products
- Detect seasonal stock fluctuations
- Track performance of warehouses
- Monitor items below reorder thresholds (suggested future addition)

---

## 🛠 Tools & Technologies

- **Power BI** for visualization and dashboarding
- **DAX** for calculated measures and time intelligence
- **Star Schema** data modeling approach
- Custom Calendar Table for consistent date filtering

---

## 🔧 Future Improvements

- Add conditional formatting to flag stockouts or low inventory
- Introduce Inventory Turnover Ratio metric
- Enable drillthrough by warehouse or product
- Add YoY or MoM comparison for sales trends


---

## 🤝 Connect

**Author:** Harsh Kumar Tyagi  
Feel free to connect on [LinkedIn](https://www.linkedin.com/in/harshtyagi1606/)
