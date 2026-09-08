# 🚕 OLA Ride Analytics Dashboard | Power BI

> An interactive Power BI dashboard designed to analyze OLA ride performance, revenue, cancellations, customer payment preferences, ride demand, peak hours, and high-demand pickup locations.

---

## 📌 Project Overview

This project is an end-to-end **OLA Ride Analytics Dashboard** developed using **Microsoft Power BI**.

The project started with raw ride data available in **Microsoft Excel**. The data was first transformed and cleaned using **Power Query** to make it suitable for analysis. After data preparation, **DAX measures and KPIs** were created to calculate important business metrics and an interactive Power BI dashboard was designed to convert the raw data into meaningful business insights.

The main goal of this project is to understand **ride demand, revenue performance, cancellation trends, customer payment behavior, peak hours, and high-demand locations** through interactive data visualization.

---

# 🎯 Project Objective

The objective of this project is to analyze OLA ride data and answer important business questions such as:

- How many rides were booked?
- How many rides were successfully completed?
- How many rides were cancelled?
- What is the overall cancellation rate?
- How much revenue was generated?
- What is the average ride value?
- Which pickup locations have the highest demand?
- Which day of the week has the highest ride volume?
- What is the peak ride-demand hour?
- Which payment method is most preferred by customers?
- How can the business improve operational efficiency?

---

# 🔄 Project Workflow

The complete project follows an end-to-end data analytics workflow:

**Raw Excel Data**  
⬇️  
**Data Import into Power BI**  
⬇️  
**Data Cleaning & Transformation using Power Query**  
⬇️  
**Data Preparation & Modeling**  
⬇️  
**DAX Measures & KPI Creation**  
⬇️  
**Interactive Dashboard Development**  
⬇️  
**Business Insights & Recommendations**

---

# 🧹 Data Cleaning & Transformation

The raw data was imported from **Microsoft Excel** into Power BI.

Using **Power Query**, the data was prepared for analysis by performing activities such as:

- Removing unnecessary or invalid records
- Handling missing and inconsistent values
- Correcting data types
- Formatting date and time fields
- Cleaning categorical fields
- Preparing columns required for analysis
- Creating useful fields for time-based analysis
- Ensuring the dataset was structured properly for reporting

This step helped convert the raw dataset into a clean and analysis-ready format.

---

# 🧮 DAX & KPI Development

DAX was used to create calculated measures and important business KPIs.

Key metrics include:

- Total Rides
- Completed Rides
- Cancelled Rides
- Total Revenue
- Average Ride Value
- Cancellation Rate
- Ride Volume by Day
- Ride Volume by Hour
- Payment Type Distribution
- Top Pickup Locations

These measures make the dashboard dynamic and allow the insights to change according to selected filters.

---

# 📊 Dashboard KPIs

| KPI | Value |
|---|---:|
| 🚕 Total Rides | 117K |
| ✅ Completed Rides | 97.8K |
| ❌ Cancelled Rides | 18.96K |
| 💰 Total Revenue | ₹14.77M |
| 💵 Average Ride Value | ₹126.43 |
| 📉 Cancellation Rate | 16.2% |

---

# 🔎 Dashboard Analysis

## 🚕 Ride Performance

The dashboard contains approximately **117K total rides**, out of which around **97.8K rides were successfully completed**.

This indicates that the majority of ride bookings were successfully converted into completed rides.

---

## ❌ Cancellation Analysis

Approximately **18.96K rides were cancelled**, resulting in an overall cancellation rate of **16.2%**.

This highlights cancellation as an important area for operational improvement.

Reducing cancellations can potentially improve customer satisfaction, ride completion, and revenue performance.

---

## 💰 Revenue Analysis

The dashboard shows approximately **₹14.77M in total revenue**, with an average ride value of **₹126.43**.

Revenue analysis helps understand the overall financial performance of the rides and the average value generated per ride.

---

## 📍 Pickup Location Analysis

**Koramangala** recorded the highest pickup demand with approximately **11.7K rides**.

Other major high-demand locations include:

- HSR Layout – 9.1K
- Whitefield – 8.5K
- Electronic City – 8.1K
- Indiranagar – 7.1K
- Marathahalli – 6.1K

These locations can be considered important areas for driver availability and demand planning.

---

## 📅 Day-wise Ride Analysis

The analysis shows that **Friday** recorded the highest ride volume with approximately **19.2K rides**.

Ride volume by day:

| Day | Rides |
|---|---:|
| Friday | 19.2K |
| Wednesday | 18.4K |
| Tuesday | 17.8K |
| Thursday | 17.5K |
| Saturday | 16.6K |
| Sunday | 14.2K |
| Monday | 13.0K |

