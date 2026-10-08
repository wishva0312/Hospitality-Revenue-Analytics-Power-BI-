# 🏨 Hospitality Revenue & Performance Dashboard

An interactive **Power BI dashboard** designed to analyze hotel revenue, booking performance, occupancy, pricing, and realization across properties and booking platforms.

The project focuses on turning hotel booking data into clear business insights through KPI cards, trend analysis, property-level performance, and interactive filters.

---

## 📊 Project Overview

This dashboard provides a consolidated view of hospitality performance and helps answer questions such as:

- How is hotel revenue performing?
- What is the current ADR, RevPAR, and Occupancy?
- How efficiently are bookings being realized?
- Which properties are performing better or worse?
- How do booking platforms compare in terms of ADR and Realisation %?
- How do key hospitality metrics change over time?
- How does performance differ by hotel city, room type, and day type?

---
## 🔗 Live Power BI Dashboard

Explore the interactive dashboard here:

**[View Live Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiOTliM2Q0YzItMWI3YS00M2I4LWE4MzMtNmUwNzQwYWU0NGM2IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)**

---
## 🖥️ Dashboard Pages

### 🏠 Home Page
A simple landing page that introduces the dashboard and provides navigation to the main analysis.

### 📈 Main Dashboard
The main analytical page contains:

- Revenue
- ADR (Average Daily Rate)
- RevPAR (Revenue per Available Room)
- Occupancy %
- Realisation %
- DSRN (Daily Sellable Room Nights)
- Week-over-Week KPI changes
- Trend by Key Metrics
- Property Performance
- Revenue by Hotel Category
- ADR & Realisation % by Booking Platform
- Day Type performance
- Interactive filters for:
  - City
  - Room Type
  - Room Date / Month
  - Week

---

## 🔑 Key KPIs

| KPI | Description |
|---|---|
| **Revenue** | Total revenue generated from hotel bookings. |
| **ADR** | Average revenue earned per occupied room. |
| **RevPAR** | Revenue generated per available room and a key measure of hotel revenue efficiency. |
| **Occupancy %** | Percentage of available rooms that were occupied. |
| **Realisation %** | Percentage of bookings that were successfully realized after considering cancellations and no-shows. |
| **DSRN** | Daily Sellable Room Nights available for sale. |
| **DBRN** | Daily Booked Room Nights. |
| **DURN** | Daily Utilized Room Nights. |
| **Cancellation %** | Percentage of bookings that were cancelled. |
| **Average Rating** | Average customer rating associated with a property. |

---

## 📌 Key Visuals

### KPI Cards
The dashboard tracks major KPIs with **Week-over-Week change indicators**, making it easier to identify whether performance is improving or declining.

### Trend by Key Metrics
A time-based line chart compares:

- RevPAR
- ADR
- Occupancy %

This helps identify changes in pricing, room utilization, and revenue efficiency over time.

### Property Performance
A detailed property-level table includes:

- Property ID
- Property Name
- City
- Revenue
- Total Bookings
- Occupancy %
- Cancellation %
- Realisation %
- DSRN
- DBRN
- DURN
- Average Rating

### Booking Platform Analysis
A combination chart compares **ADR and Realisation % across booking platforms**, helping identify differences in pricing and booking effectiveness.

### Revenue by Hotel Category
A donut chart shows how revenue is distributed across hotel categories.

### Day Type Analysis
The dashboard compares key metrics across different day types using:

- RevPAR
- Occupancy %
- Realisation %
- ADR

---

## 🎛️ Interactive Filters

Users can dynamically filter the dashboard using:

- **City**
- **Room Type**
- **Month / Room Date**
- **Week**

These filters allow users to analyze specific locations, room categories, and time periods.

---

## 🛠️ Tools & Technologies

- **Power BI Desktop**
- **DAX**
- **Power Query**
- **Data Modeling**
- **Interactive Data Visualization**
- **KPI & Trend Analysis**

---

## 🧮 Data Modeling & DAX

The report uses a dimensional data model with entities including:

- `fact_bookings`
- `dim_date`
- `dim_hotels`
- `dim_rooms`
- `key_measures`

DAX measures are used to calculate and present hospitality KPIs, Week-over-Week changes, and analytical metrics.

---

## 💡 Business Insights This Dashboard Can Support

The dashboard can help hotel management and analysts:

- Monitor overall revenue performance.
- Evaluate pricing through ADR.
- Measure revenue efficiency using RevPAR.
- Track room utilization through Occupancy %.
- Identify booking realization issues.
- Compare hotel properties and cities.
- Evaluate booking platform performance.
- Analyze weekday/weekend or day-type differences.
- Identify changes in performance over time.
- Support data-driven revenue and operational decisions.

---

## 🎯 Project Objective

The objective of this project is to build an interactive hospitality analytics dashboard that transforms hotel booking data into meaningful KPIs and business insights.

The project demonstrates practical skills in **Power BI, DAX, data modeling, data visualization, KPI development, and business analysis**.

---

## 👤 Author

**Jadhav Vishwateja Nayak**

Aspiring Data Analyst | Artificial Intelligence & Machine Learning

**Skills:** Power BI • DAX • SQL • Excel • Data Analysis • Data Visualization

---

## ⭐ If You Like This Project

If you find this project useful, feel free to ⭐ the repository and explore the dashboard.
