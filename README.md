# Earthquakes-Analysis-Dashboard

### 📊 Dashboard Link: https://app.powerbi.com/groups/me/reports/0641f268-1b32-4768-b2e6-e8a580c6acf6/4a85a568b3cd93580072?experience=power-bi
📄 PDF Link: https://github.com/mayankb-rm/Earthquake-Data-Analysis/blob/main/Earthquakes%20Analysis.pdf

---

## 📌 Problem Statement

This Power BI Dashboard was designed to provide a deep analytical understanding of global earthquake activity over time. It aims to identify patterns in **magnitude**, **depth**, **frequency**, **location**, and **seasonality**. The goal is to help **disaster management agencies**, **geologists**, and **researchers** assess risk and prepare more effectively for seismic events.

The dashboard provides insights such as:
- Monthly and yearly earthquake frequency.
- Magnitude distribution and severity trends.
- Relationship between **depth and magnitude**.
- Geographical hot spots for seismic activity.

---

## 🛠️ Steps Followed

**Step 1**: Loaded the earthquake dataset (CSV format) into **Power BI Desktop**.

**Step 2**: Opened **Power Query Editor** and enabled:
- `Column Distribution`
- `Column Quality`
- `Column Profile`

**Step 3**: Changed profiling to consider the **entire dataset** for accurate insights.

**Step 4**: Cleaned the data:
- Removed blank or ambiguous **magnitude types**.
- Formatted **date columns** to extract `Year` and `Month`.
- Ensured correct data types for numerical columns like `Magnitude`, `Depth`, and `Latitude/Longitude`.

**Step 5**: Created DAX measures for:
- Total Earthquakes
- Earthquakes by Year, Month, Magnitude, and Depth
- Created calculated columns for Month name and Year from date

**Step 6**: Designed visuals:
- **Cards**: Total Earthquakes
- **Bar charts**: Earthquakes by Month, Year, and Magnitude
- **Histogram**: Earthquake Depth Distribution
- **Scatter plot**: Depth vs Magnitude Relationship
- **Map visual**: Global earthquake locations

**Step 7**: Added slicers for **Magnitude Type** and **Year** to enable dynamic filtering.

**Step 8**: Applied a professional theme and published the dashboard to **Power BI Service** for online access.

---

## 📈 Key Visuals & Metrics

### 📊 Total Earthquakes Recorded: **8,313**

---

## 📅 Earthquakes By Month
| Month      | Earthquake Count |
|------------|------------------|
| January    | 94               |
| February   | 95               |
| March      | 85               |
| April–December | Range between 60–95 |

👉 Earthquakes occur **consistently** across all months without major seasonal variation.

---

## 📆 Earthquakes By Year

- Spanning years from **1900 to 2000**.
- Most active periods:
  - Mid to late 20th century showed gradual increases.
  - Highest earthquake frequency in **post-1950** period.

---

## 📐 Magnitude Distribution

| Magnitude | Earthquake Count |
|-----------|------------------|
| 6         | 1182             |
| 7         | 926              |
| 8         | 469              |
| 9         | 365              |
| 10        | 11               |

⚠️ **Magnitude 6** is the most common threshold observed in global seismic activity.

---

## 🌍 Earthquake Distribution by Location

- Global map plotted with earthquake epicenters using **latitude and longitude**.
- Supports geographical filtering and zooming for **regional seismic analysis**.

---

## 📏 Depth Analysis

### Depth Histogram:

- Most earthquakes occurred at a **depth of 0–200 km** (~6800+ earthquakes).
- Very few earthquakes recorded below **400 km**.

### Depth vs Magnitude Correlation:

- Earthquakes with **higher magnitude** tend to occur at **intermediate depths**.
- Some deep earthquakes exist but are less frequent and less intense.

---

## 🔬 Magnitude Type Analysis

Magnitude types include:
- `mb` (Body wave magnitude)
- `ms` (Surface wave magnitude)
- `mw`, `mwb`, `Mt`, `mj`, `(blank)` etc.

Note: A considerable number of rows had **blank `magType`**, which were filtered where necessary to maintain analytical accuracy.

---

## 🔍 Key Insights Summary

1. **Total Earthquakes Analyzed**: **8,313**
2. **Magnitude 6** earthquakes are most frequent globally.
3. **January and February** saw marginally higher earthquake counts.
4. **Shallow-focus earthquakes (0–200 km)** dominate the dataset.
5. Earthquake **magnitudes and depths** do not always follow a linear pattern.
6. Majority of records fall within **1950–2000**, suggesting improved tracking and instrumentation during this time.

---

## 💼 Tools & Technologies Used

- Power BI Desktop  
- Power Query Editor  
- DAX for Measures & Calculated Columns  
- Map & Scatter Plot Visualizations  
- Power BI Service (for publishing)

---

## ✅ Outcome

This **Earthquake Analysis Dashboard** provides comprehensive visibility into seismic activity worldwide. It helps organizations:
- Monitor seismic risk over time.
- Evaluate hazard-prone areas.
- Make informed decisions for disaster preparedness and structural planning.

📬 *To access or embed this dashboard, or to collaborate on related projects, feel free to connect or fork this repository.*
