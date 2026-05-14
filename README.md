# 🚦 Road Safety in Poland — Data Visualization Project

> A comprehensive visual analysis of road traffic accidents in Poland and Europe, created for a Data Visualization university course.

---

## 📋 Overview

This project explores road safety trends through a series of interactive and static visualizations. Using data from the Polish Police, WHO, and EU road safety databases, we investigate patterns in traffic accidents across time, geography, weather conditions, and traffic volume — both within Poland and across Europe.

---

## ✨ Visualizations

| # | Title | Type | Scope |
|---|-------|------|-------|
| 1 | Road Safety by Voivodeship (2024) | Choropleth map | Poland |
| 2 | Improvement in Road Safety (2001–2024) | Dual line chart | Poland |
| 3 | Accidents by Weather Conditions (2001–2024) | Donut + stacked area | Poland |
| 4 | Accident Intensity by Hour & Day of Week | Heatmap | Poland |
| 5 | Daily Accidents vs. Traffic Volume (2023) | Scatter plot + regression | Poland |
| 6 | Fatal Accidents in Top 10 European Countries (2024) | Horizontal bar chart | Europe |
| 7 | Global Traffic Death Rate (WHO) | Interactive choropleth | World |
| 8 | Accident Location Clusters (2023) | Interactive point map | Poland |

---

## 🗂️ Data Sources

- **[Polish Police — Annual Road Traffic Reports](https://statystyka.policja.pl/st/ruch-drogowy/76562,wypadki-drogowe-raporty-roczne.html)** — accident counts by voivodeship, year, and weather conditions (2001–2024)
- **`incidents.csv`** — georeferenced accident incident data with timestamps (2020–2023)
- **`DANE2023.csv`** — daily average traffic volume measurements across Poland (2023)
- **`fatalities_2010-24_public_0.xlsx`** — EU/EFTA road fatality counts by country (2010–2024)
- **`who_traffic_death_rate.csv`** — WHO global traffic death rates per 100,000 population

---

## 🛠️ Technologies

- **Python 3**
- [`pandas`](https://pandas.pydata.org/) — data loading and wrangling
- [`matplotlib`](https://matplotlib.org/) — static charts and maps
- [`seaborn`](https://seaborn.pydata.org/) — statistical visualizations
- [`geopandas`](https://geopandas.org/) — geospatial data processing
- [`folium`](https://python-visualization.github.io/folium/) — interactive web maps

---

## 🚀 Getting Started

### Prerequisites

Make sure you have Python 3.8+ installed. Then install the required dependencies:

```bash
pip install pandas matplotlib seaborn geopandas folium openpyxl
```

### Running the Notebook

```bash
jupyter notebook Projekt_wizualizacja_gotowy.ipynb
```

> **Note:** Some cells require the raw data files (`incidents.csv`, `DANE2023.csv`, `fatalities_2010-24_public_0.xlsx`, `who_traffic_death_rate.csv`) to be present in the same directory as the notebook.

---

## 💡 Key Findings

- 🔻 **60% fewer total accidents** in 2024 compared to 2001, and a **66% drop in fatalities** over the same period — a remarkable improvement in road safety.
- 🌤️ **Good weather conditions paradox** — the majority of accidents (over 50%) occur in good weather, as drivers tend to drive faster when conditions feel safe.
- 🕔 **Peak accident hours** fall on weekday afternoons (4–6 PM), aligning with rush hour traffic.
- 📍 **Łódź voivodeship** reports the highest accident rate per capita; **Podlaskie** is the safest.
- 🌍 **Romania** leads European countries in road fatalities (2024), while Western European nations consistently perform better.

---

## 👥 Authors

| Name | 
|------|
| **Hubert Kwiatek** |
| **Olek Zawada** |
| **Karol Jank** |

---

## 📄 License

This project was created for academic purposes as part of a Data Visualization university course. Data used belongs to their respective public sources as listed above.
