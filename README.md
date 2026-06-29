# Credit_Default_Swap_Pricer
A Python implementation of a CDS pricing engine built in Jupyter Notebook.

## What it does
- Prices coupon bonds using discounted cash flows
- Builds survival probability curves from market spreads via the credit triangle
- Computes both legs of a CDS: the premium leg and the protection leg
- Calculates the par spread and marks existing positions to market
- Computes CS01 (credit DV01) using bump and reprice
- Runs spread shock scenario analysis across a range of market moves

## Key concepts demonstrated
- Time value of money
- Hazard rates and the credit triangle
- Risky annuity (RPV01)
- CDS valuation from first principles
- Credit sensitivities and scenario analysis

## Built with
- Python
- NumPy
- Matplotlib
- Jupyter Notebook via Anaconda

## Background
Built as a learning project during MSc Business and Finance at Warwick Business School 
to develop hands-on understanding of credit derivatives pricing.
