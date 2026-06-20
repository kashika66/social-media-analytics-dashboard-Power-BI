# Instagram Social Media Analytics Dashboard (Power BI)

## 📌 Overview
This Power BI dashboard analyzes Instagram performance data — covering reach, engagement, 
follower growth, and content strategy — to uncover what drives results and forecast 
future growth trends.

## 🎯 Objective
To track Instagram engagement and reach trends, identify which content types and posting 
strategies perform best, and forecast follower growth over the next 6 months using historical data.

## 🛠️ Tools Used
- SQL (data extraction and cleaning)
- Power BI (data modeling, DAX measures, visualization)

## 📊 Dashboard Features
- KPI cards for Total Reach, Avg Engagement Rate, Total Followers Gained, and % Viral Posts
- Custom DAX measures for engagement rate and growth %
- 6-month forecasting on reach and follower growth trend lines
- Breakdown of traffic sources, media type performance, and post performance distribution
- Slicers for filtering by Media Type, Content Type (brand/creator), and Date Range

## 🖼️ Screenshots
![Dashboard Overview](screenshots/instagram-analytics-dashboard.png)

## 📂 Data Source
Sample/simulated Instagram performance data, structured and queried using SQL before 
building the Power BI model.

## 🔗 Live Dashboard / File
.pbix file available in this repository.

## 💡 Key Insights
- Posts without a call-to-action drove nearly double the reach of posts with one 
  (122M vs 66M), suggesting CTAs may need to be tested or repositioned to avoid 
  suppressing organic reach.
- Reels and images performed almost identically in engagement rate (4.23% each), 
  slightly ahead of carousels (4.18%) — indicating format alone isn't the main 
  driver of engagement.
- Traffic sources are fairly evenly split across Hashtags, External, and Reels Feed 
  (each ~16-17% of reach), showing a diversified discovery mix rather than reliance 
  on a single channel.
- 25% of posts achieved viral status, and reach/follower growth are forecasted to 
  remain stable over the next 6 months.
