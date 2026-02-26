Decision-Centric Customer Lifetime Value Optimization
Overview

This project reframes Customer Lifetime Value (CLV) as a decision-centric optimization problem under uncertainty, rather than a static prediction task.

The system integrates:

Time-causal customer state construction

Latent churn modeling via discrete-time survival analysis

Expected discounted lifetime value computation

Budget-constrained decision optimization

Counterfactual uplift modeling

Sensitivity and failure-mode analysis

The objective is to optimize business decisions, not prediction accuracy.

Dataset

Online Retail II (UCI Machine Learning Repository)

~1.06 million transactions

Non-contractual retail setting

Methodology
1. Transaction Timeline Construction

Research-grade data cleaning and temporal ordering.

2. Customer State Representation

RFM + temporal signals computed without leakage.

3. Latent Churn Modeling

Discrete-time survival analysis with person-period expansion.

4. Expected CLV Estimation

Discounted expected value under survival uncertainty.

5. Decision Optimization

Budget- and risk-aware targeting strategy.

6. Counterfactual Policy Evaluation

Uplift-based comparison of targeting strategies.

7. Sensitivity & Failure Analysis

Stress-testing assumptions and robustness validation.

Key Insight

CLV should be treated as a decision variable, not a predictive score.
