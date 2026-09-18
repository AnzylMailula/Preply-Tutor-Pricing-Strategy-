From $5 to $25: A Pricing Strategy Case Study

I used two years of my own Preply tutoring data to test whether temporary price reductions could grow a sustainable student base and whether rising prices could buy back my time without costing me income.

The Decision

Progressively increase price over time (from $5 to $25), using temporary price reductions as a recovery tool whenever acquisition weakens at a new price ceiling, then pushing higher again working toward a sustainable target of 8–9 hours a day, 5 days a week, instead of the higher-volume, longer-hours pattern low pricing originally required.

Headline Results:
Metric	Result
Trial-to-return rate	47.1% (374 trials → 176 returned)
Monthly lessons taught	Fell from 283 (Mar 2025) to 228 (May 2026)
Monthly earnings	Held steady at $1,720–$1,813 over the same span
Gross vs. Net pay	$46.31K gross → $28.91K net (~37.6% platform commission)
Price tested	$5 → $25

The core finding: lesson volume dropped ~20% while earnings stayed flat. Rising price wasn't just a revenue lever, it was the mechanism that let me work fewer hours for comparable income.

Background

Preply is a global online tutoring marketplace (founded 2012, 100,000+ tutors, 180+ countries, $1.2B valuation as of 2026) where tutors set their own rates and compete for visibility among tens of thousands of peers. I'm one of those tutors, and separately, a self-taught data analyst. This project is where those two sides met: instead of leaving pricing to instinct, I applied real analytical rigor to my own business.

What's in This Repo
Preply Pricing Strategy Tutor Decision Brief.md — full executive summary: decision, evidence, recommendations, caveats, and outlook
Data Cleaning Notes and Technical steps .md — full technical writeup: Power Query cleaning pipeline, DAX measures, data model
[[PreplyBusinessIntel].pbix — the Power BI dashboard](https://github.com/AnzylMailula/Preply-Tutor-Pricing-Strategy-/blob/main/PreplyBusinessIntel.pbix)
<img width="763" height="428" alt="image" src="https://github.com/user-attachments/assets/1390b2b9-9a17-4de6-85d7-e11b787f89ed" />


Key Findings:
Price directly drove acquisition volume. $9 in March 2025 produced 28 new students; $16 in the same month produced 1.
A temporary price cut reliably recovers demand. Validated  May 2025's weak $12 result recovered via a June reduction; September 2025's weak $16 result recovered via $14.

The price ceiling kept rising without collapsing demand. By 2026, price reached $25, with $18 still producing real volume (11 acquired / 6 returned in June 2026).
Nearly half of trial students return. A strong conversion rate for a no-lock-in marketplace product.
Poland is a disproportionately important market 24.45% of lessons, 26.70% of revenue flagged as a lead for further channel investigation, not something this dataset alone can explain.

Honest Limitations:
Prices weren't retested at $5–8 after March 2025, so that early volume isn't proven to be repeatable, only observed once.
Results above $18 are still thin (mostly single bookings) $25 is an active ceiling test, not a proven sustainable price.
The 47.1% conversion figure is a proxy (recorded trial → subsequent booking), not a true attended-trial rate, since Preply doesn't log no-shows separately from confirmed lessons.
The dataset covers pricing, students, and earnings, not marketing spend, channel data, or demographics beyond location, so some findings (like Poland) can only be surfaced as leads, not fully explained.
Tools

Power Query (M) · Power BI · DAX · Google Calendar (manual data verification)

Why This Project

I didn't want to leave pricing decisions to instinct in a marketplace with over 100,000 competing tutors. This project applies the same analytical rigor I want to bring to a commercial/pricing analytics role — to my own real business, with real students, real prices, and real income on the line.
