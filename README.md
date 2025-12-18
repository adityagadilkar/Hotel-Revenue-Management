# HotelRevAI – AI-Driven Revenue Analysis for Hotels

## 📌 Project Overview

HotelRevAI is an end-to-end **hotel revenue analytics and decision-support system** built using Power BI and structured data modeling techniques. The project transforms raw hotel booking data into actionable insights that help **General Managers (GM)** and **Revenue Managers (RM)** optimize occupancy, pricing, and overall revenue.

The solution integrates **data modeling, KPI analytics, guest segmentation, forecasting, and strategy simulation** into a unified, interactive dashboard framework.

---

## 🎯 Objectives

* Analyze hotel performance using industry-standard KPIs
* Understand guest behavior and booking patterns
* Identify revenue leakage from cancellations and no-shows
* Forecast future occupancy trends
* Support data-driven pricing and upselling strategies

---

## 🗂 Repository Structure

```
HotelRevAI-AI-Driven-Revenue-Analysis-for-Hotels
│
├── Dashboard/                 # Power BI dashboards (GM & RM views)
├── Dataset/                   # Hotel bookings dataset
├── Module 1/                  # Data Modeling & Ingestion
├── Module 2/                  # Occupancy & Revenue Metrics
├── Module 3/                  # Guest Analysis
├── Module 4/                  # Forecasting & Cancellation Trends
├── Module 5/                  # Revenue Strategy Dashboard
├── Presentation/              # Final project presentation
├── LICENSE                    # MIT License
└── README.md                  # Project documentation
```

---

## 🧩 Modules Implemented

### **Module 1: Data Modeling and Ingestion**

* Load booking, customer, room, and hotel branch data
* Design a **Star Schema** with FactBookings at the center
* Dimensions: Date, Room, Customer, Hotel Branch
* Derived fields:

  * Booking duration
  * Room category
  * Stay type

**Business Impact:**

* Ensures data consistency and scalability
* Enables accurate KPI calculations and slicing across dimensions

---

### **Module 2: Occupancy & Revenue Metrics**

* Key KPIs calculated:

  * **Occupancy %**
  * **Average Daily Rate (ADR)**
  * **Revenue per Available Room (RevPAR)**
* Performance analysis across:

  * Daily, weekly, and seasonal trends
  * Booking channels (Direct vs OTA)

**Insights Delivered:**

* Demand seasonality and peak periods
* Pricing strength vs room utilization
* Reduced commission impact through direct bookings

---

### **Module 3: Guest Analysis Module**

* Guest type segmentation:

  * Business
  * Family
  * Solo
* Customer clustering:

  * First-time guests
  * Loyal guests
  * High spenders
* Visual analysis of:

  * Nationality
  * Booking source
  * Stay duration

**Business Value:**

* Identifies high-value customer segments
* Supports targeted marketing and personalization strategies

---

### **Module 4: Forecasting and Cancellation Trends**

* Occupancy trend-based forecasting
* Cancellation rate analysis by time
* Lead time distribution insights
* No-show and refund trend analysis

**Key Outcomes:**

* Highlights revenue leakage risks
* Improves demand planning and overbooking strategies
* Supports proactive cancellation policy design

---

### **Module 5: Revenue Strategy Dashboard**

* Identify upsell opportunities:

  * Spa
  * Dining
  * Add-on services
* Pricing recommendations by:

  * Season
  * Room type
* Interactive **What-If analysis** for:

  * Price uplift
  * Occupancy sensitivity

**End Users:**

* General Managers (strategic overview)
* Revenue Managers (pricing & demand optimization)

---

## 📊 Dashboards Included

* **General Manager Dashboard**

  * Revenue, occupancy, booking status, services, and future outlook

* **Revenue Manager Dashboard**

  * ADR, RevPAR, channel mix, cancellations, and seasonal demand

---

## 🛠 Tools & Technologies

* **Power BI** – Data modeling & visualization
* **DAX** – KPI and calculated measures
* **Star Schema Modeling** – Performance-optimized analytics
* **Excel / CSV Dataset** – Source data

---

## 📈 Key KPIs

* Occupancy %
* ADR (Average Daily Rate)
* RevPAR
* Cancellation Rate
* Lead Time
* No-Show Count
* Refund Count

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 🙌 Author

**Aditya Gadilkar**

---
