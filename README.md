# ODS Investors Dashboard

A standalone investment analysis dashboard built for a 2–3 month trading horizon. No backend, no framework, no build step — just one HTML file you can host anywhere.

---

## Live Demo

> **(https://buynowllc.github.io/Stocks_Tool/)**  
> *(https://buynowllc.github.io/Stocks_Tool/)*

---

## What's Inside

### 3 Tabs

| Tab | Description |
|-----|-------------|
| **Overview** | Summary metrics + 3 charts (conviction breakdown, sector distribution, avg upside by tier) |
| **Stock Explorer** | Full 102-stock table with search, filters, sort, and click-to-expand SWOT panels |
| **★ Kamran's Shortlisted** | 6 hand-picked top performers with live price context, upside targets, catalysts, and risk notes |

### Stock Explorer Features
- 🔍 **Search** across ticker, company name, sector, catalyst text, and competitive edge
- 🏷️ **Filter** by conviction rating (Rating 1–5)
- ↕️ **Sort** by rating, upside potential, ticker A–Z, or outlook
- 📋 **Click any row** to expand a full analysis panel showing:
  - SWOT (Strengths, Weaknesses, Opportunities, Threats)
  - Competitive edge
  - Upcoming earnings catalyst
  - Recent deals & news

---

## Data Coverage

- **102 stocks** analyzed across 18 sectors
- **21** Aggressive Entry (Rating 1)
- **50** Accumulate (Rating 2)
- **26** Hold (Rating 3)
- **7** Reduce (Rating 4)
- **5** Don't Buy (Rating 5)
- Average upside on Rating 1 picks: ~42%

---

## Tech Stack

| Component | Details |
|-----------|---------|
| Framework | None — pure HTML/CSS/JS |
| Charts | [Chart.js 4.4.1](https://www.chartjs.org/) via CDN |
| Hosting | GitHub Pages / Netlify Drop |
| Dark mode | Automatic via `prefers-color-scheme` |
| Dependencies | Internet connection (for Chart.js CDN only) |

---

## How to Deploy

### Option A — GitHub Pages *(this repo)*
1. Upload `index.html` to this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)` folder
4. Save — live in ~1 minute at `https://yourusername.github.io/ods-dashboard`

### Option B — Netlify Drop *(fastest)*
1. Go to [netlify.com/drop](https://netlify.com/drop)
2. Drag and drop `index.html`
3. Done — instant live URL, no account needed

---

## How to Update

1. Edit `index.html` locally (stock data is in the `stocks` array in the `<script>` block)
2. Re-upload to GitHub → commit → GitHub Pages auto-redeploys in ~1 min
3. Or drag the new file onto Netlify Drop to replace the old one

---

## Disclaimer

> This dashboard is for **informational purposes only** and does not constitute investment, legal, or financial advice. All investments carry risk of loss. Past performance does not guarantee future results. Always conduct your own due diligence and consult a licensed financial advisor before making any investment decisions.
>
> Data based on public filings, analyst consensus, and earnings reports as of **May 2026**.

---

## License

Private use only. Not for redistribution.

---

*Built by ODS Investors · May 2026*
