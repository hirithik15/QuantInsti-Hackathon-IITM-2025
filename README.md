# QuantInsti-Hackathon-IITM-2025

## Next-Week Equity Return Prediction & Systematic Top-2 Strategy  
### QuantInsti Hackathon (IIT Madras) — Ranked 3rd

This project builds a walk-forward machine learning pipeline to predict next-week positive returns for equities and executes a systematic long-only strategy with transaction costs.

---

## Problem Statement
- Train a **Voting Classifier** to predict probability of positive next-week returns.  
- Each week, **go long the top 2 ranked stocks**, equal-weighted.  
- Apply **10 bps per-side** transaction cost.  
- Use a **rolling 4-year training window**, retraining only at year-end.  
- Compute full portfolio analytics before/after costs.

A detailed discussion of methodology, assumptions, and results is provided in  
`Results/QuantInsti_Hackathon_My_Approach.pdf`.

---
