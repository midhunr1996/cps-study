# Requirement Management — Memorize-It Guide 🧠

> How to use this: read each section's **story** once to *understand*, then cover the page and try to say the **📝 Write-in-exam** points from memory using the **🧠 Hook**. The story is the glue; the hooks are the handles. Do this twice and it sticks.

**The one big story that ties EVERYTHING together:**
A kid named **Mira walks into a robot shop and says: "I want a robot pet."** Behind the counter is **Pip, a parrot** whose only job is to **repeat the wish back perfectly** — because if Pip mishears even one word, the workshop in the back will build the **wrong** robot. The whole chapter is just *"how does Pip turn a fuzzy human wish into exact, written, testable orders the workshop can actually build — and keep them straight for the product's whole life?"* Keep **Mira (the customer), Pip (the requirement), and the workshop (the supplier)** in your head the whole time.

---

## 🎬 The Memory Movie (use this if sentences won't stick)

Don't memorize letters — **watch a movie**. Close your eyes and play *Pip builds Mira's robot pet* in 6 scenes. Each picture **is** one phase of the RM process, in order, so replaying the movie hands you the answer.

1. 🧺 Pip walks around with a **basket**, scooping up every wish, law and old note he can find. → **(1) COLLECT requests.**
2. ⚖️ He dumps the basket on a **judge's scale** and sorts them: *relevant? important? what kind?* → **(2) ASSESS requests** (this is where the **Kano** judge lives).
3. ✍️ He writes each survivor as a **crisp index card** — short, exact, testable. → **(3) DEVELOP requirements** (SMART · testable · linked).
4. 🪜 He carries the cards **down a ladder**, handing smaller and smaller orders to each workshop floor. → **(4) TIER DOWN** to component level.
5. ✅ He ticks a **checklist** as the workshop proves each card was built right. → **(5) track VALIDATION / VERIFICATION.**
6. 🔁 Someone changes their mind — Pip catches it and **updates every card**. → **(6) follow up of CHANGES.**

> Replay in one breath: **basket → scale → index cards → down the ladder → tick the checklist → catch the changes.**

**Two documents Pip carries (memorize these as two binders):**
- 📕 **Red "WISH" binder = PRD** (*Lastenheft*). The **customer's** list of *what* they want. ("Red = the customer's Request.")
- 📗 **Green "PROMISE" binder = Implementation Spec** (*Pflichtenheft*). The **supplier's** answer: *how* and *with what*. ("Green = the supplier's Guarantee.")

**Picture-hooks for the lists that won't stick:**
- 🌳 **Why RM?** — the **tree-swing cartoon**: everyone draws a different swing from the same words → that chaos is *why* Pip exists (one common understanding, no field disasters, happy customer).
- 🪜 **Kano's 5 shelves** — a shop with 5 shelves: a 🍞 **bread shelf** (basic/must — only noticed when empty), a 📈 **dial** (performance/should — more = happier), a 🎁 **surprise gift** (delighter/could — wow!), a 😐 **grey box** (indifferent — meh), a 🤢 **stink bomb** (reverse/don't — having it makes it worse).
- 🧠 **SMART** — a brain wearing a **smart-watch**: **S**pecific, **M**easurable, **A**chievable, **R**easonable, **T**ime-bound.
- 🔭 **Why "specific"** — *"the man on the mountain with the telescope"* — same sentence, 5 different drawings → fix it with **IF–THEN code**.
- 📺 **Why not TOO specific** — a **bicycle hidden in a TV box** — they fixed the *problem* (shipping damage), not the package → clever solution emerged.
- 🌉 **"Linked" disaster** — a **broken bridge with a 28 cm step** (Germany's North-Sea zero vs Switzerland's Mediterranean zero) → unlinked requirements smash together.
- 🛞 **System Wheel** — a **wagon wheel**: hub = mechanics/E-E/software, inner ring = the 7 "DNA" datasheet props, outer ring = the 10 extended properties.
- 🚪 **Tier-down flowchart** — a bouncer at a door: *acceptable? → in. Not? → can I tweak it? → yes: modify / no: throw it out.*
- 🛑 **Analysis paralysis** — a man **frozen forever at the planning desk**, never starting.
- 🔄 **ReqIF** — a **power-adapter plug** that lets two different requirement tools (and customer↔supplier) talk in one **XML** language.

