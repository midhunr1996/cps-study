# Change Management — Memorize-It Guide 🧠

> How to use this: read each section's **story** once to *understand*, then cover the page and try to say the **📝 Write-in-exam** points from memory using the **🧠 Hook**. The story is the glue; the hooks are the handles. Do this twice and it sticks.

**The one big story that ties EVERYTHING together:**
Meet **Ada, the keeper of an electric car called "Volt."** The blueprint was frozen long ago (**PRD freeze**), but the real world keeps poking the car: new laws, failed tests, a supplier swaps a plug. Ada's whole job is to let the car **change safely** — *as few changes as possible, but as many as needed* — and to keep a perfect **logbook of every version** so nobody ever loses track of which Volt is which. Keep Ada and her ever-changing car in your head the whole time. **The opposite of risk management:** there we *stopped* things going wrong; here we *manage* the things that must change anyway.

---

## 🎬 The Memory Movie (use this if sentences won't stick)

Don't memorize letters — **watch a movie**. Close your eyes and play *the life of Volt the electric car* in 8 scenes, in slide order. Each picture **is** the point, so replaying the movie hands you the answer.

1. 🦎 A **colour-changing chameleon** sits on the car. *Changing by its nature = not CM. Re-painting the actual design = CM.* → **What CM is.**
2. 🪆 Four nested **Russian dolls** tip out: a whole **fleet** → a **new model-year** → a **HW+SW combo** → one tiny **circuit board**. → **VM ▸ LCM ▸ Config-CM ▸ Change-CM** (objects grow as dolls shrink).
3. 🧊 A frozen **blueprint cracks** — a crack labelled "new LAW," another "failed TEST." → **PRD freeze is soft; "have-to" changes break in.**
4. 📒 Ada opens a **logbook with a version stamp** `3.9.4`; she **never erases**, only adds a new page. → **Version & document control.**
5. ❄️🔟 A **snowball rolls UP the hill** getting smaller: the *later the root cause, the cheaper the fix*. → **Inversed Rule of Ten.**
6. 🎢 The car rides a **roller-coaster hill**: climb (invest) → top (mature/profit) → drop (degrade). → **Product life-cycle curve.**
7. 🐄⭐❓🐕 A **farmyard** appears: a **star**, a **cash cow**, a **question mark**, a **poor dog**. → **BCG matrix.**
8. 🧩 Ada locks **LEGO bricks** into one snap-together **kit** and lines up **3 paint-swatch versions** of the same car. → **Configuration management + Variant management.**

> Replay in one breath: **chameleon → dolls → cracked blueprint → never-erase logbook → uphill snowball → roller-coaster → farmyard → LEGO kit + paint swatches.**

**Picture-hooks for the lists that won't stick:**
- 🦎 **CM vs not-CM** — chameleon changing colour *on purpose* = no CM; someone *re-painting the car's blueprint* = CM.
- 🪆 **The 4 "M"s (object size)** — Russian dolls, biggest first: **V**ariant(fleet) ▸ **L**ifecycle(model-year) ▸ **C**onfig(HW+SW combo) ▸ **Change**(one PCB). More objects as the doll shrinks.
- 🧱 **Effort grows with 4 things** — a weightlifter straining under 4 plates: **Complexity · late Detection · Overlapping changes · Variants.** ("Tangled, Late, Crowded, Many.")
- ⏱️ **4 phases of WHEN** — a clock with 4 chimes: **before SOP** (most changes) → **launch** (critical) → **SOP–EOP** (fix & cost-down) → **after EOP** (learn for next).
- 🔗 **WHERE = 2 linked drawers** — a **project drawer** (whole change) chained to a **PDM drawer** (single object). The **chain is the point** — unchained = data branches.
- 🌗 **3 TYPES of change** — a balloon you **inflate (enlarge)**, **pop a piece off (reduce)**, or **squeeze into a new shape (change).**
- 🐢🚀 **SIZE: evolution vs disruption** — a tortoise taking baby steps (better phone) vs a rocket leaping to a new island (smartphone replaces telephone).
- 🔢 **Version `3.9.4`** — three dials: big dial **MAJOR** (re-design), middle **MINOR** (feature, can roll past 9 → `3.10.4`!), small **MICRO** (bug-fix patch).
- 📋 **Version-content "W-questions"** — a detective's form: **What? Why? Who? When? For-whom? Who-approved? When-approved?** + object, status, version.
- 🎢 **Life-cycle phases 0–5** — roller-coaster: **0 Invest** (pay to climb) · **1 Introduce** (slow climb to break-even) · **2 Growth** (steep up) · **3 Maturity** (top, most money) · **4 Saturation** (rolling down) · **5 Degradation** (off the rails, kill it).
- 🐄⭐❓🐕 **BCG → life-cycle order** — **❓Question → ⭐Star → 🐄Cash Cow → 🐕Poor Dog.** Question-marks feed future stars; cash cows pay.
- 🧩 **CM 5-step process** — **O-I-C-S-V**: **O**rganize → **I**dentify → **C**ontrol(the change happens here!) → **S**tatus-accounting → **V**erify/audit.
- 🎚️ **Variant decision** — a see-saw of **base BC vs derivation BC** → look at the **SUM**: positive sum = implement, negative sum = stop/optimize.

