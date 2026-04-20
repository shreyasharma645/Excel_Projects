# 🍕 Pizza Place Sales Dashboard

An end-to-end Excel dashboard analyzing a pizza restaurant's full-year 2015 sales data — covering revenue trends, product performance, customer ordering patterns, and a 2016 revenue forecast.

---

## 📊 Project Overview

This project transforms raw pizza order data into a fully interactive Excel dashboard. It answers key business questions: Which pizzas make the most money? When do customers order? What size do they prefer? And what can we expect in 2016?

---

## 📁 File Structure

| Sheet | Description |
|---|---|
| `DATA` | Raw cleaned dataset — 48,620 rows of order-level transaction data |
| `TABLE` | PivotTables powering all dashboard visuals |
| `FORECAST SHEET` | Time-series revenue forecast for Jan–Jun 2016 with confidence bounds |
| `DASHBOARD` | Interactive dashboard with slicers, KPI cards, and charts |

---

## 🔢 Key Numbers

| Metric | Value |
|---|---|
| Total Revenue | $817,860 |
| Total Orders | 21,350 |
| Pizzas Sold | 49,574 |
| Avg Order Value | $38.31 |
| Avg Pizzas per Order | 2.32 |
| Pizza Types | 32 |
| Date Range | Jan 1 – Dec 31, 2015 |

---

## 📌 Key Findings

- **Best month:** July ($72,558) — worst month: October ($64,028)
- **Busiest day:** Friday ($136,074) — slowest: Sunday ($99,204)
- **Peak hours:** 12 PM–1 PM drive the highest order volume
- **Top pizza:** The Thai Chicken Pizza ($43,434)
- **Worst pizza:** The Brie Carre Pizza ($11,589) — candidate for menu removal
- **Best size:** Large (L) = 46% of total revenue ($375,319)
- **Dead weight:** XXL size generated only $1,007 all year
- **Categories:** Classic leads (27%), followed closely by Supreme, Chicken, and Veggie

---

## 🛠️ Tools & Features Used

- **Excel PivotTables** — for dynamic slicing across category, size, day, month, and hour
- **Slicers** — filter dashboard by Category, Size, and Veg/Non-Veg
- **Charts** — line (monthly trend), bar (top 5, day, hour), pie (category), horizontal bar (size)
- **KPI Cards** — total revenue, orders, quantity, avg order value
- **Excel Forecast Sheet** — built-in exponential smoothing with upper/lower confidence intervals
- **Conditional Formatting** — highlights peak and low performers

---

## 📈 2016 Forecast

Using Excel's built-in time-series forecasting (ETS model), projected monthly revenue for Jan–Jun 2016 ranges between **$64K–$68K** per month, consistent with 2015 performance — indicating a stable, seasonal business with no strong growth trend.

---

## 💡 Business Recommendations

1. **Cut or rework the Brie Carre** — lowest revenue pizza all year
2. **Push Large size upsells** — already 46% of revenue, highest margin opportunity
3. **Staff up on Fridays 12–1 PM** — peak revenue window every week
4. **Drop XXL from the menu** — $1,007 annual revenue doesn't justify the inventory cost
5. **Run promos in Oct–Dec** — consistently the weakest quarter

---

## 📂 Dataset

The raw data includes:
- Order ID, Order Details ID
- Pizza name, type, size, price
- Date and time of order
- Category (Classic / Supreme / Chicken / Veggie)
- Ingredients
- Veg / Non-Veg classification

---

## 🏷️ Topics

`excel` `data-analytics` `dashboard` `pivot-tables` `data-visualization` `sales-analysis` `forecasting` `business-intelligence` `excel-dashboard` `pizza`
