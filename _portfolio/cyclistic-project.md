---
title: "🚴 Cyclistic Bike-Share Analysis"
excerpt: "Interactive data analysis identifying trends between casual riders and annual members to drive membership conversions."
description: "End-to-end data analysis of Cyclistic bike-share data with actionable business recommendations."
collection: portfolio
type: "project"
permalink: /portfolio/cyclistic-report
date: 2026-03-19
tags:
  - Data Analysis
  - Python
  - Plotly
  - Google Data Analytics
  - Cyclistic
header:
  teaser: https://elina714.github.io/files/cyclistic_project/fleet_evolution_2020_2021.png
  image: https://elina714.github.io/files/cyclistic_project/fleet_evolution_2020_2021.png
  caption: "Fleet Evolution 2020–2021"
---

> 🚀 This project demonstrates end-to-end data analysis: data cleaning, exploration, visualization, and business strategy recommendations.

---

<!-- 🔗 Interactive Report Embed -->
{% raw %}
<div style="position: relative; padding-bottom: 75%; height: 0; overflow: hidden; max-width: 100%; border-radius: 12px; box-shadow: 0 4px 20px rgba(0,0,0,0.15); margin: 25px 0;">
  <iframe
    src="https://elina714.github.io/files/cyclistic_project/cyclistic-analysis.html"
    style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: none; border-radius: 12px;"
    title="Cyclistic Data Analysis Report"
    loading="lazy"
    allowfullscreen>
  </iframe>
</div>
{% endraw %}
<!-- 🚀 Full-Screen Button -->
<p style="text-align: center; margin: 1.5rem 0;">
  <a href="{{ '/files/cyclistic_project/cyclistic-analysis.html' | relative_url }}"
     target="_blank"
     class="btn btn--primary">
    🔗 Open Full Interactive Report
  </a>
</p>

---

## 📋 Project Overview

| Field | Details |
|-------|---------|
| **Goal** | Analyze trip data to identify trends between casual riders and annual members |
| **Stakeholder** | Lily Moreno, Director of Marketing at Cyclistic |
| **Data Period** | January 2021 – December 2022 |
| **Final Dataset** | 11.25 million cleaned trips |
| **Tools** | Python, Pandas, Plotly, HTML/CSS |

---

## ❓ Key Questions Addressed

1. How do annual members and casual riders use Cyclistic bikes differently?
2. Why would casual riders buy Cyclistic annual memberships?
3. How can Cyclistic use digital media to influence casual riders to become members?

---

## 🔍 Key Findings

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 15px; margin: 20px 0;">

<div style="background: #f8f9fa; padding: 15px; border-radius: 8px; border-left: 4px solid #667eea;">
<strong>🎯 Usage Patterns</strong><br>
Members = commuters (Mon–Fri peaks)<br>
Casuals = tourists (weekend peaks)
</div>

<div style="background: #f8f9fa; padding: 15px; border-radius: 8px; border-left: 4px solid #f5576c;">
<strong>📍 Geographic Clustering</strong><br>
Members: downtown/business districts<br>
Casuals: tourist areas (Millennium Park, Navy Pier)
</div>

<div style="background: #f8f9fa; padding: 15px; border-radius: 8px; border-left: 4px solid #28a745;">
<strong>⏱️ Trip Duration</strong><br>
Casual: ~23.5 min/trip<br>
Member: ~12.2 min/trip
</div>

<div style="background: #f8f9fa; padding: 15px; border-radius: 8px; border-left: 4px solid #ffc107;">
<strong>🔌 Dockless Usage</strong><br>
"Public Rack" locations show the highest usage for both groups
</div>

</div>

---

## 🧹 Data Cleaning Summary

- Removed invalid and missing station data  
- Standardized datetime formats  
- Filtered unrealistic trip durations  
- Handled missing coordinates and station names  
- Combined multiple datasets into a unified dataset  

---

## 💡 Strategic Recommendations

- Target high-frequency casual riders (>3 rides/month) with personalized offers  
- Optimize pricing to highlight membership value  
- Introduce weekend or trial memberships to lower entry barriers  
- Use location-based marketing in high-traffic and transit areas  

---

## 📎 Tools & Technologies

- Python (Pandas, NumPy)  
- Data Visualization (Plotly)  
- HTML/CSS (Report design)  
