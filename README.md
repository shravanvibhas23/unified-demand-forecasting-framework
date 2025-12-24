# unified-demand-forecasting-framework
Unified framework for evaluating time-series demand forecasting models across stable, fast, and intermittent patterns using statistical, ML, and AutoML approaches with rolling validation and MASE.


Unified Evaluation Framework for Demand Forecasting

This project implements a unified evaluation framework for time-series demand forecasting, designed to compare statistical, machine learning, and AutoML models across different demand patterns using realistic validation.

The framework was developed as part of a conference research study and focuses on practical, real-world forecasting scenarios.

🔍 Problem Overview

In domains like supply chain, retail, and financial services, demand patterns vary significantly:

Stable demand

Fast-moving demand

Slow or intermittent demand

A single forecasting model does not perform best across all scenarios.
This project answers:

Which forecasting model works best for which demand pattern?

🧠 Key Features

Demand classification using ADI & CV²

Rolling-origin (walk-forward) evaluation

Fair comparison of Statistical, ML, and AutoML models

Robust accuracy measurement using MASE

Automatic best-model selection per demand category

⚙️ Models Implemented
Statistical Models

ETS (Holt-Winters)

ARIMA

SARIMA

Croston

SBA

Machine Learning

XGBoost

AutoML

AutoGluon

MLJAR

TPOT

📊 Final Results
Overall Model Ranking
Rank	Model	Accuracy
1	ARIMA	75.9%
2	AutoGluon	75.6%
3	MLJAR	75.0%
4	XGBoost	74.8%
5	Croston	73.9%
Best Model by Demand Type
Demand Type	Best Model	Accuracy
Fast	ARIMA	79.7%
Stable	AutoGluon	75.8%
Slow	ARIMA	74.4%

Peak Accuracy: 75.9%

🛠 Tech Stack

Python

NumPy, Pandas

Statsmodels

Scikit-learn

XGBoost

AutoGluon, TPOT, MLJAR

Matplotlib, Seaborn

🚀 How to Run
pip install -r requirements.txt
python forecasting_framework.py

📌 Use Cases

Demand forecasting & benchmarking

Supply chain analytics

Financial time-series modeling

Intermittent demand analysis

Model selection and evaluation

📄 Research Context

This framework was created and validated as part of a national conference presentation, combining academic rigor with industry-focused forecasting practices.
