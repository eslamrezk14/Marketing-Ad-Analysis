# 📱 Marketing Ad Analysis | Power BI Dashboard

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI">
  <img src="https://img.shields.io/badge/Meta-0866FF?style=for-the-badge&logo=meta&logoColor=white" alt="Meta Ads">
  <img src="https://img.shields.io/badge/Status-Complete-success?style=for-the-badge" alt="Status">
</p>

## 📌 Table of Contents
- [Project Overview](#-project-overview)
- [Data Model & Architecture](#-data-model--architecture)
- [Key Features](#-key-features)
- [Marketing Insights](#-key-insights)
- [Visual Gallery](#-dashboard-screenshots)
- [Technical Skills](#-skills-demonstrated)
- [How to Use](#-how-to-use)
- [Contact](#-contact-information)

---

## 🎯 Project Overview
An interactive Power BI suite designed for **El MADAAR** to analyze advertising performance across Meta platforms (Facebook, Instagram) and Snapchat. This dashboard transforms fragmented campaign metrics into a unified strategic tool, focusing on ROI, audience behavior, and conversion optimization.

## 🏗️ Data Model & Architecture
Unlike basic reports, this project relies on a robust data structure:
* **Ad Data Table:** Contains performance metrics (Reach, 3-sec plays, Budgets).
* **Calendar Dimension:** A dedicated Date Table for time-intelligence analysis (YoY, MoM).
* **Centralized Measure Table:** Home to custom DAX calculations like `Active Watchers Rate`, `Video Completion Rate`, and `Cost per Conversion`.

> **Relationship View:** The model follows a professional schema connecting campaign facts with temporal dimensions.

---

## ✨ Key Features
* **Cross-Platform Integration:** Unified view for Meta and Snapchat campaigns.
* **Video Engagement Funnel:** Detailed analysis of `Auto-play` vs. `Click-to-play` behavior.
* **Demographic Deep-Dive:** Interactive segmentation by Age (6 groups) and Gender.
* **Goal Tracking:** Real-time comparison between **Sales-focused** vs. **Reach-focused** objectives.
* **Budget Efficiency:** Tracking performance based on different budget allocations (e.g., 100 vs. 75).

---

## 💡 Key Insights

* **🏆 High-Value Segment:** The **25-34** age group is the top converting demographic.
* **📅 Optimal Timing:** **Saturday** consistently delivers the highest engagement and "Active Watchers" rate.
* **🎥 Content Performance:** A **0.63% Active Watchers Rate** was maintained across 14.81K reached users.
* **🚀 Campaign Leader:** The *"Sat-Thu Promo"* significantly outperformed other campaigns, generating 105 message starts.
* **👥 Gender Split:** Audience is balanced with **49.66% Male** and **38.26% Female** (with 12.08% unknown).

---

## 📸 Dashboard Screenshots

### 1. Main Performance Dashboard
*The primary interface for monitoring KPIs and audience distribution.*
![Marketing Dashboard](images/final-project.png)

### 2. The Engine (Data Model)
*A look under the hood at the table relationships and DAX organization.*
![Data Model](images/relation-screenshot.png)

---

## 🎓 Skills Demonstrated
* **Advanced DAX:** Creating complex measures for marketing-specific KPIs (e.g., Conversion Ratios, Drop-off Rates).
* **Data Modeling:** Designing a star-schema-like structure for better performance.
* **UI/UX for Marketing:** Designing with a focus on "Actionable Metrics" rather than just "Vanity Metrics".
* **ETL (Power Query):** Cleaning and merging data from different social media export formats.

---

## 🚀 How to Use
1.  **Clone:**
    ```bash
    git clone [https://github.com/eslamrezk14/Marketing-Ad-Analysis.git](https://github.com/eslamrezk14/Marketing-Ad-Analysis.git)
    ```
2.  **Software:** Open with [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3.  **Interact:** Use the slicers to filter by **Campaign Name** or **Platform**.

## 📂 Project Structure
```text
Marketing-Ad-Analysis/
├── Power BI Dashboard.pbix   # Main Analysis File
├── README.md                 # Project Documentation
└── images/                   # Dashboard & Model Screenshots
    ├── final-project.png
    └── relation-screenshot.png
