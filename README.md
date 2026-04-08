# Supplier Performance & Strategic Sourcing Dashboard

## Overview

This project is an executive-ready supplier performance and strategic sourcing decision dashboard built in Streamlit. It takes messy procurement Excel or CSV inputs, normalizes them into a consistent analytical model, and turns them into supplier risk visibility, sourcing priorities, action plans, and scenario comparisons.

The goal is not just to show charts. The dashboard is designed to help procurement, supply chain, and operations teams decide where spend is concentrated, where supplier and component risk is building, which suppliers should be retained or exited, and what sourcing actions should happen next.

## Business Problem

Procurement data is rarely ready for decision-making out of the box. Teams often inherit spreadsheets with inconsistent field names, incomplete risk inputs, mixed formats, and no clear link between raw spend data and the sourcing decisions leadership needs to make.

This project closes that gap by translating raw procurement data into a business-facing workflow that supports supplier reviews, sourcing strategy discussions, continuity risk assessments, and portfolio-level action planning.

## Key Features

- Executive dashboard with KPI cards, business narrative, priority supplier actions, and decision-first visuals
- Robust handling of messy Excel and CSV procurement inputs
- Supplier and component portfolio summaries
- Component-level supply risk scoring
- Supplier-level risk scoring
- Kraljic-style component segmentation
- ABC / Pareto prioritization views
- Supplier decision recommendations:
  - Keep / Consolidate To
  - Keep and Monitor
  - Eliminate / De-prioritize
- Scenario analysis for consolidation, mitigation, and sourcing tradeoff testing
- Strategic sourcing plan, supplier action plan, and sequenced action guidance
- Executive-ready exports for presentation and handoff

## Tech Stack

- Python
- Streamlit
- Pandas
- NumPy
- Altair
- OpenPyXL
- GitHub

## How It Works

1. Upload procurement data from Excel or CSV.
2. The app normalizes inconsistent source fields into a common structure.
3. It calculates supplier, component, risk, concentration, and sourcing analytics.
4. It classifies components and suppliers into decision-ready views.
5. It surfaces executive summaries, supplier actions, scenario comparisons, and strategic sourcing outputs.

## Example Use Cases

- Preparing for an executive supplier review
- Identifying single-source and high-risk component exposure
- Comparing consolidation and mitigation scenarios
- Prioritizing supplier exits, retention, and monitoring plans
- Teaching sourcing strategy, Pareto logic, and Kraljic analysis with a practical business dataset

## How to Run

1. Install dependencies:

```powershell
python -m pip install -r requirements.txt
```

2. Launch the Streamlit app:

```powershell
python -m streamlit run app.py
```

3. Open the local URL shown in the terminal, usually:

```text
http://localhost:8501
```

## Screenshot Placeholders

- `[Screenshot Placeholder] Executive Dashboard`
- `[Screenshot Placeholder] Component Risk`
- `[Screenshot Placeholder] Supplier Decisions`
- `[Screenshot Placeholder] Scenario Analysis`
- `[Screenshot Placeholder] Strategic Sourcing`
- `[Screenshot Placeholder] Action Plan`

## Future Enhancements

- Named scenario save/load and side-by-side scenario comparison history
- Audience-specific exports for executives, procurement managers, and supply chain analysts
- Sensitivity testing for supplier failure, lead-time shocks, and mitigation breakdowns
- Confidence scoring for inferred inputs and modeled assumptions
- More presentation-ready export layouts for board or leadership reviews

## Why This Project Matters

This dashboard shows how business analytics can move beyond reporting and into decision support. It combines Streamlit, Python, Pandas, NumPy, Altair, and GitHub into a portfolio-quality application that turns messy procurement data into sourcing, risk, and supplier action decisions.

For hiring managers and recruiters, the value of the project is that it demonstrates more than code. It shows business framing, data normalization, analytical modeling, decision logic, scenario evaluation, and executive-ready communication in one product.
