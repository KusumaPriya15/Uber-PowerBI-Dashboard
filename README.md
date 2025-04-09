# 🚖 Uber Trip Analysis Dashboard – Power BI

This project analyzes Uber trip data using **Power BI**, offering visual insights into bookings, revenue trends, and time-based patterns to help stakeholders make informed decisions.


## 📁 Datasets Used
1. **Uber Trip Details.xlsx** – Trip-level data including distance, time, vehicle type, etc.
2. **Location Table.xlsx** – Contains city/location mappings for pickup/drop-off analysis.


## 📊 Dashboard Structure

### 🧩 **Dashboard 1: Overview**
- KPIs: Total Bookings, Total Booking Value, Avg Trip Distance, etc.
- Filters by Payment Type, Trip Type (Day/Night), Date, City
- Dynamic measure selector & title
- Vehicle type grid analysis
- Booking trends by day

### 🕒 **Dashboard 2: Time Analysis**
- Area chart for 10-minute pickup intervals
- Line chart by day of the week
- Heatmap for hour vs. day patterns
- Global dynamic measure selector

### 📋 **Dashboard 3: Details Tab**
- Drill-through enabled grid for raw trip records
- Bookmark toggles between filtered & full dataset


## 🎯 Objective

- Detect booking trends and revenue peaks
- Analyze trip efficiency (distance & time)
- Identify top-performing cities and time slots
- Improve pricing models and driver allocation


## 🛠 Tools & Techniques

- Power BI Desktop
- DAX Measures & Disconnected Tables
- Power Query
- Interactive Visuals (Slicers, Bookmarks, Tooltips)


## 📄 Problem Statement

A full PDF detailing KPIs, expected outcomes, and visual implementation is included in the repo.
