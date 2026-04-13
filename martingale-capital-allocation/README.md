## Capital Allocation and Long-Term Risk-Adjusted Returns

### Overview

This project explores how different capital allocation rules affect long-term risk-adjusted performance, with a focus on strategies that resemble martingale-style scaling.

The goal was to understand whether increasing exposure after losses can improve long-term returns, and how this approach behaves once risk is measured properly.

### What I did

- simulated a base trading strategy with fixed position sizing  
- introduced a capital allocation rule that increases exposure after losses  
- tracked performance over long horizons  
- evaluated results using risk-adjusted metrics such as Sharpe ratio and drawdown  

### What makes this unique

Most discussions around martingale strategies focus on short-term outcomes or theoretical probability arguments.

This project looks at the problem from a long-term perspective, focusing on risk-adjusted performance rather than raw returns.

It also treats capital allocation itself as the main variable, rather than the underlying trading signal.

### What turned out interesting

While returns can increase under certain conditions, the distribution of outcomes becomes much more skewed.

Drawdowns grow faster than expected, and risk-adjusted metrics often deteriorate even when average returns improve.

### Why it matters

Position sizing and capital allocation are often more important than the strategy itself.

Understanding how these rules behave over time is critical for building systems that are both profitable and sustainable.
