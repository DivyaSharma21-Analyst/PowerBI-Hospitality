# Power BI-AtliQ Hospitality Analysis

## 🔗 Live Dashboard
👉 [Click here to view the interactive dashboard](https://app.powerbi.com/view?r=eyJrIjoiNGQ5ZDIzMjQtOTZmMi00MTBiLThkYmEtODQ2ZjI0YTdiYTEyIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9 )

## 🖼️ Dashboard Preview

![Dashboard Preview](./dashboard-preview.png)

## 📘 Project Overview
AtliQ Grands is a luxury hotel chain with properties in major Indian cities like Mumbai, Delhi, Bangalore, and Hyderabad. Due to rising competition and internal decision-making issues, the company experienced a ~20% drop in revenue and market share. This project uses Power BI to analyze 3 months of booking and operational data to uncover performance gaps and support data-driven recovery strategies.

---

## 🎯 Objective
To build an interactive and scalable Power BI dashboard that enables:
- Root cause analysis of declining revenue and occupancy
- Comparison of performance across cities, booking platforms, and room types
- Tracking of hospitality-specific KPIs to assist the Revenue Management team

---

## 🧰 Tools & Technologies
- Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- DAX Studio (for performance optimization)
- Excel / CSV (data sources)

---

## 📂 Data Sources
- `dim_date.csv`
- `dim_hotels.csv`
- `dim_rooms.csv`
- `fact_bookings.csv`
- `fact_aggregated_bookings.csv`

All data was integrated using folder import and modeled using a star schema.

---

## 📊 KPIs Tracked
- **RevPAR**: Revenue per Available Room  
- **ADR**: Average Daily Rate  
- **Occupancy %**  
- **Realisation %** (Revenue Realised ÷ Revenue Earned)  
- **Cancellation %**  
- **DSRN**: Daily Sellable Room Nights  
- **DBRN**: Daily Booked Room Nights  
- **DURN**: Daily Utilized Room Nights  

---

## 📈 Dashboard Features
- Overview of KPIs with week-over-week trends
- City-wise and property-level performance analysis
- Booking platform comparison (Realisation % and ADR)
- Room category trends
- Drill-down capability and dynamic filters for day type, platform, city, etc.

---

## 💡 Key Insights
- Mumbai generated the highest revenue (~₹669M)
- Direct Channel 2 had the highest ADR and Realisation %, making it a strategic opportunity
- Weekend bookings had higher Occupancy % but flat Realisation %
- Elite rooms were the most booked but also had the highest cancellation loss
- Total cancellation losses amounted to ~₹298M
- AtliQ Exotica (Mumbai) led across most metrics
- Week 24 saw the highest weekly revenue spike (~₹139.6M)

---

## 📌 Outcome
The dashboard provided a unified view of business performance and supported strategic planning to achieve a targeted 20% recovery in revenue and market share.

```
