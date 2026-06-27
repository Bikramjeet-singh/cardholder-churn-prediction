# Cardholder Churn Prediction

End-to-end ML project predicting credit-card customer churn — EDA, modeling, calibration, and a deployed scoring API with drift monitoring.



Predicts which credit-card customers are likely to churn, estimates the
revenue at risk, and serves scores via an API for retention workflows.

## Data
Real spine: Kaggle "Credit Card customers" (sakshigoyal7) — ~10k customers,
~18 features, ~16% churn. Synthetic transaction layer added on top
(label-blind, conditioned on real account features).

Note: data is not committed. Download via:
`kaggle datasets download -d sakshigoyal7/credit-card-customers --unzip -p data/`

## Structure
- `notebooks/` — EDA and modeling
- `src/` — reusable pipeline code
- `data/` — raw data (gitignored)

## Status
In progress: EDA + feature engineering.