**How to lock it in:** read a scene → shut your eyes → re-see the picture → say the meaning out loud. Movie + picture-hooks twice today, once tomorrow, then test with flashcards. **Seeing beats reading; testing beats re-reading.**

---

## 0. The shape of the whole chapter (see this first)

Change Management is **step 4 of System Engineering**: `1 Basics → 2 Requirements → 3 Risk → 4 CHANGE → 5 Ideation → (6 Design) → (7 Test) → (8 Project Setup)`. It lives between **PRD freeze** and **Re-lease**.

The one-line spirit of the whole chapter:
> **"As few changes as possible, but as many as needed"** — keep development stable, yet end up with a sellable product.

And the master picture: **Ada keeping Volt the car alive and honestly logged as the world keeps changing it.** Everything hangs off that.

---

## 1. What *is* change management? (and what it is NOT)

🧒 **Story:** A **chameleon** sits on Volt's hood, changing colour. That's a change — but the chameleon was *built* to do that, so it's **not** change management. Now imagine someone re-drawing the car's actual blueprint — *that* is change management. Careful: the word also means the *organizational/people* kind (changing behaviours, strategy, structures) — but **in this course we ignore that.** We mean **engineering change management** = changing a **product or its parts.**

📝 **Write in exam — Definition:**
- **Engineering change management** (Ger. *Änderungsmanagement, ÄM*) = the **process of changing a product or parts of it.**
- The *other* CM (Ger. *Veränderungsmanagement*) = **organizational** changes (processes, behaviours, strategy, systems, structures) → **not** our topic.
- **Content:** changes of requests & requirements must be **aligned, tracked, followed up.**
- **Target:** **as few changes as possible** (stable development) **but as many as needed** (sellable product).
- A change *intended by the product* (chameleon) = no CM; a change of the *product design itself* = CM.

🧠 **Hook:** *Chameleon changes on purpose = no CM. Re-paint the blueprint = CM.* Goal = **"few but enough."**

---

## 2. Four cousins, all about "what object?" (VM / LCM / CM / CM)

🧒 **Story:** Tip out **Russian dolls**, biggest to smallest. The **biggest doll = the whole fleet of car variants** (Variant management). Inside, a **model-year generation** E90→F30→G20 (Lifecycle management). Inside that, a **HW+SW combo**, e.g. "SW 3.7.2 + d-sample board" (Configuration management). The **tiniest doll = one circuit board** (Change management). The **smaller the doll, the MORE of them there are.**

📝 **Write in exam:** (object increases in number top→down)
- **Variant management (VM):** products/variants — e.g. sedan, convertible.
- **Product life cycle management (LCM):** new generations — e.g. E90→F30→G20.
- **Configuration management (CM):** configurations = HW+SW combos — e.g. ECU SW 3.7.2 + d-sample PCB.
- **Change management (CM):** components — e.g. d-sample PCB.

🧠 **Hook:** **Dolls shrink V → L → C → C; counts grow.** Two "CM"s — **C**onfiguration vs **C**hange — don't mix!

---

## 3. The 5 W's of change (Effort, When, Where, For-whom, Why)

🧒 **Story:** Ada interrogates every change like a journalist: how *hard*, *when*, *where*, *for whom*, *why*.

### 3a. EFFORT — what makes a change expensive
🧒 A weightlifter groans under **4 weight-plates.**
📝 Effort grows with: **system complexity · late point of detection (Rule of Ten) · overlapping (parallel) changes · variants.**
🧠 **Hook:** *Tangled, Late, Crowded, Many.*

