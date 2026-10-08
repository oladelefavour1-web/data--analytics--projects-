# Data Analytics Projects

A collection of data analytics projects focused on business performance analysis across African markets.

---

## 1. AfriMart KollyBright Sales Dashboard

This is a data analytics project that analyses sales performance for AfriMart KollyBright across African countries to understand business performance. The project provides an interactive view of key business performance indicators, including revenue, profit, units sold, product performance, and country-level sales.

The objective was to transform sales data into meaningful business insights that can help identify high-performing markets and products and support better business decision-making.

### Business Objectives
The analysis was designed to answer key business questions such as:
- How is AfriMart performing in terms of revenue and profit?
- Which African country generates the highest revenue?
- Which products contribute the most to profit?
- How many units have been sold?
- Which markets and products are performing strongly?
- Where are there opportunities for improved sales performance?

### Key Performance Indicators
| KPI              | Performance |
|------------------|-------------|
| Total Revenue    | 10 billion  |
| Total Profit     | 2 billion   |
| Total Units Sold | 1 million   |

### Key Insights
- **Nigeria generated the highest revenue** among African countries included in the analysis, making it the strongest revenue-generating market in the dataset.
- **Rice (50kg bag)** is the top-performing product by profit.
- Sales are tracked across multiple African countries (Nigeria, Tanzania, Côte d'Ivoire, Kenya, Rwanda, Ghana, Uganda, Egypt).

### Dashboard Features
The Power BI dashboard provides visual insights into:
- Total revenue
- Total profit
- Total units sold
- Revenue by country
- Product performance
- Profit performance
- Sales distribution across African markets

### Tools Used
- Power BI

### Business Recommendations
Based on the findings, AfriMart KollyBright could consider:
1. **Strengthening the Nigerian market** – Since Nigeria generated the highest revenue, the business could explore opportunities to maintain and expand its presence in this market.
2. **Prioritising high-profit products** – Products such as the Rice (50kg Bag) could receive greater attention in inventory planning, marketing, and sales strategies.
3. **Monitoring other African markets** – Comparing performance across countries can help identify markets with growth potential and areas requiring additional sales strategies.

### Dashboard
- [View the full AfriMart Sales Dashboard (PDF)](AfriMart_Sales_Powerbi.pdf)

---

## 2. ZoomRide SQL Project

**File:** `zoomride_favour.sql`

ZoomRide is a fictional ride-hailing company operating in 6 African cities (Lagos, Abuja, Port Harcourt, Nairobi, Accra, and Kampala). This project uses SQL (MySQL) to set up a realistic (and deliberately messy) database and answer key business questions about trips, revenue, customers, and drivers.

### Database Structure
Three linked tables:
- **customers** (40 rows) – Who rides
- **drivers** (20 rows) – Who drives
- **trips** – One row per booked trip (links a customer to a driver)

All fares are in Naira (₦). Cancelled trips have fare = 0. The data includes real-world issues such as missing values, inconsistent city names, and duplicates.

### Project Objectives
The SQL analysis covers:
1. Total number of trips
2. Longest completed trips
3. Trips by city
4. Data quality checks (duplicates and missing fares)
5. Data cleaning
6. Revenue by city
7. Revenue by month
8. Revenue by vehicle type
9. Customers who never booked a trip
10. Top 3 customers by total spend

### How to Use
1. Go to [onecompiler.com/mysql](https://onecompiler.com/mysql) (keep the dropdown on MySQL).
2. Paste the entire `zoomride_favour.sql` file and click **Run**.
3. The script rebuilds the tables safely (safe to re-run).
4. Queries are written below the “YOUR QUERIES START HERE” section.

### Tools Used
- MySQL

---

## Repository Structure
