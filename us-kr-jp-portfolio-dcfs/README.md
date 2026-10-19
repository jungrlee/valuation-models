# Hedged US–Korea–Japan portfolio: DCF valuations

**File:** `Portfolio_DCF_Valuations.xlsx`. Prices from 22–28 Sep 2026.

These are the valuation workings behind a hedged multi-asset portfolio of US, Korean and Japanese stocks. Every stock that can sensibly be valued on cash flows is valued here. All models draw on one shared Assumptions sheet: risk-free rate, equity risk premium and terminal growth for each market.

| Group | Stocks | Model |
|---|---|---|
| US large caps | UNH, ADBE, CRM, MSFT, GOOGL, JNJ | 10-year FCFF DCF (revenue × fading FCF margin, WACC) |
| US income | T, VZ, CMCSA, PYPL, CI, VICI | FCFE perpetuity, two-stage FCFE or AFFO, at the cost of equity |
| Korea / Japan | KT, LG Uplus, Krafton, Hankook Tire, Coway, Astellas | Systematic 10-year model: discounted earnings (payout = 1 − g/ROE) blended 50/50 with discounted FCF, with limits on beta, growth and ROE |

14 of the 18 stocks clear the 15% upside hurdle used in portfolio selection.

![Summary](docs/summary.png)

## Notes

- **The systematic model is a screening tool.** It runs on consensus and statistics from data feeds. Large upsides for Korean names mostly reflect low P/E multiples, not company-specific forecasts.
- **Financials are not here.** Banks and insurers in the portfolio were valued with justified P/B in the memo. The memo is not included.
- **Weights are typed in.** Portfolio weights come from the optimiser and do not move when valuations change.
- **Changes before publication.** The audit found no formula errors, and the logic is unchanged. I restyled the workbook and added a cover sheet.

![KT](docs/kt.png)

Not investment advice.
