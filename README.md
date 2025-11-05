# Quant Portfolio with Walk-Forward Optimization & Sandbox Replay

This project implements a *multi-alpha quant portfolio system* with
Walk-Forward Optimization (WFO), sandbox deployment simulation,
and deterministic replay verification ("Replication Mandate").

---

##Overview

The framework builds and evaluates five alpha models:

1. *PairsAlpha* – mean-reversion pair trading  
2. *BreakoutAlpha* – breakout momentum  
3. *MTFMomentumAlpha* – multi-timeframe momentum  
4. *RotationAlpha* – sector/asset rotation  
5. *OrderbookAlpha* – simple microstructure-based model (mocked)

It includes:
- Event-driven backtester  
- Hyperparameter tuning with Optuna  
- Walk-Forward Optimization  
- Sandbox deployment simulator  
- Replay validation ensuring deterministic results  

---

##Project Structure

| Jupyter Notebook | Description |
|--------|--------------|
| data | Stored historical market data |
| Core codebase | alphas, backtester, WFO, and deployment scripts 
| output | Backtest results, equity curves, and JSON summaries |
| logs | Sandbox trade logs and replay verification files |
| Result | exploration and visualization |
