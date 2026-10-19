# Valuation models

Six company and deal valuations I built in Excel while studying for the Finance MBA at SKK GSB. Each workbook opens on a cover sheet that shows the live key outputs, the data date, the method notes and a review log of what changed before publication.

Every number is a live formula on a labelled input. If you change an assumption, the whole workbook updates.

| Folder | Subject | Methods | Data as of | Headline (base case) |
|---|---|---|---|---|
| [skhynix-intel-nand-ma](skhynix-intel-nand-ma) | SK hynix's US$9bn purchase of Intel's NAND business (Solidigm) | Accretion/dilution, scenario DCF, PPA, sources & uses, FX hedging, Monte Carlo, post-mortem | Signing Oct 2020; outcome to H1 2026 | +9.6% year-1 EPS; NPV +US$6.1bn base, −US$5.6bn downturn |
| [rubrik](rubrik) | Rubrik (NYSE: RBRK) | 10-year DCF with Base/Bull/Bear scenarios, EV / NTM revenue, reverse DCF | 24 Apr 2026 | DCF $21.75 vs. price $54.02 ($40.19 if SBC is added back) |
| [apple](apple) | Apple (NASDAQ: AAPL) | DCF with scenarios, perpetuity and exit-multiple terminal values, reverse DCF | 2 Oct 2026 | $151 / $234 per share vs. $333.69; price implies 7.3% perpetual growth |
| [amazon](amazon) | Amazon (NASDAQ: AMZN) | DCF, trading comparables, residual income, reverse DCF | 21 Aug 2026 | DCF $119, comps $207, RI $91 vs. $258.63 |
| [posco](posco) | POSCO Holdings (KRX: 005490) | Through-the-cycle DCF, sensitivity, reverse DCF | 8 Oct 2026 | ₩510,600 vs. ₩309,500; price implies ~0% growth |
| [us-kr-jp-portfolio-dcfs](us-kr-jp-portfolio-dcfs) | 18 US, Korean and Japanese stocks considered for a hedged portfolio | FCFF, FCFE, AFFO and a systematic earnings/FCF model on shared market inputs | 22–28 Sep 2026 | 14 of 18 clear a 15% upside hurdle |

## What the models have in common

- **A reverse DCF in every company model.** Rather than stop at "the DCF says X", each model asks what growth or margin today's price implies. For Apple, Amazon and Rubrik the price needs more than the base case. For POSCO it needs almost nothing: the market prices no margin recovery.
- **Stock-based compensation is a cost.** It is not added back to free cash flow. The Rubrik model shows the difference both ways.
- **Checks.** Each sensitivity table has a cell confirming that its centre equals the base case. The Rubrik model also reconciles FY2027 free cash flow to company guidance.
- **Dated inputs.** Every price, rate and balance-sheet figure is labelled with its date and source.

## Colour code

| | |
|---|---|
| Blue text | Hard-coded input |
| Black text | Formula |
| Green text | Link to another sheet |
| Yellow fill | Key assumption to flex |
| Green fill | Key output |

## Notes

- **Team work.** Rubrik was a team project, and I built the valuation. The version here is my rebuild using information public on the project date.
- **Excluded material.** Class-case models built on copyrighted case materials, and any workbook containing licensed Bloomberg or exchange data, are not published.
- **Figures to check.** Figures dated after mid-2026 come from public sources cited in each workbook. Check them against the filings before relying on them.

## Disclaimer

These are training and portfolio pieces built on public information. They are not investment advice or a recommendation to buy or sell any security.

Author: Jung Ryul Lee · Related: [krw-fx-monitor](https://github.com/jungrlee/krw-fx-monitor)
