# BDC Capital Structure & Asset Ringfencing Analysis

*Analysis date: March 2026 | Data as of December 31, 2025*

This document summarizes the capital structures of two large publicly traded BDCs — **Blue Owl Capital Corporation (OBDC)** and **Ares Capital Corporation (ARCC)** — and examines how their senior secured debt ringfences specific pools of portfolio assets.

---

## 1. Blue Owl Capital Corporation (OBDC)

### Overview
- **Total portfolio fair value:** ~$16.5B across 234 portfolio companies
- **Total debt outstanding:** $9.4B (principal value)
- **Net debt-to-equity:** 1.19x
- **Cash & restricted cash:** $569M
- **Undrawn credit facility capacity:** $3.6B

### Capital Stack (Dec 31, 2025)

| Layer | Type | Amount | % of Debt |
|-------|------|--------|-----------|
| **Secured borrowings** | Revolving credit facility, SPV Asset Facilities, CLOs | ~$4.4B | 46.5% |
| **Unsecured notes** | Public investment-grade bonds | ~$5.0B | 53.5% |
| **Total debt** | | **$9.4B** | 100% |
| **Equity (NAV)** | | ~$7.9B | — |

### Secured Facilities — Structure & Ringfencing

#### A. Revolving Credit Facility
- **Maturity:** $50M of commitments mature 8/26/2027; remainder matures 11/22/2029
- **Collateral:** Unless otherwise indicated, *all* OBDC portfolio companies are pledged as collateral supporting amounts outstanding under the Revolving Credit Facility (and SPV Asset Facilities)
- **Borrowing base:** Subject to advance rates applied to different asset types in the portfolio
- **Covenants:** Standard BDC asset coverage ratio (total assets ≥ 150% of total debt, i.e., max 2:1 leverage)

#### B. SPV Asset Facilities (II, III, IV)
OBDC operates through wholly owned special purpose vehicle (SPV) subsidiaries. The structure works as follows:

1. OBDC **sells and contributes** specific portfolio investments into the SPV subsidiary
2. The SPV borrows against those contributed assets under its own credit agreement
3. The SPV's assets are **ringfenced** — they secure only the SPV's own borrowings and are **not available to pay OBDC's other debts** (including unsecured noteholders)
4. OBDC retains economic exposure through its equity ownership of the SPV

Key SPV entities include:
- **ORCC III Financing LLC** — governed by a Loan and Servicing Agreement (amended multiple times, most recently August 2025)
- **SPV Asset Facility II** — ~$300M committed (as of Q1 2024), SOFR + 275 bps, maturing 4/17/2033
- **SPV Asset Facility IV** — secured line of credit

The SPV Asset Facilities contain:
- Limitations on OBDC incurring additional indebtedness
- Restrictions on OBDC's ability to make shareholder distributions upon certain events
- Customary events of default with cure and notice provisions

#### C. CLO Transactions (CLO I through CLO VI)
OBDC has entered into six term debt securitization (CLO) transactions. These are **true-sale securitizations** where:

1. A pool of OBDC's loans is transferred to a CLO issuer entity
2. The CLO issues **multiple tranches** of rated debt (Class A, Class A-F, Class B notes, Class A loans) at different seniority levels
3. Assets pledged to CLO noteholders are **not available to pay OBDC's other debts**
4. OBDC typically retains the subordinated/equity tranche
5. Interest rates are weighted average spreads over 3-month or 6-month SOFR

Recent CLO activity:
- **CLO I** reset at $390M
- **CLO III** reset at $260M
- **CLO VI** fully paid down ($260M) and subsequently terminated
- **CLO II** terminated (July 2025)

Historical CLO sizes (as of Q1 2024): CLO I ($390M), CLO II ($260M), CLO III ($260M), CLO IV ($293M), CLO V ($510M), CLO VII ($239M), CLO X ($260M)

### Unsecured Notes Outstanding

