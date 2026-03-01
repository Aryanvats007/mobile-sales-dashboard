# 📱 Mobile Sales Analytics Dashboard 2025

> A comprehensive Excel dashboard built from "500" real mobile sales records covering 10 brands, 10 countries, and 12 months of 2025 data.

 📊 Dashboard Overview

| Sheet | Description |
| 📊 KPI Dashboard | Total Revenue, Units, Ratings + Monthly Trend Chart |
| 📱 Brand Analysis | Brand leaderboard with Revenue, Units & Pie Charts |
| 🌍 Country Analysis | Geographic revenue breakdown with bar & pie charts |
| 📦 Product Analysis | Top 15 models, Storage mix, Payment methods |
| 📋 Raw Data | All 500 records with filters enabled |

💡 Key Insights

- 💰 ""Total Revenue:"" $4,639,641
- 📦 ""Total Transactions:"" 500 across 10 brands
- 🏆 ""Top Brand:"" Motorola ($497,446 revenue)
- ⭐ ""Avg Customer Rating:"" 3.96 / 5.0
- 🌍 ""Markets:"" USA, UK, India, Germany, France, Australia, Canada, UAE, Saudi Arabia, Pakistan

 📁 Repository Structure

```
mobile-sales-dashboard/
│
├── Mobile_Sales_Dashboard_2025.xlsx   ← Main Excel Dashboard (5 sheets)
├── synthetic_mobile_sales_2025.csv    ← Raw source data (500 records)
└── README.md                          ← This file
```

 🔍 Data Fields

| Column | Description |
|--------|-------------|
| Sale_ID | Unique transaction ID |
| Brand | Mobile brand (Apple, Samsung, Xiaomi, etc.) |
| Model | Specific model name |
| Country | Country of sale |
| Storage | Storage variant (64GB/128GB/256GB/512GB) |
| Color | Phone color |
| Price_USD | Selling price in USD |
| Units_Sold | Number of units in transaction |
| Revenue_USD | Total revenue (Price × Units) |
| Customer_Rating | Rating out of 5.0 |
| Payment_Method | Cash / Credit Card / Debit Card / Installments / Online Payment |
| Sale_Month | Month number (1–12) |
| Sale_Year | Year (2025) |


 📈 Charts & Visualizations

- 📉 Line Chart — Monthly Revenue & Units Sold Trend
- 📊 Bar Chart — Revenue by Brand (vertical)
- 📊 Bar Chart — Units Sold by Brand (horizontal)
- 🥧 Pie Chart — Revenue Share by Brand
- 📊 Bar Chart — Revenue by Country
- 🥧 Pie Chart — Country Revenue Share
- 📊 Horizontal Bar — Top 15 Models by Revenue
- 🥧 Pie Chart — Storage Mix (64GB/128GB/256GB/512GB)
- 🥧 Pie Chart — Payment Method Distribution


 🛠️ Tools Used

- Microsoft Excel — Dashboard, charts, formulas
- Excel Formulas — `SUMIF`, `COUNTIF`, `AVERAGEIF`, `RANK`, `IF`, `SUM`, `AVERAGE`
  
 👤 About

Created as part of a "Data Analytics Portfolio" to demonstrate:
- Data cleaning and aggregation
- KPI tracking and visualization
- Excel dashboard design
- Business insights from sales data
