# Supply Chain Optimization Platform

> Built by two data science grads — Hema Manasi Potnuru & Mahimna Darji — This simulates and visualizes a full-scale supply chain system using Python, MongoDB, Tableau, and Streamlit. It's what logistics dashboards should look like in 2025.

---

## 🔍 Project Overview

Supply chains are complex, messy, and sensitive to delay, cost, and demand fluctuations. We built this to:

* Simulate a logistics operation across the U.S.
* Perform advanced analytics on delivery, cost, and inventory
* Forecast future demand and flag delays or stockouts
* Present interactive insights using Tableau and Streamlit

---

## 👨‍💻 Authors

* **Hema Manasi Potnuru**
* **Mahimna Darji**

---

## 🛠️ Tech Stack

| Layer        | Tools Used                       |
| ------------ | -------------------------------- |
| Data Storage | MongoDB Atlas                    |
| Backend      | Python, pandas, Prophet, pymongo |
| Dashboards   | Tableau, Streamlit               |
| GeoMapping   | Folium                           |
| Development  | Google Colab, Jupyter Notebook   |

---

## 📦 Features Built

### ✅ Inventory Forecasting

* Forecast SKU demand using Prophet
* Risk scoring for understocked items

### ✅ Shipment Analytics

* Visual shipment tracking map
* Delay anomaly detection
* Rolling shipment trends

### ✅ Cost Optimization

* Distance vs. cost modeling
* Mode-wise cost comparison

### ✅ Vendor Insights

* Performance radar charts
* Delay vs reliability trade-offs

### ✅ Dashboards

* Tableau for rich visuals
* Streamlit for live exploration

---

## 📈 Sample Dashboards

| Tableau                   | Streamlit             |
| -------------------------------- | --------------------------------- |
| 📍 Shipment Maps + Delay Filters | 💡 Forecast & Delay Thresholds    |
| 💸 Cost Distributions by Mode    | 🗭 Vendor Performance Comparisons |
| 📦 Inventory Levels by Warehouse | 📊 Interactive Bar/Line KPIs      |

---

### 🔗 Live Tableau Dashboard

Explore the full interactive dashboard on Tableau Public:

👉 [View Dashboard on Tableau Public]([https://public.tableau.com/app/profile/YOUR_USERNAME/viz/YOUR_DASHBOARD_NAME](https://public.tableau.com/views/SupplyChainOptimizationPlatform/VendorPerformanceOverview?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link))

---

## 📊 Insights Discovered

* Road transport is cheapest but least reliable
* Certain vendors showed >25% delay rate
* Shipment volume follows weekly cycles
* SKUs 003 & 004 were consistently understocked
* Cost/km outliers flagged poorly optimized routes

---

## 🧠 Additional Analysis & Insights from Our Backend

### 🧠 Vendor Efficiency Index

We created a custom **Efficiency Index**:

```
Efficiency Index = (Total Shipments ÷ (Avg Delay Days + 1)) × Performance Score
```

This helped rank vendors based on speed, reliability, and volume.

📈 *Top Vendors with Highest Efficiency Index*

---

### 🛠 Inventory Stability Score

To detect unstable SKUs, we calculated:

```
Stability Score = Stock Level ÷ (Lead Time × Days Since Last Update)
```

Lower scores indicate **high-risk inventory** due to outdated updates, long restock times, and low availability.



### 🚨 Shipment Cost Anomaly Detection

We applied **Z-score analysis** to flag unusually high or low shipment costs.

> ❗ *Shipments beyond ±3 Z-scores were identified as potential fraud, logging errors, or route issues.*

---

## 📌 Why This Project Stands Out

* 🔄 Full-stack ETL + analytics pipeline (simulated data, real logic)
* 🌐 Realistic dashboard scenarios for ops teams
* 📉 Live forecasting + delay detection
* 🧹 Built for future extension to APIs and real-time ingestion

---

## 🌱 Future Enhancements

* Real-time route APIs (Google/ORS)
* Daily auto-refresh from database
* Public Streamlit + Tableau Cloud deployment
