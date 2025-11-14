# option-trading
This repo tracks my 6-month roadmap to develop Python skills in options trading.

## Projects
1. Python fundamentals for data science
2. Market data ingestion & storage
3. Black-Scholes & Greeks
4. Implied Volatility solver & surface plotting
5. Monte Carlo pricing & Greeks
6. Finite-difference PDE solver
7. Volatility surface modeling & calibration
8. Delta-hedged straddle backtest
9. Risk analytics: Greeks aggregation & VaR
10. Execution simulator & slippage modeling
11. Performance engineering & production practices
12. Dashboard & portfolio demo
13. Statistical factor modeling for volatility
14. ML-based signal generation for vol forecasts

## Quickstart (local)
```bash
python -m venv .venv
source .venv/bin/activate     # mac/linux
pip install -r requirements.txt
python -m ipykernel install --user --name=venv --display-name "Python (.venv)"    # set up jupyterlab to link with venv
