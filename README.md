# -PTCL-Telenor-Pakistan-Merger-Model
A self-built merger / accretion-dilution model analyzing PTCL's acquisition of Telenor Pakistan, built as a hands-on financial modeling exercise using real, sourced disclosure data wherever available.

## Deal Background

- **Announced:** December 14, 2023 — PTCL agreed to acquire 100% of Telenor Pakistan and Orion Towers
- **Closed:** December 31, 2025
- **Full integration into Ufone:** July 1, 2026
- **Purchase price:** Rs 108 billion
- **Financing:** US$400m debt facility (International Finance Corporation), 7-year term

## Methodology

Since PTCL trades as one consolidated entity that includes an unrelated digital banking subsidiary (Ubank), Group-level consolidated figures were deliberately **not** used as the acquirer baseline — mixing a loss-making bank segment into a telecom merger model would distort every downstream output. Instead:

- **PTCL side:** built from the **Wireless segment** (Ufone) — the actual entity Telenor Pakistan is being integrated into — reconstructed from PTCL's Annual Report 2024, Note 51 (Operating Segment Information)
- **Telenor side:** built from Telenor Group's Q4 2024 report, Note 3 (segment revenue disaggregation), which discloses Pakistan-specific revenue and EBITDA directly

## Data Sources

| Input | Source |
|---|---|
| PTCL Wireless segment financials | PTCL Annual Report 2024, Note 51.3/51.4 |
| PTCL shares outstanding | PTCL Annual Report 2024, Note 6.2 (5,100,000,000 shares) |
| Telenor Pakistan revenue/EBITDA | Telenor Group Q4 2024 Report, Note 3 |
| Telenor Pakistan asset base | Telenor Group Annual Report 2024, geographic asset disclosure |
| Deal terms, financing | Public deal announcements, Telenor Group press releases |

## What's Reported vs. Modeled

Every tab distinguishes explicitly between **real, disclosed figures** and **modeled assumptions** (documented in-line via notes on each sheet):
- Reported: Revenue, EBITDA, and key balance sheet items for both companies' historical years
- Modeled: D&A/finance cost splits where not disclosed at segment level, Telenor's liabilities/equity (undisclosed — deliberately left blank rather than fabricated), synergy assumptions, and all forward projections

## Key Finding

The combination is projected to be **accretive in every forecast year (FY2025E–FY2027E)** — driven primarily by Telenor Pakistan's standalone profitability offsetting PTCL Wireless's structurally loss-making position, even after absorbing new acquisition debt costs. Sensitivity analysis shows this conclusion holds even at 0% synergy realization, though it is more sensitive to revenue growth and interest rate assumptions.

## Structure

`Assumptions` → `PTCL P&L/BS` + `Telenor P&L/BS` → `PPA Analysis` → `Debt Schedule` → `Pro Forma Combination` → `Accretion/Dilution Analysis` → `Sensitivity Table` → `Output`

## Limitations

- PTCL figures reflect the Wireless segment only, not the consolidated Group
- Telenor Pakistan's liabilities and equity are not disclosed at the segment level and were excluded rather than estimated
- Goodwill is not separately allocated to identifiable intangibles due to lack of disclosure
- All projections are illustrative, built for modeling practice — not an investment recommendation

---
Built independently as a financial modeling exercise.