This indicates that ride demand varies across different days of the week.

---

## ⏰ Peak Hour Analysis

The hourly analysis identifies **7:00 PM** as the peak ride-demand period.

This suggests that evening hours are particularly important for demand management and driver allocation.

---

## 💳 Payment Type Analysis

**UPI** is the most preferred payment method, contributing approximately **49.23% of total rides**.

Payment distribution:

- UPI – 49.23%
- Cash – 22.67%
- Card – 20.81%
- Ola Money – 7.30%

The high UPI share indicates strong customer adoption of digital payments.

---

# 💡 Key Business Insights

### 📍 High-Demand Locations
Koramangala is the leading pickup location with **11.7K rides**, indicating strong customer demand in this area.

### 📅 Busiest Day
Friday has the highest ride volume at approximately **19.2K rides**.

### ⏰ Peak Hour
The highest ride demand is observed around **7 PM**.

### 💳 Payment Preference
UPI is the dominant payment method with approximately **49.23%** of rides.

### ❌ Cancellation Opportunity
A **16.2% cancellation rate** indicates an opportunity to investigate cancellation reasons and improve ride completion.

### 💰 Revenue Performance
The business generated approximately **₹14.77M** in total revenue with an average ride value of **₹126.43**.

---

# 🎯 Business Recommendations

Based on the analysis, the following actions can help improve operational efficiency:

### 1. 🚗 Optimize Driver Allocation
Increase driver availability in high-demand locations such as **Koramangala, HSR Layout, Whitefield, and Electronic City**.

### 2. ⏰ Prepare for Peak Hours
Ensure sufficient driver availability around **7 PM** to handle increased demand.

### 3. 📅 Plan According to Demand
Friday shows the highest ride volume, so driver supply and operational planning can be adjusted accordingly.

### 4. ❌ Reduce Ride Cancellations
Analyze the major reasons behind cancellations and take corrective actions to improve the completion rate.

### 5. 💳 Improve Digital Payment Experience
Since UPI accounts for nearly half of the rides, maintaining a smooth and reliable digital payment experience can improve customer convenience.

---

# 🎛️ Interactive Dashboard Features

The Power BI dashboard includes:

- 📅 Date Range Filter
- 🏙️ City Filter
- 🚦 Ride Status Filter
- 💳 Payment Type Filter
- 🚘 Vehicle Type Filter
- 📈 Rides Over Time
- 📍 Top Pickup Locations
- 🟢 Ride Status Distribution
- 📅 Rides by Day of Week
- ⏰ Rides by Hour of Day
- 💳 Payment Type Distribution
- 📊 KPI Cards
- 🔄 Interactive Slicers

The dashboard is interactive, allowing users to filter the data and explore different business scenarios.

---

# 🛠️ Tools & Technologies

| Tool / Technology | Purpose |
|---|---|
| Microsoft Excel | Raw Data Source |
| Power Query | Data Cleaning & Transformation |
| Power BI | Dashboard Development |
| DAX | Measures & KPI Calculations |
| Data Modeling | Structuring Data for Analysis |
| Data Visualization | Business Insight Presentation |

---

# 📷 Dashboard Preview

![OLA Ride Analytics Dashboard](dashboard.png)

---

# 📚 Key Learning

This project helped strengthen my practical understanding of the complete data analytics process.

The major learning outcomes include:

- Working with raw business data
- Data cleaning and transformation using Power Query
- Creating calculated measures using DAX
- Developing business KPIs
- Designing interactive Power BI dashboards
- Analyzing trends and patterns
- Extracting actionable business insights
- Presenting data through effective visual storytelling

The project demonstrates that **data analytics is not only about creating charts, but about transforming raw data into meaningful information that can support better business decisions.**

---

# 🏁 Conclusion

The **OLA Ride Analytics Dashboard** provides a consolidated view of ride operations and customer behavior.

The analysis identifies key patterns such as:

- High-demand pickup locations
- Peak ride hours
- Busiest days
- Revenue performance
- Cancellation trends
- Customer payment preferences

These insights can help businesses make better decisions related to **driver allocation, demand forecasting, cancellation reduction, revenue optimization, and operational planning**.

---

# 👨‍💻 Author

**Arpan Patra**

### Data Analytics | Power BI | Excel | DAX

---

⭐ If you found this project interesting, feel free to **star ⭐ the repository**.

#PowerBI #DataAnalytics #PowerBIProject #DAX #PowerQuery #Excel #BusinessIntelligence #DataVisualization #DataAnalyst
