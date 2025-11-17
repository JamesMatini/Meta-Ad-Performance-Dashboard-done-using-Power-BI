# Meta-Ad-Performance-Dashboard-done-using-Power-BI
Analyze Facebook and Instagram ad campaigns to track reach, engagement, conversions, and budget utilization. Build dynamic visualizations in Power BI including gender, age, country, time, and ad-type trends, enabling the marketing team to optimize campaigns, maximize ROI, and improve audience targeting.

# 📊 Meta Ad Performance Analysis Dashboard
# Facebook
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/387eb319-7394-4493-94eb-d5fe9bed321c" />

#Instagram 
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/512f3148-fb8b-45ab-9400-66a03e8d8689" />



## 🎯 Business Objective  
This project analyzes paid advertising campaigns running on **Facebook** and **Instagram** to provide visibility into campaign performance.  
The dashboard helps the marketing team:  
- Identify the most effective platform (Facebook vs Instagram)  
- Track campaign ROI and optimize budget allocation  
- Understand audience engagement patterns  

---

## 🗂️ Scope  

**In Scope:**  
- Paid campaigns on Facebook and Instagram  

**Out of Scope:**  
- Other platforms (Messenger, Audience Network)  
- Organic engagement  

---

## 📊 KPIs & Definitions  

| KPI | Definition | Formula | Purpose |
|-----|------------|--------|---------|
| Impressions | Number of times ads were displayed | Count of event_type = Impression | Measure reach |
| Clicks | Number of times users clicked ads | Count of event_type = Click | Engagement intent |
| Shares | Number of ad shares | Count of event_type = Share | Viral engagement |
| Comments | Number of user comments | Count of event_type = Comment | Feedback & sentiment |
| Purchases | Number of purchases after seeing ads | Count of event_type = Purchase | Conversions |
| Engagements | Total interactions | Clicks + Shares + Comments | Engagement volume |
| CTR | Click-through rate | (Clicks ÷ Impressions) × 100 | Ad effectiveness |
| Engagement Rate | % of impressions resulting in engagement | (Engagements ÷ Impressions) × 100 | Overall appeal |
| Conversion Rate | % of clicks resulting in purchases | (Purchases ÷ Clicks) × 100 | Funnel efficiency |
| Purchase Rate | % of impressions resulting in purchases | (Purchases ÷ Impressions) × 100 | Reach-to-conversion |
| Total Budget | Total spend on campaigns | Sum(campaigns.total_budget) | Cost analysis |
| Avg. Budget per Campaign | Average spend per campaign | Total Budget ÷ Campaign Count | Budget distribution |

---

## 📈 Charts & Visualizations  

1. **Target Gender – Donut Chart**  
   - Displays selected metric by gender to identify top-performing segments  

2. **Target Age Group – Bar Chart**  
   - Highlights engagement across age groups; metric dynamically adjustable  

3. **Country – Map**  
   - Geographic view of campaign reach and engagement  

4. **Calendar Month – Heat Map**  
   - Monthly activity visualization to detect seasonal trends  

5. **Weekly Trend – Stacked Column by Ad Type**  
   - Compare ad type contributions over weeks  

6. **Hourly Trend – Area Chart**  
   - Shows activity by hour of day to understand user patterns  

7. **Ad Type – Matrix**  
   - Compares selected metric across ad types and platforms side by side  

---

## 🧩 Tools & Techniques Used  

| Component | Tools / Techniques |
|-----------|------------------|
| Data Analysis | SQL queries for campaign metrics |
| Data Processing | Data cleaning, transformation, KPI calculations |
| Visualization | Power BI dynamic charts, matrices, maps, heatmaps |
| Reporting | Interactive dashboards for marketing insights |

---

## 💡 Business Impact  

- Identify top-performing campaigns and platforms  
- Optimize budget allocation to maximize ROI  
- Improve audience targeting by gender, age, and location  
- Track engagement trends over time for strategic decision-making  

---

## 🏗️ Project Structure  

