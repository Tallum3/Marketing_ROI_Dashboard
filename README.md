# Marketing Campaign ROI Analysis

**Live Interactive Dashboard:** https://public.tableau.com/views/MarketingROIDashboard_17793263763180/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

## Project Overview
This project is an end-to-end Business Intelligence analysis designed to evaluate the performance and Return on Investment (ROI) of digital marketing campaigns across Google, Meta, and TikTok. The goal of this project is to provide a Chief Marketing Officer (CMO) with a high-level, actionable scorecard to determine where to allocate future ad spend.

## Tech Stack
* **Python (pandas):** Handled missing data, standardized date formats, and performed data type validation on a raw, real-world dataset.
* **SQL (SQLite):** Engineered queries to aggregate data and calculate executive KPIs (Net Profit, ROI %, and Cost Per Acquisition).
* **Tableau:** Designed an interactive, executive-level dashboard featuring KPI banners, dynamic trend lines, and color-coded profitability tracking.

## Key Insights
1. **Top Performing Platform:** Google Ads generated the highest overall revenue at $22,033,745.
2. **Highest ROI:** Despite having lower total revenue, TikTok Ads yielded the highest Return on Investment at 662.2%, indicating highly efficient ad spend.
3. **Trend Analysis:** Revenue saw a massive peak in April, driven by highly efficient but volatile TikTok campaigns. Conversely, Google and Meta demonstrated more stable, consistent revenue generation, peaking later in June.

## Repository Files
* `notebook.ipynb`: Contains the Python data cleaning "car wash" script and the SQL queries used for aggregation.
* `Dashboard_Screenshot.png`: A static view of the final Tableau dashboard.
