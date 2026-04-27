# 🌪️ NOAA Storm Events Analysis (1950-2020)

## 📌 Project Overview
This project explores 70 years of extreme weather data in the United States, utilizing the official NOAA Storm Events database. By processing over **1.65 million events** and 71 distinct weather types, this project aims to uncover the true relationship between disaster frequency, intensity, and their cumulative impact on human life and the economy.

## 🛠️ Tech Stack & Data Engineering
* **Data Processing (Python):** Consolidated 213 disparate raw files into 3 core datasets (Details, Fatalities, Locations). Standardized financial shorthand (K, M, B) into numeric formats and filtered out unstructured narrative noise for optimal performance.
* **Visualization (Power BI):** Designed a multi-view interactive dashboard.
* **Metric Calculation (DAX):** Engineered complex measures including Cumulative Deaths, dynamic Metric Toggling (Human vs. Economy Target), and Source Reliability (Coefficient of Variation - CV).

## 💡 Key Insights & Discoveries

**1. The Reporting Bias Phenomenon**
* A massive spike in recorded events from 1996 to 2020 was identified. Analysis indicates this is largely driven by advancements in reporting technology and early warning systems (Reporting Bias) rather than solely climate change, evidenced by a stabilized cumulative mortality rate despite higher event frequencies.

**2. The "Magnitude Paradox" (Frequency vs. Intensity)**
* **Economic Impact:** Hail, despite having a generally low individual magnitude, causes massive cumulative economic damage due to its high frequency and widespread impact area. 
* **Human Impact:** Tornadoes remain the deadliest disaster overall. However, correlation analysis reveals that extreme event magnitude does not perfectly correlate with human casualties; location vulnerability plays a more critical role.

**3. Geospatial & Categorical Vulnerability**
* **Texas** stands out as the most heavily impacted state overall.
* **Hurricanes** are the most financially devastating ($123.7 Billion), primarily affecting coastal regions in the latter half of the year.

**4. Source Reliability Framework**
* Developed a unique reliability index using the Coefficient of Variation (CV). Results proved that reports from *Trained Spotters*, *Law Enforcement*, and *Emergency Managers* are highly credible, whereas automated sources like *SNOTEL* or *BUOY* showed high variance and lower reliability.

## 📊 Dashboard Previews
![Dashboard](https://github.com/ThanhDustin/project-Storm-Events-Data-Analysis-Visualization/blob/main/hinhoverview.png)
![Dashboard](https://github.com/ThanhDustin/project-Storm-Events-Data-Analysis-Visualization/blob/main/hinhdetail.png)
![Dashboard](https://github.com/ThanhDustin/project-Storm-Events-Data-Analysis-Visualization/blob/main/hinhcorrandsource.jpg)
