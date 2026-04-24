# Sun OS — The Sunspell Venture Lab

*Umbrella document describing Sunspell, the Aither ↔ Sunspell loop, and the full portfolio of operational tools and consumer products under development.*

*Last updated: April 2026*

---

## Contents

0. [What Sun OS Is](#0-what-sun-os-is)
1. [Sunspell — The Venture Lab](#1-sunspell--the-venture-lab)
2. [The Aither ↔ Sunspell Loop](#2-the-aither--sunspell-loop)
3. [Portfolio Map](#3-portfolio-map)
4. [Sun OS — Operational Tools for Aither](#4-sun-os--operational-tools-for-aither)
5. [Sunspell Consumer Ventures](#5-sunspell-consumer-ventures)
6. [Priority Matrix](#6-priority-matrix)
7. [Team & Resources](#7-team--resources)
8. [Capital](#8-capital)
9. [Decision Framework](#9-decision-framework)
10. [Cadence & Review](#10-cadence--review)

---

## 0. What Sun OS Is

Sun OS is the system of products that together move the founder's work from *execution-led* (doing the design work at Aither) to *orchestration-led* (running a portfolio of tools and ventures).

It contains two categories:

1. **Operational tools** — software that automates and compounds Aither's studio work (the internal layer)
2. **Consumer ventures** — products born from Aither's pattern recognition, incubated for external launch (the external layer)

Both categories live inside **Sunspell**, the parent venture lab. Aither (the design studio) is the first engine. Sunspell is the second.

### The thesis in one sentence
*Every repeatable pattern you see at Aither becomes a tool inside Sun OS. Every transformative pattern you see in the wild becomes a venture under Sunspell.*

---

## 1. Sunspell — The Venture Lab

### What Sunspell is
Sunspell is the venture lab spun out of Aither. It owns all the "Sun-" prefixed products and any future portfolio companies incubated from Aither's work.

### What Sunspell does
- Observes patterns in Aither's client work
- Builds internal tools to compound studio leverage
- Incubates new consumer products and services
- Eventually spins out consumer products into their own brands / companies

### What Sunspell is NOT
- Not an investment fund (doesn't deploy capital to external founders)
- Not a consulting firm (that's Aither)
- Not an agency (that's Aither)
- Not a product company on its own (the consumer products get their own standalone brands at launch — e.g., Sunspoke, Sool, Sapour)

### Why Sunspell exists
Because most design studios see problems they could solve, but never build the products. Sunspell exists to capture that value instead of letting it dissipate.

---

## 2. The Aither ↔ Sunspell Loop

```
┌─────────────────────────────────────────────────┐
│  AITHER (design studio)                         │
│  Sees problems in the wild:                     │
│  - Client patterns (what's broken)              │
│  - Product patterns (what's needed)             │
│  - Behavior patterns (what's changing)          │
└──────────────┬──────────────────────────────────┘
               │ pattern recognized
               ▼
┌─────────────────────────────────────────────────┐
│  SUNSPELL (venture lab)                         │
│  Turns pattern into product:                    │
│  - Internal tool (if serves Aither)             │
│  - Consumer product (if serves broader market)  │
└──────────────┬──────────────────────────────────┘
               │ product ships
               ▼
┌─────────────────────────────────────────────────┐
│  RESULT                                          │
│  - Aither becomes more leveraged                │
│  - Sunspell owns IP and revenue                 │
│  - New patterns observed, loop continues        │
└─────────────────────────────────────────────────┘
```

**Why this is the unfair advantage:** most founders guess what to build from the outside. The Aither → Sunspell loop sees what breaks in the wild before building — fewer false starts, tighter fit, faster validation.

---

## 3. Portfolio Map

| Product | Type | Status | Description |
|---|---|---|---|
| **Sunpull** | Operational tool | In progress (Michael) | Pinterest-style save + memory layer. Captures saves across platforms (LinkedIn, IG, forwarded links) into tagged boards. Foundational for every other tool. |
| **Sundial** | Operational tool | Next (spec ready) | Slack-only PM system. Retainer flow, capacity/debt model, Monday/Friday rhythm. Replaces the previous Aion PM bot. |
| **Sunspoke (internal)** | Operational tool | Live thinking, not started | Communication coaching tool for Aither's managers. Plaud + Claude + Slack. Runs as R&D for the consumer product. |
| **Sunrun** | Operational tool | Later | Composable execution blocks (Extract / Generate / Compare / Refine / Evaluate). Powers the audit-funnel service pivot. This is the moat inside Sun OS. |
| **Sunreach** | Operational tool | Later | Sales layer: prospect tracking, custom outbound, proposal drafts. Built on Sunpull + Sunrun. |
| **Sunkeep** | Operational tool | Urgent after Sundial | Client account health, renewal timing, QBR prep. Urgent because current retainers end July 31. |
| **Sunbill** | Operational tool | Later | AR / invoicing / payment nudges. Sundial handles L1 reminders until this exists. |
| **Sunhire** | Operational tool | On demand | Candidate pipeline, interview notes. Only built when actively recruiting. |
| --- | --- | --- | --- |
| **Sunspoke (consumer)** | Consumer venture | Scoping (Q2 2026) | Voice coaching product. Three SKUs: Object (desk sculpture), Wear (pendant), Clip (phone accessory). Full spec lives in `sunspoke.md`. |
| **Sapour** | Consumer venture | Conceptual | Scent × identity × attraction. Scent profile capture, wearable fragrance generation, matching. |
| **Airon** | Consumer venture | Conceptual | Smart travel concierge. Refundable flight booking, price tracking, auto-rebook. Adjacent to travel automation. |
| **Sool** | Consumer venture | Conceptual | Emotional operating system. Twin AI that reflects the user — journaling, habits, behavioral tracking, long-term pattern learning. |
| **Sumani** | Consumer venture | Conceptual | Knowledge / intent / systems. Operating system for ideas and taste. Projects → blocks → composable workflows. |

**Architectural distinction:**
- Operational tools stay inside Sunspell, serve Aither primarily, may never go public
- Consumer ventures get their own standalone brands, their own websites, their own go-to-market motions — Sunspell just owns the cap table

---

## 4. Sun OS — Operational Tools for Aither

### 4.1 Sunpull (in progress · Michael)
**Type:** Memory layer
**Purpose:** Captures saves across platforms (LinkedIn, Instagram, forwarded links via SMS) into a Pinterest-style board. Tagged by intent (partnership, prospect, brand ref, tool, post fodder).
**Foundational because:** every downstream tool reads from Sunpull for context. Sundial pulls prospect context from it. Sunreach pulls outbound context. Sunrun pulls reference material.

### 4.2 Sundial (next · spec ready)
**Type:** PM / ops layer
**Purpose:** Slack-only project management. Owns the canonical roadmap + retainer flow + Monday/Friday rhythm + housekeeping. Three tracks:
- Retainer (passive observability + summary production)
- Sunspell/Suncraft (active capacity + debt model, team-decided makeup)
- Housekeeping (recurring ops — subscriptions, AR, renewals with L1/L2 automation)

Replaces the previous Aion PM bot. Salvages transcript pipeline + Slack plumbing from Aion.

### 4.3 Sunspoke (internal) (not started · see consumer section)
**Type:** Communication coaching for Aither managers
**Purpose:** Records and analyzes Aither manager communication patterns. Slack delivery. R&D layer for the consumer Sunspoke product. Used to validate coaching thesis on real users (Aither's own team) before shipping externally.

### 4.4 Sunrun (later · the real moat)
**Type:** Execution engine
**Purpose:** Composable blocks that produce actual deliverables. Encoded taste, personas, rubrics. Powers audit-funnel services, prospect emails, brand moodboards, post drafts.

This is the most defensible tool in Sun OS. Whoever owns Sunrun owns Aither's ability to scale without linearly scaling humans.

### 4.5 Sunreach (later · revenue)
**Type:** Sales layer
**Purpose:** Pipeline tracking, custom outbound per prospect, proposal drafts, follow-up nudges. Directly supports the retainer-count-growth goal.

### 4.6 Sunkeep (urgent after Sundial · accounts)
**Type:** Client retention
**Purpose:** Renewal conversation timing, account health signals, QBR prep.
**Urgency driver:** current retainers end July 31. Without Sunkeep, those retainers won't renew or roll cleanly into new scopes.

### 4.7 Sunbill (later · back office)
**Type:** AR / invoicing
**Purpose:** AR tracking, payment nudges, expense processing. Sundial handles L1 reminders until Sunbill exists (~Q3).

### 4.8 Sunhire (on demand · HR)
**Type:** Candidate pipeline
**Purpose:** Candidate tracking, interview notes. Only builds when actively recruiting. Not a standing tool.

---

## 5. Sunspell Consumer Ventures

These are the consumer products incubated from Aither's pattern recognition. Each will eventually have its own standalone brand, team, and go-to-market.

### 5.1 Sunspoke — in active development (v0 2026, public launch 2027)
Voice-coaching product. Three SKUs: Object (desk sculpture), Wear (pendant), Clip (phone accessory). Shared software platform, three carry contexts.

**Thesis:** a mirror you can live with. Listens only to you.

Full spec: `sunspoke.md`.

### 5.2 Sapour — conceptual
**Domain:** Scent × identity × attraction
**Core ideas:** capture natural scent, translate to profile, generate wearable fragrance, enable scent-based matching.
**Why it's novel:** most novel and defensible of the ventures. Physical + digital + emotional crossover.
**Status:** concept only.

### 5.3 Airon — conceptual
**Domain:** Travel × automation × prediction
**Core:** smart travel concierge. Books refundable flights, tracks prices, auto-rebooks. Future: full travel planning, budget optimization, group travel matchmaking.
**Why it matters:** practical, high-frequency, monetizable. More execution-heavy, less experimental.
**Status:** concept only.

### 5.4 Sool — conceptual
**Domain:** Emotion × identity × AI companionship
**Core:** emotional operating system. "Twin" AI that reflects the user. Journaling (voice or text), habit building, behavioral tracking, simulated conversations, long-term pattern learning.
**Future:** AR presence, deeper emotional modeling, legacy intelligence.
**Why it matters:** deeply personal, high retention potential. Most delicate to execute.
**Status:** concept only. Note: has thematic overlap with Sunspoke Keep (future Sunspoke line); worth reconciling when both are ready for development.

### 5.5 Sumani — conceptual
**Domain:** Knowledge × intent × systems
**Core:** operating system for ideas, taste, and action. Projects, blocks (modular actions like extract/generate/analyze), composable workflows.
**Target:** founders, designers, operators.
**Why it matters:** closest to the founder's externalized brain. Could become a general-purpose thinking OS.
**Status:** concept only. Architecturally shares DNA with Sunrun (internal execution engine) — potential consolidation opportunity.

### Thematic through-line across all ventures
Every Sunspell consumer product translates something *abstract* into something *structured*:
- Scent → Sapour
- Emotion → Sool
- Intent → Sumani
- Travel complexity → Airon
- Communication patterns → Sunspoke

They also all create *new forms of identity*:
- Scent identity
- Emotional identity
- Behavioral identity
- Preference identity
- Communicative identity

**The portfolio thesis:** externalize the interior, then give it back structured. The founder is making bets across every form of human tacit knowledge.

---

## 6. Priority Matrix

### Q2 2026 (now)
- 🟢 Sunpull — ship v1 (Michael continuing)
- 🟡 Sundial — begin build (spec ready)
- 🟡 Sunspoke (consumer v0) — begin proof of concept with founder (Jasmine) using Plaud rework
- 🔵 Sunkeep — spec out, urgent because of July 31 retainer cliff

### Q3 2026
- Sunspoke (consumer) — ship Founder's Edition Object to 20 founders
- Sundial — ship v1
- Sunkeep — ship v1
- Begin Sunrun spec

### Q4 2026 / early 2027
- Sunrun — build core blocks
- Sunreach — build on top of Sunpull + Sunrun
- Sunspoke v1 — begin custom hardware development with Chinese firm

### 2027
- Sunspoke v1 public launch (all three SKUs on custom hardware)
- Sunbill — build
- Potentially: Sool scoping (shares DNA with Sunspoke Keep)

### 2028+
- Sunspoke v2 platform (Pair, Keep, Practice)
- New ventures from the portfolio (Sapour, Airon, Sumani)

---

## 7. Team & Resources

### Founder (Jasmine)
**Allocation:** split between Aither (client-facing), Sunspell (venture direction), Sunspoke (as lead product). ~30% Aither, ~30% Sunspell ops, ~40% Sunspoke when active.

### Michael — Engineering lead (Sunspell)
**Scope:** all operational tools (Sunpull, Sundial, Sunrun, etc.) + Sunspoke consumer software.
**Constraint:** not a hardware engineer. External hardware partners for Sunspoke v1.

### Wayeez — Design Intern (Sunspoke)
**Scope:** research and coordination on Sunspoke — shortlisting fabricators and industrial designers (Jasmine + Aither choose), drafting flow mockups (Aither refines), managing vendor logistics, iterating UX during founder cohort. Intern role supporting the senior design work done by Aither. See `wayeez-brief.md`.

### Aither team
**Scope:** brand system, website, renders, packaging creative for Sunspoke. Opportunity cost accounted inside Sunspell budget.

### Future hires (as needed)
- Hardware program manager (Sunspoke v1 custom build, 2027)
- Industrial designer (contract, Sunspoke Object / Wear v1)
- Privacy lawyer (contract, ongoing)
- Community manager (Sunspoke cohort, late 2026+)

---

## 8. Capital

### Sunspell operating capital (2026)
- Funded by Aither profit distribution + founder capital
- Budget for all Sun OS tools: ~$60-80K total for year (most are low-cost Michael builds)
- Budget for Sunspoke v0: ~$115-180K (see `sunspoke.md`)
- **Total 2026 Sunspell spend: ~$200-300K**

### Sunspoke-specific fundraising
- Friends-and-family round off Founder's Edition traction: $200-400K at $15-20M SAFE cap
- Seed round off v0 data (2027): $2-3M to fund custom hardware + public launch
- Keep Sunspoke legally separate from Sunspell for clean fundraising later

### Other consumer ventures
- Remain concept-only until Sunspoke proves the loop works
- Then each raises its own round as it graduates out of Sunspell

---

## 9. Decision Framework

When a new product idea appears, route it through these filters:

1. **Pattern source:** Was this observed at Aither, or guessed from market research?
   - Aither-observed → promising
   - Market-guessed → skeptical
2. **Category:** Does it serve Aither (operational tool) or external users (consumer venture)?
3. **Fit with portfolio thesis:** Does it translate something abstract into something structured? Does it create a new form of identity?
4. **Leverage on Aither:** Does it make Aither more leveraged, or just add complexity?
5. **Founder conviction:** Would the founder still care about it in 5 years?

Products that pass all five filters enter the portfolio. Products that fail any filter stay conceptual.

---

## 10. Cadence & Review

### Weekly (Aither + Sunspell)
Monday: portfolio status review. What shipped, what's blocked, what's being learned.

### Monthly (Sunspell focus)
- Review each active product's progress against its internal roadmap
- Reallocate engineering time (Michael) across products
- Kill decisions — what should we stop?

### Quarterly (strategy)
- Portfolio review — does the priority matrix still make sense?
- Budget review — are we on track for 2026 spend targets?
- Founder review — which products are pulling at me most?

### Annual
- Strategy offsite (founder + Michael + Wayeez + key Aither leaders)
- Decide which consumer ventures graduate out of Sunspell for standalone development
- Refine Aither ↔ Sunspell loop based on the year's learnings

---

## Appendix — Naming glossary

- **Aither** — design/technology studio; the first engine; the client-facing business
- **Sunspell** — venture lab parent entity; holds all "Sun-" products and future portfolio companies
- **Sun OS** — the collective name for all the tools inside Sunspell
- **Sunspoke** — the first external consumer product from Sunspell; has its own roadmap in `sunspoke.md`

---

**Owner:** Jasmine
**Contributors:** Michael (engineering), Wayeez (design/ops), Aither team (brand)
**Review cadence:** Weekly status, monthly priority, quarterly strategy
