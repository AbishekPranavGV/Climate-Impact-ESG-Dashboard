# 🌍 Intelligent ESG & Logistics Decision System

A real-time monitoring dashboard that integrates **Environmental, Social, and Governance (ESG) metrics into logistics operations. This system fetches live weather and air quality data to calculate sustainability risk scores for shipments.



## 🚀 Features
- **Live Environmental Integration:** Connects to OpenWeather API for real-time AQI, Temperature, and Wind Speed data.
- **Carbon Footprint Calculator:** Estimates CO2 emissions based on fuel type (Diesel, Petrol, Electric) and distance.
- **Sustainability Risk Index:** A weighted algorithm that assesses environmental risk to provide operational "Proceed" or "Delay" decisions.
- **Persistent Data Logging:** Uses SQLite to track historical shipment data and risk trends.
- **Interactive Analytics:** Visualizes risk trends and emission patterns over time using Plotly.

## 🛠️ Tech Stack
- **Frontend:** Streamlit
- **Data Handling:** Pandas, SQLite
- **Visualizations:** Plotly Express
- **API:** OpenWeather (Weather & Air Pollution)

## 📦 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/Climate-Impact-ESG-Dashboard.git](https://github.com/AbishekPranavGV/Climate-Impact-ESG-Dashboard.git)
   cd Climate-Impact-ESG-Dashboard
