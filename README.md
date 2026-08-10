# The Product-Led Business MBA — Self-Paced Hub

A self-directed MBA built on one thesis: **how a product-led business actually works, end to end, from a single unit of value to an owned P&L.** This hub *is* the course; each module is a file; you read at your own pace — fast where it's easy, slow where it bites.

---

## How this course teaches

The pedagogy standard — how every chapter is motivated, sequenced, built, and assessed — lives in the **`instructional-design` skill** (`.claude/skills/instructional-design/`), not here. It is loaded before any module is written and run as a ship-gate before any module is published. This file is the *course architecture* that skill gets applied to. (If content ever reads like a five-minute summary, it has failed the skill's first rule — flag it.)

Two course-specific honesty conventions — the skill's provenance rule, cashed out as inline tags in every module:

- **Confidence flags.** `[established-as-convention]` a rulebook humans agreed on (accounting, GAAP definitions) · `[established-as-finding]` a discovered regularity (operating leverage, network effects) · `[synthesis]` my integration · `[contested]` practitioners disagree · `[heuristic]` useful rule, not a law. The convention/finding split is load-bearing: it stops a human agreement being sold to you as a law of nature.
- **You're a witness, not just a student.** You've run a real BU, a real P&L, a 15-person team. On the "war layer" — how operators actually behave — that makes you a primary source I don't have. When a module's account contradicts what you lived, the default is that *I'm* wrong. Those disputes are the highest-value input this hub receives; `PROGRESS.md` captures them.

---

## Course architecture

*Designed before any chapter (the skill's first rule). Everything below is derived top-down from it — no module exists except as a lever on this.*

**Enduring understanding.** A product-led business is not twelve separate subjects — it is **one money-loop, multiplied**: create value for a single user, capture some of it, reinvest to acquire the next, defend the base so it compounds. Finance, positioning, pricing, retention, growth, sales, org are not topics; they are *levers on that one loop*, or the forces that snap it under multiplication. Master the loop and the "subjects" collapse into one machine.

**Driving question.** *Given a product some people already love, what has to be mechanically true to turn it into a durable, largely self-funding business whose P&L you could own — and where does that machine break under scale?*

**Competence statement — what a graduate can DO** (not what they've been exposed to). Handed a product-led company's raw numbers and market context, a graduate can:

1. read its three statements as one system and name the two or three levers actually moving enterprise value;
2. prove whether its unit economics *survive multiplication* (channel saturation, retention leak, rising cost-to-serve) — not merely whether they look good at small scale;
3. **make and defend a call under incomplete information** — a pricing, capital-allocation, or go-to-market decision — naming the one variable that drove it and steelmanning the strongest case against it.

*Conditions:* conflicting data, no clean answer, a real P&L on the line. Capability 3 — judgment under ambiguity — is the GM delta, and it is what the **capstone certifies** (the course-level judgment task, per the skill's §7). Each module also carries its own decision-forcing case: a named protagonist, a clock, incomplete information, and a call you commit to in writing *before* the module reveals what happened.

**The spiral — three threshold concepts** that recur at rising sophistication rather than being taught once and dropped. Each is a *portal*: it displaces a common wrong model, and once you're through it the rest of the course reads differently.

| Threshold concept | The wrong model it displaces | Where it recurs, deepening |
|---|---|---|
| **The money-loop** — the business is one unit, multiplied | "finance, product, marketing are separate disciplines" | M1 (build the loop) → M6 (pricing sets its capture) → M7 (the channel feeds it — and saturates) → Capstone (model it whole, under shock) |
| **Retention compounds or kills** — NRR > 100% is an appreciating asset | "growth = acquisition" | M1 §4½ (cohorts, NRR) → M3 (the whole leg) → M6 (expansion pricing) → M1 Ch6 (retention, not the CAC ratio, earns the multiple) |
| **Positioning is the headwater** — who-it's-for decides price, channel, motion, narrative | "build a great product and the rest follows" | M5 (establish it) → re-read by M6 (price), M7 (channel), M8 (sales motion), M11 (narrative) |

**Motivation arc.** The stake you already hold: you want to own a P&L — build or run your own thing — without being fooled by your own numbers or your own hires. Each block is a visible competence *gain*, not a topic covered: after M1 you can read any company's machine; after M5–M6 you can position and price it; after M9–M10 you can run the org around it; the capstone is you in the GM chair, holding the number. The real risk in solo study isn't difficulty — it's drift, so each module seam re-anchors *why the next lever matters given the one you just built.*

---

## The roadmap (dependency map)

Ordered by dependency, not calendar. `[✓]` at standard · `[⟳]` filled but pre-standard, being rewritten under the skill · `[ ]` queued.

### Spine (read first)
**Wes Bush — *Product-Led Growth*.** The through-line: the product itself as the primary engine of acquisition, conversion, and expansion — the loop the whole course dissects.

### `[✓]` M1 — Corporate Finance & Business Economics  ·  *prerequisite for everything*
The money machine: what a business *is* mechanically, the three statements as one system, unit economics, cost & leverage, time value & valuation, capital. Carries the first encounter of threshold concepts **#1 (money-loop)** and **#2 (retention)**.
- Reading anchors: David Skok (*SaaS metrics*), Berman & Knight (*Financial Intelligence*), Damodaran (valuation)
- Case: build the unit economics of a real SaaS product from assumed data
- Output: Unit Economics + P&L + Valuation dashboard
- *Status: all 10 conceptual chapters rewritten to the skill standard (stakes-first, prior-model confrontation, derived, war layer, judgment beat); assessment layer upgraded (interleaving, a trap case, a no-answer-key judgment task, process-level feedback, calibration). Glossary is a reference sheet. Self-reviewed against the §9 ship-gate; final test is you reading it as the witness.*

### `[ ]` M2 — Product Strategy & Systems  ·  *needs M1*
What strategy actually is (fit, not a list of good activities), business-model design, North Star / OKRs, growth loops.
- Reading anchors: Porter (*What Is Strategy?*), Rumelt (*Good Strategy Bad Strategy*), *Business Model Generation*, Doerr (*Measure What Matters*), Casey Winters / Reforge (loops)
- Case: map your product's core growth loop
- Output: Strategy map · Metric hierarchy (North Star → team metric → task) · Growth-loop diagram

### `[ ]` M3 — Retention, CS & Expansion  ·  *needs M1 §4½*
Activation and onboarding, churn (logo vs revenue), Net Revenue Retention, expansion mechanics. The deepening of threshold concept **#2** — the leg that quietly decides everything downstream.
- Reading anchors: Ramli John (*Product-Led Onboarding*), Mehta/Steinman/Murphy (*Customer Success*), Patrick Campbell (retention & expansion)
- Case: define your activation metric + aha moment; model NRR
- Output: Activation/onboarding flow · Retention & expansion playbook

### `[ ]` M4 — Data & Experimentation  ·  *needs M1, M3*
Funnels, cohorts, the analytics stack, trustworthy A/B testing. Instrumentation *after* you understand the mechanism it measures.
- Reading anchors: Amplitude/Mixpanel playbooks, Kohavi (*Trustworthy Online Controlled Experiments*)
- Case: design one clean experiment end to end
- Output: Funnel + cohort-retention view · A/B test design doc

### `[ ]` M5 — Positioning  ·  *headwater — feeds M6, M7, M8, M11*
Who the product is *for*, against what alternatives, on what unique value. The establishment of threshold concept **#3**; placed early on purpose — everything downstream reads from it.
- Reading anchors: April Dunford (*Obviously Awesome*, *Sales Pitch*)
- Case: position your product through the 10-step method
- Output: Positioning canvas

### `[ ]` M6 — Pricing & Monetization  ·  *needs M1, M5*
Value-based pricing, the value metric, packaging (Good-Better-Best), why underpricing is a silent killer at scale. Deepens **#1** (pricing sets the loop's capture) and **#3** (price reads from position).
- Reading anchors: Ramanujam & Tacke (*Monetizing Innovation*), Patrick Campbell (pricing)
- Case: design a value metric + tiered packaging for your product
- Output: Pricing strategy doc

### `[ ]` M7 — GTM & Growth  ·  *needs M2, M5*
Channels, the growth model, the product-led acquisition motion. Turning "some people love it" into "many people, repeatably, through channels" — and where the channel saturates (deepens **#1**).
- Reading anchors: Lenny Rachitsky (GTM), Andy Raskin (strategic narrative), Brian Balfour / Reforge (growth model)
- Case: build a channel-fit hypothesis + growth model
- Output: GTM one-pager · Growth model

### `[ ]` M8 — Sales Motion & Revenue Org  ·  *needs M5, M7*
Product-Led Sales, the PQL, the self-serve → sales handoff, how a revenue org is structured and forecast. Where PLG and classic sales collide — and how to reconcile them.
- Reading anchors: Kyle Poyar / Elena Verna (PLS), Mark Roberge (*The Sales Acceleration Formula*)
- Case: define your PQL and handoff trigger
- Output: PLS motion doc · Revenue-org & forecast read

### `[ ]` M9 — Leadership & Org  ·  *needs the business context of M1–M8*
Managing people, feedback, delegation, operating cadence, negotiation. The shift from *doing* to *designing a machine that does*.
- Reading anchors: Kim Scott (*Radical Candor*), Andy Grove (*High Output Management*), Fisher & Ury (*Getting to Yes*)
- Case: design a weekly/monthly/quarterly operating cadence
- Output: Feedback & delegation playbook · Org chart + R&R · Negotiation script

### `[ ]` M10 — General Management & Business Ops  ·  *needs M1, M9*
The GM delta: owning the number, business-review rhythm, hiring beyond tech, commercial/legal literacy (enough not to be fooled by your own hires).
- Reading anchors: Matt Mochary (*The Great CEO Within*), Geoff Smart (*Who*), a SaaS commercial-contract primer
- Case: draft a BU operating rhythm + a hiring scorecard for a non-tech role
- Output: BU operating-system doc (planning cadence + review rhythm + hiring scorecard + contract-risk checklist)

### `[ ]` M11 — Narrative & Executive Presence  ·  *needs M5, and the whole story*
Communicating the thing you built — to a team, a board, an investor.
- Reading anchors: Nancy Duarte (*Resonate*), Sequoia pitch-memo templates
- Case: build the story deck for your product
- Output: Roadmap story deck · 10-slide pitch deck

### `[ ]` Capstone — The P&L-Owned BU Operating Plan  ·  *integrates everything*
The course-level judgment task. Sit in the GM chair and hold the number: a 3-statement-lite model for a product-led BU — revenue built from the growth loop, cost structure, headcount across product/sales/marketing — then a **reforecast under a shock** (churn spike, CAC doubles) and the **capital-allocation call you defend** against the strongest counter-case. Genuinely ambiguous, no answer key; scored on the reasoning, not the number.
- Output: BU plan + defense — a personal asset you carry into a HoP/GM interview, or use to run your own thing.

---

## Two standing principles (they run under every module)

**Invariant vs conditional.** Every module teaches the *invariant* layer — mechanisms true in any market, any year (a money loop must close; positioning precedes pricing; retention compounds or kills). This hub cannot teach the *conditional* layer — which channel is cheap right now, what AI just changed about build cost and moats; those have a shelf life of months and you source them live. Don't expect the core to tell you *what to build*; expect it to tell you *what always has to be true* about whatever you build. This cuts through the war layer too: *that* a metric gets gamed the moment a bonus attaches to it is invariant; *which* game is fashionable this year is conditional — teach the first, date-stamp or drop the second.

**Know → live.** Reading a mechanism is not owning it. Each module ends with retrieval and application (the skill's §7): practice, a judgment call, a trap case, and hooks to run the idea against your own numbers (SHT, AhaSlides, whatever you're building). The gap this hub is really trying to close isn't knowledge; it's turning named mechanisms into things your gut fires deliberately — which is why every module ends in a *decision*, not a summary.

---

## How to move

Open the module file. Read. Capture what matters — especially where your lived experience *disputes* mine — in `PROGRESS.md`. When you want the next module built, say so. The tutor moves with you, not ahead of you.
