# Equity Factor Analysis & Multi-Factor Portfolio Modeling (FI)

This repository contains two financial research projects focused on equity factor modeling, portfolio construction, and performance attribution using classical asset pricing models.

The projects apply **CAPM, Fama-French (3-Factor), and Carhart (4-Factor)** frameworks to both individual equities and optimized portfolios.

---

## Project 1: Factor Analysis of JPMorgan (CAPM & Fama-French)

This project analyzes the factor exposures of **JPMorgan Chase (JPM)** using:

- Capital Asset Pricing Model (CAPM)
- Fama-French 3-Factor Model

### Key Objectives:
- Estimate market beta
- Measure size (SMB) and value (HML) exposures
- Evaluate statistical significance of factor loadings
- Compare explanatory power across models (R²)

### Insights:
- Market exposure is the primary driver of returns
- Factor sensitivities help explain excess return behavior
- Multi-factor models improve explanatory power vs CAPM alone

---

## Project 2: Multi-Factor Analysis of an Optimized Portfolio (CAPM, FF3, Carhart)

This project extends the analysis to an **optimized equity portfolio**, incorporating:

- CAPM
- Fama-French 3-Factor Model
- Carhart 4-Factor Model (Momentum)

### Key Objectives:
- Construct an optimized portfolio (Max Sharpe)
- Evaluate factor exposures at the portfolio level
- Measure momentum (MOM) contribution
- Compare model fit across CAPM, FF3, and Carhart

### Insights:
- Market factor remains dominant
- Size and value exposures vary based on portfolio construction
- Momentum impact is not statistically significant
- Multi-factor models provide deeper performance attribution

---

## Tools & Libraries

- Python
- pandas
- statsmodels (OLS regression)
- yfinance
- PyPortfolioOpt
- matplotlib
- pandas_datareader (Fama-French data)

---

## Skills Demonstrated

- Factor modeling & regression analysis
- Portfolio optimization
- Risk-adjusted performance evaluation
- Statistical interpretation of asset pricing models
- Financial data processing and visualization

---

## Purpose

These projects demonstrate practical implementation of classical asset pricing theory applied to real market data, bridging financial economics and quantitative portfolio management.