### 3b. WHEN — 4 phases
🧒 A clock chimes 4 times across the car's life.
📝 **Until SOP** (most changes, the dev time) → **Launch management** (just before SOP, critical but still needed) → **SOP→EOP** (trouble-shooting quality + cost-down) → **After EOP** (record field issues, improve next product's requirements).
🧠 **Hook:** *Build → Launch → Fix → Learn.*

### 3c. WHERE — 2 LINKED places
🧒 Two filing drawers **chained together.**
📝 Document in the IT system at **two locations: (1) project-management level** (the whole change, e.g. a new standard hitting both sheet-metal and ECU software) and **(2) where the original object was made** (e.g. PDM system, a single drawing → BoM change). **!!! Both MUST be linked**, or the **data branches.**
🧠 **Hook:** *Two drawers, one chain — unchained = branched data.*

### 3d. FOR WHOM
📝 Applies to **all internal products** AND **bought/supplied products**. Suppliers must be **closely tracked & report all changes** (value-chain mgmt). **Only nominate ISO 9001-certified suppliers** and **put the reporting duty in the contract.** Late changes = high cost (contracts are fixed — sometimes on purpose by the supplier).
🧠 **Hook:** *Watch the supplier — ISO 9001 + a contract clause.*

### 3e. WHY
📝 Enables **"design for upgrade capability"** (later HW/SW updates) · **traceability** (versioning) · **releasable product** (conformity) · **cost control** · avoid extra work · avoid missed deadlines · avoid dev issues · keep **high quality.**
🧠 **Hook:** *Upgrade · Trace · Release · Control · Quality.*

---

## 4. Level, Type & Size of a change

🧒 **Story:** Sort every change three ways — how *high-level*, what *kind*, how *big a leap*.

📝 **Level:** the **higher** the level of change, the **fewer** there are (big changes are rare).

📝 **Type (3):** a balloon you can —
- **Scope-Enlargement** = add new content (new requirement),
- **Scope-Reduction** = cancel content (drop a needed signature),
- **Scope-Change** = change existing content (update a value / sharpen a requirement).

🧠 **Hook (Type):** *Inflate · Pop · Reshape.*

📝 **Size (2):** 🐢 **Evolutionary** = gradual improvement of the state of the art (a *better phone*); risk = long-term failure if you never disrupt. 🚀 **Revolutionary/Disruptive** = rethink the problem, radical new solution (a *smartphone instead of a telephone*); risk = product never establishes.
🧠 **Hook (Size):** *Tortoise tiptoe vs rocket leap.*

---

## 5. Version control & Document control (the logbook)

🧒 **Story:** Ada's golden rule: **never erase — always add a new version.** Her logbook shows the object's whole history so anyone can roll back. Each object is named by **ID + version** (requirement #073 isn't enough — v1.0 or v1.1?).

📝 **Write in exam — Version control:**
- **Motivation:** traceability over the whole life cycle (frequency of changes + evolution visible; roll-back possible).
- **No overwriting** → create a **new version**; version number is an **attribute** (auto-counter in pro tools).
- **Identify = ID/name + version number** together.

📝 **Numbering schemes:** single-level numeric (0,1,2…) · single-level alphabetical (a,b,…,aa,ab…) · **two-stage** (`a.0…b.0` or `1.1,1.2,2.0`).
**Semantic `MAJOR.MINOR.MICRO`:** Major = re-design (before the dot) · Minor = feature (after the dot) · Micro = bug-fix. From `3.9.4` → `4.9.4` (major) / `3.10.4` (minor — *not* 4.x!) / `3.9.5` (micro).
🧠 **Hook:** *Big dial · middle dial (can roll past 9!) · small dial.*

📝 **Process:** like "new requirements" — change into pool → *acceptable?* → no: decline w/ reason (or modify & re-loop) → yes: **release new version.**

📝 **Version-content (what to log):** object · status · version no. · **What** changed · **Why** · **For whom** · **Who** changed · **When** changed · **Who approved** · **When approved.**
🧠 **Hook:** *Detective's W-form: What, Why, Who, When, For-whom, +approval.*

📝 **Document control (ISO 9001):** info must be **available where/when needed · protected (confidentiality, integrity) · managed for distribution/access/discovery/use · stored with preserved readability · change-monitored · external docs marked.**
- *Available where needed* → safety manuals **at the machine**, not just on a drive.
- *Readability for 30 years* → can you still read that CD/USB/format later? (Paper may outlast it.)
🧠 **Hook:** *Right place · protected · readable in 30 yrs · external = stamped.*

---

## 6. Impact of changes (+ the INVERSED Rule of Ten)

🧒 **Story:** One little change ripples everywhere — it can **tangle variants, delay time, raise cost, break the PRD contract,** and in the worst case **kill the whole project.** Example: you started the endurance test with the **old round plug**, now everything switches to **rectangular plugs** — stop & redo? swap mid-test? ignore?

📝 **Impact:** increased complexity (variants/configs) → quality issues & unhappy customers · time delay · worse cost/benefit · breaks the PRD · worst case **project stopped.**

🧒 **Inversed Rule of Ten (the twist!):** Normal Rule of Ten = the later you **detect**, the dearer. Here it's about the **root cause**: the **later the root cause sits** in the design process, the **cheaper & easier** to change. Cheap (late root cause) → expensive (early root cause): **update design → update assembly process → change concept → redesign the test → change the whole system.**

🧠 **Hook:** *Snowball rolling UP the hill shrinks — late root cause = small fix. (Inverse of the normal ❄️ snowball.)*

---

## 7. Design, Concept & Requirement changes

🧒 **Story:** The frozen **blueprint cracks.** Two crack-types: ones you have no choice about, and ones you choose.

📝 **Design & concept change — caused by:** failed tests (bad concept/design/implementation) · realization issues (planned HW won't work / too costly → switch to SW) · needing a **re-design or new concept.**

📝 **Requirement changes:** ideal = **hard PRD freeze** (no changes after). Reality = **soft** freeze → changes happen.
- **"Have-to" changes (no choice, before launch):** a **new law** effective before launch · a **failed verification** → relax an **over-engineered** requirement (else change design/concept).
- **"Can-be" changes (your decision):** new/extended **applications** (wire for automotive *and* aeronautics) · **company strategy** · **customer expectation** (B2B = extra cost — why RM matters!) · **tool kits** (round → rectangular plugs) · **cultural/political** (no combustion engines).

📝 **How to handle:** **re-open requirement process → impact analysis (resources + risks) → create a CR → CCB (or project lead) decides & records → prioritize (cost/benefit) → plan implementation.** Valid config = **base line + all CRs.** If done: update reqs → document → implement → **track verification** → release.

🧠 **Hook:** *Crack types = "have-to" (law/failed test) vs "can-be" (your call). Path: **CR → CCB → prioritize → plan**.*

---

## 8. Product life cycle (the roller-coaster)

🧒 **Story:** Volt rides a **roller-coaster**: you **pay to climb**, you **peak and earn**, then you **roll down and get scrapped.** Run the whole ride again = a **new generation** (managed by **PLM/LCM**).

📝 **Repeat reasons:** *Positive* — new customer requirements, intrinsic advancement, state-of-the-art advances. *Negative* — competing products, quality issues, bad reviews, cost reduction.

📝 **Networking:** **Horizontal** = across **generations** (usually forward-only; rarely a successor changes the predecessor — tool-kit defects, part standardization). **Vertical** = across **products**, **bidirectional**, strength depends on **"technical proximity"** (cars→trucks > cars→bicycles); also works across generations.

📝 **Branches (not linear):** continue · **merge** · **split** · **die.** (Example: the Linux distribution timeline. Use IT support for big portfolios.)

📝 **Cycle length:** trend = **shorter** (fast fashion), countered by sustainability. Depends on **industry** (auto ~7 yrs vs phone ~1 yr), **new technology** (digital tools speed up, complexity slows down), and **starting point.**

📝 **Starting point / derivation:** **New development** (nothing reused) · **Wide derivation** (basic features inherited) · **Close derivation** (most carried over, minor tweaks). *Example: landline → (wide: adopt SIM) → mobile → (close: bigger display) → smartphone.*

### 8a. The life-cycle CURVE — 6 phases (memorize!)
🎢 Roller-coaster phases **0–5**:
| Phase | Name | What |
|---|---|---|
| 0 | **Investment** | dev + production setup; high cost & uncertainty; **as short as possible** |
| 1 | **Introduction** | slow sales, no profit yet; ends at **break-even** (fast!) |
| 2 | **Growth** | steep sales rise, first revenue; **short & steep** |
| 3 | **Maturity** | **most profitable**; growth declines; **as long as possible** |
| 4 | **Saturation** | no growth; sales fall; profit falls even faster |
| 5 | **Degradation** | profit negative; **take it off the market** |

🧠 **Hook:** *0 pay-to-climb · 1 slow climb to break-even · 2 steep up · 3 top (max money) · 4 rolling down · 5 off the rails.*

### 8b. Life Cycle Management (LCM)
📝 Aim = **coordinate** all products' cycles to avoid company swings → keep **continuous production use, constant workload, consistent revenue.** Bad timing: too-fast succession = overload + sharp profit fall; successor **too late = a "hole."**
📝 **Stretch a cycle:** *cost measures* — remove unneeded **functions** (focusing), remove **parts not experienced**, cut **over-spec** (smaller semiconductors); plus **product enrichment** (new features). **Keep selling in degradation** for: long-term customer retention · **cross-sales** (entry-ticket) · shared investment / scale pricing.
🧠 **Hook:** *Coordinate cycles → no holes, no overload.*

---

## 9. BCG Matrix (the farmyard)

🧒 **Story:** A **farmyard** of products: a **shooting Star**, a **Cash Cow** to milk, a **Question Mark** new arrival, and a sad **Poor Dog.** Boston Consulting Group plots them on **market growth × relative market share.** It only **records the actual** situation — it does **not forecast.**

📝 **Four quadrants (growth / share / decision):**
- ⭐ **Stars** — high growth, high share, *best product* → **invest** (own cash flow) or skim without losing share.
- 🐄 **Cash Cow** — low growth, high share → **"milk" (skim), no discounts.**
- ❓ **Question Marks** — high-growth, low share, *new product* → **invest from other sources or discontinue.**
- 🐕 **Poor Dog** — low growth, low share, *discontinued* → **terminate** (latest when contribution margin / DB is negative).

📝 **Typical order:** **❓ → ⭐ → 🐄 → 🐕.** Question-marks make **future stars**; cash cows **finance** investments; products **support each other.**

📝 **Relative market share = company share ÷ competitor share.** (>1 = you lead.) In the exercise, A & B = Stars, C = Cash Cow, D = Question Mark, E & F = Poor Dogs → **push D with C's money, stop E + F, launch a new product.**

🧠 **Hook:** *Farmyard: Star → Cow → Question → Dog. Growth ↑ × your-share-vs-rival.*

---

## 10. Configuration management (snap the LEGO together)

🧒 **Story:** Ada snaps the chosen **LEGO bricks** (one inverter version + one motor version + one damping version) into a single **working combo** and writes down exactly which bricks. **Configuration** management cares about the **combo's properties**; **change** management cares about the **single brick.** (Same "CM" letters — different job!) It runs even **after SOP** (for upgrades), owned by a **configuration manager.**

📝 **Targets:** handle variant **complexity** · manage **configuration items (HW/SW/combos)** · ensure system **performance/function/integrity** from the combo · **document** changes · **inform** everyone (transparency) · enable **concurrent/distributed engineering** · enable **roll-backs** · create **reproducible** configurations.

📝 **5-step process (O-I-C-S-V):**
1. **Organization** — rules, tools, naming, tasks, info duty, audits, training.
2. **Identification** — pick configuration units, build the **product structure**, version control, define the **base line** & **granularity** (single screw vs whole transmission).
3. **Control** — **← change management happens HERE.**
4. **Status accounting** — document the configuration + items (system properties, item properties, versions).
5. **Verification & audit** — **test** that requirements are met (whole system or per unit).

📝 **Standards:** EIA-649C (ANSI/EIA) · Automotive SPICE (**SUP**) · IEEE 828-2012 · ISO 10007 · NIST. Needed to pass **ISO 26262 ch.8** (vehicle FuSi) & **ISO 20000** (IT service mgmt).

🧠 **Hook:** *LEGO combo = config; one brick = change. Process = **O-I-C-S-V** (control = where change lives).*

---

## 11. Variant management (paint-swatch versions)

🧒 **Story:** Ada lines up the **same Volt in several paint-and-trim versions.** Underneath, the **same base product** → parts bought in bulk → **economy of scale.** Customers see different **looks** (HMI, colour, shape) and **features** (personal vs enterprise). More variants = more money but **more effort.**

📝 **VM basics:** business model defines the variants. **Tasks:** transparency · optimize (create/delete variants) · link with **LCM**, impact **config-CM.** **Target:** **as many as needed for revenue, as few as possible for complexity** → use **standard interfaces & tool kits.**

📝 **Extra effort by area:** **Development** (what must the base change to enable the variant?) · **Testing** (which tests can be skipped safely?) · **Sales** (don't let variants "negative" each other; build IT-configurators so customers can decide) · **General** (which variants are banned in a country? do they **cannibalize** existing sales?).

📝 **Increase variants** → customization · new **markets** (US vs EU) · new **clientele** (teens → silver agers) · new **use cases** (craft → medical). **Decrease variants** → cut cost via **synergies** (one plug for all).

📝 **Economy & ROI:** new variant = **low extra cost** (base already covers it), **fewer customers**, but **ROI usually higher** than the base.

### The variant business-case decision (the see-saw)
🧒 **Story:** Weigh **base BC vs derivation BC**, then look at the **SUM.** Positive sum → keep; negative sum → fix or kill.

📝 **Write in exam (7 cases):**
| # | base | derivation | sum | decision |
|:-:|---|---|---|---|
| 1 | + | + | + | implement |
| 2 | + | + (> base) | + | implement & check if variant becomes the new base |
| 3 | + | − | + | implement **only if** the variant's economy of scale is *why* the base is positive |
| 4 | + | − | − | don't implement; check base still positive |
| 5 | − | + | + | implement |
| 6 | − | + | − | stop product / optimize base / add positive variants |
| 7 | − | − | − | stop product or optimize |

🧠 **Hook:** *Follow the SUM column — positive = go, negative = stop. Case 3 is the trap: a "−" variant stays if it props up the base's scale.*

---

## 12. Loose ends (quick wins)

- **Software – version control (mostly code):** Azure DevOps · BitKeeper · BitBucket · **Git** · IBM Rational Synergy · RCS · Subversion. 🧠 *"Git & friends."*
- **Software – product portfolio:** **cplace · ClickUp.**

---

## 13. Summary (what you'd write to close an essay)

📝
- In an **ideal project, no change management is needed.**
- In reality CM is vital to: **traceability (versioning) · releasable/conform product · cost control · avoid extra workforce · avoid missed deadlines · avoid dev issues · keep high quality.**
- The spirit: **"as few changes as possible, but as many as needed."**
- 💬 *"While change management is important, **don't be afraid of changes!**"*

---

## 🎴 One-screen cheat-card (last 5 minutes before exam)

| # | Thing | Memory hook |
|---|---|---|
| Spirit | as few as possible, as many as needed | keep stable, stay sellable |
| CM vs not | re-paint blueprint (yes) vs chameleon (no) | design change = CM |
| 4 cousins | VM ▸ LCM ▸ Config-CM ▸ Change-CM | Russian dolls, counts grow |
| Two "CM"s | Configuration vs Change | combo vs single brick |
| Effort grows with | complexity·detection·overlap·variants | Tangled·Late·Crowded·Many |
| WHEN (4) | preSOP·launch·SOP-EOP·postEOP | Build·Launch·Fix·Learn |
| WHERE (2) | project level + PDM, **LINKED** | two drawers, one chain |
| For whom | internal + suppliers (ISO 9001 + contract) | watch the supplier |
| Type (3) | enlarge·reduce·change | inflate·pop·reshape |
| Size (2) | evolution vs disruption | tortoise vs rocket |
| Versioning | MAJOR.MINOR.MICRO, never overwrite | 3.9.4 → 3.10.4 (not 4.x) |
| Version content | what·why·who·when·approve | detective's W-form |
| Doc control (ISO9001) | available·protected·readable·marked | manual at the machine |
| Inversed Rule of 10 | later root cause = cheaper | snowball rolls UP |
| Requirement change | have-to vs can-be → CR→CCB | cracked frozen blueprint |
| Life-cycle phases | 0 invest…5 degrade | roller-coaster |
| LCM | coordinate cycles, no holes | no overload/no gap |
| BCG | Star·Cash Cow·Question·Dog | farmyard; ❓→⭐→🐄→🐕 |
| Config process | O-I-C-S-V | change lives in Control |
| Variant target | as needed / as few as possible | tool kits + std interfaces |
| Variant decision | read the SUM column | + = go, − = stop (case 3 trap) |
</content>
