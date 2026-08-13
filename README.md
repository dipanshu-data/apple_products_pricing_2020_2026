# apple_products_pricing_2020_2026
Personal project

## Project Title / Headline

A concise, descriptive name for the dashboard. Example: Apple Price by Platform Dashboard: Global apple products pricing Insights Dashboard A dynamic, interactive data visualization tool built to explore apple products pricing in Amazon & Flipkart data worldwide—focusing on Discount Comparisons, Sales event discount, Average rating and Stock health.


## Short Description / Purpose

1–2 sentences explaining what the dashboard does and why it exists.

Example: The Apple Product Price by Platform Dashboard is a visually engaging and analytical Power BI report designed to help users explore and compering over a two major platform(Amazon & Flipkart) The dashboard focuses on highlighting "discount lift during sales event, average discount by platform, platform stock health, product average rating by platform". This tool is intended for use by a Pricing/Merchandising team selling apple product across two biggest revenue given market (Amazon & Flipkart) where I promote/ad product.


## 🛠️ Tech Stack

The dashboard was built using the following tools and technologies:

- 📊 **Power BI Desktop** – Main data visualization platform used for report creation.
- 📂 **Power Query** – Data transformation and cleaning layer used to fix delimiter/encoding issues, reshape data, and prepare it for modeling.
- 🧠 **DAX (Data Analysis Expressions)** – Used for calculated measures (discount %, out-of-stock %, price volatility, YoY comparisons), conditional formatting logic, and per-platform/category breakdowns.
- 📝 **Data Modeling** – A dedicated Date table was built and marked as an official date table to enable clean time-intelligence functions (`SAMEPERIODLASTYEAR`, YoY calculations) and proper cross-filtering with the main pricing table.
- 🔍 **Data Analysis** – 80,000+ rows of Apple product pricing (2020–2026) analyzed across platform, category, condition, and sale-event dimensions.
- 🎛️ **Interactive Slicers & KPIs** – Model/SKU, Platform, Category, and Date Range slicers synced across all report pages for consistent filtering.
- 📁 **File Format** – `.pbix` for development, `.csv` as the raw data source, and `.png`/`.gif` for dashboard preview screenshots in this README.



## Features / Highlights

The best dashboard explanation format. • Business problem  • Walk through of key visuals (briefly!) • Business impact & Insights

• Business problem: Which platform (Amazon vs Flipkart) offers better/deeper discounts?
		  Which product category or model gets discounted most, and when?
		  Do sale events (Big Billion Days, Great Indian Festival, Black Friday, Prime Day) actually move price/discount/stock?
		  How has pricing (and discounting) on Apple products evolved from 2020 to 2026? … are difficult to answer quickly with raw data.


• Walkthrough of Key Visuals

    ## 🖼️ Dashboard Features

### 📌 Key KPIs (Top Left)
A KPI strip gives an instant health check of the dataset:
- **Discount Lift during Sales Events:** 13.4%
- **Average Discount:** 21.4%
- **Average Rating:** 4.5
- **Out of Stock:** 16.8%
- **In Stock:** 68.8%
- **Low Stock:** 14.4%

### 🎛️ Filter Panel
An interactive slicer panel lets users filter all visuals by **Platform, Category, Model/SKU, Condition, and Date Range** — enabling focused analysis on any specific product or time period without editing the report.

### 📊 Top Discount by Sales Event (Clustered Column Chart)
Ranks major sales events — Big Billion Days, Great Indian Festival, Black Friday, Prime Day — by average discount percentage, split by platform. Highlights which promotional events drive the deepest discounts and how that varies between Amazon and Flipkart.

### 📦 Average Current Price by Condition & Category (Stacked Column Chart)
Displays average price broken down by **Condition** (New vs. Renewed/Refurbished) and **Category** (iPhone, Mac, iPad, Watch). Helps identify the price gap between new and refurbished products across each product line.

### 🔍 Platform Deep-Dive (Matrix)
A drill-down matrix showing **Platform → Product Category** with Average Current Price, Average Rating, and Total Review Count — enables side-by-side comparison of platform performance at a category level.

### ⚠️ Stock Health (Matrix)
A matrix listing **Model Name, Product Category, Out-of-Stock %, and Average Discount**, filtered to surface only models with **high out-of-stock rates paired with high discounts** — flagging cases where inventory may not be keeping pace with promotional demand.

## Business Impact & Insights 

Sale events genuinely work: average discount jumps by +13.4 percentage points during active sale events vs baseline pricing. Platform discounting isn't uniform: one platform discounts deeper overall, but that gap isn't consistent across product categories. Inventory planning: Identify which specific Model/Platform combinations chronically run out of stock, so restocking can be prioritized before the next sale event. Platform strategy: Instead of a obscure "focus on Amazon or Flipkart," the category-level breakdown lets a team decide per product line where to prioritize listings, ad spend, or stock allocation.

### Screenshot

Show what the dashboard looks like.![Alt text](https://github.com/username/repo/assets/image.png)
Show what the dashboard looks like.
Example: ![Dashboard Preview](https://github.com/the-mansi-goel/Ski-dashboard/blob/main/Snapshot%20of%20the%20Dahbaord.png)
