# Early-Warning Indicators for Market Crashes: A Comparative Study of 1929 and 2008

**Working Paper (Draft in Progress)**

This repository contains code, data processing pipelines, and preliminary analyses for the working paper *“Early-Warning Indicators for Market Crashes: A Comparative Study of 1929 and 2008.”*  
The project investigates whether major market dislocations exhibit identifiable statistical warning signs in the months leading up to the 1929 Wall Street Crash and the 2008 Global Financial Crisis.

---

## Research Aim
To determine whether simple, historically grounded metrics—volatility behaviour, drawdown structure, and distributional shifts—provide meaningful early-warning signals preceding major market crashes.

---

## Core Questions
- **Volatility Dynamics:** Do abnormal volatility regimes emerge systematically before the 1929 and 2008 crashes?  
- **Structural Similarity:** Are the pre-crash periods statistically comparable across the two events?  
- **Predictive Utility:** Can basic historical indicators serve as practical early-warning mechanisms for extreme market events?  

---

## Methodology Overview
The analysis focuses on daily index-level data:

- **1929:** DJIA (Shiller dataset; daily where available)  
- **2008:** S&P 500 or DJIA (Yahoo Finance / FRED)  

**Key methodological components include:**
- Log-return computation and index normalisation  
- Rolling volatility estimation (20-day, 50-day)  
- Rolling maximum drawdowns  
- Distributional comparison of pre-crash vs baseline periods  
- Volatility-surge thresholding (e.g., >2σ above historical mean)  
- Optional: volume-based indicators (2008 only)  
- Statistical testing (t-test, Mann–Whitney U, Kolmogorov–Smirnov)  

---

## Outputs
The repository will include:
- Cleaned datasets used for both crash periods  
- Python scripts for indicator computation and statistical testing  
- Reproducible visualisations (normalised index overlays, volatility curves, drawdown profiles)  
- Draft figures intended for inclusion in the final paper  
- Notes and preliminary interpretations  

---

## Current Status
The paper is under active development.  
Analyses and figures will be updated iteratively as the statistical tests and comparative models are refined.
