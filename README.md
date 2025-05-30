# 📊 Superstore Sales Dashboard (Tableau)

This project presents an interactive Tableau dashboard built using the Superstore dataset. It offers a dynamic and insightful view into key performance indicators (KPIs) such as Sales, Orders, and Customers over time, with flexible parameter-driven controls.

![Dashboard Preview](https://github.com/Siam-analytics/SuperStoreSales/blob/main/Screenshot%202025-05-30%20200255.png)

## 🔧 Features

### 1. 🧮 Key Performance Indicators (KPIs)
- **Metrics Tracked:** Sales, Orders, Customers.
- **Comparison:** Current year vs. prior year with percentage change.
- **Dynamic Coloring:** Green for positive growth, red for decline.
- **Year Selector:** Controlled via a `SelectDate` parameter to switch between years.

### 2. 📊 Dimension-Based Bar Charts
- **Metrics Visualized:** Sales and Orders.
- **Flexible Dimensions:** Controlled by a `Select Dimension` parameter (e.g., Sub-Category, Category).
- **Prior Year Comparison:** Row-level % growth shown alongside.
- **Top N Filter:** Limit results using a `TopN` parameter (e.g., Top 5, Top 10).

### 3. 📈 Multi-Metric Area Chart
- **Visualized Over Time:** Tracks Sales, Orders, and Customers across years.
- **Interactive Filters:** Dimension and year can be selected dynamically via parameters.

### 4. 🗺️ Regional Map
- **Geographic Insights:** Displays Sales, Orders, and Customers by region/state.
- **Color Intensity:** Represents volume/quantity by state.

### 5. 📊 Column Charts (Yearly Comparison)
- **Breakdown:** Separate charts for Sales, Orders, and Customers.
- **Tooltip Insights:** Includes values for current year, prior year, and % difference.

### 6. 💧 Waterfall Chart
- **Purpose:** Visualizes part-to-whole contribution by sub-category.
- **Measure Flexibility:** Switch between Sales, Orders, and Customers using parameter control.

---

## 🚀 How to Use

1. Download or clone the repository.
2. Open the `.twb` file in Tableau Desktop.
3. Use parameter controls to explore:
   - Different years
   - Top N categories
   - Dimensions (e.g., Category, Sub-Category)
   - Metrics (Sales, Orders, Customers)

---

## 🛠️ Tools Used

- **Tool:** Tableau Desktop
- **Dataset:** Sample Superstore (built-in Tableau dataset)

---

## 📌 Notes

- The dashboard is fully interactive with parameter controls.
- Visualizations are designed to support performance monitoring and trend analysis.

---

## 📬 Contact

If you have any questions or suggestions, feel free to open an issue or reach out!

