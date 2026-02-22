# Multi-Asset Ensemble Predictive Framework

## Project Overview
This project develops a Python-based ensemble learning system designed to predict directional price movements for a multi-asset equity basket (AAPL, GE, PSCT). Beyond simple prediction, the framework implements institutional-grade risk management techniques, including volatility-adjusted position sizing and comprehensive performance attribution.

## Key Transferable Skills
* **Automated Data Pipelines:** Developed a robust ingestion engine using `yfinance` to handle live market data, feature engineering, and data cleaning for multiple ticker symbols simultaneously.
* **Risk Architecture:** Implemented a **1.5x Volatility Scaling** mechanism to dynamically adjust leverage based on market regime—a core requirement for modern risk-parity and quantitative strategies.
* **Performance Attribution:** Built a metrics suite to calculate industry-standard KPIs, moving beyond "raw returns" to analyze **Sharpe Ratio**, **Maximum Drawdown (MDD)**, and **Alpha**.
* **Ensemble Methodology:** Leveraged multiple machine learning models (Random Forest, Gradient Boosting, etc.) to create a diversified predictive signal, reducing the variance associated with single-model approaches.

## Technical Stack
* **Language:** Python 3.x
* **Data Analysis:** `pandas`, `numpy`
* **Machine Learning:** `scikit-learn`
* **Data Ingestion:** `yfinance`
* **Visualization:** `matplotlib`

## Performance Results
The model was validated against a benchmark equity curve to ensure statistical robustness. Key results include:
* **Directional Accuracy:** 52.87% (A statistically relevant and realistic figure for high-frequency financial time series).
* **Max Drawdown (MDD):** Monitored to ensure strategy survival during high-volatility regimes.
* **Sharpe Ratio:** Calculated to measure the efficiency of the alpha generated relative to the risk taken.

## Development Workflow
This project utilizes an AI-assisted development workflow. My focus was on the **architectural logic**—selecting risk parameters, determining feature importance, and validating statistical significance—while utilizing AI tools for syntax optimization and boilerplate debugging. This approach mirrors the modern professional "Pair Programming" environment used in top-tier financial institutions.
