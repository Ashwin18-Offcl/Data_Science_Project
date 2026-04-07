

<p align="center">
  <img src="https://via.placeholder.com/950x300.png?text=Walkability+Analysis+Melbourne"
       width="950"
       alt="Walkability Analysis Banner"/>
</p>

<p align="center">
<b>Scalable Walkability Analysis of Melbourne</b><br>
Transforming <b>urban data → spatial intelligence → actionable insights</b> using statistical & geospatial analysis
</p>

---

# 🚀 Repository Overview

```
Domain            : Urban Analytics / Spatial Data Science
Project Type      : Final Semester Computing Project
Institution       : University of Melbourne
Supervisor        : Dr. Richard Sinnott
Region            : Inner Melbourne, Australia
Data Source       : AURIN (Australian Urban Research Infrastructure Network)
Tech Stack        : Python 2 | Pandas | Folium | Matplotlib | Seaborn
Focus             : Scalable Walkability Index Computation
```

---

# 🌆 Problem Statement

Measuring **walkability** at scale is computationally expensive due to:

* Road network traversal complexity
* Large geographic regions (SA3 / SA4)
* High processing time in AURIN workflows

👉 Traditional systems struggle with **large-area analysis**

---

# 💡 Core Idea

Instead of analyzing large regions directly:

✔ Break regions into **smaller statistical units (SA1s)**

✔ Perform **localized walkability computation**

✔ Aggregate results to represent larger regions

---

# 🧠 Walkability Framework

```
Small Units (SA1) → Compute Walkability → Aggregate → Larger Regions (SA2/SA3/SA4)
```

---

# 📊 What is Walkability Index?

A metric that evaluates how pedestrian-friendly a region is based on:

✔ Road connectivity

✔ Population density

✔ Land-use diversity

---

# 🗺 Statistical Area Hierarchy (Australia)

| Level | Description    | Population       |
| ----- | -------------- | ---------------- |
| SA1   | Smallest unit  | 200 – 800        |
| SA2   | Suburb-level   | ~10,000          |
| SA3   | Regional areas | 30K – 130K       |
| SA4   | Large regions  | Entire sub-state |

---

# ⚙️ Scalable Approach

### 🔹 Step 1: Micro-Level Analysis

* Compute walkability for **SA1 units**

### 🔹 Step 2: Aggregation Strategy

* Combine SA1 results using **mean values**

### 🔹 Step 3: Multi-Level Representation

* Build:

  * SA2 (Suburbs)
  * SA3 (Regions)
  * SA4 (Large zones)

---

# 🔥 Why This Approach Matters

✔ Reduces computational load

✔ Enables large-scale analysis

✔ Maintains interpretability

✔ Supports parallel processing potential

---

# 📈 Analytical Modules

## 🔹 1. Walkability Visualization

* Bar plots for suburb comparison

## 🔹 2. Choropleth Maps

* Interactive spatial visualization using Folium

## 🔹 3. Data Integration

* Merge socio-economic datasets with walkability

## 🔹 4. Correlation Analysis

* Identify relationships with:

  * Public health
  * Transport access
  * Economic indicators

## 🔹 5. Spatial Autocorrelation

* Detect clustering patterns across suburbs

## 🔹 6. City Comparison

* Melbourne vs Sydney walkability insights

---

# 🧪 Data Pipeline

```
AURIN Data → Preprocessing → SA1 Analysis → Aggregation → Visualization → Insights
```

---

# 🛠 Tools & Technologies

| Tool             | Role                    |
| ---------------- | ----------------------- |
| Python 2         | Core programming        |
| Pandas           | Data manipulation       |
| Matplotlib       | Static visualization    |
| Seaborn          | Statistical plotting    |
| Folium + Leaflet | Interactive maps        |
| Jupyter Notebook | Analysis & presentation |

---

# 📁 Project Structure

```
📁 Walkability-Melbourne
│
├── notebooks/
│   ├── bar_plots.ipynb
│   ├── choropleth_maps.ipynb
│   ├── correlations.ipynb
│   ├── spatial_analysis.ipynb
│   └── comparison.ipynb
│
├── choropleth-map/
│   └── *.html (interactive maps)
│
└── README.md
```

---

# 📊 Key Insights Delivered

✔ Walkability variation across Melbourne suburbs

✔ Relationship between walkability & socio-economic factors

✔ Spatial clustering patterns

✔ Scalable analytics framework for urban studies

---

# 🎯 Learning Outcomes

✔ Geospatial data analysis

✔ Urban informatics concepts

✔ Statistical aggregation techniques

✔ Data visualization (static + interactive)

✔ Handling large-scale datasets efficiently

---

# 🧭 Who Is This For?

✔ Data Science students

✔ Urban planners

✔ GIS analysts

✔ Researchers in smart cities

✔ Developers exploring spatial analytics

---

# 🚀 Career Impact

This project demonstrates:

✔ Real-world data analysis skills

✔ Ability to handle large datasets

✔ Strong visualization capability

✔ Understanding of spatial systems

✔ Research-level project experience

---

# 🌟 Future Enhancements

* Parallel processing for SA1 computations
* Machine learning-based walkability prediction
* Real-time urban data integration
* Web dashboard for interactive exploration
* Migration to Python 3

---

# 📊 Summary

```
Massive Urban Data → Smart Segmentation → Efficient Computation → Actionable Insights
```

---

# 🧑‍💻 Author

**Final Year Computing Project**
University of Melbourne

---

# 🚀 How to Use

```bash
# Open Jupyter Notebook
jupyter notebook

# Run notebooks in order for full pipeline
```

