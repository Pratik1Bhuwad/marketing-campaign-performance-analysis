# Ad Campaign Performance Analysis 

This project analyzes the performance of **Facebook Ads** vs **Google AdWords** campaigns using statistical and visual techniques. The goal is to uncover which platform yields better conversion rates, cost-effectiveness, and trends over time.

---

## 📌 Project Overview

This notebook covers:

- Data Cleaning & Preprocessing
- Outlier Handling
- A/B Testing (Facebook vs AdWords)
- Correlation Analysis
- Time Series Analysis of Facebook Campaigns
- Visualization of Weekly & Monthly Trends

---

## 📁 Dataset Description

The dataset contains ad campaign data from both platforms with metrics such as:

- `date_of_campaign`
- `ad_clicks`, `ad_conversions`
- `ad_views`, `cost_per_ad`, `cost_per_click`
- `click-through rate (CTR)`
- `conversion_rate`

---

## 📈 Key Analyses

### - A/B Testing (Facebook vs AdWords)
- **Mean Facebook Conversion Rate**: 29.48%
- **Mean AdWords Conversion Rate**: 10.03%
- **T-Test Result**: Facebook has a significantly higher conversion rate (p-value ≈ 0.00)

### - Correlation Analysis
- **Facebook Clicks vs Conversions**: Very weak correlation
- **AdWords Clicks vs Conversions**: Slightly higher but still weak

### - Time Series Insights
- **Weekly Conversions**: Highest on **Monday**
- **Monthly Conversions**: Peaks in **January** and **July**
- **Monthly Cost Per Conversion (CPC)**: Highest in **July**, lowest in **January**

---

##  Visualizations

- Regression plots of clicks vs conversions
- Bar chart of weekly conversion patterns
- Line plots for monthly conversions and cost per conversion

---

##  Tools & Libraries Used

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scipy (for statistical testing)

---

##  Conclusion

- Facebook Ads yield better conversion efficiency compared to AdWords.
- Monday tends to perform best for conversions.
- July shows a spike in both conversions and cost-per-conversion, suggesting increased ad spend or holiday impact.

---


## 🔗 Author

**[Pratik Bhuwad]**  
_Data Science Enthusiast | A/B Testing | Ad Analytics_