**How to lock it in:** read a scene → shut your eyes → re-see the picture → say the meaning out loud. Movie + picture-hooks twice today, once tomorrow, then test with flashcards. **Seeing beats reading; testing beats re-reading.**

---

## 📖 The Full Story — "The Wish That Had to Be Caught Exactly" (read this once, like a bedtime story)

> The whole chapter as **one connected tale**. Don't try to memorize it — just *read it like a story* and let it run as a film in your head. Because each thing happens **for a reason**, the concepts stick by themselves. Exam words are in **bold**. After the story there's a tiny **beat → exam point** table.

A kid named **Mira** pushes open the door of a robot shop; a bell jingles, and she announces: *"I want a robot pet!"* Behind the counter sits **Pip, a bright green parrot**, whose entire job is to **repeat the wish back — perfectly.** Because in the workshop at the back, dozens of builders will build exactly what Pip squawks, word for word. Mishear one syllable and they build the *wrong* robot. So Pip leans in, because a wish is **not yet a buildable order.** His whole task is to turn Mira's fuzzy human wish into **exact, written, testable cards** the workshop can obey — and keep them straight for the robot's entire life.

First Pip writes the idea of his trade on the wall: a **requirement** is an **accurately phrased development target for one property**, already accounting for **every relevant condition** (will the pet live outdoors? must it be silent at night?). One robot pet, he warns, needs **hundreds to tens of thousands** of these cards — and the count only grows (an autonomous car gains more every year). Serious shops follow rulebooks for this — **ISO/IEC/IEEE 29148**, **SQuaRE (ISO 25000)**, maturity models like **CMMI** and **SPICE** — and it all lives inside the **ItO — Idea to Offer**, the journey from a customer's wish to a finished product.

Why be this fussy? Pip points at a cartoon pinned by the till: the famous **tree-swing**. The customer described a swing, sales drew another, the engineer a third, the workshop built a fourth, and what the customer *truly* needed was a fifth — all from the same few words. *That chaos is exactly why Pip exists.* Requirement Management **finds every requirement from supersystem down to component level and keeps them alive across the whole lifecycle**; it is the **enabler** of customer satisfaction, of one **common understanding** between customer and supplier, and of **avoiding safety/field disasters and costly late changes.** Set the targets wrong, Pip says gravely, and **the whole product is wrong.** His three eternal enemies: an **unclear** definition, an **incomplete** set (the missing card you find too late), and an **inaccurately interpreted** card.

To keep customer and workshop honest, Pip carries **two binders**. Mira hands him the **red WISH binder — the PRD (*Lastenheft*)** — the sum of everything *she* wants (the **"what"**), used in the **nomination phase** to ask suppliers for offers. The workshop reads it and writes back the **green PROMISE binder — the Implementation Spec (*Pflichtenheft*)** — *how* they'll build it and *with what* (technical concept, resources, plan), where **every PRD requirement must be answered by at least one deliverable.** The day Mira signs the green binder, building begins. *Red = the customer's Request; green = the supplier's Guarantee.*

