# 🏨 Hotel Booking Analysis with Snowflake

**hotel booking analytics pipeline** using **Snowflake** as the cloud data warehouse, from raw CSV ingestion to business-ready analytics and dashboard visualization.

---

## 📌 Project Overview

The goal of this project is to:
- Clean and transform raw hotel booking data
- Build business-ready datasets in Snowflake
- Analyze booking trends, revenue, and customer behavior
- Visualize key KPIs using a dashboard (Snowsight)

---

## 🏗️ System Architecture

![System Architecture](docs/data_architecture.png)

---

## 📊 Dashboard Overview

The dashboard provides both **high-level KPIs** and **detailed analytics**:

### 🔑 Key Metrics
- **Total Revenue**
- **Total Bookings**
- **Total Guests**
- **Average Booking Value**

### 📈 Visual Analytics
- Monthly Revenue Trend
- Monthly Booking Trend
- Top Cities by Revenue
- Bookings by Status (Confirmed / Cancelled / No-show)
- Bookings by Room Type

![Dashboard](docs/dashboard.png)

---

## 🧠 Business Questions Answered

- How does revenue change over time?
- Which cities generate the most revenue?
- What is the distribution of booking statuses?
- Which room types are booked the most?
- What are the overall booking and revenue KPIs?

---

## 🗂️ Project Structure

```text
hotel-booking-analysis-snowflake/
│
├── data/
│   └── hotel_bookings_raw.csv      # Raw input data
│
├── scripts/
│   └── sql/
│       ├── raw_layer.sql           # Raw table creation
│       ├── cleaned_layer.sql       # Data cleaning & transformation
│       └── business_layer.sql      # Business-ready models
│
├── docs/
│   ├── data_architecture.png       # System architecture diagram
│   └── dashboard.png               # Dashboard screenshot
│
├── README.md
└── LICENSE
