# Smart Urban Mobility & Transit Analytics Using Power BI

## 📌 Project Overview

The **Mobility & Transit Analytics** project is an interactive business intelligence solution developed using Microsoft Power BI. It analyzes transportation patterns, passenger demand, route performance, geographic mobility, and the influence of weather conditions on mobility.

The project transforms raw mobility data into meaningful insights through data cleaning, data modeling, DAX calculations, and interactive visualizations.

## 🎯 Project Objectives

- Analyze passenger demand and transportation patterns.
- Evaluate route and transit performance.
- Explore geographic mobility trends across cities and regions.
- Understand the relationship between weather conditions and passenger demand.
- Compare transportation modes and identify demand patterns.
- Present actionable insights through interactive dashboards.

## 📊 Dashboards

### 1. Geospatial & Transit Analytics

This dashboard focuses on geographic mobility and transit performance.

**Key Features:**
- Geographic analysis of mobility patterns.
- Route-wise passenger demand and performance analysis.
- City and region-based filtering.
- Weather overlays and weather-related mobility analysis.
- Time-based analysis of transportation trends.

### 2. Demand Intelligence & Mobility Analytics

This dashboard focuses on passenger demand and transportation behavior.

**Key Features:**
- Passenger demand and trip analysis.
- Transportation mode comparisons.
- City-wise and route-wise demand analysis.
- Weather sensitivity analysis.
- Time-based demand trends and forecasting-related metrics.

## 🛠️ Tools & Technologies

- **Microsoft Power BI** – Interactive dashboards and reporting.
- **Power Query** – Data cleaning, transformation, and preparation.
- **DAX (Data Analysis Expressions)** – Measures, KPIs, and analytical calculations.
- **Star Schema Data Modeling** – Fact and dimension tables for structured analysis.
- **Data Visualization** – Charts, KPI cards, slicers, and geographic visuals.

## 🗂️ Data Model

The project uses a star schema to organize mobility data and support analytical reporting.

**Fact Table**
- `Fact_Mobility` – Contains mobility-related measurements such as passenger count, temperature, rainfall, and other available operational attributes.

**Dimension Tables**
- `DIM_Date` – Date-based analysis.
- `DIM_Location` / `DIM_City` – Geographic and city-level analysis.
- `DIM_Weather` – Weather condition analysis.
- `DIM_Vehicle` – Transportation and vehicle-related analysis.
- `DIM_Route` – Route-level analysis.

*Note: Table names and attributes may vary slightly depending on the final Power BI model.*

## 📈 Key Analytical Areas

- Passenger demand analysis.
- Geographic and regional mobility patterns.
- Route performance comparison.
- Weather and mobility relationships.
- Transportation mode analysis.
- KPI monitoring and interactive filtering.

## 🚀 How to Explore the Project

1. Clone or download this GitHub repository.
2. Install [Microsoft Power BI Desktop](https://www.microsoft.com/power-platform/products/power-bi/desktop).
3. Open the `.pbix` report file.
4. If prompted, update the data source paths to match your local dataset location.
5. Refresh the data if the required source files are available.
6. Explore the dashboards using slicers, filters, charts, and KPI cards.

## 📁 Repository Structure

```text
PowerBI-Mobility-Analytics/
│
├── Mobility_Transit_Analytics.pbix
├── Demand_Intelligence_Analytics.pbix
├── README.md
│
├── Dataset/
│   └── sample_mobility_data.csv
│
├── Documentation/
│   ├── Dashboard_1_Documentation.docx
│   └── Dashboard_2_Documentation.docx
│
└── Screenshots/
    ├── Dashboard_1.png
    └── Dashboard_2.png
```

*The structure above is illustrative. It should match the files actually uploaded to the repository.*

## 💡 Project Learning Outcomes

- Practical experience in Power BI dashboard development.
- Data cleaning and transformation using Power Query.
- Data modeling using fact and dimension tables.
- DAX-based KPI and measure development.
- Interactive reporting and data visualization.
- Translating transportation data into meaningful analytical insights.

## 👨‍💻 Author

**Asif Khan**

B.Tech – Computer Science & Engineering

**Areas of Interest:** Data Analytics, Business Intelligence, Data Visualization, and Artificial Intelligence.

---

⭐ If you find this project useful, feel free to explore the dashboards and documentation in this repository.
