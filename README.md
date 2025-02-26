# 📊 Marketing Campaign Analysis Dashboard

## 📝 Overview  
This project presents an interactive **Marketing Campaign Analysis Dashboard** built in **Microsoft Excel** to evaluate the performance of various marketing campaigns. The dashboard offers key performance indicators (KPIs) and comprehensive visualizations to help stakeholders understand campaign effectiveness, budget allocation, and channel performance.  

---

## 🎯 Objectives  
- Analyze overall campaign performance using key advertising metrics (CTR, CPC, CPM, and Budget Utilization).  
- Identify top-performing channels, creatives, and service providers.  
- Visualize impressions, clicks, and budget trends over time.  
- Provide an interactive experience using slicers for targeted insights.  

---

## 📁 Dataset  
The dataset used for this analysis was sourced from **Kaggle** and contains the following columns:  

- `campaign_item_id`: Unique identifier for each campaign item  
- `no_of_days`: Campaign duration in days  
- `time`: Campaign timeline  
- `ext_service_name`: External service/platform name  
- `creative_id`: Creative asset identifier  
- `impressions`: Number of ad displays  
- `clicks`: Number of clicks received  
- `campaign_budget_usd`: Total allocated campaign budget (USD)  
- `max_bid_cpm`: Maximum bid for cost per thousand impressions (CPM)  
- `media_cost_usd`: Cost spent on media purchasing  
- `channel_name`: Marketing channel (e.g., Social Media, Display Ads)  

> **Note:** Columns `unique_reach` and `total_reach` were removed due to null values.  

---

## 📈 Key Metrics (KPIs)  
The dashboard features the following **KPI Cards**:  

- **Average CTR (Click-Through Rate)**: [(Total Clicks / Total Impressions) × 100]  
- **Average CPC (Cost Per Click)**: [Total Media Cost / Total Clicks]  
- **Average CPM (Cost Per Thousand Impressions)**: [(Total Media Cost / Total Impressions) × 1000]  
- **Average Budget Utilization**: [(Media Cost / Campaign Budget) × 100]  

---

## 📊 Visualizations  

### 1️⃣ Line Chart: *Campaign Performance Over Time*  
- Tracks **impressions** and **clicks** over the campaign timeline.  
- Reveals trends, peaks, and drops in user engagement.  

### 2️⃣ Pie Chart: *Budget Allocation per Channel*  
- Illustrates how the marketing budget is distributed across different channels.  
- Identifies heavily and underfunded channels.  

### 3️⃣ Bar Chart: *Media Cost per Service Provider*  
- Compares **media costs** across various external service providers.  
- Highlights cost efficiency among providers.  

### 4️⃣ Column Chart: *Top Performing Channels by CTR*  
- Ranks channels based on their **click-through rate** (CTR).  
- Identifies high-performing platforms for future investments.  

### 5️⃣ Column Chart: *Top 10 Creatives by CTR*  
- Displays the best-performing creative assets.  
- Helps optimize creative strategies based on effectiveness.  

---

## 🧩 Interactivity Features  

### 🗂️ Slicers Included:  
- **Weekday Category:** Analyze campaign performance by day of the week.  
- **Channel Name:** Filter visualizations by specific marketing channels.  
- **External Service Name:** Drill down into data per service provider.  

---

## 🚀 How to Use the Dashboard  
1. **Open the Excel file** and navigate to the **Dashboard** tab.  
2. Use the **slicers** (weekday, channel, service) to filter and explore specific segments.  
3. Hover over charts to view detailed data points and comparisons.  
4. Refer to the KPI cards for quick insights into overall performance.  

---

## 🏆 Key Insights Derived  
- Identified top-performing channels and creatives based on CTR.  
- Highlighted cost-effective service providers through media cost analysis.  
- Uncovered trends in user engagement over campaign durations.  
- Analyzed budget allocation efficiency across different channels.  

---

## 🛠️ Tools Used  
- **Microsoft Excel:** Data analysis, visualization, and dashboard creation.  
- **Power Query:** Data cleaning, transformation, and preparation.  
- **PivotTables & PivotCharts:** For data aggregation and dynamic charting.  
- **Slicers:** To enable interactive filtering and exploration.  


