# Cash Flow Forecasting for Small Businesses
**Stage:** Problem Framing & Scoping (Stage 01)

## Problem Statement
Many small businesses struggle with forecasting monthly cash flow because their current tools (spreadsheets or manual bookkeeping) lack predictive capabilities. As a result, they often face liquidity shortfalls or over-allocate funds, which can threaten their operations.

## Stakeholder & User
- Primary stakeholder: small business owners
- Secondary stakeholders: accountants and financial advisors
- Context: decisions about payroll, supplier orders, and short-term expenses

## Useful Answer & Decision
- **Type:** Predictive  
- **Artifact:** Forecasting model & dashboard  
- **Decision Supported:** anticipate 30-day cash flow risk and adjust spending

## Assumptions & Constraints
- Data availability: historical monthly transaction data exists
- Latency: forecasts needed within seconds for usability
- Compliance: must follow financial data privacy standards

## Known Unknowns / Risks
- Data quality: inconsistent or missing transaction records
- User adoption: whether owners trust automated forecasts
- Economic volatility: unexpected shocks may reduce accuracy

## Lifecycle Mapping
Goal → Stage → Deliverable
- Define problem scope → Problem Framing (Stage 01) → Scoping paragraph + repo setup  
- Build baseline model → Modeling (Stage 02) → Initial predictive artifact  
- Deploy & test → Deployment (Stage 03) → Interactive dashboard for stakeholder feedback  

## Repo Plan
- `/data/` → sample and cleaned datasets  
- `/src/` → model and pipeline code  
- `/notebooks/` → exploratory analysis + experiments  
- `/docs/` → stakeholder memos, framing slides  
Updates: weekly commits and progress tracking
