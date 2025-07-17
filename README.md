# 📶 Mobile Network Signal Strength Analysis

This project analyzes the mobile network signal strength data collected from various locations, comparing multiple network providers (Jio, Airtel, Vi, BSNL). It includes data cleaning, exploratory data analysis (EDA), visualization, and summary of insights derived from the dataset.

## 📁 Dataset

The dataset includes signal strength and ASU values measured at four different places for the following mobile service providers:

- Jio
- Airtel
- Vi (Vodafone-Idea)
- BSNL

Each entry contains:

- Timestamp
- Location name
- Latitude/Longitude (geolocation)
- Signal Strength (in dBm)
- ASU values for each provider

## 🧠 Objectives

- Clean and preprocess the raw signal strength data.
- Perform exploratory data analysis to understand signal quality across locations and providers.
- Visualize the performance comparison.
- Identify the best-performing provider at each place.

## 🛠️ Tools & Libraries

- Python 3.x
- Google Colab
- Pandas
- Matplotlib
- Seaborn
- NumPy
- Plotly (optional for interactive plots)
- Folium (optional for geospatial maps)

## 📊 Exploratory Data Analysis Highlights

- 📌 **Signal Strength Comparison**: Analyzed and compared average signal strengths across locations.
- 🔁 **Provider-Wise Performance**: Compared the signal performance of Jio, Airtel, Vi, and BSNL.
- 🗺️ **Location Trends**: Identified which providers perform better in which places.
- 📉 **Heatmap & Correlation Analysis**: Explored relationships between signal strengths and ASU.

## 📷 Visuals Included

- Bar plots of signal strength by provider
- Scatter plots comparing signal and ASU
- Line graphs showing signal trends
- Heatmaps for correlation

## 📌 Key Findings

- **Place 1**: Jio and Airtel show consistently strong signal strength.
- **Place 2**: Vi shows the lowest performance.
- **Place 3**: Jio and BSNL perform better than Airtel and Vi.
- **Place 4**: All providers are relatively balanced.
