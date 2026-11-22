# Corporate Financial Planning & Profitability Analysis

> A practice project focused on financial analysis, profitability, budget tracking, scenario modelling, and executive reporting using Microsoft Excel.

---

## Project Overview

This project simulates a corporate financial planning and profitability analysis workflow. It consolidates departmental data, evaluates financial performance, analyses profitability, tracks budget variances, and models different business scenarios to support management decision-making.

## Project Objectives

- Consolidate departmental financial datasets.
- Perform product-level and departmental profitability analysis.
- Analyse actual vs. budget performance.
- Identify expense overruns.
- Develop financial scenarios.
- Evaluate the impact of raw material price increases.
- Build a CFO-focused financial dashboard.

## Dashboard Preview

![CFO_Dashboard](Excel/CFO_Dashboard.png)

## Tools & Technologies

- Microsoft Excel
- Power Query
- PivotTables & PivotCharts
- Excel Financial Modelling
- Scenario Manager
- Data Tables
- Goal Seek
- VBA
- LM Studio
- Local LLM Integration

## Project Workflow

1. Data ingestion and consolidation
2. Data cleaning and transformation using Power Query
3. Data validation and reconciliation
4. Financial and profitability analysis
5. Budget variance analysis
6. Expense overrun identification
7. Scenario modelling
8. Dashboard development
9. AI-assisted executive memo generation

## Project Structure

- **Documentation** – Project requirements and documentation
- **Data** – Source datasets
- **Excel** – Financial models and analysis workbooks

### Important: Power Query Connections

The Excel workbook uses Power Query to import data from the source Excel files.

After downloading or cloning this repository, the Power Query source paths may need to be updated to match the location of the project folder on your local machine.

To restore data refresh functionality:

1. Open `CFO_Master_Model.xlsx` in Excel.
2. Go to **Data → Queries & Connections**.
3. Edit the source paths of the relevant Power Query queries to point to the files in `Data/Source_Files/`.
4. Refresh the queries.

The workbook's data transformations and analytical model are designed to work with the provided source files.

## Project Classification

| Attribute | Details |
|---|---|
| Project Type | Practice Project |
| Domain | Data Analytics / Financial Analysis |
| Primary Tool | Microsoft Excel |
| ETL | Power Query |
| Automation | VBA |
| AI Integration | LM Studio with local LLM |

## Disclaimer

This is a practice project developed for educational and analytical purposes. The datasets and financial outputs are not intended to represent the actual financial performance of any real company.
