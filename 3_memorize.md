# Risk Management — Memorize-It Guide 🧠

> How to use this: read each section's **story** once to *understand*, then cover the page and try to say the **📝 Write-in-exam** points from memory using the **🧠 Hook**. The story is the glue; the hooks are the handles. Do this twice and it sticks.

**The one big story that ties EVERYTHING together:**
You and your friends are building **Riku, a self-driving delivery robot**. You desperately don't want Riku to crash, hurt someone, or arrive late. Everything in this chapter is just *"how do smart engineers stop Riku from going wrong — and stop it as early and cheaply as possible?"* Keep Riku in your head the whole time.

---

## 0. The shape of the whole chapter (see this first)

Risk Management is **step 3 of System Engineering**: `1 Basics → 2 Requirements → 3 RISK → 4 Change → 5 Ideation → (6 Design) → (7 Test) → (8 Project Setup)`.

The whole chapter answers risk in **5 moves**, and they happen in order:

> **D-A-E-C-M-D** → *"**D**etectives **A**lways **E**at **C**old **M**exican **D**onuts"*
> **D**etect → **A**nalyse → **E**valuate → **C**ontrol → **M**onitor → **D**ocument

Memorize that one sentence and you already know the skeleton of the exam. Everything else just hangs off these six words.

---

## 1. What *is* a risk?

🧒 **Story:** Before Riku even moves, you ask: *"What could go wrong?"* Maybe the battery dies, maybe it rains. These haven't happened yet — they're *risks*. The moment Riku actually crashes, it's no longer a risk; it's a **problem** (too late!). That's the key difference.

📝 **Write in exam — Definition of risk:**
- **"Risk is the effect of uncertainty"** (definition from **ISO 9001**).
- Risk management's job: **sort and structure risks** in a structured way (→ PDCA).
- Risks are **events/circumstances that can prevent reaching the project goal** (probability **< 100 %**).
- If a risk **already happened → it's a *problem*** (handled differently!).
- Separate **general company risks** from **project-specific risks**.

🧠 **Hook:** *Risk = "not yet". Problem = "already".* Probability under 100 % = still a risk.

---

## 2. PDCA — the engineer's heartbeat

🧒 **Story:** How do you do *anything* well? Like baking cookies: **Plan** the recipe → **Do** the baking → **Check** the taste → **Act** to make the next batch better. Engineers call this loop **PDCA**, and they spin it forever. It comes from **ISO 9001** and is also called the **Deming cycle / Shewhart cycle**.

📝 **Write in exam — PDCA:**
- **Plan** — plan the process/product; set goals & resources; address risks & opportunities.
- **Do** — implement the plan.
- **Check** — monitor and measure the process / target condition.
- **Act** — take action to improve performance.

🧠 **Hook:** **P-D-C-A** = "**P**lease **D**on't **C**rash **A**gain." It's a *circle*, never a straight line.

---

## 3. Three things teachers love to ask ("general principles")

🧒 **Story:** Three surprising truths about risk that sound clever in an exam:
1. Risks have a good twin — **opportunities** (a risk can be a *positive* event too!).
2. People are scared to report bad news, so you build a **"speak-up line"** — an *anonymous* tip box so anyone can warn you about Riku without getting in trouble.
3. Money adds up (2€ + 2€ = 4€), but **risks do NOT add up** — you must *aggregate* them with models like **Monte Carlo simulation**.

📝 **Write in exam:**
- Opportunities can be recorded as **positive events**.
- Set up an **anonymous "speak-up line"** for unreported risks/violations.
- **Risks do not add up** → aggregate via **models & simulations (Monte Carlo)**.

