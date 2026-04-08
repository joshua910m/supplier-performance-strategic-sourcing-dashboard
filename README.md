# Supplier Performance & Strategic Sourcing Dashboard

An executive-ready Streamlit dashboard that turns messy procurement data into supplier decisions, sourcing priorities, risk visibility, and scenario-based action plans.

## Overview

This project was built to help supply chain, procurement, and operations leaders move from raw purchasing records to practical sourcing decisions. The app accepts imperfect Excel or CSV procurement data, normalizes the fields into a consistent analytical model, and then translates the portfolio into supplier recommendations, component risk views, strategic sourcing priorities, and scenario comparisons.

Instead of stopping at descriptive analytics, the dashboard connects spend, quality, lead time, concentration, Kraljic-style positioning, and scenario modeling into one decision workflow. The result is a business-facing tool that can support executive reviews, sourcing workshops, classroom demonstrations, or portfolio-level supplier strategy work.

## Why This Project Matters

Most procurement data is not presentation-ready. It is often spread across inconsistent files, uses non-standard column names, and does not immediately answer the real management questions:

- Where is the money concentrated?
- Which suppliers are truly strategic versus replaceable?
- Where is the portfolio exposed to single-source or high-risk components?
- What happens if we consolidate suppliers more aggressively?
- Which actions should the supply chain team take next?

This dashboard closes that gap by converting messy input data into a sourcing narrative, risk model, priority supplier actions, and decision-ready visuals.

## Key Features

- Executive dashboard with KPI cards, business narrative, priority supplier actions, and portfolio visuals
- Robust ingestion and normalization for messy procurement Excel and CSV files
- Supplier and component spend analysis
- Component-level supply risk scoring
- Supplier-level risk scoring
- Kraljic-style component segmentation
- ABC / Pareto prioritization across spend, risk-adjusted burden, and strategic priority
- Supplier decision logic:
  - Keep / Consolidate To
  - Keep and Monitor
  - Eliminate / De-prioritize
- Scenario analysis for supplier consolidation, mitigation assignment, and tradeoff testing
- Strategic sourcing plan, supplier risk assessment, and sequenced action planning
- Executive visual export and downloadable analysis bundles

## Business Value

This dashboard helps organizations:

- Identify where supplier and component concentration create continuity risk
- Focus sourcing and mitigation work on the parts that matter most
- Separate large suppliers from strategically sensitive suppliers
- Compare resilience and savings tradeoffs across scenario options
- Turn portfolio analytics into a structured action plan for sourcing teams
- Present supplier strategy in a format that executives can understand quickly

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
2. The app normalizes source fields even when headers are messy or inconsistent.
3. It calculates supplier, component, and sourcing analytics.
4. It classifies supplier decisions and component sourcing positions.
5. It provides an executive dashboard, deeper analytical views, scenario testing, and export-ready outputs.

## Running Locally

1. Install dependencies:

```powershell
python -m pip install -r requirements.txt
```

2. Run the app:

```powershell
python -m streamlit run app.py
```

3. Open the local Streamlit URL shown in the terminal, usually:

```text
http://localhost:8501
```

## Deployment

This project is designed to run well on Streamlit Community Cloud when connected to a GitHub repository.

Deployment basics:

1. Push the project to GitHub.
2. Go to [Streamlit Community Cloud](https://share.streamlit.io/).
3. Create a new app from the GitHub repo.
4. Set:
   - Branch: `main`
   - Main file path: `app.py`
5. Deploy.

## Sample Use Cases

- Procurement leader preparing for a supplier review with finance and operations
- Supply chain analyst prioritizing mitigation for single-source components
- Sourcing manager evaluating consolidation versus resilience tradeoffs
- Operations team reviewing which suppliers require monitoring versus exit planning
- Student or instructor using the dashboard to teach sourcing strategy, Pareto logic, and Kraljic analysis

## What Makes the Dashboard Different

- It handles messy procurement inputs instead of assuming perfect source data
- It connects analytics to decision logic rather than stopping at charts
- It supports both executive storytelling and analytical drill-down
- It combines supplier performance, supply risk, strategic sourcing, and scenario modeling in one workflow

## Screenshot Placeholders

Add screenshots here when publishing the project portfolio:

- `[Screenshot Placeholder] Executive Dashboard`
- `[Screenshot Placeholder] Component Risk View`
- `[Screenshot Placeholder] Supplier Decisions View`
- `[Screenshot Placeholder] Scenario Analysis`
- `[Screenshot Placeholder] Strategic Sourcing & Action Plan`

## Repository Structure

- `app.py` — main Streamlit application
- `requirements.txt` — Python dependencies
- `README.md` — project overview and business context

## Future Enhancements

- Save and compare named sourcing scenarios more formally
- Add audience-specific exports for executives, procurement, and supply chain managers
- Add presentation-mode storytelling across the major visuals
- Add confidence scoring for inferred input fields
- Add scenario sensitivity testing for supplier failure or lead-time shocks
- Add richer deployment diagnostics and environment health checks

## Portfolio Positioning

This project is best positioned as a supplier performance and strategic sourcing decision dashboard: a business analytics product that transforms messy procurement data into portfolio-level supplier insight, sourcing recommendations, and executive-ready communication.
