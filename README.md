# RFM Reseller Segmentation

## 📊 Project Overview
Customer segmentation dashboard using RFM (Recency, Frequency, Monetary) analysis. Built with BigQuery for backend logic and Looker Studio for interactive visualization. Enables dynamic filtering and performance analysis across 600+ resellers.

## 🛠️ Tools & Technologies
- **BigQuery**: SQL-based segmentation logic and schema control
- **Looker Studio**: Dashboard visuals, slicers, and interactivity
- **Google Sheets / CSV**: Initial data source

## 🧠 RFM Logic
- **Recency**: Days since last purchase, anchored to 2014
- **Frequency**: Total transactions per reseller
- **Monetary**: Total revenue per reseller
- Tier labels (`High`, `Medium`, `Low`) assigned via SQL CASE logic

## 📈 Dashboard Features
- **Bubble Chart**: Recency vs. Monetary, bubble size = Frequency  
  _Title: Visualizing Reseller Value: Recency vs. Monetary, Frequency as Bubble Size_
- **Table View**: ResellerKey with RFM metrics and segmentation labels
- **Bar Charts**: Distribution of Recency, Frequency, and Monetary segments
- **Slicers**: Interactive filters for RecencyLabel, FrequencyLabel, MonetaryLabel

## 🔗 Live Dashboard
[View Dashboard](https://lookerstudio.google.com/reporting/dfc3604e-f1a8-4336-ad37-3e56445610a4)

## 📸 Screenshots
Screenshots available in `/screenshots` folder:
- `bubble_chart.png`
- `table_view.png`
- `slicers.png`
- `bar_charts.png`
