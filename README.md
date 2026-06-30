# Madhav Ecommerce Sales Dashboard (Power BI)

An interactive Power BI dashboard built to analyze a full year of ecommerce sales performance — tracking revenue, profit, quantity, and customer-level insights, with quarter-wise filtering for deeper drill-down.

## 📊 Overview

This dashboard consolidates ecommerce business performance across an entire year, covering state-wise sales, category and sub-category breakdowns, payment mode preferences, top customers, and month-by-month profit trends.

## 🖥️ Dashboard Features

### KPI Cards
- **Sum of Amount:** 438K
- **Sum of Quantity:** 5615
- **Sum of Profit:** 37K
- **Sum of AOV (Average Order Value):** 121K

### Filters
- **Quarter Selector:** Qtr 1, Qtr 2, Qtr 3, Qtr 4
- **Dropdown Filter:** Additional slicing option (set to "All" by default)

### Visuals
- **Sum of Amount by State:** Bar chart comparing Maharashtra, Madhya Pradesh, Uttar Pradesh, and Delhi
- **Sum of Quantity by Category:** Donut chart — Clothing (63%), Electronics (21%), Furniture (17%)
- **Sum of Quantity by Payment Mode:** Donut chart — COD (44%), UPI (21%), Debit Card (13%), Credit Card (12%), EMI (10%)
- **Sum of Amount by Customer Name:** Top customers — Harivansh, Madhav, Madan Mohan, Shiva
- **Profit by Month:** Full-year trend (January–December), highlighting profitable vs. loss-making months
- **Sum of Profit by Sub-Category:** Printers, Bookcases, Saree, Accessories, Tables

## 🛠️ Tools & Techniques Used

- **Power BI Desktop** – Report design and data modeling
- **DAX** – KPI measures (Amount, Quantity, Profit, AOV)
- **Slicers & Filters** – Quarter-based and category-based filtering
- **Data Visualization** – Cards, bar charts, donut charts, and trend charts for monthly profit

## 📁 Repository Contents

```
├── Madhav_Ecommerce_Sales_Dashboard.pbix   # Power BI report file
├── images/                                 # Dashboard screenshots
└── README.md
```

## 🚀 How to Use

1. Clone or download this repository.
2. Open `Madhav_Ecommerce_Sales_Dashboard.pbix` in [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3. Refresh the data source if connected to a live dataset, or explore using the embedded sample data.
4. Use the Quarter buttons and dropdown filter to interact with the visuals.

## 📌 Key Insights

- Clothing remains the dominant category by quantity sold, at 63% of all sales.
- COD continues to be the most preferred payment mode at 44%, followed by UPI at 21%.
- Maharashtra leads all states in total sales amount.
- Harivansh is the top customer by purchase amount across the year.
- Several months (May, June, August, September, December) show negative profit, signaling potential cost or discounting issues worth investigating.
- Printers and Bookcases are the top profit-generating sub-categories.

## 📷 Screenshots

dashboard screenshot to an `images/` folder and reference it here, for example:

```markdown
<img width="883" height="499" alt="Mahadev dashboard snapshot" src="https://github.com/user-attachments/assets/b0d70b95-1a07-4705-8235-502427fa5be7" />

```

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
