# SCT_DA_1

# 🛒 Superstore Sales Dashboard
### 📊 A Complete Business Intelligence & Data Analytics Project

> **Built by:** Mayank | **Tool:** Microsoft Excel | **Dataset:** Kaggle Superstore Sales Data
> **Internship:** SkillCraft Technology
![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoftexcel&logoColor=white)
---

## 📌 Table of Contents

- [🎯 Project Overview](#-project-overview)
- [📁 Dataset Summary](#-dataset-summary)
- [🔢 Key Business Metrics](#-key-business-metrics)
- [🧹 Data Cleaning Steps](#-data-cleaning-steps)
- [🏗️ Dashboard Structure](#️-dashboard-structure)
- [📊 Pivot Tables](#-pivot-tables)
- [📈 Charts Created](#-charts-created)
- [🎛️ Slicers & Interactivity](#️-slicers--interactivity)
- [🎨 Conditional Formatting](#-conditional-formatting)
- [💡 Key Business Insights](#-key-business-insights)
- [🗂️ Data Dictionary](#️-data-dictionary)
- [📐 Helper Columns Added](#-helper-columns-added)

---

## 🎯 Project Overview

This project involves building a **complete interactive sales dashboard** in Microsoft Excel using the Superstore Sales dataset from Kaggle. The objective is to provide a business intelligence view of sales performance across categories, regions, segments, time periods, and shipping operations.

### 🎯 Objectives
- ✅ Visualize **Total Sales & Profit** by Category
- ✅ Analyze **Sales Trends** over time (Monthly, Quarterly, Yearly)
- ✅ Identify **High & Low Performers** using Conditional Formatting
- ✅ Enable **interactive filtering** using Slicers
- ✅ Deliver **actionable business insights** for client presentation

---

## 📁 Dataset Summary

| Property | Detail |
|---|---|
| 📂 **Source** | Kaggle — Superstore Sales Forecasting |
| 📄 **File Name** | `train.csv` |
| 📏 **Total Rows** | 9,800 |
| 📋 **Total Columns** | 18 |
| 📅 **Date Range** | January 2015 – December 2018 |
| 🌍 **Geography** | United States — 49 States, 529 Cities |

---

## 🔢 Key Business Metrics

### 💰 Revenue & Orders

| Metric | Value |
|---|---|
| 💵 Total Revenue | **$2,261,536.78** |
| 📦 Unique Orders | **4,922** |
| 👥 Unique Customers | **793** |
| 🏷️ Unique Products | **1,849** |
| 📈 Avg Order Value | **$459.48** |
| 📉 Avg Sale per Line | **$230.77** |
| 🔼 Highest Single Sale | **$22,638.48** |
| 🔽 Lowest Single Sale | **$0.44** |
| ⏱️ Avg Shipping Days | **4.0 days** |

---

### 📦 By Category — 3 Categories

| Category | Orders | Customers | Total Sales | Avg Sale |
|---|---|---|---|---|
| 💻 Technology | 1,813 | 684 | $827,455 | $456.40 |
| 🪑 Furniture | 2,078 | 705 | $728,658 | $350.65 |
| 📎 Office Supplies | 5,909 | 787 | $705,422 | $119.38 |

---

### 🏷️ By Sub-Category — 17 Sub-Categories

| Sub-Category | Orders | Total Sales | Avg Sale |
|---|---|---|---|
| 📱 Phones | 876 | $327,782 | $374.18 |
| 🪑 Chairs | 607 | $322,822 | $531.83 |
| 📦 Storage | 832 | $219,343 | $263.63 |
| 🗃️ Tables | 314 | $202,810 | $645.89 |
| 📋 Binders | 1,492 | $200,028 | $134.07 |
| 🖥️ Machines | 115 | $189,238 | $1,645.55 |
| 🔌 Accessories | 756 | $164,186 | $217.18 |
| 🖨️ Copiers | 66 | $146,248 | $2,215.88 |
| 📚 Bookcases | 226 | $113,813 | $503.60 |
| 🏠 Appliances | 459 | $104,618 | $227.93 |
| 🪴 Furnishings | 931 | $89,212 | $95.82 |
| 📄 Paper | 1,338 | $76,828 | $57.42 |
| 🛒 Supplies | 184 | $46,420 | $252.28 |
| 🎨 Art | 785 | $26,705 | $34.02 |
| ✉️ Envelopes | 248 | $16,128 | $65.03 |
| 🏷️ Labels | 357 | $12,347 | $34.59 |
| 📎 Fasteners | 214 | $3,001 | $14.03 |

---

### 🌍 By Region — 4 Regions

| Region | Orders | Customers | Total Sales | Avg Sale |
|---|---|---|---|---|
| 🏆 West | 3,140 | 681 | $710,219 | $226.18 |
| 🥈 East | 2,785 | 669 | $669,518 | $240.40 |
| 🥉 Central | 2,277 | 626 | $492,646 | $216.36 |
| 📍 South | 1,598 | 509 | $389,151 | $243.52 |

---

### 👥 By Segment — 3 Segments

| Segment | Orders | Customers | Total Sales | Avg Sale |
|---|---|---|---|---|
| 🛒 Consumer | 5,101 | 409 | $1,148,060 | $225.07 |
| 🏢 Corporate | 2,953 | 236 | $688,494 | $233.15 |
| 🏠 Home Office | 1,746 | 148 | $424,982 | $243.40 |

---

### 🚚 By Ship Mode — 4 Modes

| Ship Mode | Orders | Total Sales | Avg Sale | Avg Days |
|---|---|---|---|---|
| 📦 Standard Class | 5,859 | $1,340,831 | $228.85 | 5.0 days |
| 📫 Second Class | 1,902 | $449,914 | $236.55 | 3.2 days |
| ✈️ First Class | 1,501 | $345,572 | $230.23 | 2.2 days |
| ⚡ Same Day | 538 | $125,219 | $232.75 | 0.04 days |

---

### 📅 By Year

| Year | Unique Orders | Customers | Total Sales | Avg Sale |
|---|---|---|---|---|
| 📅 2015 | 947 | 589 | $479,856 | $245.70 |
| 📅 2016 | 1,019 | 567 | $459,436 | $223.57 |
| 📅 2017 | 1,295 | 635 | $600,192 | $236.86 |
| 📅 2018 | 1,661 | 690 | $722,052 | $221.62 |

---

### 🗺️ Top 10 States by Sales

| Rank | State | Orders | Customers | Total Sales |
|---|---|---|---|---|
| 🥇 1 | California | 1,946 | 570 | $446,306 |
| 🥈 2 | New York | 1,097 | 409 | $306,361 |
| 🥉 3 | Texas | 973 | 367 | $168,572 |
| 4 | Washington | 504 | 223 | $135,206 |
| 5 | Pennsylvania | 582 | 255 | $116,276 |
| 6 | Florida | 373 | 178 | $88,436 |
| 7 | Illinois | 483 | 231 | $79,236 |
| 8 | Michigan | 253 | 105 | $76,136 |
| 9 | Ohio | 454 | 196 | $75,130 |
| 10 | Virginia | 224 | 107 | $70,636 |

---

### ⚠️ Bottom 5 States by Sales

| State | Orders | Total Sales |
|---|---|---|
| North Dakota | 7 | $919 |
| West Virginia | 4 | $1,209 |
| Maine | 8 | $1,270 |
| South Dakota | 12 | $1,315 |
| Wyoming | 1 | $1,603 |

---

### 📦 Shipping Days Distribution

| Days | Orders | % of Total |
|---|---|---|
| ⚡ 0 days | 514 | 5.2% |
| 🟢 1 day | 363 | 3.7% |
| 🟢 2 days | 1,295 | 13.2% |
| 🟡 3 days | 978 | 10.0% |
| 🟡 4 days | 2,718 | 27.7% |
| 🟠 5 days | 2,147 | 21.9% |
| 🔴 6 days | 1,170 | 11.9% |
| 🔴 7 days | 615 | 6.3% |

---

## 🧹 Data Cleaning Steps

| # | Step | Detail |
|---|---|---|
| 1 | 🗑️ **Removed Duplicates** | 8 duplicate Order ID + Product ID rows removed |
| 2 | 📅 **Fixed Date Format** | Parsed `dd/mm/yyyy` to proper datetime |
| 3 | 🔢 **Fixed Shipping Days** | Reformatted column from Date to Number |
| 4 | 📊 **Added Helper Columns** | 9 new columns added for analysis |
| 5 | 📋 **Named Table** | Converted to Excel Table named `SuperstoreData` |
| 6 | 🔍 **Auto Filter** | Filter enabled on all 18 columns |
| 7 | 🧊 **Froze Header Row** | Top row frozen via View → Freeze Panes |
| 8 | ✅ **Verified Data Types** | Sales = Currency, Dates = Date, Numbers = Number |

---

## 📐 Helper Columns Added

| Column | Formula | Purpose |
|---|---|---|
| 📅 **Year** | `=YEAR(C2)` | Group data by year |
| 📅 **Month Num** | `=MONTH(C2)` | Sort months in correct order |
| 📅 **Month Name** | `=TEXT(C2,"mmm")` | Display Jan, Feb, Mar... |
| 📅 **Quarter** | `=TEXT(C2,"YYYY")&" Q"&INT((MONTH(C2)+2)/3)` | Group by quarter (2015 Q1 etc.) |
| 🚚 **Shipping Days** | `=D2-C2` | Calculate delivery time in days |
| 💰 **Profit (Est.)** | `=IF(O2="Technology",R2*0.20,IF(O2="Furniture",R2*0.08,IF(O2="Office Supplies",R2*0.25,R2*0.15)))` | Estimate profit using category margins |
| 🏷️ **Sales Band** | `=IF(R2>=1000,"High",IF(R2>=200,"Medium","Low"))` | Classify each sale by size |
| 📦 **Order Size** | `=IF(R2>=500,"Large",IF(R2>=100,"Medium","Small"))` | Tag order size |
| 🔢 **Order Count** | `=1` | Enables accurate order counting in pivot |

---

## 🏗️ Dashboard Structure

```
📊 Dashboard          ← Main visual page with all charts & slicers
📋 Pivot_Source       ← All 10 pivot tables (hidden from client)
🗂️ Data              ← Cleaned raw data (9,792 rows after dedup)
📈 Chart Data         ← Helper tables for non-pivot charts
```

---

## 📊 Pivot Tables — 10 Total

| # | Name | Rows | Key Values | Chart Type |
|---|---|---|---|---|
| PT1 | 📦 Sales by Category | Category | Sales, Orders, Profit, Avg Order | Horizontal Bar |
| PT2 | 🏷️ Sales by Sub-Category | Sub-Category | Sales, Orders, % Total | Horizontal Bar |
| PT3 | 📅 Monthly Trend | Order Date (Month+Year) | Sales, MoM % | Line Chart |
| PT4 | 📅 Quarterly Trend | Quarter | Sales, Profit, Orders | Column + Line Combo |
| PT5 | 📅 Yearly Trend | Year | Sales, Profit, YoY% | Line + Column Combo |
| PT6 | 🌍 Sales by Region | Region | Sales, Orders, % Total | Pie / Donut |
| PT7 | 👥 Segment × Category | Segment / Category | Sales | Stacked Bar |
| PT8 | 🗺️ Region × Category | Region / Category | Sales | Stacked Column |
| PT9 | 🚚 Orders by Ship Mode | Ship Mode | Orders, Avg Days | Donut Chart |
| PT10 | 🌡️ Sales Heatmap | Month / Year | Sales | Colour Table |

---

## 📈 Charts Created — 10 Charts

| # | Chart Name | Type | Key Insight |
|---|---|---|---|
| 1 | 📊 Sales & Profit by Category | Horizontal Bar | Technology leads revenue |
| 2 | 📈 Sales Trend by Quarter | Line + Column Combo | Q4 peak every year |
| 3 | 🏷️ Profit by Sub-Category | Column Chart | Copiers highest avg sale |
| 4 | 🥧 Sales by Year | Pie / Donut | 2018 = 32% of total revenue |
| 5 | 📉 Monthly Sales Trend | Line with Markers | Clear seasonal waves |
| 6 | 🌍 Sales by Region | Pie Chart | West dominates at 31% |
| 7 | 👥 Segment × Category | Stacked Bar | Consumer drives volume |
| 8 | 🗺️ Region × Category | Stacked Column | Tech strong in all regions |
| 9 | 🚚 Orders by Ship Mode | Donut Chart | Standard Class = 60% |
| 10 | 📅 YoY Growth | Line + Column Combo | 75% order growth 2015–2018 |

---

## 🎛️ Slicers & Interactivity

### 5 Slicers Connected to All Pivot Tables

| Slicer | Options | Use Case |
|---|---|---|
| 📅 **Year** | 2015, 2016, 2017, 2018 | Compare performance year by year |
| 📅 **Quarter** | 2015 Q1 → 2018 Q4 | Detect seasonal patterns |
| 📦 **Category** | Furniture, Office Supplies, Technology | Deep dive into one product line |
| 🌍 **Region** | Central, East, South, West | Geographic analysis |
| 👥 **Segment** | Consumer, Corporate, Home Office | Customer type analysis |

### 🔗 How Slicers Work
```
Click ONE value  →  All 10 charts update instantly
Hold Ctrl + Click  →  Select multiple values
Click ✕ on slicer  →  Clear filter and reset all charts
Use 2–3 slicers together  →  Deep-dive cross-analysis
```

### 💡 Power Slicer Combinations

| Combination | Business Question |
|---|---|
| Year=2018 + Region=West | Best year in best region |
| Category=Technology + Segment=Corporate | Highest value transactions |
| Region=South + Quarter=Q1 | Weakest market, slowest season |
| Segment=Consumer + Quarter=Q4 | Peak season planning scenario |
| Year=2016 + all regions | Why did sales dip in 2016? |

---

## 🎨 Conditional Formatting

| Location | Rule Applied | Visual |
|---|---|---|
| 📊 Category Sales column | Color Scale | 🟢 Green (high) → 🔴 Red (low) |
| 🏆 Sales Rank column | Icon Set — Stars | ⭐ Full=Rank1, Half=Rank2, ☆=Rank3 |
| 📈 MoM % Change | Icon Set — Arrows | 🟢 Up arrow = growth, 🔴 Down = decline |
| 📅 Quarterly Sales | Top/Bottom Rules | 🟢 Top 4 quarters green, 🔴 Bottom 4 red |
| 📅 YoY Growth % | Color Scale | 🟢 Positive growth, 🔴 Negative |
| 🏷️ Sub-Category Sales | Data Bars | Blue bars proportional to value |
| 🌡️ Sales Heatmap | 3-Color Scale | Light Blue → Gold → Dark Red |
| 🗂️ Raw Data Sales | 3-Color Scale | White → Green (low to high) |

---

## 💡 Key Business Insights

### 🏆 Top 10 Findings

**1. 📈 Strong Revenue Growth**
> Orders grew **75%** from 947 (2015) to 1,661 (2018). Total revenue up from $479K to $722K — 50% growth in 4 years.

**2. 📅 Q4 Seasonality is Dominant**
> Q4 (Oct–Dec) drives **~35% of annual revenue** every year without exception. Q1 is consistently the weakest.

**3. 💻 Technology = Star Category**
> Highest revenue ($827K), highest avg sale ($456), fewest orders but most value. Best ROI category.

**4. 🪑 Furniture Needs Pricing Review**
> $728K in sales but only **8% estimated profit margin** vs Technology's 20%. Volume without profit.

**5. 📎 Office Supplies = Loyal Customer Base**
> Most orders (5,909) and most customers (787) but lowest avg sale ($119). Strong repeat-buying behaviour.

**6. 🌍 West Region is the Cash Cow**
> $710K revenue, largest customer base (681). Largest single revenue contributor.

**7. 📍 South is the Untapped Opportunity**
> Fewest customers (509), lowest revenue ($389K). Biggest potential for targeted expansion.

**8. 🏢 Corporate = High Value Segment**
> Only 236 customers generating $688K — average of $2,917 per customer. High-value, low-volume segment.

**9. 📦 Standard Class Dominates Shipping**
> 60% of all orders choose Standard Class. Customers clearly prioritise cost savings over delivery speed.

**10. 🗺️ California = 20% of Revenue**
> $446K from one state. Top 2 states (CA + NY) = **33% of total revenue** — geographic concentration risk.

---

## 🗂️ Data Dictionary

| Column | Type | Description | Example |
|---|---|---|---|
| Row ID | Number | Unique row identifier | 1, 2, 3... |
| Order ID | Text | Unique order (one order = multiple rows) | CA-2015-100293 |
| Order Date | Date | Date order was placed | 08/11/2016 |
| Ship Date | Date | Date order was shipped | 11/11/2016 |
| Ship Mode | Text | Shipping method | Standard Class |
| Customer ID | Text | Unique customer identifier | CG-12520 |
| Customer Name | Text | Full name of customer | Claire Gute |
| Segment | Text | Customer type | Consumer |
| Country | Text | Always United States | United States |
| City | Text | City of delivery | Henderson |
| State | Text | State of delivery | Kentucky |
| Postal Code | Number | ZIP code | 42420 |
| Region | Text | Geographic region | South |
| Product ID | Text | Unique product identifier | FUR-BO-10001798 |
| Category | Text | Product category (3 total) | Furniture |
| Sub-Category | Text | Product sub-category (17 total) | Bookcases |
| Product Name | Text | Full product name | Bush Somerset Collection... |
| Sales | Decimal | Revenue in USD | $261.96 |

*Helper columns (Year, Month, Quarter, Shipping Days, Profit Est., Sales Band, Order Size, Order Count) added during data preparation*

---

## 🛠️ Tools & Skills Demonstrated

| Tool / Skill | Application |
|---|---|
| 📊 **Microsoft Excel** | Primary dashboard and analysis tool |
| 🔄 **Pivot Tables** (10 total) | Multi-dimensional data aggregation |
| 📈 **PivotCharts** (10 total) | Visual storytelling from pivot data |
| 🎛️ **Slicers** (5 slicers) | Interactive cross-filtering |
| 🎨 **Conditional Formatting** (8 rules) | Visual performance highlighting |
| 🧮 **Excel Formulas** | YEAR, MONTH, TEXT, IF, RANK, COUNTIF, INT |
| 🧹 **Data Cleaning** | Deduplication, type fixing, validation |
| 📐 **Calculated Fields** | Avg Order Value inside pivot tables |
| 📉 **Business Analysis** | KPI identification, insight generation |
| 🎤 **Client Presentation** | Slicer-driven storytelling for stakeholders |

---

## 📊 Quick Reference Card

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
📊 SUPERSTORE DASHBOARD — QUICK STATS
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

COUNTS
──────────────────────────────────────
📦 Categories          →       3
🏷️  Sub-Categories      →      17
🌍 Regions             →       4
👥 Segments            →       3
🚚 Ship Modes          →       4
🗺️  States              →      49
🏙️  Cities              →     529
🛒 Products            →   1,849
👤 Customers           →     793
📋 Unique Orders       →   4,922
📄 Total Data Rows     →   9,800

MONEY
──────────────────────────────────────
💵 Total Revenue       → $2,261,536
📈 Avg Order Value     →      $459
🔼 Highest Sale        →   $22,638
🔽 Lowest Sale         →     $0.44

TIME
──────────────────────────────────────
📅 Years of Data       → 4 (2015–2018)
⏱️  Avg Shipping Time   → 4.0 days
⚡ Fastest Delivery    → 0 days (Same Day)
🐢 Slowest Delivery    → 7 days
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

---

## 👤 Author
 Hey, I’m Mayank, a Data Analyst & Tech Enthusiast.

 ### 🚀 Stay Connected

---

*📅 Project Completed: June–July 2026*
*📂 Dataset Source: Kaggle — Superstore Sales Forecasting*
*🔗 [View Dataset on Kaggle](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting)*
