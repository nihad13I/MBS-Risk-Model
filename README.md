# MBS Portfolio Risk & Optimal Liquidation Model
## Reconstruction of the "Margin Call" Systemic Risk Scenario

### Overview
This project provides a quantitative analysis of a Mortgage-Backed Securities (MBS) portfolio during a period of correlation failure. It simulates the technical threshold for firm insolvency and calculates the optimal liquidation strategy under extreme market impact, inspired by the financial scenarios depicted in the film *Margin Call*.

### Key Features
* **Tranche Valuation:** Modeling Senior, Mezzanine, and Equity tranches of an MBS portfolio.
* **Risk Metrics:** Calculation of **Value at Risk (VaR)** and **Tail Value at Risk (TVaR)** to identify "fat-tail" risks.
* **Correlation Failure:** A comparison between a "Standard Model" and a "Revised Model" showing how shifting correlations lead to Joint Default Frequency (JDF) spikes.
* **Optimal Liquidation:** Application of the **Almgren-Chriss Model** to calculate the permanent and temporary market impact of a fire sale.

### Technical Stack
* **Language:** Python
* **Libraries:** NumPy, SciPy (for Norm distribution), Matplotlib (for visualization), Pandas.

### Key Results
The model demonstrates the "Survival Ratio," showing that the cost of immediate liquidation, while high (approx. 1:30 ratio), is the only path to firm survival when the insolvency threshold is breached due to a 25% drop in asset value.
