# 🚲 Blue Bikes Case Study: Station Performance Analysis

Welcome to the Blue Bikes Case Study repository! This analysis explores user behavior and operational trends within the Blue Bikes system using interactive Tableau dashboards. It focuses on station performance, trip duration, and time-of-day usage, helping Blue Bikes enhance system efficiency, improve user satisfaction, and make data-informed resource allocation decisions.

---

## 📊 Tableau Dashboard Overview

**📌 Dashboard Link:**  
[👉 View the Interactive Dashboard](https://public.tableau.com/views/BlueBikeassignment_ChoulyThy/Dashboard1)

This dashboard answers the key business question:

> **"What are the top N most popular stations for bike trips during peak hours on weekdays versus weekends?"**

The Blue Bike pricing model is based on trip duration, so understanding peak usage patterns helps improve profitability and service delivery.

## 🔍 Key Insights

### 1. 🗺️ Top Performing Stations on Weekends
- The dashboard displays the **Top 30 stations** ranked by total trip duration (minutes).
- High-performing stations (in blue) generate above-average ride duration and volume.
- Most popular stations are clustered around central Boston—strategic for both tourists and locals.

### 2. ⏰ Peak Time & Day
- **Peak Hour:** 17:00 (5 PM)
- **Peak Day:** Wednesday
- **Total Rides:** 127,122 (for selected filters)
- **Avg. Trip Duration:** 81.89 minutes

This suggests that the late afternoon and early evening periods are the most critical for demand management.

### 3. 📊 Time-of-Day Usage
- Afternoon hours (12 PM–6 PM) dominate with the highest ride counts.
- Usage is especially high among **Weekend Subscribers**, making up over **66% of total afternoon rides**.

### 4. 🧭 Station Distribution Map
- The station map visualizes spatial concentration of bike usage.
- Larger and brighter bubbles indicate higher usage — mostly clustered around downtown and transportation hubs.

---

## 📈 Visual Components

### 🔸 Top Stations Bar Chart
- Compares top stations based on trip duration.
- Separates **Weekday vs. Weekend** trends.
- Helps prioritize station-level improvements for bike rebalancing and capacity planning.

### 🔸 Time-of-Day Usage Chart
- Displays ride volume across each hour of the day.
- Useful for adjusting supply (bikes/docks) during high-demand hours.

### 🔸 Station Map
- Interactive geo-plot of stations with size indicating trip volume.
- Supports regional planning and service area optimization.

---

## ⚙️ Dashboard Interactivity

- **Top N Filter**: Adjust how many top stations to visualize.
- **Day Type Toggle**: Switch between weekday and weekend views.
- **Hover Tooltips**: Show detailed station data (trip count, duration, etc.)
- **Interactive Filters**: Click a station to see its time-of-day performance.

---

## ✅ Recommendations

1. **Optimize Peak-Time Supply**  
   Allocate more bikes and docks during the 17:00 peak, especially on Wednesdays and weekends.

2. **Focus on High-Demand Stations**  
   Prioritize maintenance, restocking, and marketing at top stations like *Aquarium T*, *Back Bay*, and *Central Square*.

3. **Differentiate Strategies for Weekends vs. Weekdays**  
   Weekend subscribers account for significant usage—consider loyalty perks, guided tours, or promotions.

4. **Enhance Coverage During Late Hours**  
   Usage between 18:00–22:00 remains high. Ensure visibility, safety, and availability during these hours.

5. **Use Data for Seasonal Adjustments**  
   Replicate this analysis seasonally to adapt fleet size, station activity, and promotional campaigns.

---

## 📁 File Structure

```bash
├── README.md                    # This file
├── /screenshots                 # Dashboard screenshots
├── /data                        # Raw data files (if available)
├── /notebooks                  # Jupyter/analysis scripts
├── /dashboard-link.txt         # External Tableau dashboard link
