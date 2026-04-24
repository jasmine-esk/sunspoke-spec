# Sunspoke — Product Requirements Document (PRD)

*Sits alongside the master spec (execution). This PRD defines what we're building, why, for whom, and at what quality bar. Companion to `sunspoke-master-spec.md`.*

*Version: v1 draft*
*Last updated: April 2026*
*Status: draft, pending founder confirmation on six open questions (see §14)*

---

## 0. Document purpose

The master spec tells the team *how* we ship. This PRD tells the team *what* we're building and *why it matters*. The PRD is the north star; the master spec is the route.

Every decision in execution must trace back to a principle in this PRD. Every decision in this PRD must trace back to the mission in §1.

---

## 1. Vision

### Mission
**To give every person a quiet mirror — one that knows only them, and helps them become the version of themselves they already wanted to be.**

### Product promise
*Sunspoke listens only to you. And it knows you.*

Not an assistant. Not a gadget. A mirror you can live with.

### The three-year arc
- **Year 1 (2026):** Closed launch with 20 founders. One product (the Wear pendant, Plaud-reworked). Prove the coaching experience is uncanny.
- **Year 2 (2027):** Public launch on custom hardware. Introduce the Object (desk sculpture) and the Phone accessory as second and third SKUs. All three products share one software platform.
- **Year 3 (2028):** Platform expansion — Sunspoke Pair (couples), Sunspoke Keep (legacy memory artifact), Sunspoke Practice (therapist B2B). Emotional LED ships. Sunspoke becomes a $100M company structure, not a $10M product.

### Million-dollar product standard
Every Sunspoke object must pass this test: *"Would a person who wouldn't usually buy tech pay this much for this, simply because of how it looks, feels, and sits in their life?"*

That test is the design brief for every material, finish, packaging, weight, sound, and moment of interaction.

---

## 2. Market & Users

### The problem
Smart people already know their communication blind spots. They hedge in hard conversations. They interrupt. They over-explain. They go quiet when they should speak up. But they have no mirror — no way to see the pattern without a human coach, and no human coach available daily.

The existing "wearable AI" market is loud, generic, and creepy: Humane, Friend, Limitless, Plaud, OpenAI's Gumdrop. They surveil the room, answer questions, interrupt conversations. None of them reflect the *wearer* back to themselves.

### The opportunity
Build the opposite. A device that only listens to you, never interrupts, and delivers reflection in literary rhythms — once a day, once a week, once a month — in your own voice.

The market is big enough: Oura ($300 ring, ~$500M ARR), Whoop ($30/mo, ~$400M ARR), Aesop (~$500M revenue on the premise that *objects can be meaningful*). Sunspoke fits in this emotional quadrant.

### Primary users (v0-v1)
1. **Founders, VPs, senior operators** — careers compound on how they communicate
2. **Therapists, coaches, clinicians** — trained to analyze communication, have no tool for their own
3. **Adults doing intentional self-work** — people already journaling, in therapy, reading self-work books

### Secondary users (v2+)
4. Couples in high-conflict or intentional-growth relationships (Sunspoke Pair)
5. Adult children capturing aging parents' voices (Sunspoke Keep)
6. Gender-affirming voice training community
7. Non-native English speakers in senior roles
8. Adults with ADHD
9. Co-parents post-divorce
10. Enterprise sales teams (longer-term B2B)

See master spec §2 for detailed expansion markets.

---

## 3. The Product Family — Three Offerings

Sunspoke is not one product. It's a family of objects that share one software soul. Each object solves a different *carry context* in the user's life.

### 3.A — Sunspoke **Wear** (pendant)
*The jewelry. Worn on your body, visible or hidden.*

A slim rod pendant worn on a chain, cord, or clip. Silver, gold, or blackened finish. Reads as minimal men's/women's jewelry, not tech.

