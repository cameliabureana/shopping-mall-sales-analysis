# Shopping Mall Sales Analysis | Excel Portfolio Project

**Project type:** Retail sales performance analysis  
**Tools:** Microsoft Excel (formulas, PivotTables, charts, dashboard), Microsoft PowerPoint  
**Analysis period:** 1 January 2021 – 8 March 2023  
**Completed:** November 2026

## Project overview

This independent portfolio project analyzes transaction-level retail sales data from ten shopping malls in Turkey. The aim is to identify which product categories and shopping malls generate the most revenue, understand changes in monthly sales, and develop evidence-based recommendations for retail planning.

**Main business question:** How can the retailer increase sales across its product categories and shopping malls?

I addressed three questions:

1. Which product categories generate the most revenue and sell the most items?
2. Which shopping malls have the highest revenue and number of transactions?
3. How does revenue change over time?

## Dataset

- **Source:** [Customer Shopping Dataset – Retail Sales Data, by Mehmet Tahir Aslan (Kaggle)](https://www.kaggle.com/datasets/mehmettahiraslan/customer-shopping-dataset)
- **Transactions:** 99,457
- **Original dataset:** 10 columns; the Excel analysis adds calculated / cleaned fields
- **Coverage:** 10 shopping malls and 8 product categories
- **Currency:** Turkish lira (TRY / ₺)
- **Time period:** January 2021 to 8 March 2023 (March 2023 is incomplete)

The underlying retail dataset was obtained from Kaggle; the data collection methodology was not independently verified as part of this project.

## Analysis workflow

### 1. Data preparation and cleaning

- Imported the transaction data into Excel.
- Calculated transaction revenue as **quantity × unit price**.
- Corrected invoice-date import/format issues in a new `invoice_date_clean` column while preserving the original date column.
- Validated the resulting monthly totals against the original CSV data and checked the final reporting date.
- Recorded modifications in `Changelog.docx`.

### 2. Exploratory analysis

Created PivotTables to summarize revenue and sales volume by category, revenue and transaction counts by shopping mall, and revenue by month/year.

### 3. Dashboard and presentation

Built an Excel dashboard with KPIs and charts, then developed a seven-slide PowerPoint presentation covering the objective, analytical questions, findings, and recommendations.

## Key findings

| Measure | Finding |
| --- | --- |
| Total revenue | **₺251.51 million** |
| Total transactions | **99,457** |
| Total items sold | **298,712** |
| Highest-revenue category | **Clothing:** ₺114.00 million; **103,558** items |
| Second-highest revenue category | **Shoes:** ₺66.55 million |
| Third-highest revenue category | **Technology:** ₺57.86 million |
| Highest-revenue mall | **Mall of Istanbul:** ₺50.87 million; **19,943** transactions |
| Second-highest revenue mall | **Kanyon:** ₺50.55 million; **19,823** transactions |
| Third-highest revenue mall | **Metrocity:** ₺37.30 million; **15,011** transactions |

For the complete months in 2021–2022, monthly revenue is broadly stable at approximately ₺8.3–10.3 million. July and October are among the stronger months in the observed data; however, two complete years are insufficient to establish a reliable seasonal pattern. The March 2023 total is lower because the data ends on 8 March.

## Business recommendations

1. **Prioritize high-performing categories:** Use the strong historical revenue of clothing, shoes, and technology to inform inventory and merchandising reviews, while checking margins before making investment decisions.
2. **Support high-volume locations:** Assess staffing and stock availability at Mall of Istanbul, Kanyon, and Metrocity, which have the highest transaction volumes and revenues in this dataset.
3. **Prepare for potentially higher-demand periods:** Review stock and capacity requirements ahead of July and October, while monitoring additional years of data before treating this as established seasonality.

These are recommendations based on descriptive historical analysis, not evidence of causal impact or future profitability.

## Repository files

| File | Contents |
| --- | --- |
| [`customer_shopping_data.xlsx`](customer_shopping_data.xlsx) | Excel dataset, calculated/cleaned fields, PivotTables, and interactive dashboard (open the **Dashboard** sheet) |
| [`Presentation_project1.pptx`](Presentation_project1.pptx) | Seven-slide presentation of project purpose, results, and recommendations |
| [`Project1_notes.docx`](Project1_notes.docx) | Original project planning notes and business questions |
| [`Changelog.docx`](Changelog.docx) | Record of data cleaning, verification, and dashboard changes |

## How to explore the project

1. Download `customer_shopping_data.xlsx` and open it in desktop Microsoft Excel.
2. Open the **Dashboard** worksheet for the visual overview and main KPIs.
3. Explore the PivotTable worksheets for category, shopping mall, and monthly breakdowns.
4. Open `Presentation_project1.pptx` for the business-facing summary.
5. Consult `Changelog.docx` for the data preparation steps.

**Note:** The Excel dashboard and PivotTables are best viewed in Microsoft Excel; GitHub does not provide a full interactive preview of Excel workbooks.

## Limitations

- This is descriptive analysis of a historical Kaggle dataset, not a live retailer's data.
- The data is not sufficient to determine profitability, customer demand drivers, or the impact of proposed actions; no cost or profit fields were analyzed.
- The available data covers two complete years plus part of 2023, limiting seasonality conclusions.
- Dataset completeness, sampling, and representativeness were not independently established.

## Dataset credit

Dataset created/published by **Mehmet Tahir Aslan** on [Kaggle](https://www.kaggle.com/datasets/mehmettahiraslan/customer-shopping-dataset). Original data is credited to its publisher; analysis, Excel dashboard, documentation and presentation are my portfolio work.
