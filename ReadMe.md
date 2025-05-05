# 🏨 Hotel Booking Cancellation Analysis using Python & Power BI

This project analyzes hotel booking data to uncover insights into customer behavior, cancellation patterns, and business performance. The analysis is performed using both **Python (Jupyter Notebook)** for detailed exploratory analysis and **Power BI** for interactive dashboard visualizations.

---

## 📁 Project Overview

**Objective:**  
To understand key factors affecting hotel booking cancellations, including lead time, booking channels, customer types, and seasonal trends, using data-driven insights.

---

## 📊 Dataset

- **Source:** [Hotel Booking Demand Dataset - Kaggle](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand)
- **Size:** ~119,000 records
- **Columns:** 32 features including:
  - `hotel`: Resort Hotel or City Hotel
  - `is_canceled`: 1 if booking was canceled, 0 otherwise
  - `lead_time`, `arrival_date_month`, `stays_in_weekend_nights`, `market_segment`, `customer_type`, `deposit_type`, `adr` (average daily rate), etc.

---

## ⚙️ Tools & Technologies

- 🐍 **Python** (Jupyter Notebook)
  - Pandas, NumPy, Matplotlib, Seaborn
- 📊 **Power BI**
  - For interactive visualizations and business dashboards

---

## 🧪 Analysis in Python

The Python notebook covers:

- ✅ Data cleaning (handling missing values, outliers)
- 📈 Exploratory Data Analysis (EDA)
- 🔍 Key metrics and visualizations:
  - Cancellation rate by hotel type
  - Lead time vs cancellation
  - Market segment impact
  - Booking trends over months/seasons
  - Country-wise booking distribution
- 📌 Correlation analysis to identify strong predictors of cancellation

> All insights were documented step-by-step with graphs and interpretations.

---

## 📈 Power BI Dashboard

The Power BI dashboard includes:

- 📅 **Booking trends by month and year**
- 🌍 **Geographic distribution** of bookings and cancellations
- 🏨 **Hotel type analysis** (City vs Resort)
- 📉 **Cancellation rate comparison** by:
  - Market segment
  - Deposit type
  - Customer type
- 📊 **Average Daily Rate (ADR)** by booking status

> The dashboard is designed to be fully interactive with slicers and filters for users to explore patterns on their own.

---

## 📌 Key Insights

- Resort hotels have higher cancellation rates than city hotels.
- Longer lead times correlate with more cancellations.
- Customers without deposits cancel more frequently.
- Most cancellations occur in summer months.
- Online travel agents (OTAs) have the highest cancellation ratio.

---

## 🚀 How to Run the Project

### 🐍 Python (Jupyter Notebook)

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/hotel-booking-analysis.git
   cd hotel-booking-analysis

