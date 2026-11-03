# NQ Event Volatility · NQ 事件波动图解

How Nasdaq-100 futures (NQ) react to US macro releases and FOMC events, 2010–2026.
纳斯达克 100 期货（NQ）在美国宏观数据和 FOMC 公布前后的波动与敏感度，2010–2026。

**Live page:** open `index.html` (served with GitHub Pages).

## What it answers

1. **How big is the shock?** Realized volatility after each release vs. the median of the previous 20 news-free trading days at the same clock time.
2. **How fast does it fade?** Minute-by-minute volatility ratio from −30 to +120 minutes.
3. **How sensitive is NQ to the surprise?** Regressions of NQ returns on standardized surprises (actual − consensus, scaled by the typical surprise); FOMC surprises from 2-year Treasury futures.
4. **How has it changed?** Rolling 3-year sensitivities: "good news is good news" in the 2010s became "good news is bad news" after 2022.

## Data and method

- NQ 1-minute bars: Databento (CME Globex), highest-volume contract per day, Jun 2010 – Oct 2026.
- Release times, actuals and forecasts: Forex Factory; actuals checked against ALFRED first releases.
- 2,855 releases across 17 event types.
- Inference: HC3 standard errors, 2,000 bootstrap resamples, Benjamini–Hochberg correction across 258 tests.

The page shows aggregated statistics only. No raw exchange prices are published here.

Statistical results only; not investment advice.
