# Modeling Centuries of Economic Growth: A Machine Learning Analysis of Historical GDP and Population Trends

![K-Means Clustering of Countries by GDP per Capita and Population](https://github.com/user-attachments/assets/59511824-a15a-4d37-8982-faf4c5f6a429)

## Overview

This project applies machine learning and statistical modeling techniques to examine over three centuries of global GDP per capita and population data. Drawing from the Maddison Project and UN demographic records, the study explores long-run development patterns and forecasts future economic trajectories.

By integrating **ARIMA time-series forecasting** and **K-Means clustering**, the project identifies macroeconomic trends and structural groupings across national economies. The analysis serves as both a research contribution and a pedagogical resource for graduate-level economics and data science.

---

## Project Structure

The repository includes the following:

- `Historical_Economic_Analysis.ipynb`: Complete Jupyter Notebook with data processing, visualizations, forecasting, and clustering analysis.
- `Article.pdf`: A full-length academic-style article with visualizations and interpretations.
- `Data/`: Cleaned and transformed GDP and population datasets.
- `Visuals/`: High-resolution figures used in the publication, including clustering and forecast charts.

---

## Methodology

### Data Sources:
- **GDP per Capita**: Maddison Project Database (2020), adjusted to 2011 international dollars.
- **Population**: UN World Population Prospects and historical reconstructions.

### Techniques Used:
- **Exploratory Data Analysis**: Visualization of historical trends, transformations, and distributional insights.
- **ARIMA Forecasting**: Statistical modeling of GDP per capita from 2024 to 2044.
- **K-Means Clustering**: Unsupervised learning on standardized log-transformed GDP and population data.
- **Visualization**: Python (matplotlib, seaborn, statsmodels).

---

## Key Findings

- Long-run data shows a structural shift post-Industrial Revolution, with accelerated growth in both GDP and population.
- ARIMA projections suggest continued economic expansion but with increasing uncertainty over long horizons.
- Clustering analysis reveals structural typologies beyond geographic or income classifications:
  - **Cluster 0**: Low-income, low-population countries (e.g., Malawi, Chad)
  - **Cluster 1**: Populous, middle-income economies (e.g., India, Nigeria)
  - **Cluster 2**: Demographic outliers (e.g., China, India)
  - **Cluster 3**: High-income, low-population countries (e.g., Norway, Canada)

---

## Usage

To explore the project:

1. Clone this repository:
   ```bash
   git clone https://github.com/your-handle/economic-forecasting-project.git
   cd economic-forecasting-project
