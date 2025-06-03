# Analyzing Motor Vehicle Collisions in New York City  
### A Data-Driven Approach to Urban Safety

## 🚦 Project Overview

This project analyzes **motor vehicle collisions in New York City** using open data from the NYC Open Data portal. The goal is to uncover trends, identify high-risk zones, and provide actionable insights to improve public safety and inform city planning.

> Conducted as part of a data science project exploring urban incident data.

---

## 📊 Objective

- Identify **time and location patterns** in traffic collisions
- Quantify injury and fatality trends across boroughs
- Explore contributing factors (e.g., distracted driving, vehicle type)
- Generate heatmaps and visuals to support urban planning and safety decisions

---

## 🗂 Dataset

- **Source**: [NYC Motor Vehicle Collisions – Crashes](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95)
- **Size**: Over 1.8 million records
- **Timeframe**: Multi-year (dataset updated daily)
- **Key Fields**:
  - Date & Time of Collision
  - Borough & Street Name
  - Number of Persons Injured/Killed
  - Contributing Factor (e.g., Alcohol Involvement)
  - Vehicle Type

---

## 🧹 Data Cleaning

- Parsed and converted date/time formats
- Removed null values in key columns (e.g., location, injuries)
- Created derived variables:
  - Hour of collision
  - Day of week
  - Aggregated injury and fatality counts

---

## 📍 Key Analyses

- 📈 **Temporal Patterns**: 
  - Peak accidents occur between 3 PM–6 PM
  - Weekdays see higher collision counts than weekends

- 🗺️ **Geographic Risk Zones**:
  - Bronx and Brooklyn show consistently high injury rates
  - Certain intersections repeatedly appear as high-risk areas

- 🚘 **Cause & Vehicle Type**:
  - Distracted driving and failure to yield are top causes
  - Passenger vehicles dominate collisions, but motorcycles and trucks show higher injury severity per accident


---

## 🧰 Tools Used

- Python (Pandas, Seaborn, Matplotlib, Plotly)
- Jupyter Notebook
- NYC Open Data API

---

## 📁 File Structure

- `Project1 - NY Motor Vehicle Collisions - Crashes.ipynb`: Full analysis notebook with code and commentary
- (Optional): `collisions.csv`: Cleaned subset of NYC crash data for fast local use

---

## ✅ Conclusion

This project highlights the **importance of data transparency and geospatial analysis** in improving public safety. The insights generated can help city officials prioritize:
- High-risk intersections for redesign
- Time-specific enforcement strategies
- Public awareness campaigns targeting top contributing factors

---

## 🚀 Future Extensions

- Train a predictive model to estimate injury likelihood per crash
- Integrate weather data for deeper risk analysis
- Build an interactive dashboard using Dash or Tableau

---

## 📌 Disclaimer

Data is sourced from a public government dataset and is anonymized. The project is intended for educational and analytical purposes only.
