# Streaming-Service-User-Analysis-Excel-Interactive-Dashboard
# Introduction
This project presents a comprehensive data analysis of a streaming service's user base using advanced Microsoft Excel techniques. The goal is to extract valuable insights from user behavior, subscription trends, device usage, and content engagement, and present them through a fully interactive Excel dashboard.
It simulates a real-world business case where management wants to optimize user experience, understand engagement levels, and uncover demographic trends to guide decision-making.

## 🗃️ Dataset Overview

The dataset consists of user-level information across various dimensions:

- **Subscription Info**: Monthly_Price, Membership_Status, Loyalty_Points  
- **User Behavior**: Watch_Hours, Total_Movies_Watched, Total_Series_Watched  
- **Demographics**: Age_Group, Country, Language_Preference  
- **Platform Usage**: Active_Devices, First_Device_Used, Has_Downloaded_Content  
- **Engagement Metrics**: Recommended_Content_Count, Average_Rating_Given  
- **Other Attributes**: Favorite_Genre, Primary_Watch_Time, Payment_Method

Total Columns: 22  
Total Rows: ~500 (simulated data)

## 📊 Excel Dashboard Features

The interactive dashboard was built using advanced Excel tools and offers:

- **Slicers** to filter by country, age group, device, and more
- **Pivot tables** for aggregation of movies vs. series watched
- **Bar and column charts** for content preference and subscription distribution
- **Trend analysis** for peak viewing times and revenue by plan
- **Conditional formatting** to highlight high engagement users
- **Custom KPIs**: Average Watch Hours, Churn Rate, Loyalty Score, Active Users

Designed to support both strategic insights and day-to-day operational tracking.

## 💡 Key Insights & Findings

- **High Engagement Genre**: Sci-Fi and Drama lead watch hours among the 18-34 age group.
- **Device Behavior**: Mobile devices dominate first-time access in emerging markets.
- **User Retention**: Over 70% of users with high loyalty points and regular logins remain active.
- **Revenue Split**: Mid-tier plans attract the largest user base but premium plans bring more revenue per user.
- **Peak Viewing Times**: Late night is the dominant watch time for users aged 18-24.

These insights help prioritize content acquisition, device optimization, and pricing strategies.

## 🧰 Tools & Excel Features Used

- Pivot Tables & Pivot Charts  
- Slicers and Timeline Filters  
- Named Ranges & Dynamic Ranges  
- IF, COUNTIFS, SUMIFS, AVERAGEIFS  
- Conditional Formatting  
- Data Validation for Dropdowns  
- Data Cleaning using Flash Fill & Text Functions  
- Dashboard Layout with Custom Design

The entire analysis was done **without using VBA or Power Query**, making it fully portable.

## 📌 Business Recommendations

1. Promote Sci-Fi and Drama content for the 18-34 audience segment.
2. Expand support for mobile-first features and app UI improvements.
3. Consider loyalty reward campaigns to boost retention.
4. Optimize pricing for mid-tier plans to increase upgrades.
5. Improve download feature promotion in countries with lower internet availability.

These strategies can drive user satisfaction and long-term growth.

## 📁 Files in This Repo

| File Name | Description |
|-----------|-------------|
| `StreamingServiceUserAnalysis.xlsx` | Excel file with raw data, pivot tables, and final dashboard |
| `README.md` | Project documentation |
| `Insights_Presentation.pptx` *(optional)* | Summary of analysis and recommendations |

## 🚀 How to Use This Dashboard

1. Open the Excel file.
2. Use the slicers (Country, Genre, Age Group, etc.) to filter data.
3. Navigate through the different visual blocks:
   - Revenue by Plan
   - Engagement by Genre
   - Watch Time Trends
4. Analyze KPIs at the top of the dashboard for performance at a glance.

No coding or Excel plug-ins are required.
