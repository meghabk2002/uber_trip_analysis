# 🚖 Uber Trip Analysis - Power BI Dashboard

## 📌 Project Overview

This Power BI dashboard provides an interactive analysis of Uber trip data to identify base-level performance, vehicle utilization efficiency, and trip trends over time. Built to offer both high-level KPIs and drill-down insights, this dashboard empowers stakeholders to make data-driven decisions quickly.

---

## 📦 Dataset Description

The dataset used for this project is based on **Uber’s publicly available trip data** for the year **2015** in **New York City**. It contains daily-level trip records for each affiliated **dispatch base** (fleet management center), including the number of trips and active vehicles.

### 🗂️ Key Columns:
| Column Name | Description |
|-------------|-------------|
| `Date` | The date of trip activity (daily level granularity). |
| `Dispatching_Base_Number` | Unique ID representing each Uber base (e.g., B02512, B02764). |
| `Affiliated_Base_Name` | Name of the base (if available). |
| `Trips` | Total number of trips completed on the given date. |
| `Active_Vehicles` | Number of distinct active vehicles/drivers operating on that day. |
| `Trips_Per_Active_Vehicle` | Calculated metric indicating average trips made per vehicle. |

> ⚙️ *Data cleaning and transformations were performed using Power Query. DAX measures were used to compute KPIs such as total trips, total vehicles, and trips per vehicle.*

---

## 🎯 Project Objective

The primary goal of this project is to **analyze and visualize Uber's dispatch-level trip data** using Power BI, with the aim to uncover insights on **trip trends**, **vehicle utilization**, and **base performance**.

### ✅ Objectives:
- Track overall trip volume and fleet activity using KPI cards.
- Identify the **most and least active dispatch bases**.
- Visualize **daily trip trends** and compare them against vehicle availability.
- Analyze **vehicle productivity** via "Trips per Active Vehicle".
- Enable **interactive filtering** using dispatch base and date.
- Support operational decisions through a clean, intuitive dashboard layout.

> 📈 This dashboard is designed to help stakeholders (such as fleet managers or analysts) identify high-performing bases, under-utilized vehicles, and operational trends over time.

---

## 📷 Dashboard Snapshot

![Uber Trip Analysis Dashboard](https://github.com/meghabk2002/uber_trip_analysis/blob/main/uber%20trip.png)

---

## 📊 Key Insights

1. **Total Activity Overview**
   - 2 Million trips recorded across 182K active vehicles.
   - Each vehicle made an average of **8.6 trips**.

2. **Top Performing Dispatch Base**
   - **B02764** stands out with over **740K trips**, making it the most efficient and high-volume base.

3. **Trip Trends Over Time**
   - Trip volume fluctuates over the year while the number of active vehicles remains stable.
   - Peaks observed mid-year around **June–August 2015**.

4. **Vehicle Utilization Efficiency**
   - Bases **B02682** and **B02598** have the highest **trips per active vehicle**.
   - **B02512** shows the lowest utilization, indicating potential inefficiencies.

5. **Distribution Patterns**
   - Scatter plot reveals a positive correlation between active vehicles and trip count.
   - Some bases maintain efficiency with fewer vehicles.

6. **Interactivity**
   - Slicers allow users to filter by **dispatch base** and **time period** for deeper analysis.

---

## 🛠️ Tools & Technologies

- **Power BI** (Desktop)
- Data Cleaning & Modeling: Power Query
- Custom DAX Measures for KPIs
- Icons from Unicode + Flaticon

---

## 🧠 Skills Demonstrated

- Data modeling and transformation
- DAX measures for performance metrics
- Visual storytelling and layout design
- Analytical thinking & executive-level presentation

---

## 📂 How to Use

1. Clone this repository.
2. Open the `.pbix` file using **Power BI Desktop**.
3. Connect to your local data source (if needed).
4. Use the slicers to filter and explore trends.

---

## 📣 Contact

**Megha BK**  
🎓 Post Graduate in Data Science and Analytics  
📊 Passionate about visual storytelling with Power BI  
📬 Connect on [LinkedIn](https://www.linkedin.com/in/megha-bk-718265222/)

---

