# Data

This directory contains public or simulated data used for credit risk modelling.


# Climate-Adjusted Credit Risk Engine

An end-to-end credit risk modelling project exploring how traditional
borrower credit indicators and physical climate risk can be combined
to assess Probability of Default (PD), Loss Given Default (LGD),
Expected Credit Loss (ECL), and lending risk.

## Business Problem

Traditional credit models primarily evaluate borrower financial
performance and repayment capacity.

Physical climate risks can also affect borrower creditworthiness
through:

- Property damage
- Business interruption
- Revenue deterioration
- Lower collateral values
- Higher LTV
- Lower DSCR
- Increased probability of default

This project develops a Python-based credit risk modelling and
stress-testing framework to quantify these effects.

## Project Objectives

1. Develop a baseline Probability of Default model.
2. Analyse key borrower credit-risk drivers.
3. Apply physical climate stress scenarios.
4. Estimate stressed PD, LGD and ECL.
5. Compare baseline and stressed credit risk.
6. Develop a reproducible credit-risk analytics pipeline.

## Technology

Python
SQL
Pandas
NumPy
Scikit-learn
XGBoost
SHAP
Matplotlib
FastAPI
Docker

## Model Architecture

Borrower Financial Data
        ↓
Credit Risk Model
        ↓
Baseline PD
        ↓
Climate Stress Scenario
        ↓
Financial Impact
        ↓
Stressed PD / LGD
        ↓
Expected Credit Loss
        ↓
Credit Risk Decision
