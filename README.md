# data-analyst-portofolio-project
# Superstore Profitability & Discount Impact Analysis

## Project Overview
This project analyzes the relationship between sales, profit, and discount strategies using the Superstore dataset. The objective is to identify key drivers of profitability, evaluate the impact of discounts, and provide data-driven business recommendations through data cleaning, exploratory analysis, and interactive dashboard visualization.

## Business Questions
- How do discounts affect company profitability?
- Which product categories generate the highest and lowest profits?
- Which regions perform best and worst in terms of profit?
- Which customer segments contribute the most to overall profit?

## Dataset
- Source: Kaggle Superstore Dataset
- Records: 9,994
- Features: 21 columns

## Data Preparation
- Data quality assessment
- Data type correction (`Order Date`, `Ship Date`)
- Missing value validation
- Duplicate check
- Outlier identification
- Feature engineering:
  - Profit Ratio
  - Profit Status
  - Discount Category
  - Year
  - Month

## Tools & Technologies
- Python (Pandas, NumPy)
- Power BI
- Excel

## Key Findings

### 1. Discount Has a Strong Negative Impact on Profitability
- Total Sales reached **$2.29M**, while Total Profit was only **$286K**.
- Average discount was **15.62%**.
- Profitability significantly declines when discounts exceed **20%**.
- High-discount transactions account for **9.34%** of total orders and contribute heavily to losses.

### 2. Technology and Office Supplies Drive Profit
- Technology and Office Supplies are the most profitable categories.
- Furniture generates the lowest profit and has the weakest margin performance.

### 3. Tables Are the Largest Loss Contributor
- Tables recorded the highest loss at **-$17.7K**.
- Average discount on Tables reached **26.13%**, resulting in negative profitability.

### 4. Regional Performance
- West Region generated the highest profit.
- Central Region showed weak profitability despite strong sales performance.

### 5. Customer Segment Insights
- Consumer Segment is the largest contributor to company profit.
- Technology and Office Supplies within the Consumer Segment deliver the strongest results.

### 6. Profit Trend
- Profit increased consistently from **$49.5K (2014)** to **$93.4K (2017)**.
- Highest-profit months: **March, October, December**.
- Lowest-performing months: **January, April, July**.

## Dashboard Highlights
The interactive Power BI dashboard includes:
- Sales, Profit, and Profit Ratio KPIs
- Discount vs Profit Analysis
- Profit by Category & Sub-Category
- Regional Performance Analysis
- Customer Segment Analysis
- Monthly & Yearly Profit Trends

## Business Recommendations
1. Limit discounts to a maximum of **20%**.
2. Reduce aggressive promotions on the **Tables** sub-category.
3. Shift Central Region strategy from price competition to high-margin product bundling.
4. Strengthen loyalty programs for the Consumer Segment.
5. Tighten discount policies during low-profit periods, especially January and April.

## Conclusion
The company demonstrates strong sales growth; however, excessive discounting significantly reduces profitability. By optimizing discount strategies, focusing on high-performing categories, and improving regional efficiency, the business can substantially increase profit without sacrificing revenue growth.
