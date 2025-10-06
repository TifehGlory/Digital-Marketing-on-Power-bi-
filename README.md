# Digital-Marketing-on-Power-bi-
## Project Overview
This documentation outlines the development of an interactive digital marketing dashboard designed to monitor campaign performance across multiple channels (Email, Instagram Ads, Influencer Marketing, Google ads.).The dashboard provides actionable insights to optimize ad spend, track conversions, and measure ROI.
## Project Objectives
1. Track key metrics (Ad Spend, Impressions, Clicks, Conversions, Revenue, ROI).
2. Compare performance by channel, product, and category.
3. Analyze time-based trends (daily/weekly/monthly).
4. Enable dynamic filtering for deeper analysis.

## Data Sources & Preparation
## Dataset Used
Marketing Campaign Data (Includes: Ad Spend, Impressions, Clicks, Conversions, Revenue, Product Name, Campaign Date, Marketing Channel).
## Data Cleaning & Transformation
1. Checked for duplicates and null values.
2. Created a Date Table for time intelligence.
3. Created DAX Measure (for Revenue per conversion, ROI, CTR, ) using Column and Measure.

<img width="508" height="201" alt="image" src="https://github.com/user-attachments/assets/1d702f47-3977-4ccd-813c-39549a854332" />


## Visual Layout

<img width="509" height="294" alt="image" src="https://github.com/user-attachments/assets/32354a93-25c0-42ba-bea3-055853964340" />


### KPI Cards using New card as visual
Total Ad Spend
Total Impression
Total Clicks
Total Conversion
Total Revenue
Overall ROI
### Charts & Graphs
1. Ad Spend by Channel (Stacked Bar Chart)
X-axis: Marketing Channel
Y-axis: Ad Spend
2. Clicks vs. Impressions (Scatter Plot)
X-axis: Impressions
Y-axis: Clicks
Size: Conversion Rate
3. Conversion Rate by Category (Horizontal Bar Chart)
Category: Product Category
Value: Conversion Rate = DIVIDE([Conversions], [Clicks], 0)
4. Revenue by Product (Horizontal Bar Chart)
X-axis: Revenue
Y-axis: Product Name
5. ROI by Product name (Stacked column chart)
Y-axis: Product Name
X-axis: ROI
6. Clicks by Impression (Stack Area Chart)
7. Conversion rate by marketing channel (Tree Map)
 ### Interactivity Features
### Slicers for:
Campaign Date (Range selector)
Product Name (Dropdown)
Product Category (Checklist)
Marketing Channel (Buttons)
Cross-filtering: Clicking on any visual updates all others.
### Key Insight Discovered

1. **Performance Overview:** The marketing strategy is driving revenue, but ROI varies significantly by product/channel, indicating inefficiencies in budget allocation.

2. **Channel level Analysis:** GoogleAds (0.52M) is the highest spend, Influencer (0.46M) is moderately spend  instagram ads (0.45M) is lower spend and under utilized with conversion check.

3. **Category Performance:** Groceries (0.24M conversions) leads, followed by Snacks (0.22M) while Household (0.21M) and Personal Care (0.21M) lag slightly.

4. Clicks (2.6M peak) and Conversions (2.4M) are stable but could grow

5. January, November and December has the highest spending which is linked to seasonal campaigns.

### Recommendations
1. Enhance Click-Through Rates (CTR)

**Action:** Implement A/B testing for ad creatives, refine audience targeting, and experiment with innovative ad formats.

**Goal:** Elevate CTR beyond the current benchmark.

2. Focus on High-ROI Categories

**Action:** Prioritize marketing efforts for Household and Personal Care products, as they deliver superior returns.

**Rationale:** These categories consistently demonstrate higher profitability per spend.

3. Optimize Budget Allocation Timing

**Action:** Redistribute ad spend more evenly across quarters to avoid over-concentration in January and December.

**Benefit:** Mitigate seasonal performance dips and maintain consistent engagement.

4. Reassess Low-Performing Categories

**Action:** Either reduce investment in Beverages and Snacks or overhaul their marketing strategies through:

a. Improved audience segmentation

b. Enhanced value proposition in ad copy

c. Competitive pricing promotions

5. Capitalize on Top-Performing Products

**Action:** Allocate additional resources to Cold Drink, Biscuits, and Dishwasher Liquid campaigns.

**Justification:** These products dominate revenue generation and warrant sustained promotional support.







