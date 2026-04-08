# Supplier Performance & Strategic Sourcing Dashboard

## Overview

Supplier Performance & Strategic Sourcing Dashboard is a Streamlit application built to turn messy procurement data into decision-ready supplier, risk, and sourcing insights. It is designed for procurement and supply chain teams that need to move quickly from raw Excel or CSV files to supplier actions, scenario comparisons, and executive-ready recommendations.

## Business Problem

Procurement teams often work with incomplete, inconsistent, and non-standard source files that make it difficult to answer the questions leadership actually cares about. Supplier risk, quality issues, lead-time exposure, single-source dependencies, and fragmented spend can all exist in the data without being translated into clear decisions.

That creates a gap between analysis and action. Leaders may know there is exposure in the supply base, but they still need a way to see where spend is concentrated, which suppliers are truly replaceable, which components are structurally risky, and what to do next.

## Solution

This application ingests messy Excel and CSV procurement files, normalizes the fields into a common structure, and converts them into supplier performance insights, sourcing risk views, scenario-based decision support, and action-oriented supplier recommendations. Instead of stopping at reporting, it combines analytics with business logic to highlight what should be retained, monitored, mitigated, consolidated, or exited.

## Key Features

- Automated data normalization for inconsistent procurement inputs
- KPI dashboard for supplier footprint, spend, lead time, defects, and single-source exposure
- Executive summary built from current supplier, component, and scenario analytics
- Supplier Risk vs Performance visualization for quality, lead-time, and spend exposure
- Decision Mix by Spend view to show how supplier spend is distributed across decision categories
- Priority supplier action recommendations with issues, actions, and savings
- Scenario analysis for supplier consolidation, mitigation, and tradeoff testing
- Strategic sourcing, risk, and action-planning views for follow-through

## Tech Stack

- Python
- Streamlit
- Pandas
- NumPy
- Altair
- GitHub

## How It Works

1. Upload procurement data from Excel or CSV.
2. Normalize messy or inconsistent fields into a common data model.
3. Compute supplier, component, concentration, and risk analytics.
4. Classify supplier actions and highlight sourcing priorities.
5. Explore scenario alternatives and review decision-ready outputs.

## Example Use Cases

- Identify single-source exposure before it becomes a continuity problem
- Evaluate which suppliers are strongest for consolidation
- Flag replaceable suppliers for exit or de-prioritization scenarios
- Compare risk concentration against spend concentration
- Support sourcing strategy and procurement decision-making with executive-ready outputs

## How to Run

1. Clone the repository:

```powershell
git clone https://github.com/joshua910m/supplier-performance-strategic-sourcing-dashboard.git
cd supplier-performance-strategic-sourcing-dashboard
```

2. Install dependencies:

```powershell
python -m pip install -r requirements.txt
```

3. Run the app:

```powershell
python -m streamlit run app.py
```

## Screenshot Placeholders

- `[Screenshot Placeholder] Executive Dashboard`
- `[Screenshot Placeholder] Supplier Decisions`
- `[Screenshot Placeholder] Scenario Analysis`

## Future Enhancements

- Power BI version for enterprise reporting environments
- Forecast and demand-planning integration
- Supplier benchmark and scorecard tracking over time
- Automated refresh pipeline from procurement source systems

## Why This Project Matters

This project is more than a dashboard. It demonstrates how analytics, business logic, and product thinking can come together to support real procurement and supply chain decisions. It handles messy procurement inputs, turns them into supplier and component risk views, and produces recommendations that are useful for leadership conversations, sourcing reviews, and practical action planning.
