# Sunspoke — Product, Vision, Roadmap

*Consolidated product doc. Covers mission, product family, phased roadmap, hardware, software, brand, team, costs. Companion to `sun-os.md` (which covers the parent venture lab, Sunspell).*

*Version: v1 (sculpture-first sequencing)*
*Last updated: April 2026*
*Status: active — v0 Phase 1 kicking off*

---

## Contents

0. [Mission & Thesis](#0-mission--thesis)
1. [The Three-Product Family](#1-the-three-product-family)
2. [Shared Product Principles](#2-shared-product-principles)
3. [Shared Software Platform](#3-shared-software-platform)
4. [Phased Roadmap (Sculpture-First)](#4-phased-roadmap-sculpture-first)
5. [Hardware Specification](#5-hardware-specification)
6. [Tech Specification — Michael's Build](#6-tech-specification--michaels-build)
7. [UI/UX & Delivery](#7-uiux--delivery)
8. [Brand Spec](#8-brand-spec)
9. [Packaging](#9-packaging)
10. [The 20 Founder Cohort Strategy](#10-the-20-founder-cohort-strategy)
11. [Partnership Pricing Paths](#11-partnership-pricing-paths)
12. ["Hide Plaud" Strategy](#12-hide-plaud-strategy)
13. [Emotional LED — Future Vision](#13-emotional-led--future-vision)
14. [Cost Breakdown](#14-cost-breakdown)
15. [Legal & IP](#15-legal--ip)
16. [Team & Roles](#16-team--roles)
17. [Success Metrics](#17-success-metrics)
18. [Open Decisions](#18-open-decisions)
19. [Risks](#19-risks)

---

## 0. Mission & Thesis

### Mission
**Give every person a quiet mirror — one that knows only them, and helps them become the version of themselves they already wanted to be.**

### Product promise
*Sunspoke listens only to you. And it knows you.*

Not an assistant. Not a gadget. A mirror you can live with.

### Thesis
The wearable AI market is loud, generic, and creepy — it surveils the room, answers questions, interrupts conversations. Sunspoke is the opposite. A device that only processes the wearer's own speech, never interrupts, and delivers reflection in literary rhythms (daily, weekly, monthly, yearly) in the user's own voice.

### Three-year arc
- **Year 1 (2026):** Closed launch with 20 founders. Ship the **Object** (desk sculpture) first — prove the experience.
- **Year 2 (2027):** Public launch on custom hardware. Add **Wear** (pendant) and **Clip** (phone accessory). All three SKUs share one software platform.
- **Year 3 (2028):** Platform expansion — Sunspoke Pair (couples), Sunspoke Keep (legacy), Sunspoke Practice (therapist B2B). Emotional LED ships.

### Million-dollar product standard
Every Sunspoke object must pass this test: *"Would a person who wouldn't usually buy tech pay this much for this, simply because of how it looks, feels, and sits in their life?"*

That is the design brief for every material, finish, packaging, weight, sound, and moment of interaction.

### The target: Oura Ring / Whoop level of execution
**Locked standard (April 2026):** Sunspoke's execution bar is Oura Ring and Whoop. That means:
- Hardware that feels like a premium object on first touch (not a tech gadget)
- Packaging and unboxing that becomes part of the product story — not an afterthought
- Software that surprises users with what it knows about them from day one
- A cohort of users who become unprompted evangelists and investors
- Press coverage that compares us to Oura/Whoop, not Humane or Friend

The explicit ambition: **build a product so good that every person who sees it wants to invest in it or buy one.** The first 20 founders are the first test of this. Their reactions will tell us whether we're at the bar or need another iteration.

### What doesn't make the Oura/Whoop cut
- Any Plaud branding visible anywhere (users or press)
- Any packaging that feels generic
- Any Slack message that feels like a typical SaaS notification
- Any archetype card that looks like a personality quiz result
- Any coaching moment that could have been written by a generic AI tool

---

## 1. The Three-Product Family

Sunspoke is a family of objects sharing one software soul. Each object solves a different **carry context**.

### 1.A — Sunspoke Object (desk sculpture) ★ FIRST TO SHIP
*The art piece. Lives on your desk, nightstand, or bookshelf.*

A small sculptural object, ~60-80mm tall. Designed as a beautiful thing first — the kind of object you'd want on your desk whether it worked or not. Gold, silver, rich color palette (oxidized bronze, ceramic, colored stone inlay).

- **Carry context:** At your workspace or home. Captures your voice during desk work, solo thinking, calls, meetings.
- **Capture mode:** Ambient voice-ID-filtered listening when in the room with the user.
- **Emotional job:** Presence. *"I show up to work, and it shows up with me."*
- **v0 hardware (Founder's Edition):** Plaud NotePin internals inside a sculptural housing designed by an industrial designer (Wayeez-sourced).
- **v1 hardware (2027):** Custom build with larger battery, richer sensor suite.
- **Price (v0 Founder's Edition):** gifted or nominal (see §11 pricing paths).
- **Price (v1 public):** $699-799.

**Reference objects:** Teenage Engineering OP-1, Nomos clocks, Arne Jacobsen desk objects, Japanese netsuke, worry stones in precious materials, Muji aroma diffuser, Moooi small sculptures.

### 1.B — Sunspoke Wear (pendant)
*The jewelry. Worn on your body, visible or hidden.*

A slim rod pendant worn on a chain, cord, or clip. Silver, gold, or blackened. Reads as minimal men's/women's jewelry, not tech.

- **Carry context:** All day, on your body. Meetings, commutes, dinners, gym.
- **Capture mode:** Continuous voice-ID-filtered listening while worn.
- **Emotional job:** Identity signal. *"I'm the kind of person who cares."*
- **v1 hardware (2027):** Custom-built rod (~42×11×7mm, 12-18g, 3 finishes).
- **Price (v1 public):** $499-599.

### 1.C — Sunspoke Clip (phone accessory)
*The ambient companion. Attaches to your phone.*

A MagSafe accessory that snaps onto the back of an iPhone. Sits alongside your phone as you use it. Recharges via MagSafe when the phone charges.

- **Carry context:** Whenever you have your phone — ~14-16 hours/day. Most reliable capture of the three.
- **Capture mode:** Continuous voice-ID-filtered listening while near user.
- **Emotional job:** Practicality. *"It just rides with my phone."*
- **v1 hardware (2027):** Custom build, MagSafe-native charging, premium finish.
- **Price (v1 public):** $349-399.

### Why three, not one
Different humans carry life differently. Some wear jewelry, some don't. Some sit at a desk all day, some are mobile. Three products cover the full spectrum with one software platform. Over time, most users will own more than one.

### Explicitly NOT in the family (yet)
- Ring (Oura owns it, too-hard engineering)
- Earring / in-ear (Apple will open AirPods live audio; v3 consideration)
- Wrist device (Whoop/Apple Watch territory)
- Glasses (Meta territory)

---

## 2. Shared Product Principles

All three products share these seven non-negotiables. Every feature must pass all seven.

1. **It only hears you.** Voice-ID gating/filtering means only the wearer's speech is processed for coaching.
2. **It never interrupts.** Zero real-time notifications unless explicitly opted-in per goal. Pull over push.
3. **Four tempos.** Daily evening recap. Weekly Read + archetype. Monthly retrospective. Yearly artifact.
4. **Specificity over generality.** "You interrupt women 3x more than men" beats "you sometimes interrupt." Every coaching moment references exact quote, time, or count.
5. **Literary, not analytical.** Prose, audio, letters, artifacts. No dashboards as primary interface.
6. **Earned trust, not default trust.** Week 1 is listening only, no coaching. All new features launch opt-in by default.
7. **Object over gadget.** The "million-dollar test" — would a person who doesn't usually buy tech pay this for this?

---

## 3. Shared Software Platform

All three products run on one shared backend:

- **Voice-ID enrollment** — 30-second voice sample at onboarding creates a speaker embedding per user
- **Capture pipeline** — audio → transcription → speaker diarization → filter to wearer-only → stored in user's private archive
- **Coaching layer** — Claude API + custom prompts generate daily recap, weekly Read, monthly retrospective, yearly artifact
- **Archetype system** — 10-12 archetypes (*The Diplomat, The Interrupter, The Softener, The Over-Explainer, The Anchor*, etc.). User's archetype revealed in Week 1 Read, evolves quarterly.
- **Delivery** — v0 via Slack DM. v1 via native iOS/Android app.
- **Data ownership** — users own their data, can export or delete anytime, designate a legacy contact.

Hardware changes across products — software does not. This is the moat and the economic engine.

---

## 4. Phased Roadmap (Sculpture-First)

### Phase 1 — Jasmine's Month (Weeks 1-4) · Proof of concept
**Goal:** validate that the coaching software is uncanny on a single sculpture prototype, before committing to a designer or mass hardware.

**Sequence:**
1. **Buy 1 Plaud NotePin** (~$169)
2. **Wayeez sources a jeweler/fabricator** to rework 1 unit into an initial sculptural form (simpler than final — just enough to be an acceptable desk object for Jasmine's testing). ~2 weeks, $200-500 for this rough v1.
3. **Michael builds the full coaching software stack** on this one unit (see §6 tech spec)
4. **Jasmine wears / lives with / uses it for 1 month** — daily recaps, weekly Reads, archetype reveal
5. Goal: after 4 weeks, answer *"does the coaching feel uncanny?"* honestly.
   - If yes → greenlight Phase 2
   - If no → iterate on coaching quality another 2-4 weeks before committing to designer work

**Ownership:**
- Jasmine: primary user, feedback loop
- Michael: full software build
- Wayeez: sources prototype jeweler, handles Plaud rework
- Aither: brand system and initial website work in parallel

### Phase 2 — Final Object Design (Weeks 5-10) · Wayeez leads
**Goal:** design and build the **final sculptural object** — the one that actually goes to 20 founders.

**Sequence:**
1. **Wayeez finds the industrial designer** for the final Object form. This is not the Phase 1 jeweler — this is a proper ID person capable of creating a real sculpture.
2. **Collaborate on sculptural form** — shape, materials, finish options (gold, silver, bronze, ceramic), weight, proportion
3. **Design the unboxing / packaging** — box, internal tray, signature, letter, cord/chain options for future Wear use
4. **Produce 20 final Founder's Edition Objects** — numbered 01-20, each hand-finished in one of three finishes selected by the founder
5. **Wayeez also designs the flows** in parallel (see §7) — onboarding conversation, daily recap layout, weekly Read format, archetype card visual. Michael implements.

**Ownership:**
- Wayeez: industrial designer sourcing, final Object design direction, packaging/box design, UX flow design, ongoing iteration (this is her primary scope — see `wayeez-brief.md`)
- Michael: tech spec updates based on final hardware, multi-user onboarding, flow implementation
- Aither: brand assets for final launch (website, renders, IG if we open one)
- Jasmine: founder statement, outreach copy, commission the designer

### Phase 3 — Founder Cohort (Weeks 10-14) · Ship to 20
**Goal:** 20 founders receive the final Object, use it for 30 days, publish feedback.

**Sequence:**
1. Send outreach to the 20 (see §10 — outreach sequence)
2. Ship Founder's Edition Objects with hand-signed letters, chain/cord options, presentation box
3. Onboard each founder to the Slack coaching pipeline
4. **Day 30 milestone:** LinkedIn post + keep-or-return decision (see §11 pricing paths)
5. Weekly feedback calls throughout Month 1

**Ownership:**
- Jasmine: outreach, weekly calls, LinkedIn post coordination
- Michael: pipeline health per user, multi-tenant hardening
- Wayeez: continuing UX improvements based on founder feedback (Month 2 of her engagement)

### Phase 4 — Feedback & Iteration (Months 3-4)
**Goal:** Process learnings from 20 founders, improve coaching, plan additions of Wear and Clip.

- Collect usage data across all 20
- Surface coaching misses, archetype accuracy, pattern detection gaps
- Iterate prompts + delivery flows based on feedback
- Decide: add Wear and Clip via Plaud-rework, or wait for custom hardware?
- Begin industrial designer search for Wear (pendant rod) if continuing Plaud-era
- Begin friends-and-family round ($200-400K) off demonstrated traction

### Phase 5 — Wear + Clip Addition (Months 4-9)
**Goal:** Expand product family to three SKUs while still on Plaud-era hardware.

- Wear: rod pendant form via additional industrial designer work (~$30-50K design + production)
- Clip: MagSafe accessory form (~$40-60K design + production)
- Test batch of 30-50 users per new SKU (some existing Wear wearers cross-buy; new testers for each SKU)
- Begin engagement with Chinese hardware firm for Phase 6 custom build

### Phase 6 — Custom Hardware (Months 9-18) · Chinese firm
**Goal:** Ship public v1 on fully custom hardware. No more Plaud.

- Engage Chinese manufacturing firm (Phase 4 hire: hardware program manager)
- Design and prototype all three SKUs on custom PCBs
- Include RGB LED driver on custom PCB (for future emotional LED feature)
- FCC, CE, Bluetooth SIG certifications
- First production run: 500-1,000 units per SKU
- **Public launch: Q2-Q3 2027**

### Phase 7 — Emotional LED Ships (Late 2027 / Early 2028)
See §13.

### Phase 8 — Platform Expansion (2028)
- Sunspoke Pair (couples)
- Sunspoke Keep (legacy / memory artifact)
- Sunspoke Practice (therapist B2B)

---

## 5. Hardware Specification

### v0 — Plaud-rework across all three form factors

| SKU | Base hardware | Rework scope | Time | Per-unit cost |
|---|---|---|---|---|
| Object | Plaud NotePin internals | Industrial designer creates sculptural housing, hand-finished in gold/silver/bronze/etc. | 4-8 weeks for design + 2-3 weeks production | $300-600/unit |
| Wear (Phase 5) | Plaud NotePin internals | Rod-shaped plated housing, pendant bail | 6-8 weeks | $200-400/unit |
| Clip (Phase 5) | Plaud NotePin internals | MagSafe puck housing | 6-8 weeks | $250-450/unit |

### Rework process (per unit)
1. Disassemble Plaud NotePin (battery safety critical)
2. Remove existing enclosure
3. Install internals into new housing (Object = sculptural form, Wear = rod, Clip = MagSafe puck)
4. Hand-finish the exterior (plating, patination, polishing)
5. Engrave Sunspoke branding + serial number on a subtle surface
6. Full QC: audio capture, Bluetooth pairing, battery cycle
7. Package

### Finish options (at launch, per SKU)
- **Object:** oxidized bronze, sterling silver, 18k gold plate, optional stone inlay (onyx, jade, tiger's eye)
- **Wear:** sterling silver, 18k gold plate, blackened silver
- **Clip:** brushed titanium, 18k gold plate, blackened steel

Each Founder's Edition buyer chooses one finish.

### v1 Custom Hardware (2027)
- Custom PCB designed specifically for Sunspoke's voice-ID-on-device architecture
- Includes RGB LED driver (for future Emotional LED feature)
- MEMS mic array for improved audio quality
- BLE 5.3+
- Inductive/MagSafe charging
- Custom battery sized per SKU
- All three SKUs manufactured via Chinese firm partnership

---

## 6. Tech Specification — Michael's Build

Michael owns the entire software stack across all three SKUs. The tech spec will be updated continuously as we learn — here are the current requirements.

### v0 Stack

```
[Plaud NotePin inside Sunspoke housing]
    ↓ records audio (Phase 1 path TBD per §6.3)
[Transcript ingestion pipeline]
    ↓
[Michael's Backend]
    ├── Speaker diarization (Pyannote)
    ├── Voice-ID filter (only wearer's speech)
    ├── Pattern analysis + context accumulation
    ├── Claude API coaching calls
    ├── Archetype classification
    └── Artifact generation
    ↓
[Slack Bot — Sunspoke]
    ├── Daily DMs
    ├── Weekly Read with archetype card
    ├── Monthly retrospective
    └── Onboarding + goal management
```

### Technology choices
- **Language:** Python 3.11+
- **LLM:** Claude API (Opus for weekly Reads, Sonnet for daily recaps)
- **Diarization:** Pyannote-audio (open source)
- **Transcription:** Plaud's if accessible, else self-hosted Whisper
- **Database:** Postgres
- **Hosting:** Fly.io or Railway
- **Slack:** slack-bolt (Python)

### v0 Build timeline

**Phase 1 — Proof of concept (Weeks 1-4, Jasmine as sole user):**
- Week 1: Plaud API investigation, project setup (see §6.3)
- Week 2: Transcript pipeline + speaker diarization + voice-ID filter
- Week 3: Coaching pipeline (prompts, archetype classification, pattern detection)
- Week 4: Slack bot + onboarding + end-to-end demo

**Phase 2-3 — Scale to 20 (Weeks 5-14):**
- Multi-tenant hardening
- Per-user voice profiles, goals, delivery times
- Cohort onboarding
- Weekly iteration based on user feedback
- **Ongoing collaboration with Wayeez** on UX flow improvements

### Tech spec is a living document
Michael **updates the tech spec continuously** (in `sunspoke.md` or in a sub-doc he maintains). Don't treat the spec as locked — expect new sections, changed stack choices, and refined data flows as the first month of real use reveals what's needed.

### 6.3 Data pipeline fallback ladder
Biggest technical risk: Plaud may or may not have a usable API. Five paths ranked by effort vs. reliability:

1. **Plaud official export** — 1-2 days if available. Look for this first.
2. **Web dashboard scraping** — 3-5 days. Moderate ToS risk at small scale.
3. **Mobile app traffic proxy (mitmproxy)** — 3-5 days. High reliability. Uses Plaud's own API endpoints.
4. **Direct BLE connection to pendant** — 1-2 weeks. Highest reliability. Zero ToS risk. Reverse-engineer BLE services, talk to the device directly. Transcribe independently with Whisper.
5. **Phone-as-microphone fallback** — 1 week. 100% reliable. Custom iOS app uses iPhone mic; Object becomes decorative. Use only if Paths 1-4 all fail.

**Week 1 deliverable from Michael:** One-page decision doc — *"We are using Path X. Week 2 timeline: Y. Risks: Z."*

### 6.4 "Hide Plaud" software requirements
- All user-facing UI uses only Sunspoke branding — never reference Plaud
- If firmware allows, rename BLE advertising name from "Plaud" to "Sunspoke"
- Users interact via Slack bot, not Plaud's app
- Hosting, email, support all on Sunspoke-owned infrastructure

### 6.5 Open technical questions for Week 1
Michael answers each by end of Week 1:
1. Does Plaud have a public or enterprise API?
2. Can Bluetooth device name be renamed via firmware?
3. What's Plaud's data retention policy in their ToS?
4. Is Plaud's transcript accuracy acceptable vs. self-hosted Whisper?
5. Does Plaud mark speaker turns in transcripts?
6. What's the on-device audio file format?
7. Does the pendant sync-and-delete, or retain files?

### 6.6 Future hardware support
When custom hardware ships in Phase 6, Michael's backend abstracts hardware differences at the firmware/BLE layer. One backend serves all three SKUs.

---

## 7. UI/UX & Delivery

### v0 — Slack is the interface
All coaching lives in Slack. No iOS app for v0. This is intentional — Slack is where the founder cohort already spends their day.

### Three Slack delivery surfaces

**1. Daily evening message (8pm default, user-configurable)**
- DM from Sunspoke bot
- 2-3 paragraphs of written summary
- 2-minute audio recap (playable in Slack)
- Connection to current goal
- Optional reflection prompt

**2. Weekly Read (Sunday evening, user-configurable)**
- Longer DM with archetype card (image attachment)
- 5-7 paragraphs of observed patterns with direct quotes and timestamps
- 3 "specificity cards" — screenshot-worthy moments
- Proposed goal refinement for next week
- 3-minute audio version

**3. Monthly retrospective (Day 30, 60, 90...)**
- Archetype evolution
- Narrative progress vs. goal
- Recommendation: evolve, swap, commit

### Onboarding flow (Day 1 setup, ~5 min)
1. Slack bot welcome with founder's number ("You are Founder's Edition 07")
2. Four questions: name, pronouns, role, one communication frustration
3. Voice enrollment: 30-second reading
4. "For the next 7 days I'm just listening. On [date] your first reading arrives."
5. Set evening delivery time

### Flow design ownership
**Wayeez designs all Slack conversation flows, visual artifacts, and UX improvements.** Michael implements.

This includes:
- Onboarding conversation copy and cadence
- Daily recap visual layout
- Weekly Read format + archetype card visual design
- Slash commands (`/sunspoke pause`, `/sunspoke goal`, `/sunspoke note`)
- Tone of voice across all bot interactions
- Iteration based on founder feedback (Month 2 of Wayeez's engagement)

### v1 native app (2027)
When custom hardware ships, port the Slack experience to iOS + Android with richer visual design. Same core flows, native visual execution.

---

## 8. Brand Spec

### Aesthetic
**Object, not gadget. Heirloom, not wearable. Mirror, not assistant.**

### Reference brands
- **Aesop** — editorial voice, quiet confidence, long-form copy
- **Le Gramme** — numbered metal objects, weight-as-identity
- **Nomos Glashütte / Ming Watches** — minimalist premium craft
- **The School of Life** — emotional/reflective voice
- **Kinfolk (early)** — photography, soft neutrals
- **Teenage Engineering** — industrial minimalism with personality
- **Japanese notebook / Muji** — restraint, negative space

### Anti-references
- Humane AI Pin (too technological)
- Rabbit R1 (too gimmicky)
- Friend pendant (too childlike)
- Limitless (too commodity)
- Duolingo (too gamified)
- Calm (too generic-wellness)

### Color palette
- **Primary:** warm cream/bone, deep charcoal/near-black
- **Accent:** brushed gold, oxidized silver, aged brass
- **Never:** bright saturated colors, gradient tech colors, neon

### Typography
- **Display:** warm serif (Fraunces, GT Sectra, Tiempos Headline)
- **Body:** clean sans or transitional serif (Söhne, Neue Haas Grotesk, Lyon Text)
- **Accent:** hand-finished monogram for numbering

### Voice
- Warm, specific, observational
- Specificity as intimacy
- No wellness-speak ("journey," "mindfulness," "authentic self")
- No tech-speak ("AI," "algorithm," "smart")
- References: Alain de Botton, Anne Lamott, NYT longform

### Aither's brand deliverables
- Brand system (logo, typography, color palette)
- Website (editorial long-scroll, password-gated)
- Founder's Edition renders in all finishes
- IG assets (when opened, post-launch)
- Packaging creative direction

---

## 9. Packaging

The unboxing is part of the product. Budget $100-200 per unit.

### What's in the box
1. Outer wooden box (heavy paperboard acceptable if sculptural) with Sunspoke monogram
2. Inner linen- or felt-lined tray with recessed cavity holding the Object
3. Hand-signed letter from the founder in a matched envelope
4. Cord/chain options in a secondary compartment (for future Wear use + display flexibility)
5. Single instruction card: *"Wear it. We're listening."* with Slack invite link
6. Hidden drawer beneath tray: magnetic charging puck (unbranded — see §12)

### Sourcing path
Wayeez owns packaging sourcing (see `wayeez-brief.md`):
- **Recommended:** Etsy or local artisan woodworker + bespoke print shop for letter stationery (Jukebox Print, Moo Luxe, local letterpress)
- **Alternative:** customize existing luxury jewelry box supplier
- Budget: $100-200/unit × 20 = $2,000-4,000

### Design references
- Aesop packaging (restraint, weight, natural materials)
- Hermès boxes (ceremonial opening)
- Japanese craft packaging (honesty of materials)

---

## 10. The 20 Founder Cohort Strategy

### Current state
~20 successful founders have expressed interest through conversation. Some are household names, all well-networked. They are the acquisition wedge for the entire company.

### Realistic conversion expectations
- 6-10 convert (commit to Founder's Edition)
- 3-5 ghost-read and don't respond
- 2-3 reply but don't commit
- 1-2 introduce 5+ friends or ask about investing

### Outreach sequence
**Message 1 — The Personal Invite (Week 1 of Phase 2)**
- From Jasmine personally, hand-typed per recipient
- References a specific past conversation
- Link to password-gated site
- Explicit ask (see pricing paths §11)
- 14-day deadline

**Message 2 — Follow-up (Week 2)**
- Lighter tone for non-responders
- Offer a quick call

**Message 3 — Close (Week 3)**
- Final nudge, with early social proof if available

### Monthly founder's call (post-shipment)
- 60 minutes, monthly, group format, hosted by Jasmine
- Topics: product progress, coaching insights, Q&A
- Becomes seed of a "Sunspoke Circle" community in v1

---

## 11. Partnership Pricing Paths

Two viable pricing paths for the 20 founders. Both valid; founder confirms one when outreach launches.

### Path A — Pure Gift
20 founders receive Sunspoke Object as a **gift**. Zero dollars exchanged.

**They receive:** Founder's Edition Object (numbered 01-20, chosen finish), lifetime subscription, Founder's Circle (monthly call, private Slack), first-access to future products.

**They commit to:** one LinkedIn post in Weeks 3-4, weekly 20-min feedback calls during Month 1, permission to quote feedback, optional quarterly content thereafter.

**Strengths:** zero friction, permanent loyalty, lifelong ambassadors, maximum evangelism.
**Weaknesses:** $0 v0 revenue, must fund full $115-180K build from capital/round.

### Path B — Try for a Month, Keep or Return
20 founders receive Sunspoke Object on loan for 30 days.

**They commit to:** LinkedIn post in Weeks 3-4 + weekly feedback during Month 1.

**At Day 30:**
- **Keep:** $499 to retain Founder's Edition + lifetime sub + Circle membership
- **Return:** No charge. Hardware returns to pipeline for Wave 2. Keeps Circle status, reserves numbered slot on future products.

**Strengths:** revenue upside ($3,500-7,000 at 50-70% conversion), hardware recovered for Wave 2, clear decision point.
**Weaknesses:** Day 30 "keep or return" feels slightly transactional, some churn, more operational overhead.

### Decision framework
Path A wins on pure evangelism and relationship quality. Path B wins on capital efficiency and hardware reuse.

### Locked decision (April 2026): UX-gated pricing path
The pricing path will be determined by the **Phase 1 UX quality**:
- If the coaching UX is *clearly uncanny* by end of Jasmine's month of testing → **Path B (Try-and-Keep)**. The product is good enough to ask founders to pay to retain it.
- If the coaching UX is *still rough or inconsistent* by end of Phase 1 → **Path A (Pure Gift)**. Accept $0 v0 revenue in exchange for maximum generosity and relationship quality.

This means we don't commit to one path until Week 4-5. Outreach emails are written with two branches; we pick the branch when Jasmine can answer honestly whether the coaching has earned the ask.

---

## 12. "Hide Plaud" Strategy

### Why
We're using Plaud internals under Sunspoke branding. For a 20-user closed beta, this is standard v0 practice. Custom hardware (Phase 6) resolves it permanently.

### Three levels of concealment

**Cosmetic (easy, high impact):**
- Rework enclosure (plating, engraving, sculptural housing)
- Remove all Plaud text and markings
- Add Sunspoke monogram + serial number
- Custom packaging with no Plaud references
- Reaches 95% of users

**Functional (medium effort):**
- All coaching delivery via Slack — users never open Plaud's app
- Michael's backend pulls transcripts invisibly from Plaud's cloud
- Setup docs don't mention Plaud
- Bluetooth device name shows as "Sunspoke" if firmware allows
- Reaches 98% concealment

**Impossible to hide:**
- FCC ID is public record, maps to Plaud's filing
- Firmware identifiers, SoC model, PCB markings
- Sophisticated founders who open the device will figure it out

### The ready answer
If a founder asks directly, *"is this a Plaud?"*

> *"We're using hardware from a validated third-party supplier for v0 while we finalize our own. Every component in the first generation is the best available today. The software, the coaching, the brand, the design — all ours. Custom hardware ships in 2027, and every Founder's Edition owner gets a free upgrade when it does."*

Founders respect resourcefulness more than performative hardware pride.

### ToS line in Legal copy
*"Sunspoke v0 is built on validated third-party voice capture hardware. Future generations will be built on proprietary hardware developed in-house."*

### NDAs
Wayeez's jeweler and Wayeez's designer both sign NDAs prohibiting mention of Plaud or the base hardware.

---

## 13. Emotional LED — Future Vision

### The vision
The Sunspoke Object (and later Wear, Clip) embed a quiet LED that reflects the user's state in color. Subtle. Almost imperceptible unless you look for it. When you notice it, it's a mirror.

### The core principle: user-configurable
**The user decides what the LED does.** Sunspoke ships LED behavior as a settings option, not a fixed feature. Defaults are off; users opt in to whatever configuration feels useful to them.

### Possible LED modes (user selects one, combination, or none)

**Reflection mode — passive, ambient**
The device detects emotional signals in the wearer's voice (pace, pitch variance, tonality, silence patterns). When a state is detected, the LED glows a color:
- **Warm gold** — calm, grounded, present
- **Cool blue** — reflective, contemplative
- **Dim red** — agitated, stressed (subtle)
- **Green pulse** — aligned with current goal

Colors chosen so that even if someone else notices, the meaning isn't obvious.

**Goal Signal mode — active, rare**
When a goal-relevant pattern is detected (interrupted someone, hedged, dodged a hard conversation), the LED pulses once briefly in the goal color. A tap on the shoulder, not a lecture.

**Custom color-to-behavior mapping**
User can map any detected signal to any color in their personal palette. Example: a user might prefer gold for "speaking more than usual today" or blue for "haven't spoken in 2 hours — maybe time to reach out." Freedom to configure.

**No LED mode (default)**
User can disable entirely. Object is still beautiful without it. Important that the hardware is never "incomplete without the feature."

### Why user-configurable
Locking a single interpretation (mood ring vs. goal nudge) risks the wrong fit for half the users. Making it a settings surface means each user builds the coaching experience that actually serves them. Also de-risks launch — we don't need one unified "correct" behavior to ship.

### Why it matters
- Makes the invisible visible — turns speech patterns into quiet awareness
- Differentiates from every competitor — no wearable AI has done this subtly
- Becomes Sunspoke's iconic "tell" in press, social media, word-of-mouth

### When it ships
- **Not v0** (Plaud hardware doesn't support LED control)
- **Engineered into v1 custom hardware** (RGB LED driver on the custom PCB — even if we don't ship the feature, we retain the option)
- **Public launch target: v1.5 or v2** (late 2027 / early 2028)

### Design principles
- Brightness 5-10% of max — visible only when looked for
- No flashing, no pulse patterns visible across a room
- Respects sleep — auto-off at user-chosen hours
- User-customizable color palette
- Opt-in only at launch

### Engineering ask for v1 hardware spec (Phase 6)
Include RGB LED driver capability on the custom PCB. Firmware ability to control brightness, color, and pulse patterns. Even if we don't ship the feature at v1 launch, the option must be preserved.

---

## 14. Cost Breakdown

### v0 launch budget (2026)

| Category | Cost | Notes |
|---|---|---|
| Plaud hardware (20 units + 5 spare) | $4,200 | $169 × 25 |
| Phase 1 jeweler prototype (1 unit) | $200-500 | Quick rework for Jasmine's test |
| Industrial designer — final Object | $20-40K | Design + prototyping |
| Production for 20 final Objects | $6,000-12,000 | $300-600/unit × 20 |
| Packaging (wooden boxes, letters, etc.) | $2,000-4,000 | $100-200/unit × 20 |
| Aither brand + website + renders | $30-50K | Opportunity cost or contractor |
| Michael engineering (v0 build) | $30-45K | 6-8 weeks focused |
| Wayeez engagement (2-3 months) | $15-30K | Design direction + sourcing + ongoing UX |
| Privacy lawyer | $15-25K | Voice-ID architecture + ToS |
| Provisional patent | $15-25K | Software claims |
| Incorporation (Delaware C-Corp) | $2-5K | Clerky or Stripe Atlas |
| Founder outreach + comms | $2-3K | |
| Tools (Stripe, Webflow, Claude API) | $1-2K | First 3 months |
| Contingency | $10K | |
| **v0 total** | **$150-250K** | Broader range reflects new design-led scope |

### v0 revenue offset

- **Path A (Gift):** $0
- **Path B (Try and Keep):** $3,500-7,000 from Day 30 conversions

### Fundraising — DEFERRED through v0
**Locked decision (April 2026):** Do not raise during v0. Build as far as possible with founder capital + Aither profit distribution to maintain maximum leverage and ownership.

- **v0 funded by:** founder + Aither profit distribution (~$115-180K)
- **Friends-and-family round:** deferred until Phase 5 or Phase 6 — raise when we need capital for Wear/Clip expansion or custom hardware, not before
- **Seed round:** raised when v0 + Phase 5 data demonstrably justify Phase 6 custom hardware + public launch (~Month 9-12)
- **Rationale:** Every month we build before raising = better cap table, better terms, higher conviction from investors. Founder's capital is the cheapest capital we'll ever have.

### v1 budget (2027)
- Custom hardware development: $300-500K
- Scale manufacturing + production: $100-150K
- iOS/Android app build: $80-150K
- Marketing + PR launch: $50-100K
- **v1 total: $530-900K** (funded by seed round raised off v0 data)

---

## 15. Legal & IP

### Corporate structure
- Delaware C-Corp (for future fundraising)
- Setup via Clerky or Stripe Atlas (~$2-5K)
- Incorporate Week 1 before deposits/funding

### Provisional patent (within 60 days of v0 ship)
- Cover voice-ID coaching software architecture
- Filter-before-analysis approach
- Archetype classification system
- Pattern detection methods
- $15-25K through Wilson Sonsini, Fenwick, or Cooley
- Refile with v1 custom hardware to add hardware claims

### Privacy architecture review (lawyer ask)
1. Where audio is processed and stored (Plaud cloud, Michael's backend, phone)
2. Data retention policy (keep forever, user-controlled)
3. Legacy contact mechanism
4. Two-party consent states — how addressed in ToS and onboarding
5. Right to export, delete, portability

### ToS v0 requirements
- Hardware source disclosure (the "validated third-party" line)
- Audio capture and processing disclosure
- Voice-ID filtering explanation
- Two-party consent warning
- Data retention policy
- Legacy contact flow
- Lifetime subscription terms
- Warranty disclaimers

### Trademark filings
- "Sunspoke" (consumer product)
- "Sunspell" (parent venture)
- ~$1-2K each, ~9 months to register

---

## 16. Team & Roles

### Founder — Jasmine
- Strategy, founder statement, outreach, cohort relationships
- Brand direction review
- Final decisions on open items
- ~40% of time during v0

### Michael — Engineering Lead
- Owns all software: Plaud ingestion, coaching pipeline, Slack bot
- Updates tech spec continuously as learnings emerge
- Interface for future custom hardware (Phase 6)
- Budget: $15-20K/mo for 2-3 months Phase 1-3, then ongoing

### Wayeez — Design & Sourcing Lead
- Sources Phase 1 jeweler for Jasmine's initial prototype
- Sources final industrial designer (Phase 2)
- Designs all UX/UI flows (onboarding, daily, weekly, archetype visuals)
- Packaging / box design
- Continuous improvement over first 2 months
- Budget: $15K/mo × 2-3 months = $30-45K
- **Full brief:** `wayeez-brief.md`

### Aither — Brand + Design
- Brand system, website, renders, IG creative, packaging art direction
- Functions as in-house creative
- Opportunity cost: $30-50K of Aither client capacity

### Jeweler (Phase 1, Wayeez-sourced)
- Quick Plaud rework for Jasmine's prototype Object
- NDA-protected

### Industrial Designer (Phase 2, Wayeez-sourced)
- Final Object form design
- 4-8 weeks design + prototyping
- NDA-protected

### Privacy Lawyer (contract)
- Voice-ID architecture review, ToS, privacy policy
- $15-25K

### Patent Attorney (contract)
- Provisional patent filing
- $15-25K

---

## 17. Success Metrics

### v0 success (Phase 3 → Phase 4)
- ≥6 of 20 commit (Path A) OR ≥6 convert at Day 30 (Path B)
- 100% of 20 Objects shipped by Week 14
- ≥70% actively engaged at Month 3
- ≥3 "uncanny" coaching moments per founder reported
- ≥12 LinkedIn posts by Week 8 (cohort evangelism)

### v1 readiness (Month 9-12)
- ≥50% retention at 6-month mark
- 180+ days of coaching data per active user
- Custom hardware spec locked
- Seed round raised off data

### v1 launch (Month 18-24)
- 1,000+ units shipped in first production run across three SKUs
- >50% Month-6 retention
- 5+ major press hits
- Cross-SKU ownership >20%

### North star
**Sunspoke becomes the first company that made wearable AI feel like a gift, not a tool.**

---

## 18. Decisions — Locked (April 2026)

Previously-open items now resolved:

1. **Pricing path for the 20 — UX-gated.** Decision deferred to Week 4-5 of Phase 1. If the coaching feels uncanny → Path B (Try-and-Keep at $499). If it needs more work → Path A (Pure Gift). Outreach emails are written with two branches; we commit when Jasmine can honestly answer the quality question. See §11.

2. **Public launch pricing across three SKUs** (Object $699-799, Wear $499-599, Clip $349-399) — confirmed as directional. Final pricing locked at public launch based on production costs + market research.

3. **Founder's origin story — captured.** See `founder-statement.md` for the drafted manifesto derived from the founder's own words: *"I want to be a better leader, better communicator. The day-to-day grind holds me back. I know my strengths; my gaps are unknown. A coach can't work with me in real time."*

4. **Fundraising — deferred through v0.** Build as long as possible on founder capital + Aither profit. Raise only when launch demands it. Friends-and-family round re-enters consideration at Phase 5 or Phase 6. See §14.

5. **Emotional LED — user-configurable in settings.** Not a fixed feature. Each user decides what the LED does for them (or turns it off entirely). See §13.

6. **Million-dollar product reference anchors — Oura Ring and Whoop level of execution.** See §0. Surprise people. Make every viewer want to invest or buy.

7. **Product name at public launch — Sunspoke.** Keep through v1. Revisit at v2 if learnings suggest a different consumer brand.

### Still open (require founder input later)

8. **Founder statement final voice** — draft lives in `founder-statement.md`. Founder edits it to match her exact voice before it goes on the website.

9. **Archetype names and count** — 10-12 archetypes to be designed by Wayeez + copywriter. Drafted list in §4 of historical PRD; to be finalized during Phase 2 flow design.

10. **The 20 founders — final list** — who exactly are these 20 people? Jasmine curates list with personal notes per recipient before outreach launches.

---

## 19. Risks

| Risk | Likelihood | Impact | Mitigation |
|---|---|---|---|
| Phase 1 coaching quality is mediocre | Medium | Critical | Explicit go/no-go gate at Week 4 before committing designer fees |
| Plaud API inaccessible | Medium | High | Five-path fallback ladder in §6.3 |
| Phase 1 jeweler's prototype looks cheap | Medium | Medium | Budget for 2-3 rework attempts; Wayeez has final approval |
| Final industrial designer costs run over | High | Medium | Three quotes, contingency budget, phased milestones |
| 20 founders don't post on LinkedIn | Medium | Medium | Written ambassador contract with posting deadline; monthly follow-ups |
| Two-party consent legal challenge | Low | High | Privacy lawyer review pre-ship |
| Plaud identifies rework, sends C&D | Low | Medium | Closed 20-user beta, NDAs, "validated third-party" ToS language |
| Custom hardware dev (Phase 6) overruns | High | High | Three engineering quotes, contingency, phased milestones |
| OpenAI + Ive launch crushes v0 launch window | Low | Medium | Ship Founder's Edition before their launch; own coaching vertical they won't enter |
| Wayeez bandwidth limited across all her responsibilities | Medium | High | Clear scope in `wayeez-brief.md`; weekly check-ins; don't add scope without removing scope |

---

## Appendix — Decisions Locked In

Don't re-litigate:

- **Product name:** Sunspoke (working name, revisited at v1 if needed)
- **Parent company:** Sunspell (venture lab)
- **v0 hardware approach:** Plaud NotePin rework, sculptural housing for Object first SKU
- **v0 sequencing:** Object first (Weeks 1-14), Wear and Clip in Phase 5 (Months 4-9)
- **v0 software delivery:** Slack-first, no iOS app until v1
- **Cohort strategy:** Closed 20-founder invite-only
- **Positioning claim for v0:** "Only coaches you on what you said" (not "only hears you" — reserved for v1 with on-device voice-ID)
- **Brand direction:** jewelry/object aesthetic, not gadget
- **Design lead:** Wayeez (sourcing + flows + iteration)
- **Engineering lead:** Michael (full software stack, continuously updated tech spec)
- **Brand + website lead:** Aither

---

**Owner:** Jasmine
**Design lead:** Wayeez
**Engineering lead:** Michael
**Brand:** Aither
**Review cadence:** Weekly during Phase 1-3, monthly thereafter
