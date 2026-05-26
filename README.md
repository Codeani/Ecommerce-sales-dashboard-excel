# 🛒 E-Commerce Sales Dashboard — Advanced Excel Project

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)
![Sheets](https://img.shields.io/badge/Sheets-6-blue?style=for-the-badge)
![Formulas](https://img.shields.io/badge/Formulas-323-orange?style=for-the-badge)

## 📌 Introduction
A fully functional E-Commerce Sales Dashboard built using **Microsoft Excel**.
The project tracks 50 online orders across **6 months (Jan–Jun 2024)**,
covering 7 product categories and 5 regions of India.

---

## ✨ Features
- 📊 Live KPI Dashboard (Revenue, AOV, Return Rate, etc.)
- 🔍 Interactive Order Lookup Tool using INDEX-MATCH
- 📅 Month-on-Month Sales Trend with Line Chart
- 🏆 Product Performance Ranking with Color-Scale
- 📈 4 Dynamic Charts (auto-update with data)
- 🧹 Clean structured data with 14 fields per order

---

## 🗂️ Project Structure

| File/Folder | Description |
|---|---|
| `workbook/` | Main Excel file with all 6 sheets |
| `report/` | Full project documentation (Word) |
| `screenshots/` | Dashboard and sheet screenshots |

---

## 📋 Workbook — Sheet Breakdown

| Sheet | What It Does |
|---|---|
| 📋 Orders Data | 50 rows × 14 columns raw transaction data |
| 📊 Summary & KPIs | 8 live KPIs + category/region/payment analysis |
| 📈 Dashboard | 4 dynamic charts — bar, pie, line |
| 🔍 Product Lookup | Type Order ID → all details auto-populate |
| 📅 Monthly Trend | COUNTIFS + SUMPRODUCT month-wise breakdown |
| 🏆 Top Products | 35 products ranked with performance badges |

---

## ⚙️ Tech Stack / Excel Features Used

| Feature | Purpose |
|---|---|
| `SUMIF` | Category & region-wise revenue |
| `COUNTIF / COUNTIFS` | Order counting by status & month |
| `INDEX-MATCH` | Dynamic order lookup |
| `IFERROR` | Error-safe formula output |
| `SUMPRODUCT` | Monthly revenue aggregation |
| `Nested IF` | Performance badge (High/Medium/Low) |
| `Conditional Formatting` | Color-scale on revenue column |
| `Charts` | Column, Bar, Pie, Line (all dynamic) |

---

## 🚀 How to Use

1. Download `workbook/Ecommerce_Sales_Dashboard.xlsx`
2. Open in **Microsoft Excel 2016 or later**
3. Go to **📋 Orders Data** — view all 50 transactions
4. Go to **📊 Summary & KPIs** — see live KPIs update
5. Go to **🔍 Product Lookup** — type any Order ID in yellow cell
6. Go to **📈 Dashboard** — view 4 interactive charts

---

## 📊 Screenshots

### Dashboard
![Dashboard](screenshots/dashboard.png)

### KPI Summary
![KPI](screenshots/kpi_summary.png)

### Product Lookup Tool
![Lookup](screenshots/lookup_tool.png)

### Monthly Trend
![Trend](screenshots/monthly_trend.png)

---

## 📈 Key KPIs Tracked
- Total Revenue (₹)
- Average Order Value (₹)
- Total Units Sold
- Return Rate (%)
- Cancelled Orders
- Category-wise Revenue Share (%)
- Region-wise Sales Breakdown
- Month-on-Month Growth (%)

---

## 📄 Documentation
Full project report available in `report/Ecommerce_Project_Report.docx`

Covers:
- Project Objective
- Dataset Description (14 fields explained)
- Tools & Technologies
- Formula explanations
- Learning Outcomes

---

## 👤 Author
     Anirban Dey
Advanced Excel Training Program
📅 Submitted: May 2025
