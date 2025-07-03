
# 🚗 UK Road Accident Analysis Dashboard (Power BI)

This project presents an interactive Power BI dashboard built to analyze and visualize road accident data across the United Kingdom. The aim is to identify accident-prone zones, trends by time and conditions, and high-risk vehicle types — helping inform road safety strategies and improve awareness.


https://medium.com/@sakshiraorane.2005/%EF%B8%8F-uncovering-patterns-in-uk-road-accidents-using-power-bi-a-dashboard-story-2c2bbf256181

---

## 🎯 Objectives

- Visualize accident severity and frequency over time
- Identify geographic hotspots using map visuals
- Analyze how environmental factors (weather, road surface, light conditions) affect accidents
- Study accident trends by vehicle type, road type, and year
- Provide interactive filtering for deep-dive exploration


---

## 🗂️ Dataset Overview

- **Source**: Kaggle
- **Fields Used**:
  - Accident Severity (`Slight`, `Serious`, `Fatal`)
  - Number of Victims & Vehicles
  - Weather & Light Conditions
  - Road Surface Type
  - Geographic Data (Latitude, Longitude, District)
  - Vehicle Types (Car, Motorcycle, Van, etc.)
  - Year of occurrence
---

## 📊 Dashboard Structure

### 🔹 KPIs:
- Total Accidents
- Total Victims
- Total Vehicles Involved

### 🔹 Charts & Visuals:
1. **Map of Accidents by District** – to visualize hotspots
2. **Bar Chart: Road Type × Surface Condition**
3. **Severity Breakdown** – Slight, Serious, Fatal
4. **Top 3 Accident-Prone Vehicle Types**
5. **Accidents by Light Condition** – e.g., daylight, darkness without streetlight
6. **Accidents per Year** – Trend line from multiple years
7. **Accidents by Weather** – Fine, Rainy, Snowy, etc.

### 🔹 Interactive Filters:
- Vehicle Type
- Year
- Road Surface

---

## 🔍 Key Insights

1. **Single Carriageway roads** record the highest number of accidents.
2. **Urban districts** have a higher concentration of road incidents.
3. **Dry roads** surprisingly show more accidents than wet or icy ones.
4. **Cars** are the leading vehicle type involved, followed by motorcycles and vans.
5. Most accidents are categorized as **Slight**, but fatal/serious ones increase with dark lighting and poor conditions.
6. Accidents are more frequent in **daylight**, but **severity increases at night**.
7. **Fine weather** correlates with more accidents — likely due to higher travel volume.
8. **Accident frequency is declining year-over-year**, indicating positive progress.
9. **Roundabouts** show the fewest accidents, possibly due to lower speed flow.
10. As severity increases, the **number of victims and vehicles involved** also rises.

---

## 🧰 Tools Used

- **Power BI Desktop** – Visualization and dashboard building
- **Power Query** – Data cleaning

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `road_accident_analysis.pbix` | Power BI project file |
| `accident_analysis_report.pdf` | Full report with insights and layout |
| `road_accidents_raw.csv` | Cleaned dataset used for visuals |
| `dashboard_screenshot.png` | Preview of the final dashboard |
| `README.md` | This documentation file |

---

## 👩‍💻 Author

**Sakshi Raorane**  
Final-year Engineering Student | Data & AI Enthusiast  


