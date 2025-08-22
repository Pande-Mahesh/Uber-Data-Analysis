# 🚖 Uber Data Analysis Dashboard (Excel + Power Query + Power Pivot)

## 📌 Project Overview
This project analyzes Uber ride data (sourced from Kaggle) using **Excel, Power Query, and Power Pivot**.  
The goal was to clean and transform raw data, build KPIs, and design an interactive dashboard with pivot tables, charts, slicers, and macros.  

---

## 🛠️ Tools & Technologies
- **Excel** (Pivot Tables, Pivot Charts, Macros)  
- **Power Query** (Data Cleaning & Transformation)  
- **Power Pivot** (Measures & KPIs)  
- **VBA** (Macro automation for slicers)  

---

## 🔄 Data Preparation
1. Took Uber data (`.csv`) from Kaggle.  
2. Opened in Excel → converted to **Table** (`Ctrl + A`, `Ctrl + T`).  
3. Loaded into **Power Query** for transformation:  
   - Changed data types (Date, Time, Currency, Numbers).  
   - Cleaned nulls and inconsistencies.  
   - Loaded as **Connection → Data Model**.  

---

## 📊 Analysis & KPI Development
Created multiple pivot tables & charts to analyze performance:  

1. **Total Bookings KPI** → Count of `Booking_ID`  
2. **Total Booking Value KPI** → Sum of `Booking_Value (₹)`  
3. **Booking Value Distribution** → Min, Median, Max, Avg (Quartiles) + Bar Chart  
4. **Trip Distance KPI** → Total & Average distance (formatted in lakhs)  
5. **Ratings Analysis** → Avg Driver Rating vs Avg Customer Rating (Bar Chart)  
6. **Earnings by Vehicle Type** → Bar + Combo Chart (₹ value + %)  
7. **Trips by Vehicle Status** → Total / Completed / Cancelled (Bar + Combo Chart)  
8. **Trip KPIs** → Count of Completed / Cancelled / Total (KPI Cards with Shapes)  
9. **Interactive Slicers** → Vehicle Type & Payment Method (connected across pivots)  
10. **Macro Buttons** → Toggle between Total Trips, Completed Trips, Cancelled Trips  

---

## ⚙️ Automation (Macros)
Implemented VBA macros to improve dashboard interactivity:  
- `Total Trips` → Show all trips  
- `Completed Trips` → Show all except null payments  
- `Cancelled Trips` → Filtered view for cancelled trips  

Also included a helper macro to **remove all macro assignments from shapes** when needed.  

---

## 📈 Dashboard Features
- KPIs: Total Bookings, Total Value, Avg Fare, Distance, Ratings  
- Dynamic filters (Vehicle Type, Payment Method)  
- Interactive **Pivot-based visuals**  
- Macros for quick filtering  
- Professional formatting (Lakhs, %, ₹ currency)  

---

## 🖼️ Dashboard Preview
Files Download link:
https://drive.google.com/drive/folders/1DPK-maC3A5WVRAPgxHIYFRRhq8j-DbUb

<img width="1032" height="589" alt="COMPLETED_TRIPS" src="https://github.com/user-attachments/assets/8c2d2a80-d82a-4dea-858d-eb4ece6b1840" />

<img width="1023" height="583" alt="CANCELLED_TRIPS" src="https://github.com/user-attachments/assets/a335a70f-3974-4460-887b-c6a9ab377944" />

<img width="1030" height="588" alt="SINGLE_VEHICLE_TRIP" src="https://github.com/user-attachments/assets/f8191ec8-52fd-4ac3-8f53-3bc11846b654" />

<img width="1022" height="587" alt="TOTAL_TRIPS" src="https://github.com/user-attachments/assets/2075c492-8272-4e5e-ba11-60c76ef50892" />


https://github.com/user-attachments/assets/d383fe0c-a6c5-47e5-899f-bcfb74781a7c

---

## 📚 Learnings
- Hands-on experience with **Power Query & Power Pivot**  
- Designing KPIs and interactive dashboards  
- Using VBA macros for automation  
- Storytelling through Excel visualizations  

---

## 👤 About Me
**Name:** Mahesh Pande  
**Age:** 23  
**From:** Wardha, Maharashtra  
**Aspiring Data Analyst** – passionate about turning raw data into actionable insights.  

---