🧠 **Hook:** **"O-S-M"** = **O**pportunity, **S**peak-up, **M**onte-Carlo (risks don't add).

---

## 4. Don't put all eggs in one basket (Portfolio & diversification)

🧒 **Story:** Imagine your pocket money. If you bet it ALL on one lottery ticket, that's super risky. If you spread it across different, *unrelated* things, you're safer for the same reward. Companies do the same with their projects. There's an **efficiency curve**: the best mixes sit *on* it; nothing can be *above* it; anything *below* it is wasteful. The Nobel-Prize idea behind this is by **Harry Markowitz**.

The exam's favourite trick — **how to make Riku's 50%-reliable crash sensor better:**
- ❌ **Wrong:** add a **second identical sensor**. Same solution to the same problem → it actually *increases* failure ("guaranteed one will fail").
- ✅ **Right:** add a **mechanical crash detector** — a *different, non-correlating* solution.

📝 **Write in exam:**
- Diversify: *"not all in one basket"* — use **asset** (different products) and **time** diversification (idea by **Markowitz**, Nobel Prize).
- Optimum portfolios lie **on the efficiency curve**; below it is **inefficient**.
- To reduce risk: implement **diversified & non-correlating** solutions (mechanical sensor, *not* a 2nd identical ECU).

🧠 **Hook:** *Two of the same = double trouble. Two different = real safety.*

---

## 5. The rulebook (Standards)

🧒 **Story:** You can't just *say* you manage risk — big standards *make* you. **ISO 9001** demands **"risk-based thinking"** (what if things deviate?). **ISO 31000** is the dedicated "Risk Management" standard. And companies must keep a money jar — **provisions** (German *Rückstellungen*) — to pay for risks if they hit. Top bosses are responsible: risk management is a **managerial task**.

📝 **Write in exam:**
- **ISO 9001** → **"risk-based thinking"** (use opportunities, prevent unwanted outcomes).
- **ISO 31000** → "Risk Management".
- Must form **provisions (Rückstellungen)** for company & product risks → linked to **quality management**.
- Company-level risk management = a **managerial task**.

🧠 **Hook:** *"9001 thinks, 31000 manages, the jar (provisions) pays, the boss owns it."*

---

## 6. Risks come from everywhere (Levels affected)

🧒 **Story:** Riku can fail in *many directions* — not just "it broke." Group them into 3 buckets so 9 items become 3:
- **Product bucket:** Technical (too heavy), Compliance (fails admission test, corruption)
- **Money/Time bucket:** Finances (pricier tools), Time (delivery bottleneck), Market (embargo), Currency (exchange rates)
- **People/Planet bucket:** Social (demographic change), Project-management, Environmental

📝 **Write in exam (9 levels):** Technical/product · Compliance · Finances/costs · Time · Market · Currency · Social · Project-management · Environmental.

🧠 **Hook:** **3 buckets → Product, Money/Time, People/Planet.** Remember the buckets, the items fall out.

> Also: there are **6 levels of risk management** by **Gleißner & Mott**, and German law **KonTraG** forces management to do risk analysis.

---

## 7. Targets of Risk Management (the master list)

🧒 **Story:** This is just the **D-A-E-C-M-D** skeleton from Section 0, now with the **Control** step opened up. When you Control a risk, you have exactly **4 choices** — like dealing with rain:
- **Avoid** — don't go out at all (reduce occurrence to 0).
- **Prevent** — take an umbrella (mitigate impact).
- **Transfer** — send your brother instead (give the risk to someone better suited / insurance).
- **Accept** — just get a little wet (only if small!).

📝 **Write in exam — Targets:** **Detect → Analyse → Evaluate → Control → Monitor → Document & communicate.**
Control options = **Avoid · Prevent · Transfer · Accept**.

🧠 **Hook:** Skeleton = **"Detectives Always Eat Cold Mexican Donuts."** Control = **A-P-T-A** ("rain: Avoid, Prevent, Transfer, Accept"). *(These match the classic 4 T's: Terminate, Treat, Transfer, Tolerate.)*

---

## 8. DETECT — finding risks

🧒 **Story:** First you hunt for risks — **regularly and systematically**, looking both *inside* and *outside* the company. How often? Depends: a slow, stable company checks rarely; a fast-changing one checks often.

📝 **Write in exam — Detect:** Regular & systematic **internal and external** analysis of developments, events, changes; **frequency depends on volatility** of the environment.

**Methods to detect (6):** KPI changes · LeLe (lessons learned) · **Headstand/Flip-Flop** · **Delphi** · Risk workshop · **PAAG/HAZOP**.

🧠 **Hook:** *"**K**ids **L**ove **H**unting **D**own **R**isky **P**roblems"* → KPI, LeLe, Headstand, Delphi, Risk-workshop, PAAG.

Plus a second mini-list for **safety in development**: **ALARP** (As Low As Reasonably Practicable) · **FMEA** · **DRBFM** (Design Review Based on Failure Mode).

### 8a. Headstand / Flip-Flop method
🧒 **Story:** Stand the question on its head! Instead of *"How do we make Riku succeed?"* ask *"How could we make Riku fail as FAST as possible?"* — kids find this way easier and funnier, so more ideas pop out. Then flip the silly answers back into real safety actions.

📝 **4 steps:** (1) **Invert the thesis** → (2) **find solutions** for the flipped thesis → (3) **invert those solutions** → (4) **define actions**.

🧠 **Hook:** *Flip → solve → flip back → act.*

### 8b. Delphi method
🧒 **Story:** Ask many experts — but keep them in **separate rooms so nobody copies or bullies anyone**. Everyone answers *anonymously*, you reveal the big disagreements (with reasons), ask again, and repeat until they roughly agree. Then take the **average**. Named after the ancient **Oracle of Delphi** (wise predictions).

📝 **6 steps:** (1) leader explains topic & targets → (2) hand worksheet to each expert, **no discussion** → (3) **anonymous** hand-in + leader evaluates → (4) share **major deviations** + comments, redistribute → (5) **repeat 2–4** until consolidated → (6) take the **average**.

🧠 **Hook:** *"Silent experts, anonymous, repeat till they agree, then average."*

---

## 9. EVALUATE — scoring the risk

🧒 **Story:** Every risk gets **two scores**, like rating a scary movie:
- **Severity** — *how bad* if it happens?
- **Occurrence/Likelihood** — *how likely* to happen? (They call it "occurrence," NOT "probability," because it's a **human guess**, not a math calculation.)
Multiply/combine the two → a **risk matrix** that tells you which risks to worry about first. All risks go in a **risk list** the project manager keeps updated.

📝 **Write in exam:**
- Two properties per risk: **Severity** (how severe) + **Occurrence/likelihood** (how likely; subjective, *not* "probability").
- Combine → **risk matrix** to **prioritise**; keep an updated **risk list** (managed by PM / risk manager).
- To judge **impact**, use: **historical data** ("empirical values") · **probability distribution** (e.g. normal) · **Monte Carlo simulation**.

🧠 **Hook:** **Severity × Occurrence = Risk Matrix.** "How bad × how likely."

### The scales — don't memorize 10 rows, memorize the *pattern*:
- **Severity (example):** 1 = low (tiny, <1% cost, <2 weeks late) → 4 = very high (function impossible, >10% cost, >3 months late).
- **Occurrence (example):** 0 = 0% (eliminated) → 5 = 100% (it occurred → now a *problem*).
- **Risk matrix rule:** a **1 (low) severity** stays low even when likely; a **4 (very high) severity** climbs fast; **0% always = eliminated**; **100% always = occurred**.

🧠 **Hook:** *Low number = mild/best. High number = nasty/worst. 0 = gone, top = already happened.*

---

## 10. CONTROL — the 5 ways to handle it (deep dive)

🧒 **Story (rain again, plus a bonus):**
- **Avoid** → reduce occurrence to **0** (ban the activity, remove the feature). Use **technical barriers like Poka Yoke**.
- **Poka Yoke** (Japanese, *"avoid silly mistakes"*) → make it *physically impossible* to do it wrong, like a USB/SIM card that only fits one way ("**key-lock principle**"). Immediate error detection & avoidance.
- **Prevent** → reduce occurrence OR soften severity, using quality methods like **PDCA**.
- **Transfer** → move the risk to whoever handles it better. *E.g. the crash ECU shouldn't bear the whole crash → transfer the risk to the car's chassis.*
- **Accept** → some risks can't be removed cheaply; bosses **consciously accept** them — **only if occurrence AND impact are low**.

📝 **Write in exam:** Avoidance (occurrence→0, Poka Yoke) · Poka Yoke = Japanese "avoid silly mistakes", key-lock principle · Prevention (reduce occurrence/severity, PDCA) · Transfer (shift to who handles best, e.g. ECU→chassis) · Acceptance (consciously, only if low/low).

🧠 **Hook:** *Avoid (ban) · Poka-Yoke (mistake-proof) · Prevent (umbrella) · Transfer (chassis) · Accept (shrug, if small).*

---

## 11. FMEA — the star of the exam ⭐

🧒 **Story:** FMEA is a giant *"what could break, and what happens then?"* checklist that a team of experts fills in **early**, before Riku is even built. It hunts down failures so you can stop them in advance.

📝 **FMEA = Failure Mode and Effects Analysis** (German: *Fehlermöglichkeiten- und Einflussanalyse*). A **reliability-improvement method**. Rates defects by **Severity, Probability, Recognizability**.
**Goals:** spot **systematic & random errors before they occur** · derive **detection & prevention** measures · improve **successor products**.

### The FMEA family (super common question)
🧒 **Story:** Start with **FMEA**. Add a letter to upgrade it:
- **+ C = FMECA** → adds **"Criticality"** → lets you **prioritise**. (When people say "FMEA," they usually mean FMECA.)
- **+ D = FMEDA** → adds **"Diagnostics"** → for **automotive electronics**, counts how self-checking reduces failures.

🧠 **Hook:** **A → C(ritical) → D(iagnostics).** "A, add Critical, add Diagnostics."

**Types of FMEA:** **System** (whole system + interfaces) · **D-FMEA** (Design — customer focus, avoid systemic errors) · **P-FMEA** (Process — production weaknesses). D-FMEA and P-FMEA must **link** (a critical design feature = an **SC** that must be checked in the process).

### FMEA standards (group by domain)
📝 Industry: **IEC 61508**, **ISO 13849** · Automotive: **ISO 26262** · Aerospace: **DO-254**, **ARP 4761**.
🧠 **Hook:** *"Cars = 26262."* (Anchor on that one; the others cluster by industry/aerospace.)

### FMEA process
📝 Prepared **early** (before detailed plans) · built in **expert workshops** from many domains · created **from the cause → to the error** · finally **verify the assumed probabilities**.

### Rule of Ten 🔟 (memorize this!)
🧒 **Story:** The longer a mistake hides, the more it costs — **×10 at every stage**. Catch Riku's bug while *planning* = 1€. Miss it till the *customer* has it = 1000€+. So fix things EARLY.

📝 Cost ×10 per stage: **Planning 1€ → Development 10€ → Assembly 100€ → Final acceptance 1000€ → Customer.** Focus on **planning & development**.

🧠 **Hook:** *Every stage you're late, add a zero.* 1 → 10 → 100 → 1000.

### FMEA is a *living document*
📝 Maintain it through the project and until **EOP** (End of Production), better **EOS** (End of Sales). **Change the product → update the FMEA** (the classic real-world bug: change a part, forget the FMEA → it fails in the field!). Old FMEA = base for the next project (**LeLe**).

---

## 12. RPV — the FMEA score (Severity × Occurrence × Recognizability)

🧒 **Story:** To rank each failure, FMEA gives **three marks out of 10** and multiplies them:
- **Severity** — how bad? (1 = nobody notices … 10 = dangerous/illegal, death)
- **Probability/Occurrence** — how often? (1 = almost never … 10 = always, 1-in-2)
- **Recognizability** — can our design *catch* it? (1 = surely caught ≥99% … 10 = never caught <10%)

Multiply → **RPV** (Risk Priority Value). Big number = fix it first.

📝 **Write in exam:** **RPV = Severity × Probability × Recognizability**, each rated **1–10**. (Note the flip: for Recognizability, **1 = best/always detected, 10 = worst/never detected**.)

🧠 **Hook:** **"S × O × R"** — *"how SORe will it be?"* = **how Bad × how Often × can we Recognize it.** (This is the classic FMEA **S × O × D = RPN**, where Recognizability = Detection.)

### Special Characteristic (SC)
🧒 **Story:** If a feature is *super severe*, you stamp it **SC** on the drawing — like a red "MUST CHECK" sticker. Every SC must be measured in production. But don't sticker *everything* (too expensive!).

📝 High severity → **Special Characteristic (SC)**, marked on drawings, **each SC checked/measured** in production; can also be a **legal/regulatory** requirement. Don't over-use SC (cost!).
**Automotive variants:** **BMW** = L/S/F (**L**egal, **S**afety, **F**unction) · **Daimler** = DS/DZ (safety / certification docs) · **VW** = D/S (**D**ocumented, **S**afety).

🧠 **Hook:** *SC = red "MUST-MEASURE" sticker.* BMW has **3 letters (LSF)**, VW has **2 (DS)**.

### FMEDA (a bit more detail)
📝 FMEA **+ Diagnostics**, **multiple-error analysis**, automotive electronics; counts how **self-detection/correction** lowers the failure rate; adds **quantifiable error data** (failure probabilities, error-state distribution); good for **complex systems**.

---

## 13. Loose ends (quick wins)

- **Software providers** to track risks: **ClickUp · cplace · Jira** → key point: **consistent linking** with up/downstream processes. 🧠 *"CCJ tracks risks."*
- **Example file:** a bicycle **cable-pull** FMEA (*341_Example_FMEA_Bicycle*).

---

## 14. Summary (what you'd write to close an essay)

📝
- Risk management **avoids greater damage** to companies & products.
- Identify risks **as early as possible** (**Rule of Ten**).
- Rate risks by **severity & occurrence** in a **risk list**.
- In development/production: analyse each product with **FMEA** and derive **Special Characteristics (SC)**.
- 💬 *"Nothing happens without risk, but without taking risks also nothing happens."* — **Walter Scheel**. → Manage risk, but still **take risks to move forward**.

---

## 🎴 One-screen cheat-card (last 5 minutes before exam)

| # | Thing | Memory hook |
|---|---|---|
| Skeleton | Detect-Analyse-Evaluate-Control-Monitor-Document | **"Detectives Always Eat Cold Mexican Donuts"** |
| Control 4 | Avoid-Prevent-Transfer-Accept | **Rain: A-P-T-A** (=4 T's) |
| Risk vs problem | not-yet vs already | <100% = risk |
| PDCA | Plan-Do-Check-Act | **"Please Don't Crash Again"** (circle) |
| Detect methods | KPI, LeLe, Headstand, Delphi, Risk-workshop, PAAG | **"Kids Love Hunting Down Risky Problems"** |
| Evaluate | Severity × Occurrence → matrix | bad × likely |
| FMEA family | A → +C(rit) → +D(iag) | add a letter to upgrade |
| RPV | Severity × Occurrence × Recognizability | **"how SORe"** (=S×O×D) |
| Rule of Ten | ×10 per stage, 1→1000€ | every stage late = +1 zero |
| Diversify | different & non-correlating | 2 same = double trouble |
| SC | high severity → must-measure sticker | BMW=LSF, VW=DS |
| Standards | cars = ISO 26262 | anchor on cars |
| Headstand | flip → solve → flip back → act | stand it on its head |
| Delphi | silent, anonymous, repeat, average | Oracle of Delphi |
| Levels affected | Product / Money-Time / People-Planet | 3 buckets |
| Standards rulebook | 9001 thinks, 31000 manages | + provisions jar |
