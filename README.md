# 🚖 Real-Time Uber Analysis Dashboard

An interactive and real-time data analytics dashboard built using **Power BI** to explore and monitor Uber trip data. The project includes **three distinct dashboards** offering comprehensive insights into operational efficiency, peak time behavior, and granular trip-level analysis. These dashboards are ideal for decision-makers looking to optimize fleet management, understand time-based demand trends, and monitor trip-level performance.

---

## 📊 Dashboard Views

### 1️⃣ **Overview Analytics Dashboard**
- 🚗 Total Trips, Revenue, Active Drivers
- 📍 Most Popular Pickup & Drop Locations
- 🧭 Map Visuals for Trip Density
- 🧮 Average Trip Duration and Distance
- 📊 Key Metrics Cards and Pie Charts

### 2️⃣ **Time Analytics Dashboard**
- 🕒 Trips per Hour, Day, Week, and Month
- 🔁 Peak Hours and Idle Hours Analysis
- 🗓️ Seasonal and Monthly Patterns
- 📈 Line Graphs and Bar Charts for Time-Based Trends
- ⏱️ Average Wait Times by Hour and Day

### 3️⃣ **Details Dashboard**
- 🧾 Individual Trip Data View
- 👤 Customer and Driver-level Drill-through
- 📌 Filter by Location, Time, Status (Completed/Cancelled)
- 🔎 Interactive Table with Sorting, Filtering, and KPI Highlights

---

## 🧰 Tools & Technologies

- **Power BI Desktop**
- **Power Query** for data cleaning and transformation
- **DAX** (Data Analysis Expressions) for measures and KPIs
- **CSV / Excel** files as the data source

---

## 📁 Folder Structure

uber-dashboard/
│
├── Uber_data_dashboard.pbix # Power BI dashboard file
├── data/
│ └── Uber Trip Details.xlsx # Sample trip data
| └── Location Table.xlsx # Sample Location data
├── visuals/
│ └── Overview_analysis # Dashboard preview images
│ └── Time_analysis # Dashboard preview images
│ └── Details # Dashboard preview images
├── README.md # Project documentation


---

## 📦 Dataset Overview

The sample dataset includes the following columns:

- Trip ID, Pickup Location, Dropoff Location
- Request Timestamp, Dropoff Timestamp
- Trip Duration, Distance, Status (Completed/Cancelled)
- Driver ID, Customer ID, Vehicle Type
- Revenue, Payment Mode

---

## ✅ How to Use

1. Open `Uber_data_dashboard.pbix` in **Power BI Desktop**.
2. If prompted, reconnect the source to `data/uber_trip_data.csv`.
3. Explore the **Overview**, **Time Analytics**, and **Details** dashboards.
4. Use **slicers, filters, and drill-through** features to dig deeper.
5. Replace the sample dataset with your own Uber trip data (same format) for real-time applicability.

---

## 📌 Use Cases

- Monitor real-time trip activity and volume
- Understand traffic and demand by time of day
- Analyze driver and customer behavior patterns
- Support decisions for dynamic pricing and resource allocation

---

## 🔮 Future Enhancements

- Connect with a live data stream or real-time API
- Integrate **Power BI Alerts** for abnormal activity
- Use **AI visuals** for forecasting and anomaly detection
- Embed dashboards into internal web portals or SharePoint

---

## 🤝 Acknowledgments

Thanks to Power BI community forums, open datasets from ride-sharing sources, and contributors who inspired dashboard design techniques.

---

## 📬 Contact

📧 nakranigrina37@gmail.com  
For feedback, data contributions, or collaboration opportunities.

---
