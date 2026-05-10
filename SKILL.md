---
name: major-partnership-insider
description: Use this skill to investigate potential major partnership announcements for a public company within the next 30-120 days by cross-validating unusual options flow, institutional filings, SEC disclosures, hiring, capex, operational readiness, and catalyst calendars. Use only public or user-provided data; produce probabilistic research, not trading instructions.
---

# Major Partnership Insider

## Purpose

Analyze whether a target public company is approaching a major strategic announcement by building a public-data evidence chain across four layers:

1. Derivatives intent: options flow, open interest, implied volatility, roll patterns, gamma/delta structure.
2. Institutional microstructure: 13F/13G/13D, activist pressure, market-maker accumulation, strategic holders.
3. Operational front-running: capex, construction, hiring, procurement, permits, customer-readiness.
4. Timeline alignment: expirations, earnings, conferences, fiscal deadlines, regulatory windows.

Do not present certainty. Do not give buy/sell instructions. Treat the result as investigative research and include invalidation risks.

## Required Inputs

Collect or ask for:

- Target ticker, company name, sector, market cap, current price, and suspected event type.
- Recent unusual options trades: date/time, contract, strike, expiry, call/put, buy/sell, volume, OI, premium, IV, order type, spot price.
- Options chain snapshots: OI by strike/expiry, call wall, put wall, gamma exposure, delta exposure, volume/OI change.
- Recent SEC filings: 8-K, S-3, 424B, ATM prospectus, 10-Q, 10-K, 13F, 13G, 13D, Form 4.
- Institutional ownership changes: activists, quant funds, market makers, strategic investors.
- Operational evidence: capex announcements, construction starts, permits, equipment orders, project timelines, hiring pages, executive hires.
- Catalyst calendar: earnings, investor days, industry conferences, product launches, fiscal year-end, regulatory approvals.
- Peer comps: recent signed deals in the same sector, contract size, capacity, customer, and valuation reaction.

If current facts matter, verify with official/current sources before concluding.

## Workflow

### 1. Establish The Base Thesis

Define the suspected event in one sentence:

- Event type: partnership, anchor customer, master lease, JV, M&A, restructuring, divestiture, financing, regulatory approval.
- Likely counterparty category: hyperscaler, chip company, cloud provider, strategic buyer, activist-backed operator, government, supplier.
- Materiality mechanism: revenue, valuation multiple, asset monetization, balance-sheet reset, business identity change.

Reject vague theses. A useful thesis must name the business mechanism.

### 2. Derivatives Forensics

Evaluate whether options activity looks like informed directional positioning or normal volatility trading.

Strong bullish evidence:

- Large premium, single-name, single-direction call buying.
- OTM calls bought aggressively despite high IV.
- Volume far above OI and average volume.
- Expiration covers a specific catalyst window with little wasted time.
- Repeated buying across days rather than one isolated print.
- Roll-up: selling lower strike calls to buy higher strike calls, implying a raised target.
- Time compression: rolling from later expiry to nearer expiry, implying event timing moved closer.
- Concentrated OI at catalyst expiry, especially paired with rising spot accumulation.

Weak or ambiguous evidence:

- Small premium relative to market cap.
- Bid-side prints that may be call selling.
- Multi-leg spreads with capped upside.
- Dealer hedging, index/ETF hedges, or sector beta trades.
- Calls bought during broad sector momentum without company-specific evidence.

Bearish or hedging evidence:

- Protective puts after a missed catalyst.
- Heavy call selling near resistance.
- Gamma pinning around call wall.
- IV crush after expected event passes.

Record contract-level facts in a table. Distinguish observed data from inferred intent.

### 3. Gamma, Delta, And Pinning Analysis

Map the options surface:

- Identify call wall, put wall, max gamma strikes, high OI strikes, and nearby expirations.
- Ask whether market makers may need to buy stock as price approaches short-call strikes.
- Separate squeeze potential from pinning risk.
- Track whether gamma concentration migrates upward over time.
- Watch for wall ratcheting: call wall moves from lower strike to higher strike as informed buyers roll up.
- If price repeatedly stalls at a call wall, treat it as resistance unless spot breaks it with volume.

Output:

- Squeeze trigger zone.
- Pinning zone.
- Invalidation zone.
- Expiry most connected to the suspected catalyst.

### 4. Institutional Microstructure

Review ownership filings and classify holders.

Activator signals:

