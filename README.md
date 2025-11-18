# Facility Location Optimization & Geospatial Analysis

A geospatial optimization project designed to determine the most strategic facility location based on cost, accessibility, and demand clusters. This project integrates location intelligence with optimization modeling to support supply chain expansion and logistics planning decisions.

---

## 📌 1. Project Overview

This project explores how businesses can select optimal facility locations (e.g., warehouses, distribution centers, service hubs) to reduce transportation costs and improve coverage efficiency. Using real-world geographic data and optimization techniques, the analysis evaluates potential location strategies tailored to customer demand distribution and distance metrics.

The model supports evidence-based decision making for expansion planning, operational cost reduction, and service level consistency.

---

## 📊 2. Data Description

The dataset used in this analysis included:
- 📍 Coordinates of potential facility locations  
- 🚚 Customer locations & demand values  
- 🛣 Distance metrics (API-based & calculated)  
- 💰 Estimated transportation costs per km  
- 📦 Minimum service requirements  

Data sources include **Google Maps Distance Matrix API** and synthetic operational data to simulate real supply chain scenarios.

---

## 🔧 3. Methodology & Approach

The analysis follows this pipeline:

1. **Geospatial Data Processing**
   - Used coordinates to calculate distance matrices.
   - Clustered demand points using spatial relationships.

2. **Optimization Modeling**
   - Applied a **cost minimization objective** with linear optimization.
   - Decision variable: Select facility location(s) that meet demand efficiently.
  
3. **Visualization Layer**
   - Built route and demand distribution maps using **Folium & Google Maps API**.

4. **Scenario Analysis**
   - Run alternative location strategies to evaluate cost vs. accessibility.

---

## 📐 4. Tools & Technologies

| Category              | Tools Used |
|----------------------|------------|
| Programming          | Python (Pandas, NumPy) |
| Optimization         | PuLP / SciPy Optimize |
| Geospatial Analysis  | Folium, Google Maps API |
| Visualization        | Matplotlib, GeoPlotting |
| Other                | Jupyter Notebook |

---

## 🚀 5. Key Results & Business Impact

✔ Identified **optimal facility location** that minimized transportation cost while maintaining acceptable service radius.  
✔ Demonstrated **X% improvement in operational routing efficiency** versus default location strategy *(Replace with actual figure if available)*.  
✔ Mapped customer service zones and suggested a **multi-site strategy for peak demand fulfillment**.  
✔ Provided actionable insight into using geolocation + optimization for strategic network design.

---

## 📁 6. Repository Structure

Facility-location-optimization/
│
├── 📓 Facility Location Optimization.ipynb # Main notebook
├── 📄 Facility Location Optimization Presentation.pdf # Summary slides
└── 📄 Facility Location Optimization Report.pdf # Detailed report


---

## ▶️ 7. How to Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/ShemezaDonald/Facility-location-optimization.git
cd Facility-location-optimization

# 2. Install dependencies (example)
pip install pandas numpy pulp matplotlib folium googlemaps

# 3. Launch Jupyter Notebook
jupyter notebook "Facility Location Optimization.ipynb"

