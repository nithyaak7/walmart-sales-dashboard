# Walmart Sales Performance Analysis | Power BI

**Business Intelligence | Retail Sales Analytics | Data Visualization | KPI Reporting**

A Power BI business intelligence project analyzing **$6.74 billion in historical sales across 45 Walmart stores** to identify top-performing departments, underperforming stores, seasonal sales patterns, and opportunities for retail performance improvement.

![Walmart Sales Dashboard](https://github.com/nithyaak7/walmart-sales-dashboard/blob/main/analysis-1.png)
![Walmart Sales Dashboard](https://github.com/nithyaak7/walmart-sales-dashboard/blob/main/analysis-2.png)
![Walmart Sales Dashboard](https://github.com/nithyaak7/walmart-sales-dashboard/blob/main/analysis-3.png)
![Walmart Sales Dashboard](https://github.com/nithyaak7/walmart-sales-dashboard/blob/main/analysis-4.png)

## Project Overview

Retail businesses need visibility into sales performance across stores, departments, and seasonal periods to support inventory, merchandising, and promotional decisions.

This project uses the Walmart Sales Forecasting dataset from Kaggle to develop a Power BI dashboard for analyzing historical weekly sales.

The analysis focuses on three business questions:

1. Which stores and departments generate the highest sales revenue?
2. Which departments consistently underperform or report negative sales?
3. How do sales patterns vary across years and around major holidays?

The project was originally developed as part of the **Business Intelligence Solutions (DBDA.X402)** coursework in November 2018.

## Dataset

**Source:** Walmart Sales Forecasting dataset, Kaggle

The dataset contains weekly department-level sales for 45 Walmart stores, categorized into three store types according to size.

| Attribute | Description |
|---|---|
| Stores | 45 |
| Departments | Up to 81 |
| Store types | A, B and C |
| Time period | February 2010 – November 2012 |
| Sales granularity | Weekly sales by store and department |

### Dataset Files

- `train.csv` — Weekly sales records by store and department
- `features.csv` — Additional store and time-related features, including holiday information
- `stores.csv` — Store type and size information

## Tools and Technologies

| Tool | Purpose |
|---|---|
| Power BI Desktop | Data analysis and interactive dashboard development |
| Power Query | Data preparation and transformation |
| DAX | Measures for sales analysis and KPI reporting |
| CSV datasets | Source data for sales and store attributes |

## Business Intelligence Approach

### 1. Data Preparation

The three source datasets were used to analyze sales performance at the store, department, and time-period levels.

A derived `Size_Class` attribute was created to categorize stores by size for comparative analysis.

### 2. KPI Development

The dashboard includes measures and views for:

- Weekly sales by department
- Weekly sales by year
- Weekly sales by store and size
- Store type by department
- Total yearly sales by month
- Total sales across the dataset

### 3. Dashboard Development

Power BI visualizations were developed to compare performance across stores, departments, years, and holiday periods.

The reports include yearly sales trends, top-performing departments, underperforming departments, store comparisons, and pre-holiday sales analysis.

## Dashboard Overview

### Sales Performance Overview

The dashboard reports **$6,737,218,987.11** in total sales across 45 stores.

| Store Type | Number of Stores | Total Sales |
|---|---:|---:|
| A | 22 | $4.33B |
| B | 17 | $2.00B |
| C | 6 | $405.50M |
| **Total** | **45** | **$6.74B** |

Type A stores account for the largest share of sales in the analyzed dataset.

### Top-Performing Stores

| Store | Total Sales |
|---|---:|
| Store 20 | $301.40M |
| Store 4 | $299.54M |
| Store 14 | $289.00M |
| Store 13 | $286.52M |
| Store 2 | $275.38M |

The ten highest-revenue stores contributed approximately 39% of total sales, according to the project report.

### Department Performance

Departments **92, 95, and 38** were identified as the highest-revenue departments, collectively contributing approximately 20% of total sales.

The analysis also highlighted underperforming departments:

- **Type A:** Departments 39, 43, 47, 51, and 78
- **Type B:** Departments 39, 47, 77, 78, and 79
- **Type C:** Departments 71 and 35

Department 47 was identified as a recurring area of concern, with negative sales recorded across multiple stores.

### Seasonal and Holiday Sales

The project analyzes sales around four major retail holidays:

- Super Bowl
- Labor Day
- Thanksgiving
- Christmas

For pre-holiday analysis, the project calculated sales during the two weeks preceding each holiday.

The report identifies strong seasonal activity around the Thanksgiving and Christmas periods, with December recording the highest monthly sales in the dashboard's monthly comparison.

## Key Findings and Business Recommendations

| Finding | Business Recommendation |
|---|---|
| Department 47 recorded recurring negative sales | Investigate product assortment, returns, pricing, and department performance |
| Store 28 showed negative sales in Department 6 | Review store-specific promotions and product placement |
| Department 38 underperformed at Store 33 despite strong overall performance | Investigate local inventory, demand, and merchandising |
| Departments 92 and 95 showed relatively low sales at Store 5 | Evaluate product mix and compare with stronger-performing stores |
| Department 71 recorded recurring negative sales in Type C stores | Review its continued viability in these stores |
| Seasonal patterns indicate opportunities beyond major holidays | Evaluate additional promotions ahead of summer sales periods |

These are analytical recommendations based on the historical dataset. They were not implemented or evaluated as part of the project.

## Project Files

| File | Description |
|---|---|
| [Power BI Dashboard](Walmart%20Sales%20Forecasting.pbix) | Editable Power BI project |
| [Dashboard PDF](Walmart%20Sales%20Forecasting.pdf) | Exported dashboard visualizations |
| [Business Intelligence Report](Walmart%20Sales%20-%20BI.pdf) | Detailed methodology, analysis, findings, and recommendations |
| [Sales Dataset](train.csv) | Historical weekly sales data |
| [Store Information](stores.csv) | Store classification and size |
| [Additional Features](features.csv) | Supporting retail and holiday attributes |

## How to Explore the Dashboard

1. Download and install Power BI Desktop.
2. Clone or download this GitHub repository.
3. Open `Walmart Sales Forecasting.pbix`.
4. If prompted, update the CSV data source paths to the downloaded project folder.
5. Refresh the dataset if necessary.
6. Explore sales performance using the dashboard's visualizations and filters.

Alternatively, open `Walmart Sales Forecasting.pdf` to view the exported dashboard without Power BI Desktop.

## Limitations

- The dataset contains historical sales from 2010–2012 and does not represent current Walmart performance.
- The dataset does not include a complete 2012 holiday season, limiting full-year comparisons.
- The promotional markdown fields contain incomplete historical data.
- Negative sales values require further investigation and should not automatically be interpreted as evidence of low customer demand.
- The project focuses on descriptive business intelligence rather than predictive sales forecasting.

## Future Enhancements

- Add a standardized date dimension for more consistent time-based comparisons.
- Build additional DAX measures for year-over-year growth and sales contribution.
- Introduce store- and department-level drill-through pages.
- Analyze relationships between promotional markdowns and sales.
- Develop a forecasting model as a separate extension of the descriptive analysis.

## Author

**Nithyaa Kesavamurthy**

Data & BI Analytics | SQL | Python | Power BI | Apache Superset

[GitHub](https://github.com/nithyaak7) · [Portfolio](https://nithyaak7.github.io/Data-Analyst-Portfolio/) · [LinkedIn](https://www.linkedin.com/in/nithyaa-k/)

