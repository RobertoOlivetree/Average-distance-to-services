# 🏙️ Spatial Analysis of Service Accessibility

This repository contains a set of scripts and data files for analyzing **the average distance to services** and the **distribution of service categories** in selected parishes. The project leverages **Python**, **GeoPandas**, **Folium**, and **OSMnx** to perform spatial analysis and visualization.

---

## 📌 Project Overview

The goal of this project is to:

- 🔍 **Analyze building accessibility** to nearby services.
- 📏 **Compute average distances** from buildings to services using a street network.
- 🗺️ **Visualize service distribution** across different categories.
- 🧭 **Generate interactive maps** with Folium for better insights.

---

## 📁 Files in this Repository

| File Name                               | Description                                                                 |
|----------------------------------------|-----------------------------------------------------------------------------|
| `Average distance to services.ipynb`   | Jupyter Notebook calculating the average distance using OSMnx.             |
| `Service category distribution.ipynb`  | Jupyter Notebook analyzing the distribution of service categories.         |
| `edificios.csv`                        | CSV file with building locations (WKT geometries).                         |
| `servicos.csv`                         | CSV file with service locations and categories.                            |
| `servicos_categoria.csv`               | CSV with additional service category details.                              |
| `freguesia.csv`                        | CSV file defining boundaries of selected parishes.                         |

---

## ⚙️ Setup & Dependencies

To run the Jupyter notebooks, install the following Python packages:

```bash
pip install pandas geopandas osmnx folium networkx shapely joblib matplotlib numpy
