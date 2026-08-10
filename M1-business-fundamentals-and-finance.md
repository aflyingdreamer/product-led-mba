# M1 — Business Fundamentals & Finance

**What you'll be able to do by the end:** look at any business — including your own — and read it as a machine. Say precisely how it makes money, whether a single customer is profitable, how fast it gets its money back, and which levers actually move the bottom line. This is the floor everything else in the program stands on.

**Why it's first:** every later module (pricing, retention, growth, GM) is ultimately an argument about *this* machine — how to make the loop bigger, tighter, or more defensible. If the finance layer is fuzzy, every downstream decision is guesswork wearing a confident face.

---

## 1.1 — What a business actually is

Strip away the industry, the product, the story. A business is a machine that **turns some money in into more money out, repeatably.** That last word is the entire game. Anyone can turn $1 into $2 once (luck, a favor, a fire sale). A *business* is a structure where the conversion repeats and, ideally, compounds.

Two distinct actions hide inside that machine, and confusing them is one of the most expensive mistakes operators make:

- **Value creation** — you make something a customer is genuinely better off having. This is the product's job.
- **Value capture** — you keep some of that value as revenue and margin. This is the business model's job.

They are not the same, and you can be great at one and dead at the other. `[established]` A product can create enormous value and capture almost none (think of a beloved free tool that never found a way to charge). A business can capture value briefly while creating little (a fad, a scam) and it doesn't repeat. A durable business does both: creates real value *and* has a mechanism to capture a slice of it, over and over.

> **The core loop.** Spend money to acquire a customer → deliver value → capture revenue from them → ideally spend some of that to acquire more and better customers. Every metric in this module is just a measurement of one part of this loop. Keep the loop in your head; the vocabulary hangs off it.

**Provenance / confidence:** the value-creation-vs-capture distinction is standard strategy (traceable to *Porter* and later to *Teece* on value capture) `[established]`. The "money machine" framing is my compression of it `[synthesis]`.

---

## 1.2 — The three financial statements

A business reports itself through three statements. They are not accounting trivia — each answers a different survival question, and they interlock. You don't need to *prepare* them (that's the accountant's job); you need to *read* them and know what each one hides.

**1. The Income Statement (P&L — Profit & Loss).** *Question it answers: over a period, did we make a profit?*
Revenue at the top, costs subtracted in layers, profit at the bottom. Its layers matter (section 1.4). The trap: the P&L is built on *accrual* accounting — it books revenue when *earned* and costs when *incurred*, not when cash actually moves. So a P&L can show a profit while the bank account is draining. `[established]`

**2. The Balance Sheet.** *Question it answers: at a single moment, what do we own and owe?*
Assets = Liabilities + Equity — always, by construction. It's a snapshot, not a movie. It tells you the financial *position*: cash on hand, debt, what's owed to you. The trap: it says nothing about whether the business is *working* — only what it's holding right now.

**3. The Cash Flow Statement.** *Question it answers: over a period, where did actual cash move?*
This is the reality check on the P&L. It strips out the accrual illusions and shows cash in vs cash out. **Profit is an opinion; cash is a fact.** `[heuristic]` Businesses rarely die from unprofitability on paper — they die when they run out of cash. This is why a fast-growing company can be "profitable" and still go under: growth eats cash (you pay to acquire customers now, collect from them later).

**How they interlock:** the profit from the P&L flows into equity on the Balance Sheet; the cash movements reconcile the Balance Sheet's cash line between two snapshots. Think of it as: P&L = the story of the period, Balance Sheet = the still frame at the end, Cash Flow = the truth serum on the story.

**Provenance:** all `[established]`, standard financial accounting. For a genuinely readable primary source, *Berman & Knight — Financial Intelligence* is the one to drill into; it's written for operators, not accountants.

---

## 1.3 — Unit economics: the atom

