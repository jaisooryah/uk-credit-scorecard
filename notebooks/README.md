# UK Credit Scorecard

End-to-end probability-of-default model on the Lending Club dataset, framed for UK retail banking (Lloyds, Barclays, NatWest, Halifax).

## Progress

- [x] Day 1 — Data load, target definition, leakage removal, downsampling
- [x] Day 2 — Feature engineering with Weight of Evidence & Information Value
- [ ] Day 3 — Logistic regression scorecard baseline
- [ ] Day 4 — XGBoost challenger model
- [ ] Day 5 — SHAP explainability & fairness check
- [ ] Day 6 — Streamlit dashboard
- [ ] Day 7 — Write-up & launch

## Stack

Python (pandas, scikit-learn, XGBoost, SHAP), Jupyter, Streamlit, Git.

## Dataset

Lending Club Loan Data (2007-2018), ~200k loans downsampled with 80/20 paid-vs-defaulted class balance. Data is not committed to this repo — download from [Kaggle](https://www.kaggle.com/datasets/wordsforthewise/lending-club) and place `accepted_2007_to_2018Q4.csv.gz` in `data/`.

## Structure

- `notebooks/` — Analysis notebooks, one per day
- `docs/` — Feature dictionary, model selection notes, deployment plan
- `data/` — Local data files (gitignored)

## Reproducing

```bash
conda create -n credit-scorecard python=3.11 -y
conda activate credit-scorecard
pip install -r requirements.txt
```