# MWG Retail FP&A Dashboard

## 1. Project Overview

This project presents an FP&A-style Power BI dashboard for Mobile World Investment Corporation (MWG), focusing on financial performance, actual vs plan analysis, working capital efficiency, and operating cash flow trends.

The dashboard was built using MWG's audited consolidated financial statements, annual reports, and management plan data for the 2021–2026 period.

## 2. Objectives

The project aims to:

- Analyze MWG's revenue, profit after tax, gross margin, and net margin trends from 2021 to 2025.
- Compare 2025 actual performance against management targets.
- Visualize 2026 forward targets for revenue, profit after tax, and net margin.
- Assess working capital efficiency through inventory, receivables, payables, and operating cash flow.
- Build a portfolio-ready Power BI dashboard for financial analysis and FP&A practice.

## 3. Dashboard Pages

### 3.1 Executive Summary

This page provides an overview of MWG's revenue, profit after tax, gross margin, net margin, and expense ratio trends.

![Executive Summary](images/dashboard_screenshots/01_executive_summary.png)

### 3.2 Actual vs Plan

This page compares MWG's 2025 actual performance against management targets and presents 2026 forward targets.

![Actual vs Plan](images/dashboard_screenshots/02_actual_vs_plan.png)

### 3.3 Working Capital & Cash Flow

This page analyzes inventory, receivables, payables, operating cash flow, and working capital ratios.

![Working Capital & Cash Flow](images/dashboard_screenshots/03_working_capital_cash_flow.png)

## 4. Key Insights

- MWG's revenue recovered strongly after 2023, reaching VND 155,928bn in 2025.
- Profit after tax rebounded from VND 168bn in 2023 to VND 7,073bn in 2025.
- In 2025, MWG exceeded its revenue target by 3.95% and its profit after tax target by 45.83%.
- The 2026 management plan targets VND 185.0tn in revenue and VND 9.2tn in profit after tax.
- Inventory-to-revenue improved from 23.72% in 2021 to 17.49% in 2025.
- Operating cash flow remained positive throughout 2021–2025.

## 5. Tools Used

- Microsoft Excel: data structuring and financial model preparation
- Power BI: dashboard development and visualization
- DAX: calculated measures and financial ratios
- Financial statement analysis: data extraction, validation, and interpretation

## 6. Repository Structure

mwg-retail-fpna-dashboard/  
├── images/  
│   └── dashboard_screenshots/  
├── notes/  
│   ├── source_log.md  
│   ├── data_dictionary.md  
│   └── methodology.md  
├── README.md  
├── mwg_financial_model.xlsx  
└── mwg_retail_fpna_dashboard.pbix  

## 7. Notes

All figures are based on publicly available company disclosures. Detailed financial tables are presented in VND billion, while KPI cards and summary charts use VND trillion for readability.

This project is intended for learning, portfolio development, and financial analysis practice.
