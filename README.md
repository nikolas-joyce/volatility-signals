# volatility-signals

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nikolas-joyce/volatility-signals/blob/main/notebooks/alpha_volatility_breakout.ipynb)

> Volatility breakout + VIX spike filter — alpha signal with ATR adaptive threshold

> Combines two complementary signals. The **volatility breakout** enters long when price exceeds a rolling mean by an adaptive ATR multiple — confirming momentum in expanding markets. The **VIX spike filter** suppresses entries (and closes positions) when VIX crosses above its 5-year 98th-percentile rolling threshold, exiting during regime-level fear events. Together they ride trending, low-volatility environments while stepping aside during market dislocations.

## Notebook structure
| Section | Description |
|---------|-------------|
| 0 | Install & imports |
| 1 | Config & data |
| 2 | Signal functions |
| 3 | Signal generation |
| 4 | Returns & performance |
| 5 | Per-ticker breakdown |
| 6 | Parameter sensitivity |
| 7 | Export signals for swarm |

**Run all cells top-to-bottom in a fresh Colab runtime.**

