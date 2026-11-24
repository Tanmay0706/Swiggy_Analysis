# 🧡 Swiggy Food Delivery Analytics Dashboard | Power BI

## 📌 Project Overview

The **Swiggy Food Delivery Analytics Dashboard** is an interactive 7-page Power BI project designed to analyze food delivery data and provide meaningful insights into orders, revenue, customer growth, cuisine performance, delivery efficiency, and demand patterns.

This dashboard enables users to explore the business through interactive visualizations, helping identify top cities, peak ordering hours, best-performing cuisines, and areas where delivery can be improved.

---

## 🎯 Objectives

- Analyze food delivery orders and revenue.
- Identify top-performing cities, services, and cuisines.
- Monitor sales and customer growth trends over time.
- Understand peak demand by hour, day, and quarter.
- Evaluate delivery time and delivery rating across cities.
- Build an interactive Business Intelligence dashboard using Power BI.

---

## 📊 Dashboard Features

- 🏠 Overview Page with Headline KPIs
- 💡 Insights Page (Peak Day, Fastest City, Highest Rated Cuisine)
- 💰 Revenue Analysis by City, Service & Payment Mode
- 👥 Customer Growth & Distribution
- 🍽️ Menu & Cuisine Performance
- 🛵 Delivery Time & Rating Analysis
- 📈 Demand Analysis by Hour, Day & Quarter
- 🗺️ Order Footprint Map by City
- 🎛️ Interactive Filters & Slicers (City, Service, Year)
- 🧭 Page Navigation Buttons
- 🎨 Custom Swiggy Orange Theme

---

## 📄 Dashboard Pages

| Page | Description |
|------|-------------|
| **Overview** | KPI cards, sales trend, city map, orders by service, payment mode, hour & city, city scorecard |
| **Insights** | Peak ordering day, fastest city, highest rated cuisine, delivery time vs rating, top 5 cuisines |
| **Revenue** | Net revenue trend, revenue by city and quarter, sale share by payment mode and service |
| **Customers** | Customer growth by month, customers by city, day of week, payment mode and service |
| **Menu** | Net revenue by cuisine, AOV by cuisine, cuisine scorecard, cuisine map, restaurants by city |
| **Delivery** | Avg delivery time and rating by hour, city, day of week and service |
| **Demand** | Order trend, AOV by hour, orders by day and service, service ranking by quarter |

---

## 📈 Key Performance Indicators (KPIs)

- Total Orders
- Total Customers
- Total Restaurants
- Total Sale
- Net Revenue
- Average Order Value
- Average Delivery Time
- Average Delivery Rating
- Average Restaurant Rating
- Peak Ordering Day
- Fastest City
- Highest Rated Cuisine

---

## 📷 Dashboard Preview

### Overview
<img width="1127" height="663" alt="Screenshot 2026-11-24 122645" src="https://github.com/user-attachments/assets/98c5a3be-bb8c-47ff-887d-d8a50e390b25" />

### Insights
<img width="1127" height="662" alt="Screenshot 2026-11-24 122714" src="https://github.com/user-attachments/assets/32848238-c88f-45bb-8d4d-9fd44a848eeb" />

### Revenue
<img width="1128" height="653" alt="Screenshot 2026-11-24 122743" src="https://github.com/user-attachments/assets/6921ea8f-a67d-4c19-a237-ba4edcbf7063" />

### Customers
<img width="1122" height="657" alt="Screenshot 2026-11-24 122806" src="https://github.com/user-attachments/assets/c7eb8772-cec7-4131-b8f2-94753837c5ec" />

### Menu
<img width="1125" height="660" alt="Screenshot 2026-11-24 122835" src="https://github.com/user-attachments/assets/0492a6b0-0fd3-40bb-a064-8c1a88a06996" />

### Delivery
<img width="1130" height="660" alt="Screenshot 2026-11-24 122901" src="https://github.com/user-attachments/assets/b12faee0-0d20-4596-ada4-cb0549298389" />

### Demand
<img width="1121" height="657" alt="Screenshot 2026-11-24 122924" src="https://github.com/user-attachments/assets/c3bd1c33-901d-4522-800d-56941163e03f" />

---

## 🛠️ Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Star Schema Data Modeling
- Microsoft Excel / CSV
- Data Visualization

---

## 🗂️ Data Model

The model follows a **star schema** with one fact table and multiple dimension tables:

- **Fact_Orders** – order-level data (order hour, delivery time)
- **Dim_Date** – date, year, quarter, month-year, day name
- **Dim_City** – city names
- **Dim_Service** – service type
- **Dim_PaymentMode** – payment modes
- **Dim_Menu** – cuisines
- **Dim_Restaurant** – restaurant details
- **_Measures** – dedicated table for all DAX measures

---

## 📊 Dashboard Insights

The dashboard provides valuable insights such as:

- Sales and net revenue trends over time
- Top-performing cities by orders and revenue
- Peak ordering hours and busiest days of the week
- Most popular services and payment modes
- Highest rated and highest revenue cuisines
- Relationship between delivery time and customer rating
- Customer growth across months and cities
- Fastest and slowest delivery cities

---

## 📚 Skills Demonstrated

This project showcases the following skills:

- Data Cleaning
- Data Transformation
- Data Modeling (Star Schema)
- DAX Measures
- Power Query
- Interactive Dashboard Design
- KPI Development
- Business Intelligence
- Data Storytelling
- Data Visualization

---

## 💼 Business Use Cases

- Food Delivery Operations Analytics
- City-wise Performance Tracking
- Delivery Time Optimization
- Menu & Cuisine Performance Analysis
- Demand Forecasting Support
- Data-Driven Decision Making

---

## 📌 Future Improvements

- Real-time data integration
- Customer segmentation (RFM analysis)
- Discount and offer impact analysis
- Delivery partner performance tracking
- Predictive analytics using Machine Learning

---

## 🚀 How to Use

1. Download or clone this repository.
2. Open `swiggy_dashboard_git.pbix` in **Power BI Desktop**.
3. Use the page navigator and slicers to explore the dashboard.

---

## 🤝 Contributing

Contributions are welcome!

1. Fork this repository.
2. Create a new feature branch.
3. Commit your changes.
4. Push the branch.
5. Open a Pull Request.
