# Barron's Close Follow Portfolio (Mock / Paper Only)

Interactive Chart.js dashboard for Jim's mock Barron's Investor Circle close-follow portfolio.

**Not real trades.** Paper ledger only.

## As of 2026-11-05 (America/Los_Angeles)

| Metric | Value |
|--------|-------|
| Total value | **$590,907.82** |
| Contributed | $600,000.00 |
| Total gain/loss | **-$9,092.18 (-1.52%)** |
| Best | EQX +9.30% |
| Worst | UCTT -19.65% |

### Positions

| Ticker | Shares | Entry | Latest close | Value | Gain % |
|--------|-------:|------:|-------------:|------:|-------:|
| VEOEY | 5,558 | $17.99 (Oct 20 close) | $19.04 | $105,835.91 | +5.84% |
| EL | 964 | $103.66 (Oct 21 close) | $109.03 | $105,176.68 | +5.18% |
| IBEX | 2,176 | $45.94 (Oct 27 close) | $43.31 | $94,277.12 | -5.72% |
| EQX | 9,842 | $10.16 (Oct 29 open) | $11.11 | $109,300.69 | +9.30% |
| UCTT | 2,093 | $47.76 (Nov 4 open) | $38.37 | $80,346.73 | -19.65% |
| RMD | 407 | $245.29 (Nov 5 open) | $235.39 | $95,970.70 | -4.03% |

RMD shares = `floor(100000 / Nov 5 open)`; leftover cash $166.97.

### VEOEY targets

- Close $19.04
- To $29 target: 9.96 (52.3% upside)
- To $21 target: 1.96 (10.3% upside)
- Above $17 support: +2.04 (12.0%)

## View

Open `index.html` (self-contained; Chart.js via CDN). Prices from Yahoo Finance daily bars.

## Disclaimer

Mock / paper portfolio for tracking Barron's picks. No brokerage orders were placed.