- Activist investor enters or expands stake.
- 13D language pressures management on strategy, asset monetization, capital allocation, sale, spin-off, customer signing.
- Board engagement, public letters, settlement agreements, or proxy pressure.

Validator signals:

- Quant/market-maker ownership jumps unusually.
- Multiple unrelated institutions accumulate in the same quarter.
- Market makers' spot holdings rise alongside large call OI, consistent with delta hedging.
- Strategic or sector-specialist funds appear.

Caution:

- 13F data is delayed.
- Quant funds often hold many names.
- Do not assume coordination. Use "independent signal convergence," not collusion, unless there is direct evidence.

### 5. Operational Front-Running

Look for real-world preparation that would be irrational without a likely deal.

Strong signals:

- Speculative build: major construction or capex before official customer announcement.
- Core-and-shell or capacity buildout without named tenant.
- Long-lead equipment procurement: transformers, GPUs, chillers, power gear, aircraft, vessels, fabs, industrial tooling.
- Hiring for solutions engineering, technical pre-sales, enterprise sales, procurement, compliance, delivery, account management.
- Basis of design, certification, permitting, interconnect approval, customer due diligence, or pilot deployment language.
- Management repeatedly discusses a new customer class or business model before signing a named deal.

Sector adaptors:

- Data centers: MW capacity, power interconnect, Tier standard, cooling, anchor tenant, lease term.
- Biotech: trial enrollment, FDA meetings, CMC readiness, manufacturing slots.
- Defense: hiring cleared staff, facility security, budget line items, OTA/prototype awards.
- Energy: permits, grid queue, offtake, equipment deposits.
- SaaS/AI: enterprise pre-sales, solution architects, procurement/security roles, usage spikes, partner certifications.

### 6. SEC And Dilution Check

Before assigning a high probability, scan for filings that can change the interpretation:

- 8-K material agreements.
- S-3, 424B, ATM programs, convertibles, shelf offerings.
- Form 4 insider selling/buying.
- Risk factors mentioning customer concentration, financing needs, project delays.
- Debt covenants, going-concern language, liquidity constraints.

Treat fresh ATM/equity offerings as a major risk unless proceeds are clearly tied to the suspected deal.

### 7. Timeline Alignment

Build a date grid:

- Options trade dates.
- Expiration dates.
- Earnings date.
- Investor conference dates.
- Industry event dates.
- Fiscal quarter/year-end.
- Project milestones.
- Regulatory/permit deadlines.
- Peer announcement cadence.

A strong setup has at least two independent signals pointing to the same 2-6 week window.

### 8. Probability Scoring

Score each module from 0-5:

- Derivatives: size, direction, persistence, OTM aggression, roll behavior.
- Institutional: activist pressure, unusual accumulation, independent holder convergence.
- Operational: capex, hiring, procurement, permits, delivery readiness.
- Timeline: expiry/catalyst fit, announcement window, industry calendar.
- Contradictions: dilution, insider selling, missed catalysts, macro/sector stress, customer delay.

Suggested probability bands:

- 80-90%: confirmed operational setup plus extreme derivatives and precise timeline, but no public announcement yet.
- 65-79%: strong multi-source convergence; one key uncertainty remains.
- 50-64%: plausible but missing either operational proof or derivatives confirmation.
- 30-49%: speculative; signals are mixed or mostly sector-driven.
- Below 30%: weak evidence or strong contradictions.

Never output 100%.

## Standard Report Format

### Executive Verdict

- Overall probability:
- Expected event type:
- Likely counterparty category:
- Expected announcement window:
- Confidence level:
- Most important evidence:
- Biggest invalidation risk:

### Evidence Matrix

| Layer | Signal | Evidence | Strength | Interpretation |
|---|---|---|---|---|
| Derivatives |  |  |  |  |
| Institutions |  |  |  |  |
| Operations |  |  |  |  |
| Timeline |  |  |  |  |
| Risks |  |  |  |  |

### Derivatives Read

Include key trades, roll patterns, IV, OI, Vol/OI, gamma walls, squeeze zones, and pin zones.

### Corporate And Operational Read

Summarize filings, capex, hiring, project readiness, peer comps, and business-model implications.

### Scenario Map

- Bull case:
- Base case:
- Bear case:
- Invalidation triggers:
- What to monitor next:

### Source Hygiene

Separate:

- Observed public facts.
- User-provided screenshots/data.
- Analyst inference.
- Speculation.

End with: "This is probabilistic research based on public/user-provided information and is not investment advice."
