# Revenue insights in hospitality domain

This project provides a detailed analysis of hotel bookings using Power BI and a dimensional data model. 
It enables users to explore hotel booking trends, room occupancy, revenue generation, and seasonal patterns in the hospitality sector.

## Dataset

- `dim_date.csv` — Date dimension table, containing full calendar-related data for time-based analysis.
- `dim_hotels.csv` — Hotel dimension, includes hotel names, categories, and other static attributes.
- `dim_rooms.csv` — Room dimension, includes room types, categories, and pricing information.
- `fact_aggregated_bookings.csv` — Fact table containing aggregated booking and revenue metrics per date, hotel, and room type.
- `Insights Hospitality domain.pbix` — Power BI dashboard file for interactive visualizations and insights.

##  Tools Used

- **Power BI** – for dashboard creation and interactive analysis
- **CSV Files** – as the data source
- **DAX / Power Query** – for calculations and data shaping
- **Interactive visuals**: bar, line, pie, KPI cards, matrix

![image](https://github.com/user-attachments/assets/745e2d21-0be2-4a29-aa4c-652f63e5fdfa)

## Insights

###  By Hotel & City:
- **Top Revenue Property**: AtlIQ Exotica, Mumbai (₹117M)
- **Top Cities**: Mumbai & Bangalore dominate the revenue share

###  By Room Category:
- **Luxury Rooms** generate **61.62%** of total revenue
- Business rooms contribute ~38.38%

###  By Time:
- **Weekends** have higher **RevPAR**, **occupancy**, and **ADR** compared to weekdays

###  By Booking Platform:
- Some platforms like **“tripster”** and **“others”** yield higher ADR
- Direct and journal bookings show decent realisation %
