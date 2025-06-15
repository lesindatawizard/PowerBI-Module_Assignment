# PowerBI-Module_Assignment

# 🏙️ NYC Airbnb Market Overview – Power BI Module Assignment

![Dashboard Preview](Screenshot%202025-06-16%20032310.png)

## 📘 Project Summary

This Power BI dashboard presents a comprehensive analysis of Airbnb listings in New York City. The project aims to derive actionable insights from listing data by incorporating interactive visuals, slicers, KPIs, and bookmarks. It serves as a strong demonstration of Power BI proficiency and is structured to align with professional reporting standards.


## 📊 Dashboard Features

### ✅ Page Title: `NYC Airbnb Market Overview`

### 🔢 Key Metrics (Cards)
- **Total Listings**: 48.90K
- **Average Price**: $152.18

### 📌 Visualizations Used (7):
1. **Room Type Distribution** – *Pie Chart*
2. **Price by Area** – *Clustered Column Chart*
3. **Top Neighborhoods by Listings** – *Horizontal Bar Chart*
4. **Average Annual Availability (Days)** – *Gauge Chart*
5. **Availability by Room Type** – *Conditional Color Table*
6. **Map of Listings by Neighborhood** – *Map Visualization*
7. **Key Performance Metrics** – *Multi-Row Card (KPI Grid)*

### 🎛️ Interactive Slicers (5):
- **Room Type** *(Tiles)*
- **Neighbourhood Group** *(Dropdown)*
- **Room Availability** *(Dropdown)*
- **Minimum Nights** *(Slider)*
- **Price Filter** *(Numeric Range Input)*

### 🔁 Reset Button
- Added a bookmark-enabled **Reset** button to clear all slicers and filters at once.

### 🖼️ Design Elements
- Airbnb-themed red-pink color palette
- Airbnb logo included for branding
- Responsive layout with consistent formatting and spacing
- Fonts and titles styled for clarity


## 🧠 Insightful Analysis

Here are some key takeaways derived from the visual dashboard:

- **Dominant Room Types**: Entire homes/apartments make up the majority of listings (51.84%), followed by private rooms (45.45%).
- **Top Neighborhoods**: Williamsburg and Bedford-Stuyvesant are the most popular neighborhoods with over 3,500 listings each.
- **Pricing by Borough**: Manhattan commands the highest average prices, while Staten Island has the lowest.
- **Availability Trends**: Shared rooms have the highest availability (~162 days annually), indicating lower booking demand.
- **Occupancy Insight**: The average occupancy rate is ~69%, with a price-per-review of ~$38, suggesting a moderate guest turnover.
- **Review-Linked Listings**: Only 79% of listings are considered active (have reviews), highlighting potential supply issues.
- **Annual Availability**: Overall average annual availability is around 112 days, showing that many hosts list part-time.


## 📂 Dataset & Tools

- **Dataset**: `AB_NYC_2019.csv` (New York City Airbnb Open Data)
- **Tool Used**: Power BI Desktop
- **Data Processing**:
  - Handled nulls in `last_review`, `reviews_per_month`
  - Converted price to numeric and filtered outliers (> $10,000)
  - Grouped and categorized prices using DAX for slicers


