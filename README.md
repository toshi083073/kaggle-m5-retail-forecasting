# kaggle-m5-retail-forecasting
End-to-End Retail / E-commerce Analytics &amp; Forecasting Project (Python / SQL / DuckDB / Looker Studio)
🚀 What This Project Demonstrates

1. Time-Series Forecasting (M5 based)
　EDA: hierarchical retail structure (state → store → item)
　Feature engineering: lag, rolling window, event impact
　ML models: LightGBM-based forecasting
　Comparison of predictions vs baseline

2. SQL & Analytics Engineering
  Data modelling with SQL / DuckDB
  Window functions (LAG / rolling)
  Daily → weekly → monthly aggregates
  Demand mart / feature mart for ML pipelines

3. Dashboarding (Looker Studio)
  Daily/weekly demand trend visualization
  Region/store-level heatmaps
  Event impact analysis (holidays, promotions)
  Forecast vs actual gap analysis

4. Dev Environment & Version Control
  VS Code + GitHub
  Python virtual env
  Project modularization under src/
  Documented notebooks under notebooks/


````markdown
## 📂 Project Structure

```
kaggle-m5-retail-forecasting/
│
├── data/                # Raw M5 data (ignored by Git)
│
├── notebooks/
│   ├── 01_eda_m5_basics.ipynb
│   ├── 02_feature_engineering.ipynb
│   └── 03_model_lightgbm.ipynb
│
├── src/
│   ├── data_loader.py
│   ├── feature_engineering.py
│   └── model.py
│
├── bi/
│   ├── looker_dashboard_design.md
│   └── example_screenshots/
│
├── sql/
│   ├── create_tables.sql
│   ├── marts_demand.sql
│   └── feature_mart.sql
│
├── reports/
│   └── eda_summary.md
│
├── requirements.txt
├── .gitignore
└── README.md
```

🧪 Technology Stack
  Python (pandas, numpy, matplotlib, lightgbm)
  SQL (DuckDB, BigQuery syntax compatible)
  Looker Studio
  VS Code + GitHub
  (Optional) dbt for analytics engineering

🎯 Purpose of This Project
  To demonstrate retail demand forecasting skills that apply directly to:
  E-commerce
  Logistics / S&OP
  Inventory planning
  BI / Dashboarding roles
  Data analytics & SQL roles

