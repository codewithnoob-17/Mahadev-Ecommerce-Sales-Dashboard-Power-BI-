# Madhav Ecommerce Sales Dashboard (Power BI)

An interactive Power BI dashboard analyzing ecommerce sales performance, covering revenue, quantity, profit, and customer-level insights, with quarter-wise filtering for deeper drill-down.

## 📊 Overview

This dashboard provides a consolidated view of ecommerce business performance — tracking sales by state, category, sub-category, payment mode, and top customers — with the ability to slice data by quarter.

## 🖥️ Dashboard Features

### KPI Cards
- **Sum of Amount:** 161K
- **Sum of Quantity:** 2008
- **Sum of Profit:** 26K
- **Sum of AOV (Average Order Value):** 44K

### Filters
- **Quarter Selector:** Qtr 1, Qtr 2, Qtr 3, Qtr 4
- **Dropdown Filter:** Additional slicing option (e.g., region/category — set to "All" by default)

### Visuals
- **Sum of Amount by State:** Bar chart comparing Maharashtra, Madhya Pradesh, Delhi, and Uttar Pradesh
- **Sum of Quantity by Category:** Donut chart — Clothing (63%), Electronics (19%), Furniture (18%)
- **Sum of Quantity by Payment Mode:** Donut chart — COD (44%), Credit Card (11%), EMI (12%), Debit Card (16%), UPI (18%)
- **Sum of Amount by Customer Name:** Top customers — Harivansh, Shiva, Madhav, Sarita
- **Profit by Month:** Bar chart for January, February, and March
- **Sum of Profit by Sub-Category:** Printers, Phones, Accessories, Bookcases, Saree

## 🛠️ Tools & Techniques Used

- **Power BI Desktop** – Report design and data modeling
- **DAX** – KPI measures (Amount, Quantity, Profit, AOV)
- **Slicers & Filters** – Quarter-based and category-based filtering
- **Data Visualization** – Cards, bar charts, donut charts for category and payment mode distribution

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

- Clothing dominates quantity sold, making up 63% of all category sales.
- COD is by far the most preferred payment mode at 44%, followed by Credit Card and Debit Card.
- Maharashtra leads in sales amount among the four states analyzed.
- Harivansh is the top customer by purchase amount, well ahead of the next closest customer.
- Printers and Phones are the highest profit-generating sub-categories.

## 📷 Screenshots

 an `images/` folder and reference it here, for example:

```markdown
<img width="888" height="498" alt="Mahadev Dashboard" src="https://github.com/user-attachments/assets/4ab2893e-c61d-47e9-9e12-e838f907b161" />

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
