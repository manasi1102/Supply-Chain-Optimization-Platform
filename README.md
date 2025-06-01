# Supply-Chain-Optimization-Platform

> Built by two data science grads — Hema Manasi Potnuru & Mahimna Darji — This imulates and visualizes a full-scale supply chain system using Python, MongoDB, Tableau, and Streamlit. It's what logistics dashboards should look like in 2025.

---

## 🔍 Project Overview

Supply chains are complex, messy, and sensitive to delay, cost, and demand fluctuations. We built this to:
- Simulate a logistics operation across the U.S.
- Perform advanced analytics on delivery, cost, and inventory
- Forecast future demand and flag delays or stockouts
- Present interactive insights using Tableau and Streamlit

---

## 👨‍💻 Authors
- **Hema Manasi Potnuru**
- **Mahimna Darji** 

---

## 🛠️ Tech Stack

| Layer         | Tools Used                            |
|---------------|----------------------------------------|
| Data Storage  | MongoDB Atlas                          |
| Backend       | Python, pandas, Prophet, pymongo       |
| Dashboards    | Tableau, Streamlit                     |
| GeoMapping    | Folium                                 |
| Development   | Google Colab, Jupyter Notebook         |

---

## 📦 Features Built

### ✅ Inventory Forecasting
- Forecast SKU demand using Prophet
- Risk scoring for understocked items
![Dashboard Overview](AvgInventory-DB.jpg)

### ✅ Shipment Analytics
- Visual shipment tracking map
- Delay anomaly detection
- Rolling shipment trends
![Dashboard Overview](Shipment-DB.jpg)

### ✅ Cost Optimization
- Distance vs. cost modeling
- Mode-wise cost comparison
![Dashboard Overview](Cost-DB.jpg)

### ✅ Vendor Insights
- Performance radar charts
- Delay vs reliability trade-offs
![Dashboard Overview](Vendor-DB.jpg)

### ✅ Dashboards
- Tableau for rich visuals
- Streamlit for live exploration

---

## 📈 Sample Dashboards

| Tableau (Top)                        | Streamlit (Bottom)                 |
|-------------------------------------|------------------------------------|
| 📍 Shipment Maps + Delay Filters     | 💡 Forecast & Delay Thresholds     |
| 💸 Cost Distributions by Mode        | 🧭 Vendor Performance Comparisons   |
| 📦 Inventory Levels by Warehouse     | 📊 Interactive Bar/Line KPIs       |

> 🔼 Include screenshots of each dashboard here (e.g., from Tableau Workbook or Streamlit output)

---

## 📊 Insights Discovered

- Road transport is cheapest but least reliable  
- Certain vendors showed >25% delay rate  
- Shipment volume follows weekly cycles  
- SKUs 003 & 004 were consistently understocked  
- Cost/km outliers flagged poorly optimized routes

---

## 📌 Why This Project Stands Out

- 🔄 Full-stack ETL + analytics pipeline (simulated data, real logic)
- 🌐 Realistic dashboard scenarios for ops teams
- 📉 Live forecasting + delay detection
- 🧩 Built for future extension to APIs and real-time ingestion

---

## 🌱 Future Enhancements
-Real-time route APIs (Google/ORS)
-Daily auto-refresh from database
-Public Streamlit + Tableau Cloud deployment
