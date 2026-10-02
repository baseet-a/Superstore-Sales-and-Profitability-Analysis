# Superstore Sales and Profitability Analysis

**An end-to-end Excel analysis of sales, profitability, and business performance**

## Executive Summary

The analysis shows that strong sales performance does not always translate into proportional profitability. Across the 2014–2017 period, the dataset generated approximately **$2.30M in sales, $286.40K in profit, and 37,873 units sold**. Sales increased to their highest level in 2017, but profit margin was lower than in 2015 and 2016.

The analysis identified several areas that help explain these patterns. The **2015 sales decline was concentrated in specific periods and product areas**, particularly Technology and Office Supplies during March and September. **Higher discounts were strongly associated with weaker profit margins**, with the relationship becoming particularly pronounced at discounts of **20% and above**. Furniture also stood out as a high-sales, low-profitability category, with an overall **2.49% profit margin**, while Tables and Bookcases generated negative profitability.

These findings highlight the importance of evaluating **profitability alongside sales performance**, particularly when analyzing discounting, product categories, and periods of changing performance.

## Interactive Dashboard

![Interactive Dashboard](Superstore-Sales-and-Profitability-Analysis/Interactive%20Dashboard/Interactive%20Dashboard.gif)

## Business Objective

The objective of this project is to analyze sales and profit patterns across products, customer segments, geographic regions, and discounts, identify areas of strong and weak performance, and investigate factors within the available data associated with profitability.

Because no additional business documentation accompanies the dataset, the analysis is limited to questions and conclusions that can be supported by the available data.

## Methodology

The analysis followed a structured end-to-end workflow:

1. Data Understanding & Quality Assessment
2. Data Cleaning & Preprocessing
3. Exploratory Data Analysis
4. Business Analysis & Investigations
5. Dashboard & Final Summary

## Tools & Skills

**Excel:** Power Query , Pivot Tables, Pivot Charts, Slicers, Conditional Formatting, Calculated Metrics, Dashboard Design

**Data Analysis:** Exploratory Data Analysis, Descriptive Analysis, Trend Analysis, Categorical Analysis, Relationship Analysis, and Profitability Analysis

## Business Questions

### Main Investigations

1. **What factors are associated with the sales decline in 2015?**
2. **What factors are associated with the lower profit margin in 2017?**
3. **How is discount associated with profit and profit margin?**
4. **Which categories and sub-categories show strong sales but weak profitability?**

### Supporting Analysis

1. **Which sub-categories generate the most sales?**
2. **What are the top 10 states by sales and profit?**
3. **Which segments generate the most sales and profit?**

## Results & Business Insights

### 1. 2015 Sales Decline

The 2015 sales decline was concentrated in **Q1 and Q3**, with March and September showing lower sales than the same months in 2014, while total profit and quantity continued to increase. The March decline was primarily associated with **Technology**, particularly **Machines**, whose sales fell from **25,314 in March 2014 to zero in March 2015**. The September decline was associated with **Technology and Office Supplies**, with Machines falling from **22,420 to 629** and Binders from **12,743 to 2,863**. At the segment level, the March decline was associated with lower Home Office sales, while the September decline was associated with lower Consumer sales.

This indicates that the 2015 sales decline was **concentrated in specific periods and product areas rather than reflecting a broad decline in business activity**. Changes in the sales mix or transaction economics of these products may therefore warrant further investigation.

### 2. Lower Profit Margin in 2017

Although 2017 generated the highest annual sales, overall profit declined in **Q2 and Q4**, with Q2 falling from **$16,390 to $15,499 (-5.43%)** and Q4 from **$38,139 to $27,448 (-28.02%)** compared with 2016. The lower profit margin was associated with **weaker profitability in Furniture, particularly Tables and Bookcases**, with the issue also appearing across specific segments. Higher discount levels were also associated with lower average profit margins, particularly from **20% and above**.

The results show that **higher sales did not translate proportionally into profitability in 2017**, highlighting the importance of evaluating margin alongside top-line growth.

### 3. Discount & Profitability

Higher discount levels were associated with lower profitability, with the relationship substantially stronger for **profit margin** than for absolute profit. The trendline showed an **R² of 0.7473 for profit margin**, compared with **0.0482 for profit**, while the discount-level analysis showed declining average profit and profit margin at higher discount levels, particularly from **20% and above**.

This indicates that discounting is **more closely associated with the profitability of sales than with the absolute amount of profit generated**, making higher-discount transactions an important area for profitability monitoring.

### 4. Strong Sales but Weak Profitability

Furniture generated substantial sales but only a **2.49% overall profit margin**, substantially below the other categories. Within Furniture, **Tables and Bookcases** generated negative overall profitability, with their average profit and profit margin declining as discounts increased and becoming negative at **20% discount and above**. All customer segments were negatively affected at higher discount levels, while **Consumer and Corporate showed the most pronounced negative values in the segment analysis**.

The findings demonstrate that **strong sales do not necessarily indicate strong financial performance**. In this dataset, the sales-profit gap is concentrated in specific sub-categories and higher-discount transactions, showing why profitability should be evaluated alongside sales when assessing business performance.

## Next Steps

The analysis highlighted several areas that could be explored further:

- **Recurring monthly declines:** Investigate recurring monthly sales and profit declines to determine whether they are consistently associated with specific categories, sub-categories, segments, or discount levels.
- **Product-level profitability:** Drill down from Tables and Bookcases to individual products to identify which products contribute most to their negative profitability.
- **Geographic profitability:** Examine sales and profitability across states and regions to identify areas where strong sales are accompanied by relatively weak profitability.
- **Sales growth vs. profitability:** Further investigate situations where sales increase without a proportional increase in profit to better understand the factors associated with the gap.
