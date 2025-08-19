## Project Overview

This project analyzes seven years of British Airways customer reviews (2016–2023) to uncover patterns in passenger satisfaction. Using Tableau, I built an interactive KPI dashboard with filters for rating metrics, time periods, aircraft types, and countries. The dashboard highlights strengths, weaknesses, and opportunities for improvement, helping airline leaders make data-driven decisions to improve the passenger experience.

<a id="dashboard-access"></a> 
![Image](https://github.com/user-attachments/assets/10c337c6-432a-4f1e-a266-294d758be7db)

[![Tableau Dashboard](https://img.shields.io/badge/View_Interactive_Dashboard-Tableau_Public-blue?style=for-the-badge&logo=tableau)](https://public.tableau.com/views/BritishAirwaysDashboard_17418998269380/Dashboard1?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

Explore the interactive version with filters for:
- Different rating metrics
- Time periods (2016-2023)
- Aircraft types
- Countries

## Table of Contents
1. [Dashboard Access](#dashboard-access)  
2. [Project Overview](#overview)   
3. [Dashboard Features](#interactive-dashboard-features)   
4. [Key Insights and Recommendations](#key-insights-and-recommendations) 

## Overview  
In this project, I analyzed **7 years of British Airways customer reviews (2016–2023)** to uncover trends in passenger satisfaction. Using Tableau, I built an **interactive dashboard** that highlights strengths, pain points, and opportunities for improvement—helping airline leaders make data-driven decisions.  

## Exploring the Data

First, I dove into the customer reviews to understand what story the data could tell. Each row represented a unique traveler's experience, with detailed ratings across key flight aspects:

**Flight Experience Metrics** (rated 1-5):
- Cabin staff service
- Food & beverages  
- Entertainment
- Seat comfort
- Value for money

---


### Connecting the Data
To enable geographic insights, I joined the review data with country information in Tableau by matching the `Place` and `Country` fields. This created a powerful foundation for location-based analysis.

![Image](https://github.com/user-attachments/assets/857f5cd6-b119-49f5-b5d9-0df8d3a472ab)

---

### Dynamic Metric Selection
I created an interactive "Pick a Metric" parameter that lets users toggle between different rating categories, with the dashboard automatically updating all visualizations to reflect the selected metric.

![Image](https://github.com/user-attachments/assets/0905b56e-9bf4-435a-854a-e5ab14e96223)

---

### Aircraft Grouping

I focused on aircraft with **50+ reviews** to ensure reliable results. Less common planes were grouped together as "Various" to keep the data clear and meaningful.

![Image](https://github.com/user-attachments/assets/ca56212e-fb55-4a37-ba99-d7d4870f7963)

&nbsp;

# Interactive Dashboard Features

The dashboard dynamically updates all visualizations when users select different metrics from the "Pick a Metric" filter. For example, choosing "Food & Beverages" will update every chart to show relevant data for that category.

### Key Visualizations:

1. **Monthly Trends**  
Track how ratings change over time

![Image](https://github.com/user-attachments/assets/650000e3-a3ec-4dbd-982a-f0dc9a3edb56)

---

2. **Global Performance Map**  
See which countries give the highest/lowest ratings
 
![Image](https://github.com/user-attachments/assets/6d86a768-cf0a-4fc6-83e7-499d4d4dd48b)

---

3. **Aircraft Comparison**  
Compare average ratings vs. number of reviews by plane type
 
![Image](https://github.com/user-attachments/assets/5e652575-6ac9-4511-ae03-65ed8876cfc1)

---

4. **Performance Summary**  
Quick-glance metrics showing overall averages
  
![Image](https://github.com/user-attachments/assets/acb0d4f0-846e-46c3-bc6c-8553178c086f)

---

5. **Interactive Filters**  
Easily explore by time period, country, or aircraft

![Image](https://github.com/user-attachments/assets/6e0dea01-aa54-4785-8aa9-0914de23ffc9)

&nbsp;

# Final Dashboard

Here is the final dashboard, which you can also view on [Tableau](https://public.tableau.com/views/BritishAirwaysDashboard_17418998269380/Dashboard1?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) to explore how all visualizations update dynamically with each filter selection.

![Image](https://github.com/user-attachments/assets/b6fbbd76-05f3-49e1-9a7a-673238d31c2f)

Try experimenting with:
- Switching between different rating metrics
- Filtering by specific years or aircraft types
- Hovering over countries on the map for detailed scores

---

## Key Insights and Recommendations

### Key Insights for Stakeholders

### 1. Pandemic Impact (2020-2021)
- All rating categories showed significant declines  
- Likely driven by flight cancellations and COVID-19 restrictions  

### 2. Priority Improvement Areas   
Consistently low-performing categories:  
- In-flight entertainment (1.4/5 avg)  
- Food & beverages (2.4/5 avg)  
- Value for money (2.8/5 avg)  

### 3. Strong Overall Performance  
- Maintained 4.2/5 average rating across 7 years
- **Boeing 747-400**: Highest-rated aircraft (4.7/5)   
- 78% of reviews gave 4+ stars overall

---

### Business Recommendations:

### 1. Immediate Upgrades  
- Modernize entertainment systems (content & hardware)  
- Partner with premium catering services  

### 2. Leverage Top Performers  
- Increase 747-400 deployment on key business routes  
- Study & replicate its cabin service best practices   

### 3. Targeted Training 
- Specialty training for food/beverage staff  



