# Prompt Chains for Quant Tasks

This module explores how LLMs can be used in prompt chains to support quant workflows.  
Each chain demonstrates a small but concrete task that would normally take manual effort.

## Submodules

### 1. Portfolio Insights
- Generate summaries of portfolio performance.
- Identify risks, drawdowns, Sharpe ratio trends.
- Explain results in plain English.

### 2. Strategy Review
- Input: backtest logs / trade history.
- Output: Markdown summary with key metrics.
- Highlight anomalies, e.g., sudden DD, skewed win/loss.

### 3. Trade / Signal Explanation
- Take a trade log or entry signal.
- Explain why it happened in terms of market structure / quant factors.
- Provide a chart annotation plan.

---

## Next Steps
- Add small input data samples (JSON, CSV).
- Write first LLM prompts that take the input → structured insight.
- Track differences in manual vs. LLM workflow time.

