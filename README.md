# Multi-Asset Portfolio Analysis & Risk Modeling

This project performs a full quantitative analysis of 8–12 financial assets using 5+ years of monthly returns. It applies statistical, econometric, and risk-management methods to evaluate asset behavior, construct optimized portfolios, and assess downside risk under different modeling assumptions.

---

## 📌 Executive Summary
- Descriptive statistics for all assets (mean, SD, skewness, kurtosis, beta)
- Sharpe ratio comparison and annualized performance metrics
- Minimum Variance Portfolio (MVP) and tangency portfolio using Markowitz optimization
- Efficient frontier with and without short selling
- 6% target-return asset allocation (risky-only & risky + T-Bills)
- Normal and nonparametric VaR/ES estimation for individual assets and portfolios
- PCA, factor analysis, and interpretation of major risk drivers
- Copula modeling to analyze cross-asset dependency structures

---

## 📊 Data
- 5+ years of monthly returns for 8–12 financial assets  
- 3-month Treasury bill rate used as the risk-free asset  
- All data collected from public financial sources (Yahoo Finance, FRED, etc.)

---

## 🔍 Methods & Models

### **1. Descriptive Statistics**
- Mean & standard deviation  
- Skewness & kurtosis  
- Asset betas (relative to S&P 500)  
- Sharpe ratios  
- Outlier checks and distribution fitting  
- Stationarity tests  

### **2. Portfolio Theory**
- Minimum Variance Portfolio (MVP)  
- Efficient frontier (with/without short sales)  
- Tangency portfolio and market price of risk  
- Portfolio allocation tables with annualized return & risk  
- 5% monthly VaR for a $100,000 investment  

### **3. Asset Allocation**
- Target return: **6% per year (~0.5% per month)**  
- Risky-asset-only efficient portfolio  
- Risk-free + tangency portfolio allocation  
- VaR/ES comparison across strategies  

### **4. PCA & Factor Analysis**
- Correlation matrix inspection  
- Identification of most/least correlated assets  
- Principal components and factor interpretation  
- Factor loadings and contribution to variance  

### **5. Risk Management**
- Asset-level VaR & ES (Normal and nonparametric)  
- Portfolio-level VaR & ES  
- Bootstrapped standard errors & 95% confidence intervals  

### **6. Copula Modeling**
- Fit Gaussian, t-copula, Clayton, Gumbel, etc.  
- Select best-fit copula based on log-likelihood & diagnostics  
- Discuss tail-dependence implications for diversification  

---

## 📈 Figures & Tables
- Equity curves for all assets (growth of \$1 vs. S&P 500)  
- Efficient frontier plots  
- Portfolio weight tables  
- VaR/ES comparison charts  
- PCA loading diagrams  
- Copula dependency plots  

---

## 📌 Purpose
This project demonstrates the use of **financial statistics, portfolio theory, and risk modeling** to construct and evaluate diversified portfolios. It integrates classical econometrics with modern risk-management tools and provides a full quantitative workflow from data collection to interpretation.

---

## 📘 Author
Henry Su (2025)
