# Algorithmic-Portfolio-Allocation

Portfolio Optimization: Theory to Python
🎯 The "Why"
In my Business Administration (HA) finance courses, I studied Modern Portfolio Theory (MPT) and the Efficient Frontier. To bridge the gap between academic theory and Data Science, I built this tool to test if a systematic, code-driven approach could outperform a standard market benchmark.

🚀 The Project
I used Python to find the optimal weights for a portfolio of five stocks (NVO, NVDA, JPM, KO, TSLA) by maximizing the Sharpe Ratio (risk-adjusted return).

Tech Stack
Data: yfinance API.

Optimization: Monte Carlo Simulation (10,000 runs) & SciPy (SLSQP optimization).

Validation: Backtested against the S&P 500 (SPY).

📈 Key Results
Optimized Portfolio: +244.43% return.

S&P 500 Benchmark: ~+100% return.

Insight: The model correctly prioritized "Quality Growth" (Nvidia/Novo) and "Stability" (JPMorgan), while minimizing high-volatility assets (Tesla) that didn't offer enough return for their risk.

🧪 Conclusion
The project successfully validates MPT in a modern context. The fact that the theoretical optimization line (Efficient Frontier) perfectly "envelopes" the random simulations proves the mathematical integrity of the model.
