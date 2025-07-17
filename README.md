# 📶 Mobile Network Signal Strength Analysis

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/18N4b6ESRNv74bP1AmdODBM8Hjm7eSGW1?usp=drive_link#scrollTo=GNujDMjeCMbn)

This project analyzes mobile network signal strength data collected from various locations, comparing multiple network providers (Jio, Airtel, Vi, BSNL). It includes data cleaning, exploratory data analysis (EDA), visualizations, and key insights derived from the dataset.

---

## 📁 Dataset

The dataset includes signal strength and ASU values measured at four different places for the following mobile service providers:

- **Jio**
- **Airtel**
- **Vi (Vodafone-Idea)**
- **BSNL**

Each entry contains:
- Timestamp
- Location name
- Latitude/Longitude (geolocation)
- Signal Strength (in dBm)
- ASU values for each provider

---

## 🧠 Objectives

- Clean and preprocess raw signal strength data
- Perform exploratory data analysis (EDA)
- Visualize performance comparison across providers
- Identify the best-performing provider at each location

---

## 🛠️ Tools & Libraries Used

- Python 3.x
- Google Colab
- `pandas`
- `matplotlib`
- `seaborn`
- `numpy`
- `plotly` *(optional for interactive plots)*
- `folium` *(optional for geospatial maps)*

---

## 📊 Exploratory Data Analysis Highlights

- 📌 **Signal Strength Comparison**: Analyzed and compared average signal strengths across locations
- 🔁 **Provider-Wise Performance**: Compared Jio, Airtel, Vi, and BSNL performances
- 🗺️ **Location Trends**: Identified strong providers per region
- 📉 **Heatmaps & Correlation**: Relationship between signal strengths and ASU values

---

## 📷 Visualizations Included

- Bar plots (Signal Strength by provider)
- Scatter plots (Signal vs ASU)
- Line graphs (Signal trends over time)
- Heatmaps (Correlation matrix)

---

## 📌 Key Findings

- **Place 1**: Jio and Airtel show consistently strong signal strength
- **Place 2**: Vi shows the lowest performance
- **Place 3**: Jio and BSNL perform better than Airtel and Vi
- **Place 4**: All providers are relatively balanced


