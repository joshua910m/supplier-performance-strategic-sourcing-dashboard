# Supplier Performance & Strategic Sourcing Dashboard

## Overview

Supplier Performance & Strategic Sourcing Dashboard is a Streamlit application built to turn messy procurement data into decision-ready supplier, risk, and sourcing insights. It is designed for procurement analysts, sourcing teams, and supply chain leaders who need to move quickly from raw Excel, CSV, or SQL-backed procurement datasets to supplier actions, scenario comparisons, and executive-ready recommendations.

## Business Problem

Procurement teams often work with incomplete, inconsistent, and non-standard source files that make it difficult to answer the questions leadership actually cares about. Supplier risk, quality issues, lead-time exposure, single-source dependencies, and fragmented spend can all exist in the data without being translated into clear decisions.

That creates a gap between analysis and action. Leaders may know there is exposure in the supply base, but they still need a way to see where spend is concentrated, which suppliers are truly replaceable, which components are structurally risky, and what to do next.

## Solution

This application ingests messy Excel and CSV procurement files or read-only SQL query results, normalizes the fields into a common structure, and converts them into supplier performance insights, sourcing risk views, scenario-based decision support, and action-oriented supplier recommendations. Instead of stopping at reporting, it combines analytics with business logic to highlight what should be retained, monitored, mitigated, consolidated, or exited.

## Key Features

- Automated data normalization for inconsistent procurement inputs
- First-class data ingestion from uploaded CSV/Excel files or read-only SQL queries
- KPI dashboard for supplier footprint, spend, lead time, defects, and single-source exposure
- Executive summary built from current supplier, component, and scenario analytics
- Supplier Risk vs Performance visualization for quality, lead-time, and spend exposure
- Decision Mix by Spend view to show how supplier spend is distributed across decision categories
- Priority supplier action recommendations with issues, actions, and savings
- Scenario analysis for supplier consolidation, mitigation, and tradeoff testing
- Post-scenario negotiation leverage modeling to identify where award concentration may support price, service, or lead-time improvements
- Strategic sourcing, risk, and action-planning views for follow-through

## Tech Stack

- Python
- Streamlit
- Pandas
- NumPy
- Altair
- GitHub

## How It Works

1. Load procurement data from Excel, CSV, or a read-only SQL query.
2. Normalize messy or inconsistent fields into a common data model.
3. Compute supplier, component, concentration, and risk analytics.
4. Classify supplier actions and highlight sourcing priorities.
5. Explore scenario alternatives, review negotiation leverage, and evaluate decision-ready outputs.

## SQL Database Configuration

SQL mode uses Streamlit native SQL connections. In the app, users can choose between:

- the bundled SQL example package backed by a local SQLite sample database
- their own configured `connections.sql` database from `.streamlit/secrets.toml`

To connect to your own database, store credentials in `.streamlit/secrets.toml`:

```toml
[connections.sql]
url = "postgresql+psycopg2://username:password@host:5432/database"
```

SQLAlchemy-compatible connection URLs are supported through Streamlit's SQL connection config. In this v1 implementation, SQL mode accepts read-only `SELECT` and `WITH` queries only.

Default bundled SQL tables:

- `procurement_data`
- `supplier_performance_summary`
- `component_risk_summary`

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

## Portfolio Context

This project demonstrates the ability to turn messy real-world procurement data into structured analytics that support actual business decisions. It combines data normalization, business logic, dashboard design, and supply chain frameworks in one practical tool rather than treating them as separate exercises.

From a portfolio perspective, it shows how to build decision-support products instead of static reports: the app ingests imperfect source data, applies supplier and sourcing logic, and presents the results in a format that is usable for executive reviews, analyst workflows, and scenario-driven planning.

This project demonstrates the ability to:
- Transform messy real-world procurement data into structured, decision-ready analytics
- Combine data engineering, business logic, and dashboard design into a single product
- Apply supply chain and sourcing frameworks in a practical, usable tool
- Build decision-support systems rather than static reporting dashboards

It is designed to reflect real-world procurement and supply chain workflows, where data is imperfect, decisions are multi-factor, and outputs must be actionable.