| Series | Maturity | Amount | Coupon |
|--------|----------|--------|--------|
| Notes due 2026 | 07/15/2026 | $1,000M | 3.400% |
| Notes due 2027 | 01/15/2027 | $500M | 2.625% |
| Notes due 2027 | 04/13/2027 | $325M | 3.125% |
| Notes due 2027 | 07/21/2027 | $250M | 7.580% |
| Notes due 2028 | 06/11/2028 | $850M | 2.875% |
| Notes due 2028 | 06/29/2028 | $100M | 8.100% |
| Notes due 2029 | 03/15/2029 | $1,000M | 5.950% |
| Notes due 2030 | 07/15/2030 | $500M | 6.200% |
| **Total** | | **$4,525M** | |

Note: The $5.0B total unsecured notes figure from the earnings release includes additional series not listed on the public debt securities page.

### What's Ringfenced vs. Unencumbered?

```
┌─────────────────────────────────────────────────────────────┐
│                    OBDC (Parent BDC)                        │
│                                                             │
│  ┌─────────────────┐  ┌──────────────┐  ┌───────────────┐  │
│  │ Revolving Credit │  │ Unsecured    │  │ Unencumbered  │  │
│  │ Facility         │  │ Notes (~$5B) │  │ Assets        │  │
│  │                  │  │              │  │               │  │
│  │ Secured by       │  │ General      │  │ Available for │  │
│  │ portfolio-wide   │  │ unsecured    │  │ new           │  │
│  │ borrowing base   │  │ obligation   │  │ investments   │  │
│  └─────────────────┘  └──────────────┘  └───────────────┘  │
│                                                             │
│  ┌─────────────────────────────────────────────────────┐    │
│  │         RINGFENCED SPV & CLO SUBSIDIARIES           │    │
│  │                                                     │    │
│  │  ┌─────────┐ ┌─────────┐ ┌─────────┐ ┌─────────┐   │    │
│  │  │ SPV II  │ │ SPV III │ │ SPV IV  │ │ CLOs    │   │    │
│  │  │         │ │         │ │         │ │ I-VI    │   │    │
│  │  │ Assets  │ │ Assets  │ │ Assets  │ │ Assets  │   │    │
│  │  │ pledged │ │ pledged │ │ pledged │ │ pledged │   │    │
│  │  │ to SPV  │ │ to SPV  │ │ to SPV  │ │ to CLO  │   │    │
│  │  │ lenders │ │ lenders │ │ lenders │ │holders  │   │    │
│  │  └─────────┘ └─────────┘ └─────────┘ └─────────┘   │    │
│  │                                                     │    │
│  │  ⚠ NOT available to pay OBDC's other debts         │    │
│  └─────────────────────────────────────────────────────┘    │
└─────────────────────────────────────────────────────────────┘
```

**Key insight:** ~46.5% of OBDC's borrowings ($4.4B) are secured and structurally senior. The assets backing the SPVs and CLOs are legally isolated — if OBDC defaulted on its unsecured notes, those creditors could not reach the ringfenced assets. Conversely, the remaining ~$12B of portfolio fair value (total $16.5B minus ringfenced assets) serves as the collateral base for both the revolving facility (via borrowing base) and the general credit supporting the unsecured notes.

---

## 2. Ares Capital Corporation (ARCC)

### Overview
- **Total portfolio fair value:** ~$29.5B
- **Total debt outstanding:** ~$16.0B (as of Aug 2025)
- **Net debt-to-equity:** 1.08x
- **Available liquidity:** >$6.0B
- **Non-accruals (at cost):** 1.8%

### Capital Stack (Year-End 2025)

| Layer | Type | Amount | % of Debt |
|-------|------|--------|-----------|
| **Direct secured debt** | Senior secured revolving credit facility (JPM-led) | ~$3.4B | ~21% |
| **Subsidiary secured debt** | SPV funding facilities (ARCC FB Funding, etc.) | ~$3.5B | ~22% |
| **Unsecured notes** | Public investment-grade bonds | ~$9.1B | ~57% |
| **Total debt** | | **~$16.0B** | 100% |
| **Equity (NAV)** | | ~$14.8B | — |

### Secured Facilities — Structure & Ringfencing

