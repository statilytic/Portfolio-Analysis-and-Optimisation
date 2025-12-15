# Portfolio Analysis and Optimisation 

The aim of this project is to analyse, evaluate and optimise three portfolios, each consisting of five randomly selected financial assets, using key performance and risk measures such as annual return, volatility, VaR, CVaR and the Sharpe ratio. The project further applies portfolio optimisation techniques to identify optimal asset allocations that maximise risk-adjusted returns under standard investment constraints.

###Technologies used
Python and Jupyter Notebook
 
## Portfolio Construction
Returns are calculated using historical data which was imported from Yahoo Finance. The historical data is set at a period of 5 years and each portfolio is equally weighted. 

The assets for each portfolio are as follows:

#### Portfolio 1:
 ##### - NVIDIA, Ford, Plug Power, SoundHound, Nu Holdings

#### Portfolio 2:
 ##### - Netflix, QuantumScape, Baytex Energy Corp, Bath and Body Works, CleanSpark Inc

#### Portfolio 3:
 ##### - Amazon, Apple, Pfizer, Hecla Mining Company, New Gold Inc

## Portfolio Analysis
### Risk Measurements
 1) Value at Risk (VaR) using Variance-Covariance Method
 2) Value at Risk (VaR) using Monte Carlo Simulation
 3) Expected Shortfall (CVaR)
 4) Sharpe Ratio
 5) 

Log returns were used to calculate VaR and ES while simple returns were used to calculate the Sharpe Ratio.

### Key Findings

 - Portfolio 1 is most attractive for risk-seeking investors, offering the highest annual return and strongest risk-adjusted performance.

 - Portfolio 2 provides the weakest risk-adjusted returns, as indicated by its lowest Sharpe ratio.

 - Portfolio 3 is best suited for risk-averse investors, exhibiting the lowest volatility and lowest VaR, despite higher exposure to extreme tail risk.


## Portfolio Optimisation
Portfolio optimisation is performed using Sharpe ratio maximisation, subject to standard constraints: asset weights sum to one and are bounded between 0 and 1. 

### Results : 
There is a substantial increase in the Sharpe ratio when optimal weights are applied, with annual returns more than doubling compared to the equal-weighted portfolios. 

Annual returns for Portfolios 2 and 3 increase more conservatively relative to Portfolio 1. Changes in annual volatility are modest, volatility increases by approximately 1% for Portfolio 1, rises by about 2% for Portfolio 2 and decreases by roughly 3% for Portfolio 3. Overall, the application of optimal portfolio weights significantly enhances risk-adjusted performance compared to equal weighting


### Project Report

A detailed report explaining the analysis and results is available in the following document: Portfolio Analysis and Optimisation.pdf