- **Carry context:** All day, on your body. Meetings, commutes, dinners, gym.
- **Capture mode:** Continuous voice-ID-filtered listening while worn.
- **Primary emotional job:** Identity signal. *"I'm the kind of person who cares."*
- **v0 hardware:** Plaud NotePin reworked into plated pendant form (MVP).
- **v1 hardware (2027):** Custom-built rod (~42×11×7mm, 12-18g, 3 finishes).
- **Price (v0 Founder's Edition):** $999 or gift depending on pricing path (see master spec §11).
- **Price (v1 public):** $499-599.

### 3.B — Sunspoke **Object** (desk sculpture)
*The art piece. Lives on your desk, nightstand, or bookshelf.*

A small sculptural object, ~60-80mm tall, designed as a beautiful thing first. Sits on any surface, photographs well, sparks *"what's that?"* conversations. Gold, silver, and richer color palette (oxidized bronze, ceramic, colored glass inlay).

- **Carry context:** At your workspace or home. Captures your voice during desk work, solo thinking, calls, meetings in that space.
- **Capture mode:** Ambient voice-ID-filtered listening when in the room with user.
- **Primary emotional job:** Presence. *"I show up to work, and it shows up with me."*
- **v0 hardware (concept):** Plaud NotePin reworked into sculptural housing by an industrial designer. Can be "heavier" and "more art-object" than the Wear since it doesn't need to be carried.
- **v1 hardware (2027):** Custom build with more volume budget — better battery, larger mic array, potentially richer sensor suite (ambient presence detection).
- **Price (Founder's Edition):** $1,299-1,499 (premium of the three).
- **Price (v1 public):** $699-799.

**Reference objects:** Teenage Engineering OP-1, Nomos wall clock, Arne Jacobsen desk objects, Moooi small sculptures, Japanese netsuke, worry stones in precious materials, Muji aroma diffuser (simple, self-contained, beautiful).

### 3.C — Sunspoke **Clip** (phone accessory)
*The ambient companion. Attaches to your phone.*

A MagSafe accessory that snaps onto the back of an iPhone (or any MagSafe-compatible case). Sits alongside your phone as you use it — on desk, in pocket, in hand. Recharges via MagSafe when the phone charges.

*[QUESTION FOR JASMINE: confirm MagSafe vs. integrated case vs. slide-in card. See §14.]*

- **Carry context:** Whenever you have your phone — which is ~14-16 hours/day. Most reliable capture of the three.
- **Capture mode:** Continuous voice-ID-filtered listening while attached to phone.
- **Primary emotional job:** Practicality. *"I don't have to think about wearing or carrying it. It just rides with my phone."*
- **v0 hardware (concept):** Plaud NotePin reworked into MagSafe puck form (metal disc ~50mm diameter, magnetic ring, Sunspoke branding).
- **v1 hardware (2027):** Custom build with MagSafe-native charging, smaller profile, premium finish.
- **Price (Founder's Edition):** $699-799.
- **Price (v1 public):** $349-399 (lowest price, highest volume).

### Why three, not one

Different humans carry life differently. Some wear jewelry, some don't. Some sit at a desk all day, some are mobile. Some want identity signals, some want invisibility. Three products cover the full spectrum with one software platform.

Over time, most users will own more than one — Wear for out-of-home, Object for desk, Clip as backup. Cross-sell economics are strong.

### What's explicitly NOT a product

For scope discipline, these are not in the three-SKU family right now:
- Ring (engineering too hard; Oura owns the category)
- Earring / in-ear (Apple will open AirPods live audio eventually; v3 consideration)
- Wrist device (Whoop/Apple Watch territory; no differentiation)
- Glasses (Meta territory; too socially loud)

---

## 4. Shared Product Principles

All three Sunspoke products share these non-negotiables. Every feature in every product must pass all seven.

1. **It only hears you.** Voice-ID gating means only the wearer's speech is processed for coaching. (v0 is voice-ID filtering post-capture; v1 is voice-ID gating on-device. Both qualify.)
2. **It never interrupts.** Zero real-time notifications unless explicitly opted-in per goal. Pull over push.
3. **Four tempos.** Daily (evening recap), weekly (Read + archetype), monthly (progress), yearly (the artifact).
4. **Specificity over generality.** "You interrupt women 3x more than men" beats "you sometimes interrupt." Every coaching moment references an exact quote, time, or count.
5. **Literary, not analytical.** No dashboards as primary interface in v0. Prose, audio, letters, artifacts. Eventually simple visualizations in v1+ only if they feel like poetry, not software.
6. **Earned trust, not default trust.** Week 1 is listening only. No coaching before we know the user. New features launch opt-in by default.
7. **Object over gadget.** Every piece of hardware must pass the "would a person who doesn't usually buy tech pay this for this?" test. If not, redesign.

---

## 5. Shared Software Platform

All three products — Wear, Object, Clip — run on one shared backend:

- **Voice-ID enrollment:** 30-second voice sample at onboarding, creates a speaker embedding per user.
- **Capture pipeline:** Audio → transcription → speaker diarization → filter to wearer-only → stored in user's private archive.
- **Coaching layer:** Claude API + custom prompts generate daily recap, weekly Read, monthly retrospective, yearly artifact.
- **Archetype system:** 10-12 archetypes (The Diplomat, The Interrupter, The Softener, etc.). Each user gets an archetype at their Week 1 Read; archetype evolves quarterly.
- **Delivery:** v0 via Slack DM. v1 via native iOS/Android app.
- **Data ownership:** Users own their data, can export at any time, can delete, can designate a legacy contact.

Hardware changes across products — software does not. This is the moat and the economic engine.

See master spec §8 for engineering detail.

---

## 6. Future Vision — Emotional LED System

### Concept
The Sunspoke Wear, Object, and Clip can all embed a small, quiet LED that reflects the user's state in color.

### How it works (design exploration)
*[QUESTION FOR JASMINE: confirm interpretation. See §14.]*

**Proposed model — Internal Reflection + Goal-Linked Hybrid:**

The LED is subtle, almost imperceptible unless you look for it. It has two modes:

**Mode A — Reflection (passive, ambient):**
The device listens for emotional signals in the wearer's voice (pace, pitch variance, tonality, silence patterns). When a clear state is detected, the LED glows a color tied to that state:
- **Warm gold** — calm, grounded, present
- **Cool blue** — reflective, contemplative
- **Dim red** — agitated, stressed (subtle signal)
- **Green pulse** — aligned with current goal

The colors are chosen so that even if someone else notices, the meaning isn't obvious. It's only meaningful to the wearer.

**Mode B — Goal Signal (active, rare):**
When a goal-relevant pattern is detected — the wearer interrupts, hedges, dodges conflict — the LED pulses once, briefly, in their goal color. A tap on the shoulder, not a lecture.

### Why this matters for the product
- **Makes the invisible visible.** Speech patterns are hard to notice in the moment; a quiet light turns them into awareness.
- **Subtle identity signal.** A device that softly glows gold when you're present is poetry; a device that blinks red when you're stressed is surveillance. Design must err toward poetry.
- **Differentiates from every competitor.** No one else in the AI wearable space has done this well. Humane tried visible projection (too loud). Sunspoke's version is whisper-quiet.

### When it ships
- **Not in v0.** Plaud hardware doesn't support LED control.
- **Not guaranteed in v1** (2027 custom hardware) — but v1 hardware spec should *include an RGB LED channel so it can ship in v1.5 or v2.*
- **Public launch target:** v2 (2028) as a "Sunspoke feels now" moment across all three SKUs.

### Design principles for the LED
- **Visible only when looked for.** Default brightness: 5-10% of max.
- **Never interrupts others.** No flashing, no pulse patterns visible across a room.
- **Respects sleep.** Auto-off at user-chosen hours.
- **User-customizable color palette.** Defaults are curated; user can rebind colors.
- **Mode switchable via pendant double-tap or Object rotation.**

### Engineering ask for v1 hardware spec
Include RGB LED driver capability in the custom PCB spec. Even if we don't ship the feature in v1, we want the *option*.

---

## 7. Phased Rollout Plan

### v0.1 — Proof of Concept (Weeks 1-4)
- **Product:** Wear pendant only (Plaud-reworked)
- **Users:** 1 (Jasmine)
- **Goal:** Prove coaching is uncanny
- See master spec §13 Phase 1

### v0.2 — Founder Cohort (Weeks 5-14)
- **Product:** Wear pendant (20 units, Plaud-reworked, silver/gold/blackened)
- **Users:** 20 founders
- **Goal:** Real data, real testimonials, fund next phases
- See master spec §13 Phase 3

### v0.5 — Object Introduction (Months 4-6)
- **Product:** Wear + **Object** (desk sculpture prototype)
- **New users:** 30-50 additional testers who want the desk version
- **Goal:** Test the Object form factor with existing Wear wearers + new audience
- Plaud-internals inside sculptural housing designed by an industrial designer
- **Cost:** ~$50-80K for industrial design + small-batch production

### v0.6 — Clip Introduction (Months 6-8)
- **Product:** Wear + Object + **Clip** (MagSafe accessory)
- **New users:** 50-100 additional testers
- **Goal:** Validate the MagSafe form factor, test cross-SKU cross-selling
- **Cost:** ~$40-60K for design + small-batch production

### v1 — Public Launch (Q2-Q3 2027)
- **Product:** All three SKUs ship on custom hardware (not Plaud-based)
- **Users:** Public DTC, deposits convert, Early Circle (21-100) gets first shipments
- **Goal:** $1-3M year-one revenue across all SKUs
- **Cost:** $400-700K custom hardware development + $200-400K marketing

### v1.5 — Emotional LED (Late 2027 / Early 2028)
- LED ships across all three products via firmware update (if hardware spec included the driver) or as a hardware revision
- User-controllable, opt-in, minimal

### v2 — Platform Expansion (2028)
- Sunspoke Pair (couples, two Wears)
- Sunspoke Keep (legacy/memory product, separate brand)
- Sunspoke Practice (therapist B2B)

See master spec §13 for execution detail on v0 phases.

---

## 8. Design Principles for Hardware Family

### Material palette
All three products share a consistent material vocabulary:

- **Metals:** titanium (lightweight premium), sterling silver (warm classic), 18k gold plate (brushed warm), blackened steel / gunmetal (stealth), polished brass (honest material)
- **Finish textures:** brushed, polished, satin, oxidized. No chrome, no high-gloss plastic, no aluminum.
- **Complementary materials:** leather (vegetable-tanned, camel or black), silk (cream or navy cord), wool felt (interior lining), natural stone inlay (optional — jade, onyx, tiger's eye for Object)
- **Cord/chain options:** fine chain (matches pendant finish), leather cord, silk cord, magnetic clasp options

### Weight as communication
Each object communicates through its mass. The Wear is ~12-18g (substantial but wearable). The Object is 60-150g (presence on a desk). The Clip is ~25-35g (feels real on the phone). None of these should ever feel *light* — lightness reads as cheap plastic.

### Packaging
Every Sunspoke purchase arrives in a wooden presentation box with:
- Linen-lined recessed cavity
- Hand-signed letter
- Multiple wear/carry options (cord, chain, leather strap, pouch)
- Care instructions on a single elegant card
- Magnetic or inductive charging puck (unbranded)

Budget $100-200 per unit on presentation alone. Inspired by: Aesop packaging, Hermès boxes, Japanese craft packaging.

### Sensory principles
- **No plastic-on-plastic clicks.** Every mechanical interaction should feel like metal on metal, or leather on wood.
- **Silence.** No chimes, no beeps, no notification sounds from the hardware. Ever.
- **Haptic only.** The only physical feedback is a single, quiet haptic pulse — and only when opted-in.
- **Charging is invisible.** Users should never see charging cables or ports during the unboxing experience.

### Moments of delight
Design the product so that every three months, users find a new moment of delight — a detail they didn't notice, a behavior they didn't know existed:
- **Month 1:** The unboxing.
- **Month 3:** The yearly artifact preview (subtle hint in the app).
- **Month 6:** A new archetype reveal as coaching evolves.
- **Month 9:** The first Sunspoke Keep invitation (legacy seeding).
- **Month 12:** The annual artifact arrives. Full cycle complete.

---

## 9. Success Metrics

### v0 (Founder Cohort, Months 1-6)
- 15+ of 20 active weekly usage at Month 3 (75% retention)
- 10+ "uncanny" moments reported in feedback calls
- 12+ LinkedIn posts from the 20 (organic evangelism)
- 3+ unprompted press mentions (earned media, not paid)
- 2-3 friends-and-family investors closed ($200-400K round)

### v0.5 (Object + Clip in testing)
- Each new form factor tested by 30+ users
- At least 40% of Wear users opt in to buy a second SKU (Object or Clip)
- Retention holds on the Wear during new SKU testing (no cannibalization)

### v1 (Public Launch, Months 12-24)
- **Year 1 revenue target:** $1-3M across three SKUs
- **Unit mix target:** 50% Wear, 30% Clip, 20% Object
- **Retention at 6 months:** >50% (Oura tier)
- **Cross-SKU purchase:** >20% of customers own two or more products within 12 months
- **Press coverage:** 5+ major press hits, 50+ smaller mentions
- **Active Founder's Circle:** 20 original + 80 Early Circle + waitlist 500+

### v2 (Platform, 2028)
- Sunspoke Pair launched, 500+ couples onboarded
- Sunspoke Keep launched, 1,000+ adult children converting
- Series A raised off demonstrable multi-product retention
- Team grown from founder+Michael+Aither to 8-12 people

### Long-term north star
**Sunspoke is known as the first company that made wearable AI feel like a gift, not a tool.**

---

## 10. Technical Architecture (Cross-Product)

One backend serves all three products. Per-product hardware differences are abstracted at the firmware/BLE layer.

```
┌─────────────────────────────────────────────────┐
│  Hardware — any Sunspoke product                │
│  (Wear pendant, Object sculpture, Clip MagSafe) │
└──────────────┬──────────────────────────────────┘
               │  BLE protocol (shared)
               ▼
┌─────────────────────────────────────────────────┐
│  Audio capture + voice-ID filtering             │
│  (v0: post-capture filter; v1: on-device gate)  │
└──────────────┬──────────────────────────────────┘
               │
               ▼
┌─────────────────────────────────────────────────┐
│  Shared coaching pipeline                        │
│  • Transcription                                 │
│  • Speaker diarization                           │
│  • Pattern analysis                              │
│  • Claude-generated coaching                     │
│  • Archetype classification                      │
└──────────────┬──────────────────────────────────┘
               │
               ▼
┌─────────────────────────────────────────────────┐
│  Delivery layer                                  │
│  • v0: Slack bot                                 │
│  • v1: iOS + Android app                         │
│  • v1.5: LED signal (hardware-dependent)         │
└─────────────────────────────────────────────────┘
```

See master spec §8 for Michael's detailed engineering build.

---

## 11. Competitive Moat

### What's defensible
1. **Voice-ID coaching architecture** — patented (provisional filing, see master spec §12)
2. **Literary coaching voice** — the specific prose style, archetype system, and four-tempo rhythm
3. **Cohort loyalty** — 20 founders evangelizing at launch is unrepeatable by a competitor
4. **Aither design quality** — product/brand/packaging integration that competitors can't match without agency-level design talent
5. **Product family depth** — three form factors, shared backend, cross-sell engine

### What's not defensible
- The hardware itself (Plaud-rework in v0, custom in v1 — still copyable)
- LLM-based coaching (anyone with Claude/OpenAI access can build)
- Slack delivery (trivially replicable)

### Why we win anyway
Because **execution quality of the complete system** — product + brand + packaging + coaching + community — is what creates the $999-1,499 price point and the >50% retention. Competitors can copy any piece; they can't easily copy the system.

---

## 12. Risks & Mitigations

| Risk | Likelihood | Impact | Mitigation |
|---|---|---|---|
| Plaud API inaccessible / breaks | Medium | High | Data pipeline fallback ladder (master spec §8.3); worst case, phone-as-mic backup |
| Coaching quality is mediocre | Medium | Critical | Phase 1 go/no-go gate at Week 4 before scaling hardware purchase |
| Plaud identifies the rework, sends C&D | Low | Medium | Closed 20-user beta, NDAs, "validated third-party hardware" framing in ToS |
| Two-party consent legal challenge | Low | High | Privacy lawyer review pre-ship, voice-ID architecture defense |
| Founder cohort churns quietly | Medium | Medium | Weekly feedback calls, human-augmented early coaching to ensure quality |
| OpenAI + Ive launch crushes us | Low | Medium | We ship first, own the coaching vertical they won't enter |
| Custom hardware dev overruns (v1) | High | High | Three engineering quotes, contingency budget, phased prototype milestones |
| Multi-SKU scope creep | High | High | PRD discipline: Object and Clip are post-v0; don't start until Wear ships to 20 |
| Emotional LED misreads emotion | Medium | Medium | Launch opt-in only; gather 6 months of data before making a public claim about accuracy |

---

## 13. Team

See master spec §14 for detailed roles. At a PRD level:

- **Founder (Jasmine):** Vision, cohort, brand direction, fundraising
- **Engineering (Michael + future hires):** Software platform, firmware spec for v1, app development
- **Design (Aither):** Brand system, product renders, packaging, all UI/UX
- **Industrial Design (contract, new hire for Object):** Sculptural form for Object, rod form for Wear v1, Clip form
- **Hardware PM (Phase 4 hire):** Chinese firm relationship for v1 custom hardware
- **Legal (contract counsel):** Privacy, patents, ToS, contracts
- **Jeweler / Rework specialist (Wayeez-sourced):** Plaud reworks for v0

---

## 14. Key Open Decisions for Founder

These are the decisions that unblock the rest of the PRD:

1. **Sequencing — which SKU first?**
   PRD default: Wear pendant first (aligned with master spec). Confirm or reassign.

2. **Clip form factor**
   PRD default: MagSafe accessory (not integrated case, not slide-in card). Confirm or reassign.

3. **Emotional LED behavior**
   PRD default: Internal Reflection (voice-based state detection) + Goal Signal (rare pulse on goal-relevant patterns). Confirm or reassign.

4. **Buyer segmentation across three SKUs**
   PRD default: Same buyer (operator/therapist/self-worker), different carry contexts. Confirm or rethink.

5. **Price architecture**
   PRD default: Tiered — Object premium ($1,299-1,499 Founder / $699-799 public), Wear mid ($999 Founder / $499-599 public), Clip accessible ($699-799 Founder / $349-399 public). Confirm or reassign.

6. **"Million-dollar product" reference anchors**
   PRD default: Aesop for packaging, Le Gramme for object philosophy, Nomos for watch craft, Hermès for unboxing, Muji for restraint, Teenage Engineering for playful-but-premium.
   Add or replace your own references.

---

## 15. What this PRD does not cover

This PRD is scoped to the product family and vision. It deliberately does not cover:

- **Fundraising strategy** — lives in master spec §11 + external investor deck
- **Hiring plan** — lives in master spec §14
- **Legal structure** — lives in master spec §12
- **Financial model** — lives in a separate financial model doc (to be built)
- **Go-to-market plan** — lives in master spec §11 and a separate GTM doc (to be built)

---

## Appendix — Reference links

- Master execution spec: `sunspoke-master-spec.md`
- Brand references board: *to be built by Aither, link here when ready*
- Hardware render gallery: *to be built by Aither, link here when ready*
- Coaching voice samples: *to be built by Michael + content writer, link here when ready*

---

**Owner:** Jasmine
**Reviewers:** Michael (engineering feasibility), Aither (design feasibility)
**Cadence:** Quarterly review, versioned updates in git
