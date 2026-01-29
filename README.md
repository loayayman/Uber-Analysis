# Uber Analysis

## 📌 Project Overview
This project provides a data-driven deep dive into Uber's operational performance. It features a sophisticated, user-centric design with a custom-built **Sidebar Navigation Menu** to streamline the analysis of revenue, fleet categories, and geographical trends. 

The project focuses on maximizing profitability by analyzing trip distances, service tiers, and the financial impact of promotional discounts.

---

## 📊 Dashboard Structure
The report is organized into six core analytical modules, accessible via the interactive sidebar:

### 1. Overview
* **High-Level KPIs:** Instant view of total completed bookings,total lost bookings, total revenue, lost percentage, total distance.
* **Trend Overlays:** Time-series analysis of demand fluctuations.
<img width="1281" height="731" alt="image" src="https://github.com/user-attachments/assets/252811cf-2b91-496d-a148-4d9b2bf3a9fd" />


### 2. Revenue
* **Earnings Tracking:** Breakdown of total bookings, revenue for every vehicle, and the most common payment method.
* **Promo Impact:** Analysis of the **Discount** metric to see how marketing campaigns influence ride frequency.
* **Financial Health:** Identification of high-value periods and revenue leakage.
<img width="1279" height="728" alt="image" src="https://github.com/user-attachments/assets/e49122aa-3c27-4ce5-b43d-9cfeab62337d" />


### 3. Vehicle
* **Fleet Performance:** Specific analysis of different vehicle types and the performance of each one.
* **Category Profitability:** Comparison of average fare and demand across different vehicle classes.
<img width="1285" height="723" alt="image" src="https://github.com/user-attachments/assets/42e6beae-3c5b-4f75-92a4-840bde97c131" />


### 4. Riders
* **Customer Retention:** Analysis of user behavior and trip satisfaction scores, completed vs lost bookings, revenue most common payment method, and the resons behind the lost bookings.
* **Driver Metrics:** Monitoring driver performance, activity hours, and ratings.
<img width="1282" height="727" alt="image" src="https://github.com/user-attachments/assets/47be7bf8-2c8d-4664-98a4-69870ae55b6b" />


---

## 💡 Key Business Insights
* **Service Optimization:** Identified the most profitable balance between **UberXL** and **Premium** services based on regional demand.
* **Peak Performance:** Januart marks the highest bookings count all over the year(8189), March and January recorded the highest total revenue(5M).
* **Geographical Scaling:** Khandsa is the top pickup location, Ashram is the top drop location.

---

## 🛠️ Technical Stack
* **Tool:** Power BI Desktop
* **Data Modeling:** Star Schema architecture for optimized query performance.
* **DAX (Data Analysis Expressions):** * Advanced measures for **Lost booking percentage**, **Total Distance**, **Average Distance**,**Average Revenue per customer**, **Most common Payment method**, **Completed rate**, **Cancelled rate**, etc. 
 
* **Power Query:** Robust ETL processes to clean trip logs and handle location coordinates.

---

## 🚀 How to Use
1.  **Download:** Clone this repository and open `Uber.pbix`.
2.  **Navigation:** Click the icons on the left-hand sidebar to switch between specialized report pages.
3.  **Interaction:** Hover over data points for detailed tooltips and use the slicers to filter by Date, Service Type, or Region.

---

## 👤 Author
**Loay Ayman**
- **LinkedIn:** https://linkedin.com/in/loayayman
- **Portfolio:** https://loayayman.vercel.app/



