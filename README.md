# 🚴‍♀️ Cyclistic Bike-Share: Strategic Membership Conversion Analysis

### 📘 Project Overview
This project is the capstone case study for the **Google Data Analytics Professional Certificate (Coursera)**. The objective is to analyze the behavioral differences between **casual riders** and **annual members** of the Cyclistic bike-share program in Chicago. The final goal is to develop **data-driven marketing strategies** to increase membership conversion and maximize long-term profitability.

---

### 🧰 Tools and Skills
- **Data Processing:** SQL for cleaning and aggregating 5.8M+ rows.
- **Visualization:** Power BI for interactive dashboarding and trend analysis.
- **Competencies:** Data Cleaning, Outlier Detection, Trend Forecasting, and Business Strategy Design.
- **Operational Focus:** Optimizing fleet turnover and improving Customer Lifetime Value (CLV).

---

### 🗂️ Data Overview
The analysis utilizes **2024 historical trip data** from the Divvy system (operated by Lyft), covering over **5.8 million records**.

- **Data Source:** [Divvy Trip Data on AWS](https://divvy-tripdata.s3.amazonaws.com/index.html)
- **Data Integrity:** - Validated consistency across 12 monthly datasets.
  - Removed duplicates and standardized categorical formats.
  - **Outlier Handling:** Filtered out records with ride durations < 1 minute or > 24 hours to ensure metric accuracy.
- **Final Dataset:** 5,860,357 clean records processed for analysis.

---

### 🔍 Key Operational Insights

#### 1. Ride Duration & Fleet Utilization
- **Finding:** Casual riders account for **80% of unusually long-duration rides**, leading to lower bike availability for other users.
- **Impact:** High duration without membership stability creates unpredictable fleet turnover.
- **Recommendation:** Implement membership incentives to stabilize usage patterns and reduce excessive "unmanaged" ride durations.

#### 2. Temporal Usage Patterns
- **Finding:** Members show high-frequency, short-duration usage (Commuting), while Casual riders peak on weekends with longer durations (Leisure).
- **Recommendation:** Introduce a **Dual-Condition Rewards System** (Frequency + Duration) to convert weekend leisure users into consistent members.

#### 3. Geographic Distribution
- **Finding:** Members are concentrated in **Business Districts**; Casual riders thrive in **Parks and Tourist areas**.
- **Recommendation:** Deploy **Cross-Zone Discounts** for new members who ride in both urban-business and recreational zones, encouraging year-round utility.

#### 4. Seasonality & Market Resilience
- **Finding:** Significant drop in casual usage during winter months.
- **Recommendation:** Launch a **"Warm Up & Ride" Winter Campaign** featuring seasonal membership discounts and double reward points to maintain off-season engagement.

---

### 💡 Strategic Business Recommendations

1. **Precision Marketing (Pamphlet):** Target high-frequency casual users with data-backed benefits of membership.
2. **Dual-Condition Rewards:** A loyalty program where points are earned based on *both* ride count and cumulative duration.
3. **Geo-Fenced Discounts:** 10% discount for new members active in diverse geographic zones (Commuter + Tourist).