#### A. Senior Secured Revolving Credit Facility (A&R Credit Facility)
- **Administrative agent:** JPMorgan Chase Bank, N.A.
- **Total commitments:** ~$5.5B (upsized from $5.4B in July 2025)
- **Pricing:** SOFR + 10 bps credit spread adjustment + 175-187.5 bps applicable spread
- **Collateral:** Secured by a borrowing base that applies different **advance rates** to different asset types in ARCC's portfolio
- **Available capacity:** ~$5.2B available for additional borrowings (as of Sep 30, 2025)

#### B. ARCC FB Funding LLC (BNP Funding Facility)
This is ARCC's primary **ringfenced subsidiary funding vehicle**:

1. **Borrower:** ARCC FB Funding LLC ("AFB"), a wholly owned consolidated subsidiary
2. **Administrative agent:** BNP Paribas
3. **Collateral agent:** U.S. Bank Trust Company
4. **Servicer:** Ares Capital Corporation
5. **Structure:** Revolving credit and security agreement (originally June 2020, amended multiple times — most recently the 7th Amendment in April 2024)

**Collateral eligibility criteria (ringfenced asset requirements):**
- Minimum **96%** Senior Secured Loans and Eligible Investments
- Maximum **4%** Second Lien Loans (including First-Lien Last-Out)
- Maximum **5%** Fixed Rate Underlying Assets
- Maximum **17.5%** of assets rated CCC+ or below (S&P/Fitch)
- **Concentration limits:** ≤15% of concentration calculation amount in First Lien Last Out / Second Lien combined; ≤10% in Second Lien alone
- Must satisfy **Maximum Weighted Average Life Test**

#### C. Other Consolidated Subsidiary Borrowings
The ~$3.5B of consolidated subsidiary indebtedness represents multiple ringfenced funding vehicles where specific asset pools are pledged at the subsidiary level, structurally senior to ARCC's parent-level unsecured obligations.

### Unsecured Notes
- ARCC issued **$2.4B** in unsecured notes during 2025 alone
- January 2025: $1.0B aggregate principal, 5.800% coupon, maturing March 8, 2032 (semi-annual interest, par + make-whole redemption)
- Total unsecured notes outstanding: ~$9.1B
- ~70% of total borrowings are now **floating rate** (up from ~50% prior year)

### What's Ringfenced vs. Unencumbered?

```
┌──────────────────────────────────────────────────────────────┐
│                     ARCC (Parent BDC)                        │
│                                                              │
│  ┌──────────────────┐  ┌──────────────┐  ┌───────────────┐   │
│  │ A&R Revolving    │  │ Unsecured    │  │ Unencumbered  │   │
│  │ Credit Facility  │  │ Notes (~$9B) │  │ Assets        │   │
│  │ (~$3.4B drawn)   │  │              │  │               │   │
│  │                  │  │ General      │  │               │   │
│  │ Borrowing base   │  │ unsecured    │  │               │   │
│  │ secured by       │  │ obligation   │  │               │   │
│  │ portfolio assets │  │ of parent    │  │               │   │
│  └──────────────────┘  └──────────────┘  └───────────────┘   │
│                                                              │
│  ┌──────────────────────────────────────────────────────┐    │
│  │           RINGFENCED SUBSIDIARIES (~$3.5B)           │    │
│  │                                                      │    │
│  │  ┌──────────────────────────────────────────────┐    │    │
│  │  │  ARCC FB Funding LLC (BNP Funding Facility)  │    │    │
│  │  │                                              │    │    │
│  │  │  • ≥96% senior secured loans                 │    │    │
│  │  │  • ≤4% second lien                           │    │    │
│  │  │  • ≤5% fixed rate                            │    │    │
│  │  │  • ≤17.5% CCC+ or below                     │    │    │
│  │  │  • WAL test must be satisfied                │    │    │
│  │  │                                              │    │    │
│  │  │  Assets pledged to BNP lenders only          │    │    │
│  │  └──────────────────────────────────────────────┘    │    │
│  │                                                      │    │
│  │  ┌──────────────────────────────────────────────┐    │    │
│  │  │  Other Consolidated Sub Facilities           │    │    │
│  │  │  (additional ringfenced pools)               │    │    │
│  │  └──────────────────────────────────────────────┘    │    │
│  │                                                      │    │
│  │  ⚠ Structurally senior to parent unsecured debt     │    │
│  └──────────────────────────────────────────────────────┘    │
└──────────────────────────────────────────────────────────────┘
```