Zoom the whole machine down to **one customer.** If a single customer isn't profitable over their lifetime, scaling doesn't save you — it accelerates the bleeding. This is the microscope, and it's the single most important tool in this module.

The atom has a few parts:

- **CAC — Customer Acquisition Cost.** Total sales + marketing spend, divided by number of new customers it produced, over a period. What it costs you to get one customer through the door. `[established]`
  - *Watch:* be honest about the numerator. Include the salaries, the tools, the ad spend — not just the ad spend. A flattering CAC is a lie you tell yourself.

- **Contribution margin per customer.** The revenue a customer pays you, minus the *variable* cost of serving them (hosting, support, payment fees, cost of goods). This is what one customer actually contributes toward covering your fixed costs and profit. Not revenue — revenue minus the cost to deliver it. `[established]`

- **LTV — Lifetime Value.** The total contribution margin a customer delivers across their whole life with you. Roughly: *average contribution margin per period × how many periods they stay.* How long they stay is set by churn (M3), which is why retention quietly controls this whole number. `[established]`
  - *Simple form:* `LTV ≈ (ARPA × gross margin %) / churn rate`. Note what this says: halve your churn and you *double* LTV. Retention is a lever on value capture, not just a defensive metric. `[synthesis of established parts]`

- **Payback period.** How many months of a customer's payments it takes to earn back their CAC. Not just *whether* you get the money back (LTV:CAC) but *how fast*. `[established]`
  - *Why it matters more than people think:* payback period is a cash-flow constraint. Long payback = you finance every customer's acquisition out of pocket for months. Two businesses with identical LTV:CAC can have wildly different survival odds if one gets paid back in 3 months and the other in 18. The 18-month one needs a war chest or funding just to grow — this is where unit economics and cash flow (1.2) shake hands.

- **The LTV:CAC ratio.** The headline health check. `[heuristic]`
  - `< 1` — you lose money on every customer. Growth = suicide.
  - `~3:1` — the rule-of-thumb target for a healthy SaaS business (you get 3x back what you spend to acquire). `[heuristic — David Skok]`
  - `> 5:1` — often *not* a trophy. It usually means you're *underspending* on acquisition and leaving growth on the table — you could afford to acquire more aggressively. A "too good" ratio is a signal, not a medal.

**The cohort lens.** Never look at these as one blended average across all customers ever. Group customers by when they joined (a *cohort*) and track each cohort over time. Blended averages hide everything that matters: a business with improving product can look flat on average while every new cohort is dramatically better than the last, and a rotting business can look healthy on average while recent cohorts collapse. `[established]` Averages lie; cohorts confess.

---

## 1.4 — The P&L and its levers

Now back out from one customer to the whole company. The P&L has layers, top to bottom, and each layer is a different lever:

```
  Revenue
– Cost of Goods Sold (COGS)      ← cost to deliver the product
= Gross Profit   (Gross Margin % = Gross Profit / Revenue)
– Operating Expenses (S&M, R&D, G&A)
= Operating Profit (EBIT)
– Interest, Taxes
= Net Profit
```

The layers you'll actually operate on:

- **Gross margin** is destiny. `[heuristic]` It's the fraction of each revenue dollar left after delivering the product. Software has famously high gross margins (~70–85%) because delivering one more copy costs almost nothing. A high gross margin is what lets you afford heavy S&M, R&D, and still profit — it's the fuel tank for everything else. A low-gross-margin business (lots of human cost or COGS per sale) is structurally starved no matter how good the top line looks. *This is exactly the tension in a cheap-price + heavy-human-support model: the support cost lives in COGS and eats the margin that would otherwise fund growth.*

- **Operating leverage.** Fixed costs (R&D, most G&A) don't scale 1:1 with revenue. So as revenue grows, if fixed costs grow slower, profit grows *faster* than revenue. That gap is operating leverage — the mechanical reason scale can turn a break-even business profitable without anything else changing. `[established]`

