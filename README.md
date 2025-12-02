# FUTURE_DS_02
Future Interns internship Task 2
Task 2: Social Media Ad Campaign Performance Analysis
PROJECT OBJECTIVE
  The main objective of this project is to analyze multi-channel advertising data (Facebook/Instagram and other marketing platforms) to measure the performance of the campaign.
  The project evaluates:
      Total Sales generated
      Total Spend across platforms
      Engagement contribution by each channel
      Cost per Sale
      Return on Investment (ROI)
      Overall efficiency and trends across campaign entries
  This helps businesses identify which channels perform best, how efficiently money is being used, and what strategies can be improved for future campaigns.

DATASET USED
  The dataset used for this analysis is:
      Advertising_Data_Cleaned.xlsx
  It contains marketing spend and performance data from multiple advertising channels:
    Billboards
    Affiliate Marketing
    Google Ads
    Influencer Marketing
    Social Media Ads (Instagram/Facebook)
    TV Advertising
  Key columns included:
    Total_Spend
    Product_Sold
    ROI
    Cost_Per_Sale
    Efficiency
    Individual channel spend values
  This dataset was cleaned and processed to support dashboard visualization in Power BI.

PROCESS
  The analysis followed a structured workflow:
  1.Data Import & Cleaning
      Loaded the cleaned Excel dataset into Power BI.
      Verified column quality, types, and missing values.
      Ensured numerical fields were aggregated correctly.
  2.Creation of Key Measures
  Using DAX, various performance measures were created:
    Total Sales Measure
    Total Spend Measure
    Average ROI Measure
    Cost Per Sale Measure
    Efficiency Measure
  These measures allowed accurate KPI reporting.
  3.Dashboard Building
  Multiple visuals were created:
    KPI Cards → Average ROI, Total Sales, Total Spend
    Bar Charts → ROI by Row Index, Sales by Row Index
    Pie/Donut Chart → Spend distribution across marketing channels
    Scatter Charts → Relationship between Total Spend, Cost per Sale, and ROI
    Gauge Chart → Average Cost Per Sale
    Line Chart → Efficiency trends
  4.Insights & Interpretation
    Each visualization was analyzed to derive performance patterns, identify high-performing channels, and understand ROI nature.

DASHBOARD (Summary of What It Shows)
  The dashboard provides a complete view of campaign performance:
  Page 1 Highlights
    Total Spend: 891.75K
    Total Sales: 2M
    Average ROI: 1.37
    ROI filter to deep dive into specific ranges
    Spend distribution across Billboards, Social Media, TV, Google Ads, and more
    Bar chart showing sales performance across data entries
    Visualization comparing total spend vs product sold
  
  Page 2 Highlights
    Avg Cost per Sale: 0.43
    ROI distribution by index
    Efficiency trend line showing performance stability
    Combined bubble chart for ROI, sales, and spend

PROJECT INSIGHTS (Based on Your Dashboard)
  1.Social Media & Google Ads show the strongest contribution
  Spend distribution indicates that channels like:
    Google Ads
    TV
    Billboards
    Social Media Ads
    receive the highest investment — but Social Media and Google Ads yield better efficiency based on ROI and product sold.
  2. Overall campaign is performing profitably
    With Total Spend ≈ 891K and Sales ≈ 2M, the campaign is delivering high returns.
    Average ROI = 1.37
    Meaning for every ₹1 spent, ₹1.37 is earned — a strong profitability indicator.
  3. Cost per Sale is extremely efficient
    Average Cost per Sale = 0.43
    This means the campaign is reaching customers at a very low cost.
  4. Efficiency trend is stable
    The line chart shows a consistent efficiency pattern, meaning the campaign performance is predictable and stable across entries.
  5. Balanced multi-channel strategy
    The donut chart shows spending is evenly distributed across all channels, suggesting a well-planned, multi-channel marketing approach.

FINAL CONCLUSION
  This analysis shows that the advertising campaign is highly successful:
    High ROI (1.37)
    Strong Sales Output (2M)
    Good Spend Management (891K)
    Very low Cost per Sale (0.43)
    Stable Efficiency trends
    Social Media, Google Ads, and TV appear to be the most effective channels.
  The dashboard helps identify which platforms drive the best results and provides actionable insights for optimizing future ad spending, improving targeting, and maximizing conversion efficiency.
