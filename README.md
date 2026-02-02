# Power-Bi-Project
# 🚖 Uber Analytics Dashboard using Power BI

An end-to-end **Business Intelligence project** built using **Microsoft Power BI**, analyzing Uber ride booking data to uncover insights related to **revenue performance, booking efficiency, trip behavior, location demand, and customer experience**.

This project demonstrates real-world **data cleaning, modeling, DAX calculations, and interactive dashboard design** with a professional Uber-themed UI.

---

## 📌 Project Overview

Uber generates large volumes of operational data every day. Analyzing this data helps businesses:
- Optimize revenue streams
- Improve ride efficiency
- Enhance customer satisfaction
- Identify high-demand locations and time periods

This project converts raw Uber ride data into **actionable insights** using Power BI.

---

## 🎯 Objectives

- Analyze overall **revenue and booking performance**
- Measure **ride completion and cancellation trends**
- Evaluate **trip efficiency** using pickup and trip duration
- Understand **location-based demand**
- Assess **customer and driver experience** through ratings
- Build a **multi-page interactive Power BI dashboard**

---

## 🛠 Tools & Technologies

- **Microsoft Power BI Desktop**
- **Power Query (M Language)** – Data cleaning & transformation
- **DAX (Data Analysis Expressions)** – KPI calculations
- **CSV Dataset (Kaggle – Uber Rides Data)**

---

## 📂 Dataset Description

The dataset includes the following key fields:

- Booking ID  
- Date & Time  
- Booking Status (Completed, Cancelled, etc.)
- Vehicle Type  
- Pickup Location  
- Drop Location  
- Ride Distance (km)  
- Booking Value  
- Payment Method  
- Customer Rating  
- Driver Rating  

---

## 🔄 Data Preprocessing

Performed using **Power Query**:
- Removed irrelevant columns
- Handled null values
- Corrected data types
- Created new columns:
  - Month
  - Hour
  - Time Slot (Morning, Afternoon, Evening, Night)
- Formatted currency, distance, and percentage values

---

## 📐 KPI Metrics (DAX)

Key measures created:

- **Total Revenue**
- **Total Bookings**
- **Completed Rides**
- **Cancelled Rides**
- **Completion Rate (%)**
- **Average Revenue per Ride**
- **Average Pickup Time (VTAT)**
- **Average Trip Duration (CTAT)**
- **Average Customer Rating**
- **Average Driver Rating**

---

## 📊 Dashboard Pages & Insights

### 📄 Page 1: Revenue Performance
**Insights:**
- Identifies top revenue-generating vehicle types
- Shows monthly revenue trends
- Highlights peak revenue time slots
- Displays payment method contribution to revenue

---

### 📄 Page 2: Booking & Completion Analysis
**Insights:**
- Booking vs completion comparison
- Hour-wise demand analysis
- Cancellation patterns by status
- Vehicle-type booking distribution

---

### 📄 Page 3: Trip Efficiency (Completed Rides Only)
**Insights:**
- Pickup time (VTAT) by vehicle type
- Trip duration (CTAT) analysis
- Ride distance trends by month
- Efficiency comparison across vehicle categories

---

### 📄 Page 4: Location Demand Analysis
**Insights:**
- High-demand pickup locations
- Booking density by region
- Revenue and distance patterns by location

---

### 📄 Page 5: Ratings & Customer Experience
**Insights:**
- Average customer and driver ratings
- Rating comparison by vehicle type
- Relationship between pickup time and customer satisfaction

---

## 🎨 Dashboard Design

- Uber-themed dark UI
- Glassmorphism-style KPI cards
- Consistent color palette
- Custom PNG icons
- Interactive slicers (Month, Vehicle Type, Booking Status, Location)
- Professional layout aligned with real-world BI standards

---

## ✅ Advantages

- Real-world business analytics use case
- Interactive and user-friendly dashboards
- Strong demonstration of Power BI, DAX, and visualization skills
- Suitable for academic submission and portfolio projects

---

## ⚠ Limitations

- Static dataset (no real-time data)
- External factors like weather and traffic not included
- Limited to available columns in the dataset

---

## 🔮 Future Enhancements

- Integration with real-time Uber APIs
- Demand forecasting using Machine Learning
- Driver performance analytics
- Predictive cancellation analysis
- AI-based route optimization

---

## 📘 Conclusion

This project showcases how **Power BI transforms raw Uber ride data into meaningful business insights**. The dashboards support data-driven decision-making by analyzing revenue, efficiency, customer experience, and demand patterns in a visually intuitive way.

---

## 📎 References

- Microsoft Power BI Documentation  
- Kaggle – Uber Dataset  
- Data Visualization Best Practices  

---

⭐ *If you like this project, feel free to star the repository!*