- **The SaaS-specific gauges** (know them, don't worship them):
  - **Rule of 40** `[heuristic — practitioner rule]`: growth rate % + profit margin % should exceed 40. A fast-grower is "allowed" to be unprofitable; a slow-grower must be profitable. It's a rough sanity check on the growth-vs-profitability trade, not a law.
  - **Burn rate & runway**: cash out per month, and how many months of it you have left. The clock every startup actually lives on.
  - **The Magic Number** `[contested]`: new revenue generated per dollar of S&M spend — a sales-efficiency gauge. Useful, but definitions vary and people game it; treat outputs skeptically.

---

## 1.5 — From unit to business (how the atom scales, and where it snaps)

Here's the integration, and it's the mental model to walk away with:

**A healthy business is a healthy unit, multiplied — and multiplication finds every hidden weakness.** If your unit economics are sound (LTV:CAC healthy, payback fast, contribution margin real) *and* the acquisition channel can supply customers at that CAC *at volume*, scaling compounds. But three things break under multiplication, and they map onto the rest of this program:

1. **The channel saturates.** CAC is cheap for the first N customers and rises as you exhaust the easy ones. The unit that looked great at small scale degrades as you push volume. (→ M7, growth)
2. **Retention leaks.** A small churn rate is survivable when you're small and inflow is high; at scale, the leak becomes the story, because you're refilling a bigger and bigger bucket. (→ M3, retention/NRR)
3. **The cost to serve grows.** Support, infrastructure, and org overhead that were cheap at small scale can quietly erode gross margin as you multiply. (→ M9, M10, org & ops)

This is why "we ran a profitable business" and "we understand unit economics cold" are different claims. Running a business where the hardest input (customer supply) was cheap or subsidized means you may never have *felt* the number that tries to kill you at scale: **CAC × the retention of the segment you chose.** That product — acquisition cost multiplied by how long your customers actually survive — is the real verdict on whether the machine scales.

---

## Case (the work of this module)

Take a SaaS product — ideally one you know, or invent plausible numbers — and build its unit economics from the ground up:

1. Estimate CAC honestly (all-in, not just ad spend).
2. Estimate ARPA (average revenue per account) and contribution margin (revenue − variable cost to serve).
3. Estimate monthly churn → derive average lifetime → derive LTV.
4. Compute LTV:CAC and payback period.
5. Now stress it: what happens to each number if CAC doubles? If churn halves? Which single lever moves the business most?

The output of the case *is* the module's deliverable below.

## Output artifact

**A Unit Economics + P&L dashboard** (a spreadsheet or one-page doc):
- The unit economics block: CAC, ARPA, contribution margin, churn, lifetime, LTV, LTV:CAC, payback.
- A lite P&L: revenue → gross profit → operating profit, with gross margin % visible.
- One sensitivity row: how the headline numbers move when you flex CAC, churn, and price ±20%.

When this exists and you can defend every number in it, M1 is done.

## Optional application hooks (skip freely)

- Run your *actual* SHT or AhaSlides numbers through 1.3. Which of those numbers do you *know*, and which would you have to guess? The guesses are the parts you operated on feel rather than instrument.
- SHT was a low-mid price + heavy-support model. Locate that support cost in the P&L (1.4) — is it in COGS (eating gross margin) or in OpEx? The answer tells you whether that beloved 24/7 support was a margin problem waiting for scale.

## Sources to drill into (when a dot needs the primary)

- **David Skok — *forEntrepreneurs* (SaaS metrics essays)** — the canonical practitioner source for CAC, LTV, payback, the 3:1 rule. Free online.
- **Berman & Knight — *Financial Intelligence*** — the readable operator's guide to the three statements. Start here if 1.2 felt thin.
- **Damodaran (NYU) — free corporate finance lectures** — when you want the rigorous version of valuation and cost of capital, later.

---

*Next when you want it: M2 — Product Strategy & Systems. Say the word and I fill it.*
