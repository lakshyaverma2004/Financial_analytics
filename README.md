<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:020a0f,30:041520,60:061a28,100:030d18&height=220&section=header&text=EXCEL%20BUSINESS%20ANALYTICS&fontSize=42&fontColor=00d4aa&fontAlignY=42&desc=Atliq%20Hardwares%20%7C%20Sales%20%7C%20PnL%20%7C%20Market%20Intelligence&descSize=13&descAlignY=65&descColor=0891b2&animation=fadeIn&stroke=00d4aa&strokeWidth=1" width="100%"/>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=16&duration=2400&pause=900&color=00D4AA&center=true&vCenter=true&width=760&height=40&lines=Raw+data+in.+Strategic+insight+out.;Customer+revenue+mapped+to+the+last+dollar.;Targets+missed%3F+Excel+knows+exactly+where.;No+guesswork.+No+dashboards-as-decoration." alt="Typing SVG"/>

<br/><br/>

![Excel](https://img.shields.io/badge/Tool-Microsoft%20Excel-030d18?style=for-the-badge&logo=microsoftexcel&logoColor=00d4aa&labelColor=020a0f)
![Domain](https://img.shields.io/badge/Domain-Business%20Analytics-030d18?style=for-the-badge&logoColor=00d4aa&labelColor=020a0f)
![Reports](https://img.shields.io/badge/Reports-5%20Structured-030d18?style=for-the-badge&logoColor=00d4aa&labelColor=020a0f)
![Focus](https://img.shields.io/badge/Focus-Financial%20Reporting-030d18?style=for-the-badge&logoColor=00d4aa&labelColor=020a0f)
![Status](https://img.shields.io/badge/Status-Complete-030d18?style=for-the-badge&logoColor=00d4aa&labelColor=020a0f)

<br/><br/>

> **Five Excel reports. One source of truth for every business decision.**
>
> [![Star](https://img.shields.io/badge/%E2%AD%90%20Star%20this%20repo-raw%20data%20%E2%86%92%20insight%20%E2%86%92%20action-00d4aa?style=for-the-badge&labelColor=020a0f)](https://github.com/lakshyaverma2004)

</div>

<br/>

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/solar.png)](#overview)

## Overview

```python
project = {
    "company"          : "Atliq Hardwares",
    "tool"             : "Microsoft Excel — Pivot Tables, Power Query, Formulas",
    "reports"          : 5,
    "scope"            : ["customer performance", "market vs target", "P&L fiscal year",
                          "P&L by markets", "P&L by months"],
    "years_covered"    : ["2019", "2020", "2021"],
    "key_markets"      : ["India", "USA", "Canada", "South Korea", "UK", "+more"],
    "key_customers"    : ["Amazon", "Flipkart", "BestBuy", "Costco", "AtliQ e Store"],
    "revenue_tracked"  : "87.5M → 598.9M (3-year trajectory)",
    "decisions_enabled": ["channel prioritisation", "market expansion", "cost control"],
    "code_required"    : False,
}
```

A structured set of Excel-based business analytics reports that dissect Atliq Hardwares' sales performance, market gaps, and profitability — from the customer level all the way up to regional P&L, month by month.

<br/>

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/solar.png)](#architecture)

## Report Architecture

```
  Source Data  (transactional records · fiscal year extracts · target sheets)
              │
              ▼
┌─────────────────────────────────────────────────────────┐
│  DATA LAYER  — Power Query + Structured Tables          │
│  Clean · Typed · Relationships mapped                   │
└────────────────────────┬────────────────────────────────┘
                         │  feeds into
                         ▼
┌─────────────────────────────────────────────────────────┐
│  ANALYTICS LAYER  — Pivot Tables + Formulas             │
│  Net Sales · COGS · Gross Margin · GM%                  │
│  YoY Growth · Variance vs Target                        │
└──────────┬──────────────────────────┬───────────────────┘
           │                          │
           ▼                          ▼
┌────────────────────┐    ┌───────────────────────────────┐
│  CUSTOMER REPORT   │    │  MARKET vs TARGET REPORT      │
│  Revenue by acct   │    │  Actual vs goal per country   │
│  YoY growth %      │    │  Gap analysis · Miss flagged  │
└────────────────────┘    └───────────────────────────────┘
           │                          │
           └──────────┬───────────────┘
                      ▼
        ┌─────────────────────────────┐
        │  P&L REPORTS (3 cuts)       │
        │  By Fiscal Year             │
        │  By Market / Region         │
        │  By Month (seasonality)     │
        └─────────────────────────────┘
```

<br/>

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/solar.png)](#reports)

## Reports Breakdown

<div align="center">

| Report | What It Answers | Key Output |
|:---|:---|:---|
| **Customer Performance** | Which accounts drive revenue? | Net sales · YoY Δ% per customer |
| **Market vs Target** | Where did we miss? By how much? | Actual vs target gap, country-level |
| **P&L — Fiscal Year** | Is the business growing profitably? | Net Sales · COGS · GM · GM% (2019–2021) |
| **P&L — Markets** | Which regions earn the most margin? | Country-level P&L with margin % |
| **P&L — Months** | When does revenue spike or dip? | Monthly trend · Seasonality signals |

</div>

<br/>

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/solar.png)](#insights)

## Insight Highlights

```
Customer Performance
──────────────────────────────────────────────────────────
  Amazon         ████████████████████████████░░░░  Top revenue channel
  Flipkart       ████████████████████░░░░░░░░░░░░  Strong domestic pull
  BestBuy        ████████████████░░░░░░░░░░░░░░░░  Key USA contributor
  AtliQ e Store  ████████████░░░░░░░░░░░░░░░░░░░░  Direct channel rising

Market vs Target — 2021
──────────────────────────────────────────────────────────
  India          161.3M actual  |  missed target by  -9.6M   ⚠
  USA             87.8M actual  |  on track                  ✓
  Canada          35.1M actual  |  missed target by  -2.1M   ⚠

P&L Trajectory — Net Sales
──────────────────────────────────────────────────────────
  2019    87.5M   ████░░░░░░░░░░░░░░░░░░░░░░░░░░░░
  2020   196.7M   █████████░░░░░░░░░░░░░░░░░░░░░░░
  2021   598.9M   ████████████████████████████████  +204% YoY 🚀

Gross Margin — 2021
──────────────────────────────────────────────────────────
  Total GM        218.2M  |  GM% ~36.4%
  USA GM%         37.0%   ████████████████████████████████
  India GM%       ~32%    ███████████████████████████░░░░░
```

<br/>

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/solar.png)](#execution)

## Example Analysis Flow

```
Business Question → "Why did India miss its 2021 sales target?"

Step 1  →  Open Market vs Target Report
        →  Filter: Country = India
        →  Actual: 161.3M  |  Target: 170.9M  |  Gap: -9.6M (-5.6%)

Step 2  →  Cross-reference Customer Performance Report
        →  Identify which accounts underperformed vs prior year

Step 3  →  Check P&L by Months — India
        →  Locate quarter where growth stalled (Q3 dip visible)

Step 4  →  Margin check via P&L by Markets
        →  India GM% = 32%  →  below USA (37%) and Canada (35%)

Conclusion  →  Volume shortfall + compressed margin in India
            →  Recommend: channel mix review + pricing audit
            →  Data-backed. Delivered in Excel. No code needed.
```

<br/>

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/solar.png)](#stack)

## Tech Stack

<div align="center">

| Layer | Technology |
|:---:|:---:|
| Core Tool | `Microsoft Excel` — Pivot Tables, Power Query, Formulas |
| Aggregation | `Pivot Tables` — dynamic slicing by customer, market, month |
| Transformation | `Power Query` — data cleaning, type casting, joins |
| Metrics | `SUMIF / IF / IFERROR / calculated fields` |
| Reporting | Five structured `.xlsx` report files |
| Versioning | `Git + GitHub` — tracked, shareable, reproducible |

</div>

<br/>

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/solar.png)](#structure)

## Project Structure

```bash
Excel-Business-Analytics/
│
├── Customer Performance Report.xlsx         # Revenue + YoY by account
├── Market Performance vs Target Report.xlsx  # Actual vs target gap, by country
├── P&L Statement by Fiscal Year.xlsx        # 2019–2021 full P&L
├── P&L Statement by Markets.xlsx            # Country-level margin breakdown
├── P&L Statement by Months.xlsx             # Monthly seasonality view
│
└── README.md
```

<br/>

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/solar.png)](#impact)

## Business Impact

```
  Manual report build time reduced    ████████████████████████████░░  ~90%
  Revenue visibility (customer lvl)   ████████████████████████████░░  Full coverage
  Market gap identification           ████████████████████████░░░░░░  Country-level
  P&L granularity (month x market)    ████████████████████████████░░  3-year depth
  Tools required beyond Excel         ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░  zero
```

<br/>

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/solar.png)](#roadmap)

## Roadmap

```
[✓]  Customer net sales with YoY growth tracking
[✓]  Market vs target variance analysis (country-level)
[✓]  P&L by fiscal year — sales, COGS, gross margin, GM%
[✓]  P&L by markets — regional profitability comparison
[✓]  P&L by months — seasonality and trend analysis
[ ]  Power BI version — live-refresh dashboard
[ ]  SQL backend — replace manual data prep with queries
[ ]  Forecast model — regression-based sales projection
[ ]  Automated report refresh via Python + openpyxl
[ ]  Executive summary slide deck auto-generated from data
```

<br/>

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/solar.png)](#skills)

## Skills Demonstrated

<div align="center">

| Skill | Application |
|:---|:---|
| **Data Analysis** | Slicing sales data by customer, market, period |
| **Financial Reporting** | Full P&L construction — net sales to GM% |
| **Business Intelligence** | Trend identification, gap analysis, KPI monitoring |
| **Market Evaluation** | Country-level performance vs targets |
| **Excel Mastery** | Pivot Tables, Power Query, structured formulas |

</div>

<br/>

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/solar.png)](#footer)

<div align="center">

<br/>

Built by **[Lakshya Verma](https://github.com/lakshyaverma2004)**  
`B.Tech CSE (AI/ML) · Manipal Institute of Technology · 2027`

<br/>

![Views](https://visitor-badge.laobi.icu/badge?page_id=lakshyaverma2004.excel-business-analytics&left_color=020a0f&right_color=041520&left_text=Repo%20Views)

<br/>

*Numbers don't lie. Excel just makes them impossible to ignore.*

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:030d18,50:041520,100:020a0f&height=120&section=footer&text=ANALYSE.%20COMPARE.%20DECIDE.&fontSize=16&fontColor=00d4aa&fontAlignY=55&desc=vermalakshya12%40gmail.com&descSize=11&descColor=0891b2&descAlignY=78" width="100%"/>

</div>
