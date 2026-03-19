<div align="center">

# 🏪 CityWide Dark Store Network Projection
### *Smarter Warehouses. Faster Deliveries. Data-Driven Decisions.*

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind](https://img.shields.io/badge/TailwindCSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Netlify](https://img.shields.io/badge/Deployed%20on-Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)

<br/>

| 🌐 Website 1 — Dark Store Analytics | 🌐 Website 2 — Social Event Store Tracker |
|:---:|:---:|
| [📊 Visit Live →](https://remarkable-baklava-216e9b.netlify.app/) | [📍 Visit Live →](https://gleeful-dodol-38f60b.netlify.app/) |
| Demand forecasting, Geospatial optimization, Real-time insights | Active dark stores near events & busy places in Pune |

</div>

---

## 🧩 Problem Statement

> **City-wide Dark Store Network Projection for Pune**

The rapid growth of quick-commerce has created a critical need to **strategically position dark stores (micro-warehouses)** across cities. Poor placement leads to:

- 🚦 Delayed deliveries due to traffic bottlenecks
- 📦 Inventory mismatches from inaccurate demand forecasting
- 💸 High operational costs from inefficient coverage zones
- 🎉 Inability to handle spikes during social events & festive seasons
- 🗺️ Ignoring population density while choosing warehouse locations

---

## 💡 Our Solution

We built an **end-to-end data-driven pipeline** that collects, cleans, and analyzes Pune's real-world data to recommend the **optimal dark store hotspots** — minimizing cost, maximizing coverage, and adapting to real-world conditions like traffic and events.

---

## 🌐 Live Demos

### 📊 Website 1 — Dark Store Analytics Dashboard
🔗 [https://remarkable-baklava-216e9b.netlify.app/](https://remarkable-baklava-216e9b.netlify.app/)

A comprehensive analytics platform presenting our full research and ML-driven insights:

| Feature | Description |
|---|---|
| 📈 Demand Forecasting | Predicts high-demand zones based on population & trends |
| 🗺️ Geospatial Optimization | Maps the best warehouse locations across Pune |
| ⚙️ Operational Insights | Tackles delivery challenges with data-backed strategies |
| 🔴🔵🟢 Density Zoning | Pune divided into High / Medium / Low density zones |
| 🚦 Traffic Analysis | Peak traffic time heatmaps by location and time of day |
| 📍 ML Hotspots | K-Means Clustering results for optimal store placement |

---

### 📍 Website 2 — Trends Ability
🔗 [https://gleeful-dodol-38f60b.netlify.app/](https://gleeful-dodol-38f60b.netlify.app/)

A live tracker showing **active dark stores near social events and busy places in Pune**, enabling:

- ⚡ Faster delivery during festivals and local events
- 💰 Lower last-mile delivery costs
- 📊 Dynamic store activation based on crowd density

---

## 🔬 What We Did — Step by Step

```
📥 Data Collection
   └── Research papers, real-world datasets, Pune population data

🧹 Data Cleaning & Analysis
   └── Cleaned CSV of Pune population data
   └── In-depth exploratory data analysis (EDA)

🗺️ Geospatial Mapping
   └── Pune_Population map → divided into 3 zones:
       🔴 Red   = High Density
       🔵 Blue  = Medium / Average Density
       🟢 Green = Low Density
   └── Ranked zones based on delivery priority

🚦 Traffic Analysis
   └── Divided the day into time slots
   └── Identified peak traffic hours per location
   └── Built traffic jam prediction graphs

🤖 ML Model — K-Means Clustering
   └── Applied optimal parameters for warehouse placement
   └── Identified best hotspots across Pune
   └── Tuned cluster count based on density zone

🌐 Website Development
   └── Built 2 React + TypeScript + Vite websites
   └── Deployed on Netlify
```

---

## 🤖 Machine Learning Model

**Algorithm Used:** `K-Means Clustering`

Our ML model takes in Pune's population, traffic, and geospatial data to identify **ideal warehouse hotspot locations.**

### How cluster count is decided:

| Zone | Population Density | Cluster Behaviour |
|---|---|---|
| 🔴 Red | High | More warehouses, smaller coverage radius |
| 🔵 Blue | Medium | Balanced number of warehouses |
| 🟢 Green | Low | Fewer warehouses, larger coverage diameter → **Cost Reduction** |

> 💡 In low-density (Green) zones, cluster diameter increases so we cover the area with fewer stores — **reducing unnecessary infrastructure costs.**

---

## ✅ Problems We Solved

| Challenge | Our Approach |
|---|---|
| 🗺️ Geographic Analysis | Population density zoning + Geospatial mapping |
| 👥 High Population Density | More clusters in high-density zones for maximum reach |
| 🚦 Traffic Management | Time-slot traffic analysis to avoid peak-hour delays |
| 💸 Cost Management | Green zone optimization reduces over-warehousing |
| 🎉 Social Event Handling | Website 2 tracks active stores near live events |
| 📈 Demand Forecasting | ML model predicts demand based on population trends |

---

## 📂 Project Structure

```
Hackron/
│
├── 📁 Code/
│   └── Website/               # React + Vite + TypeScript source code
│       ├── src/
│       ├── tailwind.config.js
│       ├── vite.config.ts
│       └── tsconfig.json
│
├── 📁 Data_Collection(Real-world)/
│   └── Research_paper/        # ML model prediction images & research
│
├── 📁 Graph_created_through_data/
│   └── Pune_Population map    # Density zone visualizations
│   └── Traffic graphs         # Peak traffic time analysis
│
├── 📁 CSV Files/
│   └── Pune population data   # Cleaned dataset used for ML
│
└── README.md
```

---

## 🏆 Why Our Hotspot Recommendations Work

Our recommended warehouse locations are optimized for:

- ✅ **Cost Efficiency** — Avoid over-placement in low-density zones
- ✅ **Fast Delivery** — Traffic-aware placement reduces last-mile time
- ✅ **Social Event Ready** — Stores pre-positioned near event hotspots
- ✅ **Maximum Customer Reach** — Coverage scales with population density
- ✅ **Time Reduction** — Shorter delivery radius in high-density zones
- ✅ **Availability** — Right inventory, right place, right time

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React, TypeScript, Vite, Tailwind CSS |
| ML Model | Python, K-Means Clustering, Pandas, NumPy |
| Data Visualization | Matplotlib, custom geospatial graphs |
| Deployment | Netlify (both websites) |
| Data Sources | Real-world Pune datasets, research papers |

---

## 🚀 Run Locally

```bash
# Clone the repository
git clone https://github.com/subhupanda21/Hackron.git
cd Hackron

# Navigate to the website code
cd Code/Website

# Install dependencies
npm install

# Start the dev server
npm run dev
```

---

## 👥 Team

**Subhu Panda**
- GitHub: [@SubhuPanda21](https://github.com/SubhuPanda21)
Team member: https://github.com/Bit-Bard

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

<div align="center">

**Built with 🔥 for Hackathon — Solving real-world quick-commerce challenges with data*

[📊 Analytics Dashboard](https://remarkable-baklava-216e9b.netlify.app/) • [📍 Event Tracker](https://gleeful-dodol-38f60b.netlify.app/)

</div>