---

## 3. Comparative Analysis

### Side-by-Side

| Metric | OBDC | ARCC |
|--------|------|------|
| **Total assets (FV)** | $16.5B | $29.5B |
| **Total debt** | $9.4B | ~$16.0B |
| **Net debt/equity** | 1.19x | 1.08x |
| **Secured % of debt** | 46.5% | ~43% |
| **Unsecured % of debt** | 53.5% | ~57% |
| **Available liquidity** | $4.2B | >$6.0B |
| **Ringfencing vehicles** | 3 SPVs + 6 CLOs | AFB + other subs |
| **Secured structure** | SPV sell/contribute + CLO securitization | Subsidiary funding facilities |

### Key Structural Differences

1. **CLO usage:** OBDC makes heavy use of CLO securitizations (6 transactions), which provide term-matched, non-recourse funding. ARCC relies more on revolving subsidiary facilities and has a larger proportion of unsecured debt.

2. **Ringfencing granularity:** OBDC's multiple SPVs and CLOs mean the portfolio is carved into many discrete collateral pools. ARCC's approach is more consolidated, with fewer but larger ringfenced subsidiaries (primarily AFB).

3. **Advance rates vs. eligibility criteria:** Both use borrowing base mechanics, but ARCC's subsidiary facility eligibility criteria are more explicitly disclosed (96% senior secured, ≤4% second lien, etc.), providing transparency into what *type* of assets end up ringfenced.

4. **Leverage:** ARCC runs at lower leverage (1.08x vs. 1.19x), giving it more cushion relative to the 2:1 statutory BDC leverage limit (150% asset coverage).

### Implications for Unsecured Creditors

In both structures, unsecured noteholders face **structural subordination** to the extent assets are ringfenced in SPVs, CLOs, or subsidiary funding vehicles. The key question is: *what's left after the secured/ringfenced claims?*

- **OBDC:** ~$16.5B total portfolio FV minus ~$4.4B ringfenced = ~$12.1B supporting the revolver borrowing base + $5.0B unsecured notes + equity. Asset coverage on unsecured notes alone is roughly 2.4x — comfortable but depends on how much of the unencumbered pool is drawn under the revolver.

- **ARCC:** ~$29.5B total portfolio FV minus ~$6.9B ringfenced (secured + subsidiary) = ~$22.6B supporting ~$9.1B unsecured notes + equity. Asset coverage on unsecured notes alone is roughly 2.5x.

Both BDCs maintain investment-grade ratings on their unsecured debt, and the high proportion of first-lien senior secured loans in the portfolio (~90%+ for OBDC) provides downside protection even in stress scenarios.

---

## Sources

- [OBDC Q4 2025 Earnings Release](https://www.blueowlcapitalcorporation.com/investors/news-events/press-releases/detail/90/blue-owl-capital-corporation-announces-december-31-2025)
- [OBDC Debt Securities Page](https://www.blueowlcapitalcorporation.com/investors/fixed-income/debt-securities)
- [OBDC Q3 2025 Earnings Release](https://www.blueowlcapitalcorporation.com/investors/news-events/press-releases/detail/86/blue-owl-capital-corporation-announces-september-30-2025)
- [OBDC 10-K (FY2025) on SEC EDGAR](https://www.sec.gov/Archives/edgar/data/0001655888/000165588826000010/obdc-20251231.htm)
- [ARCC Investor Resources](https://ir.arescapitalcorp.com/)
- [ARCC Q4 2025 Earnings Call Transcript (Motley Fool)](https://www.fool.com/earnings/call-transcripts/2026/02/04/ares-capital-arcc-q4-2025-earnings-transcript/)
- [ARCC SEC Prospectus Filing](https://www.sec.gov/Archives/edgar/data/1287750/000110465925087467/arcc-20250902xn2.htm)
- [ARCC BNP Funding Facility Amendment (8-K)](https://www.sec.gov/Archives/edgar/data/1287750/000128775024000021/arcc-20240412.htm)
