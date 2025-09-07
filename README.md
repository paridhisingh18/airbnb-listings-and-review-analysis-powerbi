# 📊 Airbnb Market Analysis Dashboard – Power BI

## 📌 Project Overview
This project analyzes **Airbnb listings across 10 major cities** to uncover insights about pricing, host activity, customer reviews, and market trends.  

The dataset includes **250,000+ listings**, **5 million+ historical reviews**, and **36 fields** covering host details, property types, room types, pricing, and review trends.  

Using **Power BI**, I built a **two-page interactive dashboard** that provides both a high-level market overview and deeper insights into pricing trends, customer preferences, and host performance.  

---

## 🗂 Dataset Information
- **Source**: Maven Analytics (original data from Inside Airbnb)  
- **Records**: 5,652,855  
- **Fields**: 36  
- **Scope**: 250,000+ listings in 10 cities  
- **Features**: Hosts, pricing, location, room type, review history  
- **File Type**: CSV  
- **Date Added**: April 9, 2021  
- **Note**: Prices are in local currency  

### Recommended Analysis (from dataset creators)
- Identify **major differences** in the Airbnb market between cities.  
- Understand which **attributes influence price** the most.  
- Detect **trends and seasonality** in review data.  
- Compare which cities offer **better travel value**.  

---

## 🎯 Objectives / Questions Answered
The dashboard is designed to answer the following business questions:

1. **Market Landscape**
   - How many listings and hosts exist across different cities?
   - Which cities have the highest number of listings and what are the average prices?
   - What is the distribution of listings by room type?

2. **Pricing & Value**
   - Which cities and property types are the most/least expensive?
   - How does average price vary by room type and property type?
   - Which cities provide the best value-for-money index (price vs. rating)?

3. **Customer Behavior**
   - Which cities receive the most reviews?
   - How has review volume changed over time?
   - What are the average review ratings across cities?

4. **Host Performance**
   - What % of listings are hosted by Superhosts?
   - Who are the top-performing hosts in terms of listings, reviews, and ratings?
   - What are the most expensive listings and who hosts them?

---

## 📂 Dashboard Structure

### **Page 1 – Market Overview**
- **KPIs (Cards):** Total Listings, Total Hosts, Avg Price per Night, Avg Review Rating  
- **City-Level Insights:**  
  - Average Price per City  
  - Total Listings per City  
- **Host Insights:**  
  - Superhost % (Donut Chart)  
  - Top 5 High-Priced Listings & Hosts  
- **Room Type Analysis:**  
  - Room Type Distribution (Bar Chart)  

👉 **Purpose:** Provides a high-level overview of the market distribution, pricing, and host activities across cities.

---

### **Page 2 – Insights & Trends**
- **Price Comparisons:**  
  - Average Price by Room Type  
  - Average Price by Property Type  
- **Customer Value & Engagement:**  
  - Value for Money Index by City  
  - Review Count by City  
- **Market Trends:**  
  - Review Volume by Year (2008–2021)  
- **Host Analysis:**  
  - Top Hosts by Listings, Reviews, Ratings, and Tenure  

👉 **Purpose:** Provides detailed insights into pricing trends, customer engagement, and identifies high-performing hosts.

---

## 🔑 Key Insights
- **Paris leads in total listings (64K+)**, while **Cape Town has the highest average nightly price (2.4K+ in local currency)**.  
- **84% of listings are hosted by Superhosts**, indicating strong market credibility.  
- **Entire Place is the most common room type (65%+)**, showing preference for privacy.  
- **Hotel rooms are the most expensive**, followed by entire villas.  
- **Rome & Paris provide the best value-for-money index**, balancing price and rating.  
- **Reviews peaked in 2019**, with a significant drop during the pandemic (2020–2021).  
- **Top hosts manage hundreds of listings**, with one host handling **627 listings and 11K reviews since 2019**.  

---

## 🛠 Tools & Skills Used
- **Power BI** → Data modeling, DAX, visualization, and dashboard building  
- **Data Cleaning & Transformation** → Power Query  
- **Data Analysis Concepts** → KPI design, trend analysis, comparative insights  
- **Visualization Techniques** → Bar charts, Donut charts, Cards, Line charts, Tables  

---

## 🚀 How to View
1. **Interactive Version (Public Link)**  
   Published via **Power BI Publish to Web** →(https://app.powerbi.com/view?r=eyJrIjoiZTIxMTRhOGQtYWVlYi00MDc5LWE5Y2UtNzQ1NTY1MzA5NjIyIiwidCI6IjJhYzEyMWViLTg1ZmUtNGQxMC05NTAxLWI1ZjY5ZDUyYmQ1OCJ9)


2. **Static Version (PDF & Screenshots)**  
   ### Market Overview
   ![Market Overview](https://github.com/paridhisingh18/airbnb-listings-and-review-analysis-powerbi/blob/main/images/MarketOverview.png)
   ### Insights & Trends
   ![Insights & Trends](https://github.com/paridhisingh18/airbnb-listings-and-review-analysis-powerbi/blob/main/images/Insight%26Trends.png)

---

## 🙌 Acknowledgments
- Dataset sourced from **Maven Analytics** (original data from Inside Airbnb, Public Domain)  
- Built and visualized entirely using **Power BI Desktop**.  
