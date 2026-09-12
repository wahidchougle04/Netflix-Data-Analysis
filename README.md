# Netflix Data Analysis & Visualization

An end-to-end Exploratory Data Analysis (EDA) of the Netflix titles dataset using Python. This project uncovers streaming content trends, content classification patterns, geographical output leaders, and rating distributions across both Movies and TV Shows.

---

## Project Overview

With streaming platforms rapidly expanding their global catalogs, understanding content strategy—ranging from genre distribution to target audience demographics—is essential. 

This project analyzes **6,234 records** from the Netflix catalog (spanning releases from 1925 to 2020) to extract actionable media insights through statistical computation and data visualization.

---

## Tech Stack & Libraries

* **Language:** Python 3.x
* **Data Processing:** `pandas`, `numpy`
* **Data Visualization:** `seaborn`, `matplotlib`
* **Development Environment:** Jupyter Notebook / Anaconda

---

## Key Insights & Analytical Findings

1. **Catalog Composition:**
   * **Movies vs. TV Shows:** Movies dominate the platform, accounting for **~68.4% (4,265 titles)** of total content, compared to **~31.6% (1,969 titles)** for TV Shows.
2. **Release Trends & Industry Impact:**
   * Content additions peaked in **2018**.
   * A noticeable decline in releases occurred during **2019–2020**, reflecting broader global media production disruptions (COVID-19 pandemic effects).
3. **Geographic Dominance:**
   * The **United States** leads globally in content creation on Netflix by a wide margin, followed by India and the United Kingdom.
4. **Duration & Runtime Metrics:**
   * The average duration of feature-length movies on Netflix centers at **~90 minutes**, following a normal distribution pattern.
5. **Target Audience & Ratings:**
   * **TV-MA** (Mature Audiences) and **TV-14** are the two largest rating categories across both Movies and TV Shows, highlighting Netflix's focus on young adult and adult demographic engagement.

---

## Dataset Summary

| Metric | Detail |
| :--- | :--- |
| **Total Entries** | 6,234 rows |
| **Total Features** | 12 columns |
| **Features Included** | `ID`, `Type`, `Title`, `Director`, `Cast`, `Country`, `Date_added`, `Release_year`, `Rating`, `Duration`, `Listed_in`, `Description` |
| **Data Types** | `int64` (2), `object` (10) |

---
<img width="422" height="750" alt="Dashboard" src="https://github.com/user-attachments/assets/cca62c55-2bf2-4a64-9267-c6cec3da2e91" />
