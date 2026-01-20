# 📊 Metrocar Analytics Dashboard
SQL + Tableau Analytics Project

# 🔍 Project Overview

This project analyzes the Metrocar ride-sharing platform using SQL for data analysis and Tableau for visualization.

All metrics were calculated directly in the database using PostgreSQL, with queries executed via DBeaver.
The final insights are presented in an interactive Tableau dashboard.
🔗 **[Metrocar Dashboard – Tableau Public](https://public.tableau.com/app/profile/anastasiia.bzhelenko/viz/Project_metrocar/MetrocarDashboard)**

### 📄 Analytical Report (PDF)

A detailed analytical report with key insights and visualizations is available here:  
📄 **[Metrocar Analytics Report (PDF)](Metrocar_Analytics_Report.pdf)**

---

# 🧱 Tech Stack

- PostgreSQL — data storage & querying

- SQL — aggregations, funnels, metrics

- DBeaver — database client for query execution

- Tableau Public — dashboards & visual analytics

---

# 📐 Key Metrics

- Total users

- Successful trips

- Total revenue

- Average revenue per ride

- Funnel conversion & drop-off rates

- Hourly ride demand

---

📊 Tableau Dashboard

The Metrocar Dashboard consists of:

1️⃣ KPI Summary

- Total users
- Completed trips
- Total revenue
![Metrocar Summary](screenshots/Metrocar%20summary.png)

2️⃣ Age Analysis

- User distribution across age groups
- Includes “Unknown” segment
![Age analysis](screenshots/Age%20analysis.png)

3️⃣ Hourly Rides Distribution

- Ride demand by hour of day
- Clear morning and evening peaks
![Hourly rides distribution](screenshots/Hourly%20rides%20distribution.png)

4️⃣ Main Users Funnel

- Download → Signup → Ride Requested → Ride Completed → Review
- Step-by-step drop-off analysis
![Main users funnel](screenshots/Main%20users%20funnel.png)

5️⃣ Rides Funnel

- Ride requested → accepted → completed → paid
- Conversion losses visualized at each stage
![Rides funnel](screenshots/Rides%20funnel.png)

# 📊 Project Status

- This project presents static data visualizations created in Tableau, based on SQL queries executed directly against the database using DBeaver.
- The dashboard summarizes key product and user metrics and is designed for exploratory analysis and stakeholder communication, rather than real-time monitoring.

---

📌 Notes

- The visualizations are static snapshots of the data at the time of analysis
- No data pipelines or automated refresh mechanisms were implemented
- The focus is on analytical thinking, metric selection, and visual storytelling