The work itself runs as **six scenes**, always in order, and Pip acts them out. **Scene one — Collect:** he grabs a **basket** and scoops up wishes — from **outside** first (the **customer before everything**, then law, standards, cultural and social expectations) and from **inside** the shop (the old **Lessons-Learned** notebook, house standards, the kit of motors he's allowed, company strategy). He notices the more people he interviews, the **less new information each one adds.** He captures each demand as a **use case**: *"As a child, I want a pet that follows me, so that I'm never lonely."* That **LeLe** notebook is sacred: read at **kick-off**, updated throughout, and at the **closing workshop** the team bakes new wisdom into the standard — obeying the **golden rule** that a fix is **never just the negation of the problem.** "We tested too late" must become *"start the test at least two weeks before release, written into the project plan,"* not "don't be late."

**Scene two — Assess:** Pip can't build everything, so he sets a **judge's scale** and weighs each wish three ways — is it **relevant** to *this* product, how **important** is it, what **kind** is it? The celebrity judge is **Mr. Kano**, who sorts every feature onto one of **five shelves**: the **bread shelf** (basic/must — invisible when present, fury when missing), the **dial** (performance/should — more is happier), the **surprise gift** (delighter/could — unexpected wow), the **grey box** (indifferent — nobody cares), and the **stink bomb** (reverse/don't — having it makes things worse). The shelves **shift** by customer, by price, and over **time** (today's delighter is tomorrow's bread). To find the shelf, Pip asks a **functional and a dysfunctional question as a pair** and reads the class from the combination. He also files each wish as **Product / Process / External** (What / How / Rest) and as either **Functional** or a **non-functional requirement (NFR)** — the "how well," like 99.9% uptime.

**Scene three — Develop:** Pip writes each survivor as a tiny, perfect **index card** — **one idea per card, active voice, written so a robot could obey it.** A good card is **complete, correct, SMART, testable, linked, atomic**, free of weak words ("roughly", "very") and free of "should/must." Each carries a **passport**: unique ID, who asked, who wrote it, who'll use it, its **fit-criterion** (test), priority, version, status. The **SMART** brain wears a smartwatch: **Specific · Measurable · Achievable · Reasonable · Time-bound.** "Specific" matters because language lies — *"I saw the man on the mountain with the telescope"* gets drawn five ways, so you pin it down with **IF–THEN** logic. But don't over-specify: a firm asked to **stop bicycles being damaged in shipping** wasn't told *how*, so someone shipped each bike in a **box printed to look like a TV** — damage plummeted. *Specify the problem, not the solution.* "Testable" means measurable and **affordable to test** (don't crash ten real cars to check one card). And every card must be **linked** — recall the **bridge built by two countries** whose sea-level zeros differed, meeting mid-river with a **28 cm step**, then "fixed" the wrong way and **doubled.**

**Scene four — Tier down:** Pip carries the cards **down a ladder** — supersystem → system → sub-system → component — handing each floor an order it can actually build **and own.** The loudspeaker maker refuses to promise the sound inside the whole car — he never built the room! At every door stands a **bouncer**: does this card fit? In. If not — can I tweak it? Yes → modify; no → toss (with a reason). *Only promise what you can build.* **Scenes five & six — Verify and Changes:** Pip doesn't run the tests himself; he simply **ticks each card off** as the workshop proves it built right (real testing belongs to the **Test** chapter), and when anyone changes their mind he **chases that change** through every linked card, handing the heavy lifting to **Change Management.**

To forget no property of Mira's pet, Pip spins the **System Wheel** like a wagon wheel: a **hub** of the three trades (mechanics, E/E, software), an **inner ring** of the seven **"DNA" datasheet** properties, and an **outer ring** of **ten extended** properties (safety, EMC, thermal, sustainability…). Each property gets a **property engineer** — the **voice of the customer for that one property** — who optimises across the whole system, not a single component. One last warning: Pip could polish cards forever and **never let the workshop start** — the trap of **analysis paralysis.** Don't freeze; start building. And because thousands of cards can't live in Word or Excel, real shops use tools (**DOORS, Codebeamer, Jama**), and when two tools — or customer and supplier — must talk, they share one universal **XML adapter, ReqIF** (Requirement Interchange Format, kept by **ProSTEP iViP**).

> **The moral (your essay close):** RM is the **most important step in system design** — it runs in **six phases**, focuses on **properties not solutions**, carries the **red PRD** and **green Implementation Spec**, and remembers that if the targets are wrong the product is wrong — *but don't drown in analysis; start realizing.*

### 🔗 Story beat → what to write in the exam

| Story beat | Exam point |
|---|---|
| Pip must repeat the wish perfectly | **Requirement** = exact written development target for **one property**, all conditions; hundreds–tens of thousands |
| Rulebooks on the wall | Standards **29148**, **SQuaRE/25000**, CMMI/SPICE; lives in **ItO** |
| Tree-swing cartoon | **Why RM**: one common understanding; identify reqs supersystem→component, maintain lifecycle; wrong targets → wrong product |
| Two binders | **PRD/Lastenheft** (customer, "what") · **Implementation Spec/Pflichtenheft** (supplier, "how + with what"); every PRD req covered |
| Six scenes | Process: **Collect → Assess → Develop → Tier-down → Verify → Changes** |
| Basket + customer first | **Collect**: customer FIRST, then law/standards (external) + LeLe/strategy (internal); diminishing returns; **use case** (role/function/reason) |
| Sacred LeLe notebook | LeLe at kick-off + closing workshop → new standard; **fix ≠ negation of problem** (anchor a concrete action) |
| Judge's scale + Mr. Kano | **Assess**: relevance/priority/classification; **Kano 5**: bread·dial·gift·grey box·stink bomb; shifts by customer/price/time |
| Functional + dysfunctional pair | Kano survey method; classify **Product/Process/External**, **Functional vs NFR** |
| Perfect index card | **Develop**: atomic, active voice, SMART, testable, linked, no weak words; passport (ID/who/why/test/version/status) |
| Telescope sentence | **Specific** → fix ambiguity with IF–THEN |
| Bicycle in a TV box | Don't over-specify — **specify the problem, not the solution** |
| 28 cm bridge step | Every requirement must be **linked** |
| Ladder + bouncer | **Tier down** super→system→sub→component; accept/reject/feedback; only own what you can build |
| Ticking the checklist | **Verify (5)**: RM tracks ticks, doesn't test · **Changes (6)** → Change Management |
| Wagon wheel | **System Wheel**: hub (3 domains) + 7 DNA + 10 extended; **property engineer** = one property's customer-voice |
| Frozen at the desk | **Analysis paralysis** — start realizing |
| Universal plug | Tools (DOORS/Codebeamer/Jama); **ReqIF** = XML interchange (ProSTEP iViP), tool↔tool & customer↔supplier |

---

## 0. The shape of the whole chapter (see this first)

Requirement Management is **step 2 of System Engineering**: `1 Basics → 2 REQUIREMENTS → 3 Risk → 4 Change → 5 Ideation → (6 Design) → (7 Test) → (8 Project Setup)`.

The chapter answers requirements in **6 phases**, and they happen in order — this is the movie:

> **Collect → Assess → Develop → Tier-down → Verify → Changes.**
> Picture: **basket → scale → index cards → ladder → checklist → catch the changes.**

Memorize the **6-scene movie** and you already own the skeleton of the exam. Everything else just hangs off one of these six scenes.

🧠 **Hook:** Three characters carry the whole story → **Mira** (customer) → **Pip** (requirement) → **workshop** (supplier). *If Pip mishears, the whole product is wrong.*

---

## 1. What *is* a requirement? (Fundamentals)

🧒 **Story:** Mira says "robot pet." That's a wish, not a buildable order. Pip's job is to turn it into a **requirement**: an *exact written development target for one property*, that already accounts for all the conditions (Will it live outdoors? Must it be quiet at night?). One robot needs **hundreds to tens of thousands** of these cards.

📝 **Write in exam — Definition:**
- **Requirement = an accurately phrased development target for a property** of the system/component, **considering all relevant conditions**.
- **Amount:** hundreds to **(ten-)thousands**, depending on product complexity (and growing over time — e.g. autonomous cars).
- Defined in standards: **ISO/IEC/IEEE 29148** (software requirements engineering), **ISO/IEC 25000 (SQuaRE)**; part of maturity models **CMMI, SPICE (ISO/IEC 15504), ISO/IEC 12207**.
- Lives inside **ItO – Idea to Offer**: *customer requirement → ItO → offer → product* (purchasing procures in parallel; after test/validation & industrialization → release for production).

🧠 **Hook:** A requirement is **one exact card for one property** — not a vague wish. Picture the binder labelled **"29148"** for the software rulebook number.

---

## 2. Why do we even need RM? (the tree-swing)

🧒 **Story:** Show anyone the famous **tree-swing cartoon** — the customer explains a swing, sales describes another, the designer draws a third, the workshop builds a fourth, and what the customer *really* needed was something else entirely. That mess is exactly what Pip prevents.

📝 **Write in exam — Why RM:**
- RM **identifies the necessary requirements from (super)system level down to component level** and **maintains them over the whole lifecycle**.
- RM is the **enabler** to: increase **customer satisfaction** · get a **common understanding** between customer & supplier · **avoid safety/field (quality) issues** · avoid **late changes & cost impacts** · feed **LeLe**.
- ➡ RM is the **essential discipline in systems design — if the targets are set wrong, the whole product is wrong!**

🧠 **Hook:** *Same words, five different swings.* RM = **one common picture**.

**Challenges** (3): **clear definition** · **completeness** (missing reqs found too late) · **inaccurate interpretation**. 🧠 *"Clear, Complete, Correctly-read"* → and **LeLe is important!**

---

## 3. The two binders (Core Documents)

🧒 **Story:** Pip carries **two binders**. First Mira hands over the 📕 **red WISH binder (PRD)** = everything *she* wants. The workshop reads it and writes back the 📗 **green PROMISE binder (Implementation Spec)** = exactly *how* and *with what* they'll build it. When Mira signs the green binder, building begins.

📝 **Write in exam — PRD (*Lastenheft*):**
- **Sum of all requirements of a commercial customer** (not necessarily the end user).
- Standards: **DIN 69901-5**, or IEEE **SRS (29148)**.
- Used in the **nomination phase** to request technical & commercial **offers** from suppliers.
- **Content:** Introduction · current state · target (main requirements) · interfaces · **functional** reqs · **non-functional (NFR)** · system architecture · expected scope of delivery · acceptance criteria.
- **Internal** dev → detailed & tiered down. **External** dev → keep generic (property level) to **avoid specifying the solution**. Takes several clarification rounds; customer picks the best offer.

📝 **Write in exam — Implementation Spec (*Pflichtenheft*):**
- The **supplier's answer to the customer's PRD**.
- Contains the **"How"** (technical concept) and the **"With what"** (resources, project plan).
- **Every PRD requirement must be covered** by ≥1 deliverable. **Customer acceptance → development starts.**

🧠 **Hook:** **Red = Request (customer, "what")** · **Green = Guarantee (supplier, "how/with what").** German: *Lastenheft* (load you carry) → *Pflichtenheft* (duty you accept).

---

## 4. The 6-phase process (the spine)

🧒 **Story:** This is the **movie** again — Pip's six scenes. Different rulebooks describe it (**IEEE SWEBOK, CMMI, IIBA/BABOK, Volere, IREB**), but the lecture uses one variant with two freeze points: **PRD freeze** and **Implementation-spec freeze**. In big projects a **requirement manager** steers it.

📝 **Write in exam — 6 phases:** (1) **Collect** requests → (2) **Assess** requests → (3) **Develop** requirements → (4) **Tier down** → (5) **Validation/Verification** → (6) **Changes**.
**Cascade of who:** Customer (request) → **Property Engineer** (1→x system properties) → **Developer** (x→y component requirements).

🧠 **Hook:** **basket → scale → index cards → ladder → checklist → catch the changes.**

---

## 5. (1) COLLECT — fill the basket

🧒 **Story:** Pip scoops up wishes from **outside** (Mira first!, plus law and rules) and from **inside** the shop (old notebooks, house rules). But careful — interviewing **more and more people gives *less and less* new info** (diminishing returns).

📝 **Write in exam — external requests:** **!!!Customer!!! (the prior source!)** · Law · Standards & guidelines · Cultural · Political · Social expectations.
📝 **Internal requests:** **LeLe** · company **standards** · existing **tool kits** (must use motor A/B) · **company strategy** (no sourcing abroad) · **CI/design** (green rounded corners) · business-dept restrictions.
📝 **Use cases** capture demand: **"As [role] / I would like to [function] / To [reason]."** Named after the goal.

🧠 **Hook:** *Customer first, then the world outside, then your own shop.* And **fewer secrets per extra interviewee** (knowledge curve goes down).

### 5a. LeLe — Lessons Learned 📔
🧒 **Story:** At the **kick-off**, the team reads the old notebook so they don't repeat last project's mistakes. They keep updating it, and at the **end** hold a workshop to write the new wisdom into the standard.

📝 **Write in exam:** use prior-project knowledge at the **start** (kick-off workshop) → **constantly update** during → **end workshop** transfers "what went well / what to improve" into the **new standard** for follow-up projects. Covers **technical, project-management, commercial** knowledge; document **in software**.
⚠ **The golden LeLe rule:** *the solution is NOT the negation of the problem.* "We started the test too late" → **NOT** "don't start so late" → **YES** "start the test ≥2 weeks before release and anchor it in the project plan." (Same for positive feedback.)

🧠 **Hook:** *Don't just say "don't do that" — write a concrete, anchored action.* Picture a notebook that **bookends** the project (start & end).

### 5b. Standards 🌍
📝 **Regional:** TGL (DDR) · **DIN** (German) · **GB/GB-T** (China). **International:** **EN** (European) · **ISO** (mechanics) · **IEC** (electrical/electronics). **Industry:** **IATF** (automotive) · **VDE** (electrotechnics).
🧠 **Hook:** *Mechanics = ISO, Electrons = IEC, Europe = EN, Cars = IATF.*

### 5c. "Who is the customer?" pitfall
📝 The parents-choosing-for-the-child cartoon: wrong requirements come from **misunderstanding who the real customer/user is**.

---

## 6. (2) ASSESS — the judge's scale ⚖️

🧒 **Story:** Pip can't build everything, so he **judges** each wish three ways: is it **relevant** here? how **important** is it? what **kind** is it? The most famous judge on the scale is **Mr. Kano**.

📝 **Write in exam — assess by:** **Relevance** (relevant for *this* product? e.g. not sold in Japan → ignore Japanese law) · **Priority** (which wins if not all fit? e.g. airbag vs turn signal; depends on **company strategy**) · **Classification**.
📝 **Design strategies (priority depends on them):** Design for **Customer** (Design Thinking) · **Costs** · **Quality/Reliability** · **Production/Manufacturing (DFM)** · **Service**.

### 6a. The Kano Model — 5 shelves 🪜
🧒 **Story:** Kano sorts every feature onto one of **5 shelves** by how it moves Mira's happiness:
- 🍞 **Basic (must)** — bread. Invisible when present, *furious* when missing. Can't beat competitors with it. *(call-centre greeting)*
- 📈 **Performance (should)** — a dial. **More = happier**, less = grumpier. *(hotline waiting time)*
- 🎁 **Delighter (could)** — a surprise gift. Unexpected → **wow**; a little gives a lot. *(live status tracking of your ticket)*
- 😐 **Indifferent** — a grey box. Present or not, nobody cares. *(the hold-music song)*
- 🤢 **Reverse (don't)** — a stink bomb. Having it makes things **worse**. *(jargon in a hotline call)*

📝 **Classification shifts by:** **customer** (delighter for one = reverse for another) · **price/business model** (delighter on a budget = basic on a premium) · **time** (today's delighter = tomorrow's basic).
📝 **Survey:** structured interview / written survey; **standardised** (remove interviewer impact); include **demographics** (find peer groups & variants). Ask a **functional + dysfunctional** pair ("how if it had MORE…?" / "…if it had LESS…?") and read the class from the combination:

| Functional | Dysfunctional | Class |
|---|---|---|
| I expect it | I dislike it | basic (must) |
| I like it | I dislike it | performance (should) |
| I like it | I am neutral | delighter (could) |
| neutral | neutral | indifferent |
| I dislike it | I expect it | reverse (don't) |
| both "I like it" / others | | remove / questionable |

🧠 **Hook (the order of happiness):** **Bread → Dial → Gift → Grey box → Stink bomb.** Missing bread = angry; more dial = happier; gift = wow; grey = meh; stink = ugh. *(Car: must=it drives · should=horsepower · could=launch control · indifferent=underfloor-screw colour · reverse=new rust after a wash.)*

### 6b. Classification of requests
📝 **By belonging:** **Product (What)** *[SE focus]* · **Process (How)** · **External (Rest)**. **By function:** **Functional** (prints my file) vs **NFR** (24/7, 99.9% uptime).
📝 **Function attributes:** inputs/outputs · value range/dimensions · tolerance · how often executed · how fast (throughput time).

🧠 **Hook:** **What / How / Rest** = Product / Process / External. **NFR = "how well", not "what".**

---

## 7. (3) DEVELOP — write the perfect index card ✍️

🧒 **Story:** Now Pip writes each requirement as a tiny, perfect card. Rule of thumb: **one idea per card, written like a robot could obey it.**

📝 **Write in exam — a good requirement is:** **Complete** (no supplier assumptions) · **Correct** · **SMART** · **testable** · **linked** · **necessary** (no "nice-to-haves") · **short** · **atomic** (one req/sentence) · **active voice** ("The motor rotates the shaft" ✅, not "is driven by" ❌) · **no weak words** ("really/very/roughly" — tools: **ReQualize, DESIRe**) · **avoid "should/must"** · **understandable** · **traceable** · **unambiguous & consistent** · **feasible** · **equipped with properties**.

🧠 **Hook:** *One card, one idea, active voice, no fuzzy words.*

### 7a. Properties of a requirement
🧒 **Story:** Each card has a little **ID badge**: who asked, who wrote it, who uses it, why, how to test it, how important, what it links to, its version & status.

📝 **Properties:** unique **ID** · description · **rationale/target** · **originator** · **creator** · **user** · **fit criterion** (testable) · **priority** · dependencies/interfaces · conflicts · release/maturity · linked documents · comments · **version** · **change history** · **status**.

🧠 **Hook:** *Every card needs a passport: ID, who, why, test, version, status.*

### 7b. SMART 🧠⌚
📝 **S**pecific · **M**easurable · **A**chievable · **R**easonable · **T**ime-Bound.
🧒 **Story (Specific):** *"I saw the man on the mountain with the telescope"* — five people draw five different pictures. Natural language is **ambiguous** → fix with **IF–THEN–ELSE code** and **exclude variants**.
🧒 **Story (not too specific):** a company asked to **cut shipping damage on a bicycle** (not "improve the box"). Result: a box that **looks like a TV** → far fewer damages. Specify the *problem*, not the *solution*.

🧠 **Hook:** Brain in a **smart-watch**. + *telescope picture = be specific* / *bicycle-in-a-TV-box = don't over-specify.*

### 7c. Testable 🧪
📝 To be testable a requirement must be **specific, detailed, affordable to test, linked to a maturity level.** *"The charger needs to be efficient"* = untestable (75%? 80%?). *"Mute button accessible after a crash"* = make sure the test is **affordable** (don't crash 10 real cars!).

📝 **Writing guideline (Bad → Better):** positive not negative · avoid "could/should" · be specific ("robust" → "works after 10× 2 m drops on concrete") · **what not how** ("handle on top" → "a possibility to carry it").

🧠 **Hook:** *If you can't measure it, you can't test it.* And *don't break the bank (or the car) to check.*

### 7d. Linked 🔗
🧒 **Story:** Every card holds hands with its neighbours. The 🌉 **bridge built from two countries** (North-Sea zero vs Mediterranean zero) ended with a **28 cm step** — and the fix went the **wrong way**, doubling it. That's what unlinked requirements do.

📝 **Link each requirement to:** its **request** (background) · **child & mother** reqs (hierarchy) · **neighbour** reqs (mutual impact) · **functions & NFR** · **test items** · **interfaces**.

🧠 **Hook:** *The 28 cm bridge step = always link your requirements.*

### 7e. SCRUM / product backlog
📝 Agile, mainly software: **Epic → feature request → product backlog**. Same idea, highly simplified. Backlog row = use-case format (Role / Function / Reason) + priority + story points + sprint + status.

---

## 8. The System Wheel 🛞 (recap, used to develop requirements)

🧒 **Story:** To not forget any property of Mira's robot, Pip spins a **wagon wheel** of properties.

📝 **Write in exam — 3 layers:**
- **Hub = realization domain:** mechanics · E/E · software.
- **Inner ring = core "DNA" (datasheet):** performance · consumption · acoustic · costs · reliability · weight · size.
- **Outer ring = 10 extended properties:** acoustical behaviour · performance & efficiency · data acquisition/access & security · design for production/service/upgrade · **safety** (ISO 26262, FuSiKo/HARA) · **EMC** (emission, immunity, ESD) · sustainability · reliability · thermal behaviour · volumetric behaviour & design (incl. **FMK** tolerance concept, crash behaviour).

📝 **Property engineer** = the **voice of the customer for one property**; optimises **across the system** (not one component); thinks in **system functions**, not components/org-charts; breaks function down to component reqs while domains offer different solutions; **system engineer decides conflicts**.

🧠 **Hook:** Wheel = **hub (3 domains) + inner ring (7 DNA) + outer ring (10 extended).** Property engineer = *one property's customer-voice.*

---

## 9. (4) TIER DOWN — carry the cards down the ladder 🪜

🧒 **Story:** Pip walks the cards **down** from supersystem → system → sub-system → component, handing each floor an order it can actually build and **own**. A loudspeaker maker **won't promise the sound inside the whole car** — he didn't build the room! Each receiver must **accept, reject, or ask to change** the card.

📝 **Write in exam:** tier down system → component level; the receiver (e.g. component team) must **accept / reject / feedback for change**; they must be able to **take responsibility**.
📝 **New-requirement flow:** new req lands in **inbox/pool** → **acceptable?** → *yes:* add to component reqs → END. *no:* **modification possible?** → *yes:* modify (or decline **with reason**) · *no:* **discard**.
📝 **Hierarchy:** **Supersystem (4) → System (3) → Sub-system (2) → Component (1).**

🧠 **Hook:** *A bouncer at each door:* fits? in. Doesn't? can I tweak it? yes→modify / no→toss. *Only promise what you can build.*

---

## 10. (5) Verify & (6) Changes — the last two scenes

🧒 **Story:** Pip doesn't run the tests himself — he just **ticks them off** as the workshop proves each card. And when anyone changes their mind, he **chases the change** through every card.

📝 **Write in exam:**
- **(5) Validation/Verification:** all reqs must be **testable**; RM does **not verify** but **tracks** that each was **confirmed by testing** (→ *Test & Verification* chapter).
- **(6) Changes:** track & follow up **changes of requests/requirements** (→ *Change Management* chapter).

🧠 **Hook:** *RM tracks the ticks, it doesn't do the tests.* Changes → hand off to Change Management.

---

## 11. Don't freeze! (Analysis Paralysis) 🛑

🧒 **Story:** Pip could polish cards forever and **never let the workshop start**. Don't.

📝 **Write in exam:** RM is vital, but **avoid "analysis paralysis"** — analysing forever to be 100% perfect **instead of starting realization**.

🧠 **Hook:** *A man frozen at the planning desk.* Start building.

---

## 12. Software & ReqIF 🔄

🧒 **Story:** Thousands of cards need real tools (not Word/Excel). And two different tools — or customer & supplier — talk through one **adapter language: ReqIF**.

📝 **Write in exam:**
- **Software must** administrate, structure/sort/filter, tailor to owner, manage workflow/status, **link**, version & change-history, **branch** for products; **traceability & transparency** matter.
- **ReqIF = Requirement Interchange Format** — an **XML** format, managed by **ProSTEP iViP e.V.**, to **exchange requirements between tools and between customer & supplier**.
- **Tools:** Codebeamer (PTC) · DOORS (IBM) · JAMA. **Agile:** ClickUp · cplace · Jira (Epic → product backlog → sprint backlog).

🧠 **Hook:** *ReqIF = the universal plug (XML) between tools and partners.*

---

## 13. Summary (what you'd write to close an essay)

📝
- **RM is the most important step in system design** — right product, right quality, highest **customer satisfaction**.
- It runs in **6 phases** and must focus on **properties, not technical solutions**: **Collect → Assess → Develop → Tier-down → Verify → Changes.**
- Two core documents: **PRD (Lastenheft, customer's "what")** and **Implementation Spec (Pflichtenheft, supplier's "how/with what").**
- *If the targets are set wrong, the whole product is wrong* — but **don't drown in analysis paralysis; start realizing.**

---

## 🎴 One-screen cheat-card (last 5 minutes before exam)

| # | Thing | Memory hook |
|---|---|---|
| Skeleton | Collect·Assess·Develop·Tier-down·Verify·Changes | **basket → scale → cards → ladder → checklist → catch changes** |
| Requirement | exact card for ONE property, all conditions | not a vague wish |
| Why RM | one common picture; targets wrong → product wrong | the **tree-swing** cartoon |
| Two docs | PRD=Lastenheft (customer, what) · Impl.Spec=Pflichtenheft (supplier, how) | **Red Request · Green Guarantee** |
| Collect | customer FIRST, then law/standards; internal=LeLe etc. | basket; fewer secrets per extra interviewee |
| LeLe rule | solution ≠ negation of problem; anchor a concrete action | "start test ≥2 wks early, in the plan" |
| Kano 5 | basic·performance·delighter·indifferent·reverse | **bread·dial·gift·grey box·stink bomb** |
| Kano shifts | by customer · by price · over time | delighter→basic over time |
| Classify | Product / Process / External · Functional / NFR | What / How / Rest |
| Develop | atomic, active, no weak words, testable, linked | one card, one idea |
| SMART | Specific·Measurable·Achievable·Reasonable·Time-bound | brain in a smart-watch |
| Specific | language is ambiguous → IF-THEN | "man on mountain with telescope" |
| Not too specific | specify problem, not solution | **bicycle in a TV box** |
| Linked | request·mother/child·neighbour·function·test·interface | the **28 cm bridge step** |
| System Wheel | hub(mech/EE/sw) + 7 DNA + 10 extended | wagon wheel |
| Tier down | accept / reject / feedback; only own what you can build | bouncer at each door |
| Verify (5) | RM tracks ticks, doesn't test | checklist |
| Changes (6) | track & follow up | hand to Change Mgmt |
| Paralysis | don't analyse forever | frozen at the desk |
| ReqIF | XML, ProSTEP iViP, tool↔tool & cust↔supplier | universal plug |
