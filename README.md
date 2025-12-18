***AI-Driven-Trade-Policy-Impact-and-Decision-Support-System***
The project addresses the critical challenge of Trade Policy Uncertainty (TPU) by developing a machine learning-based Decision Support System (DSS). It predicts the non-linear economic impacts of tariff shocks on US trading partners and provides actionable sourcing recommendations

**Project Overview**

This repository contains the source code and documentation for the MSc Business Data Analytics project: "AI-Driven Trade Policy Impact and Decision Support System."

The project addresses the critical challenge of Trade Policy Uncertainty (TPU) by developing a machine learning-based Decision Support System (DSS). It predicts the non-linear economic impacts of tariff shocks on US trading partners and provides actionable sourcing recommendations.

**Key Features**

Predictive Modeling: Utilizes a Random Forest Regressor to forecast GDP and Inflation impacts based on tariff scenarios and trade deficits.

Triple Risk Heuristic: Implements a business logic layer to identify "Critical Risk" zones (High Tariff + High Deficit).

Sensitivity Analysis: Calculates a GDP Sensitivity Factor to power "What-If" simulations.

Decision Support: Generates automated strategic insights (e.g., "Diversify Immediately," "Safe Haven Candidate").

**Repository Structure**

data/: Contains raw and processed datasets (Note: Large files may be excluded via .gitignore).

notebooks/: Jupyter Notebooks used for EDA and model prototyping.

src/: Python scripts for the full data pipeline (Cleaning, Modeling, Evaluation).

output/: Generated dashboard data files (FINAL_PROJECT_DASHBOARD_DATA.csv).

requirements.txt: List of Python dependencies.

