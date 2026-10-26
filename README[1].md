# Bike Sales & Customer Analytics

An Excel-based customer analytics project exploring bike purchase behavior across customer demographics, income, household characteristics, commute distance, and geographic regions.

The project demonstrates an end-to-end spreadsheet workflow: raw-data review, data cleaning, exploratory analysis, pivot-based segmentation, customer lookup, and an executive-style dashboard.

## Project at a Glance

| Metric | Result |
|---|---:|
| Raw dataset records | 1,026 |
| Records in cleaned dataset | 1,000 |
| Records excluded during cleaning | 26 |
| Customers analyzed | 1,000 |
| Bike purchasers | 481 |
| Non-purchasers | 519 |
| Bike purchase rate | 48.1% |
| Average customer income | 56,360 |
| Average customer age | 44.16 years |

*Metrics above were recalculated from the workbook's RAW DATA and CLEAN DATA sheets. Average income is shown in the dataset's original numeric units; the workbook does not establish a currency.*

## Business Questions

- What share of customers purchased a bike?
- How does purchase behavior vary across customer demographics?
- How can income, age, education, occupation, household profile, commute distance, and region be used to segment customers?
- Which customer groups could be investigated further for marketing and sales opportunities?

## Tools & Techniques

- **Microsoft Excel**
- Data cleaning and standardization
- Exploratory data analysis (EDA)
- Pivot-table analysis
- Customer lookup tool
- KPI dashboard and data visualization
- Customer segmentation and business-question framing

## Workbook Structure

The Excel workbook contains six worksheets:

| Worksheet | Purpose |
|---|---|
| `RAW DATA` | Source customer records |
| `CLEAN DATA` | Standardized dataset used for analysis |
| `EDA` | Key summary metrics |
| `INFO_FINDER` | Customer lookup worksheet |
| `PIVOT_ANALYSIS` | Pivot-based analysis |
| `DASHBOARD` | High-level KPI dashboard |

## Key Findings

- **48.1%** of the 1,000 customers in the cleaned dataset are marked as bike purchasers.
- **51.9%** are marked as non-purchasers, so the dataset contains a slightly larger non-purchasing group.
- The cleaned dataset contains **511 male customers** and **489 female customers**.
- The cleaned dataset includes **508 customers from North America**, **300 from Europe**, and **192 from the Pacific region**.
- Average customer age is approximately **44.2 years**, and average income is **56,360** in the dataset's original units.

These are descriptive findings, not proof that any customer characteristic causes a purchase. Further segmentation and validation would be needed before making campaign or targeting decisions.

## Data Quality Checks

The cleaned worksheet was programmatically checked for:
- Record count and field structure
- Missing values across the 13 columns
- Duplicate customer IDs
- Purchase-status counts and headline metrics

Results:
- 1,000 cleaned records across 13 fields
- 0 missing values in the cleaned worksheet's 13 fields
- 0 duplicate IDs in the cleaned dataset
- 481 `PURCHASED` and 519 `NOT PURCHASED` records

The workbook contains 1,026 records in `RAW DATA` and 1,000 records in `CLEAN DATA`. The 26-record difference is documented here; the workbook alone does not provide enough evidence to confidently attribute every excluded record to a specific cleaning rule.

## How to Use

1. Download `bike_sales_customer_analytics.xlsx`.
2. Open it in Microsoft Excel.
3. Start with `DASHBOARD` for the KPI overview.
4. Review `PIVOT_ANALYSIS` and `EDA` for supporting analysis.
5. Compare `RAW DATA` with `CLEAN DATA` to understand the transformation workflow.

## Repository Contents

- `README.md` — project overview, methods, results, and usage guide
- `bike_sales_customer_analytics.xlsx` — Excel workbook with data, analysis, and dashboard
- `VALIDATION_NOTES.md` — checks performed and interpretation cautions

## Limitations

- Findings describe the data in this workbook and should not automatically be generalized to all bike buyers.
- The workbook does not establish the dataset's currency or a causal relationship between customer attributes and bike purchases.
- The exact rationale for all 26 records absent from the cleaned sheet should be documented if the original cleaning rules become available.
- Confirm the dataset's license and redistribution terms before publishing the workbook publicly.

## About This Project

This portfolio project demonstrates practical Excel-based data preparation, descriptive analysis, customer segmentation, and dashboard reporting. The goal is to turn customer data into clear, auditable summaries that can support better business questions and decisions.
