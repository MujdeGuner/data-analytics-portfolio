# Airline Passenger Satisfaction & NPS Analysis

## 📌 Project Overview
This project delivers a comprehensive statistical analysis of airline passenger satisfaction using a dataset of over 100,000 records. The primary objective is to identify key performance indicators (KPIs) that drive the **Net Promoter Score (NPS)** and overall customer loyalty through advanced quantitative methods and data modeling.

## 🛠 Tech Stack & Methodology
* **Data Processing:** Advanced Excel, Power Query for ETL (Extract, Transform, Load) processes.
* **Statistical Analysis:** * **Correlation Analysis:** Evaluating the strength and direction of relationships between specific services and overall satisfaction.
    * **Descriptive Statistics:** Calculating mean performance and variance (Standard Deviation) across 14 service categories.
    * **Segmentation:** Comparative analysis based on Flight Class (Business vs. Economy), Travel Type, and Passenger Demographics.
* **Reporting:** Pivot Tables and calculated fields for NPS categorization and trend identification.

## 📊 Key Statistical Insights

### 1. Service Correlation Matrix (Feature Importance)
Based on the `Service.csv` analysis, the following services show the strongest linear relationship with overall satisfaction:
* **Inflight Wi-Fi Service (r ≈ 0.66):** The primary predictor of satisfaction. High investment in digital connectivity yields the highest ROI on passenger experience.
* **Inflight Entertainment (r ≈ 0.60):** A critical driver for long-haul flight engagement.
* **On-board Service (r ≈ 0.56):** Shows a significant impact on premium cabin loyalty.

### 2. Segmented Performance Analysis
Utilizing the `Class_Dist_Report.csv`, the project highlights critical performance gaps:
* **Business Class:** Consistently maintains higher satisfaction levels (~64%) compared to **Eco Class** (~52%), primarily driven by *Seat Comfort* and *Leg Room Service*.
* **Standard Deviation Analysis:** Certain services like "Food and Drink" show higher volatility (STD_DEV > 32.0), suggesting inconsistent service delivery across different routes.

### 3. Operational Impact: Delay Analysis
The `Delays.csv` analysis quantifies how operational inefficiencies affect perceived convenience:
* **Threshold Identification:** Analyzing the tipping point where departure/arrival delays (Avg. ~15 mins) begin to significantly degrade the "Time Convenience" score.
* **Impact:** There is a direct inverse correlation between total delay minutes and NPS in the "Personal Travel" segment.

## 📈 Net Promoter Score (NPS) Implementation
Passenger feedback was normalized from 1-5 Likert scales to a 0-100 index:
* **Promoters:** Satisfaction Score ≥ 80
* **Passives:** Satisfaction Score 50-70
* **Detractors:** Satisfaction Score < 50

## 📂 Repository Structure
* `/Data`: Raw CSV exports and processed datasets.
* `/Analysis`: Statistical summaries, correlation tables, and pivot distributions.
* `/Visuals`: Screenshots of analytical dashboards and trend charts.

## 💡 Strategic Recommendations
1.  **Prioritize Digital Infrastructure:** Focus on Wi-Fi stability to capitalize on its high correlation (0.66) with satisfaction.
2.  **Service Standardization:** Address the high variance in "Cleanliness" and "Inflight Service" to ensure a uniform brand experience across all flight distances.
3.  **Targeted Improvements for Eco Segment:** Enhance "Seat Comfort" for long-haul economy flights to minimize the satisfaction gap with Business class.

---
