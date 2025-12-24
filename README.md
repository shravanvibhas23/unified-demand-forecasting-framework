# unified-demand-forecasting-framework
Unified framework for evaluating time-series demand forecasting models across stable, fast, and intermittent patterns using statistical, ML, and AutoML approaches with rolling validation and MASE.


Unified Demand Forecasting Evaluation Framework

A conference-validated, production-oriented time-series forecasting framework that benchmarks statistical, machine learning, and AutoML models across stable, fast, and intermittent demand patterns using realistic evaluation.

📌 Built with real-world forecasting constraints in mind
📌 Focused on model selection, not just model accuracy

🎯 Why This Project Matters (Recruiter View)

In real business scenarios, no single forecasting model works best for all demand types.
This project demonstrates:

Strong time-series fundamentals

Practical model evaluation & benchmarking

Ability to combine research + engineering

Decision-driven forecasting, not trial-and-error modeling

🔍 What This Framework Does

Classifies demand using ADI & CV²

Applies rolling-origin (walk-forward) validation

Evaluates Statistical, ML, and AutoML models

Uses MASE for scale-independent accuracy

Automatically selects the best model per demand category

⚙️ Models Benchmarked

Statistical:
ETS, ARIMA, SARIMA, Croston, SBA

Machine Learning:
XGBoost

AutoML:
AutoGluon, MLJAR, TPOT

📊 Results Snapshot
Overall Ranking
Model	Accuracy
ARIMA	75.9%
AutoGluon	75.6%
MLJAR	75.0%
Best Model by Demand Type
Demand	Best Model	Accuracy
Fast	ARIMA	79.7%
Stable	AutoGluon	75.8%
Intermittent	ARIMA	74.4%

📈 Key Insight:

Model choice should be driven by demand behavior, not model complexity.

🛠 Tech Stack

Python, NumPy, Pandas

Statsmodels, Scikit-learn

XGBoost

AutoGluon, TPOT, MLJAR

🚀 How to Run
pip install -r requirements.txt
python forecasting_framework.py



Senior Python Developer (Analytics)

Financial & Supply Chain Analytics Roles
