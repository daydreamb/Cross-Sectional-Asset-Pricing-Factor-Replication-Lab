# Cross-Sectional Asset Pricing Lab

A modular research framework for empirical asset pricing, factor replication, and cross-sectional inference.

---

## Objective

Build and evaluate equity risk factors using:

- Portfolio sorting  
- Fama-MacBeth regression  
- Robust statistical inference  
- Backtest diagnostics  
- Dynamic factor timing  

Designed to mirror institutional quantitative research workflows.

---

## Core Modules

### 1. Factor Construction

- Cross-sectional ranking and standardization  
- Decile portfolio formation  
- Long-short factor returns  
- Implementations: Value, Momentum, Quality  

**Outputs**
- Mean excess return  
- Volatility  
- Information ratio  
- Factor correlation matrix  

---

### 2. Cross-Sectional Pricing Tests

Implemented:

- Time-series beta estimation  
- Fama-MacBeth regressions  
- Newey-West adjusted t-statistics  
- Clustered standard errors  

Evaluated:

- Statistical significance of risk premia  
- Cross-sectional R²  
- Economic magnitude of compensation  

---

### 3. Backtest Robustness

Diagnostics include:

- Rolling window stability  
- Subsample consistency  
- Out-of-sample validation  
- Multiple testing awareness  

Focus: mitigating data mining bias and overfitting risk.

---

### 4. Factor Timing Extension

- Rolling predictive regressions  
- Time-varying expected returns  
- Dynamic allocation comparison  
- Utility-based performance evaluation  

Assesses whether conditional exposure improves risk-adjusted returns.

---

## Repository Structure
/data
/factors
/regression
/diagnostics
/timing
/utils


Modular design enables reuse across asset classes and signal sets.

---

## Methods

### Statistical Tools

- Ordinary Least Squares estimation  
- Hypothesis testing  
- Robust inference  
- Rolling estimation  

### Asset Pricing Framework

- Cross-sectional beta pricing  
- Long-short portfolio construction  
- Conditional expected return modeling  

---

## Research Questions

- Are canonical factors statistically priced?  
- How stable are factor premia over time?  
- Does conditional modeling improve economic value?  
- How sensitive are results to sampling and estimation error?  

---

## Extensions

Potential future extensions:

- Bayesian shrinkage  
- Machine learning cross-sectional models  
- Multi-asset factor integration  
