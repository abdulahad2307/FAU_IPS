# Integrated Production Systems (IPS) — Complete Study Notes

**A from-scratch study guide for the IPS exam**
Prof. Dr.-Ing. Jörg Franke · FAPS · FAU Erlangen-Nürnberg

---

## How to use these notes

These notes assume **zero prior knowledge**. Every technical term is defined the first time it appears, and every Japanese/lean keyword is kept **exactly as it is used in the lecture** (Kaizen, Kaikaku, Jidoka, Poka Yoke, Heijunka, Gemba, Muda/Muri/Mura, Chaku-Chaku, etc.) so you learn the vocabulary the examiner expects.

The course has **13 lecture units** plus **3 case studies**. The exam draws on both:
- **Lecture units** → mostly *explain / compare / list* questions (qualitative).
- **Case studies** → mostly *calculate* questions (OEE, Cp/Cpk, energy, income statements).

**The single most important mental model in the whole course** is the **IPS "House"** (explained in Unit 2). Almost every method you learn is a brick in that house. If you can draw the house and place each method in it, you understand the course.

At the end of each unit you'll find **"Exam focus"** — the things most likely to be asked, several of them lifted from the *mock questions the lecturer embedded in the slides themselves*.

---

## The big picture (read this first)

An **Integrated Production System (IPS)** is a company-specific, logically structured **set of standards, principles, methods and tools** that defines *how a company produces*. "Integrated" means the elements are **not used in isolation** — they reinforce each other. Using one method alone (e.g. just Kanban) without the supporting culture and methods leads to **goal conflicts** and failure.

The whole philosophy is usually called **Lean Production** (its origin is the **Toyota Production System, TPS**, developed by **Taiichi Ohno**). Lean is built on avoiding **all unnecessary work** and producing **in the cycle (takt) of the customer**.

The **overarching goals** (the "roof" of the house):
- **Lowest costs**
- **Highest quality**
- **Shortest lead times**
- **Highest safety**

The **three core principles** everything rests on:
1. **Value creation through elimination of waste**
2. **Process orientation / flow principle / just-in-time**
3. **Continuous improvement process (CIP) / pursuing perfection**

Keep those three principles in your head — they are the spine of the entire course.

---

# Unit 1 — History of Integrated Production Systems

**Why it matters:** You cannot understand *why* lean exists without understanding the problems of the systems that came before it. Exam questions here are about **naming the stages, their characteristics, and their limitations**.

### The historical progression

**1. Handcraft (manufacture)**
- Before industrialization: skilled craftspeople made whole products by hand.
- Regional example used in the lecture: **Nuremberg** — toy trade (dolls from the 14th century, tin soldiers), **pencil production (Staedtler, Faber-Castell)**, the **"Adler"** (first steam engine in Germany, 1835), ball-grinder by **Friedrich Fischer (1883)**, **"Hercules"** bikes (1886), the **"Torpedo"** free-wheel hub.
- **Manufactories** (19th century) were the *transitional stage*: they divided the varied activities of one profession into **single steps** — the first move toward division of labor.
- Limitation: highly manual, fragmented industry, serial-production technology **not yet mature**.

**2. Taylorism — "Scientific Management"** (Frederick W. Taylor, book *"The Principles of Scientific Management"*, **1911**)
- Taylor (born 1856, Pennsylvania; worked at Midvale Steel and Bethlehem Steel) applied **scientific methods** to production work.
- **Three basic methods of Taylor:**
  1. **Separation of planning from execution** — management plans, workers execute.
  2. **Scientific analysis** of each task to find the **"one-best-way"** to do a job.
  3. **Detailed instruction** of the worker (worker-machine level) from above.
- **Result:** production could be **rationalized** (made efficient), BUT the worker's **self-determination and individual responsibility were denied**. The worker became responsible only for a **sub-activity**, no longer for solving problems.

**3. Ford — the assembly line** (Henry Ford, Model T)
- Idea borrowed from the **conveyors in US abattoirs / grain elevators** (1870).
- **Characteristics of Ford's line production:**
  - Production divided into **single specialized steps**.
  - Resources organized **by the production flow**.
  - All steps prepared in the **same cycle time**.
  - An interruption in one step **blocks the whole line**.
  - **High vertical integration** → high complexity.
- **Achievements:** production time per car fell from **12.5 h (1913)**; productivity grew **~152 %** (1913→1914); car price fell from **$1,300 (1910) to $290 (1924)**.
- **Problems (the limits of Ford + Taylor):**
  - Higher **fault liability** of the whole production.
  - **Limited worker freedom of action.**
  - **Alienation, deadening, motivation problems** from monotonous work.
  - **Lack of communication** → social problems.

**4. Approaches to overcome Taylorism**
- **Volvo (1970s, Uddevalla):** abolished the assembly line; **autonomous group work**, minimized hierarchy, **work rotation**, process-oriented stations, management by objectives.
- **Volkswagen (1980s, Wolfsburg, "Hall 54", Golf II):** tried to overcome Taylor by **automation** — replacing monotonous work, using employees as **skilled technicians** to control robotics. Problems: **reduced availability** (setting/standstill of machines), team tension, workers hoarding exclusive knowledge.
- **Toyota / Lean Production (Taiichi Ohno):** the successful answer. **Lean is not a discrete concept but a philosophy** of avoiding all unnecessary work, producing in the **customer's cycle**, with **highly skilled workers** and **high availability of machinery**. Over 50+ years of consistent profitable growth Toyota **passed GM** as the world's largest carmaker.

### Exam focus — Unit 1
- Be able to **list the stages** (handcraft → manufactory → Taylorism → Ford → attempts to overcome → Lean) and give **one characteristic + one limitation** of each.
- Know **Taylor's 3 methods** and the **"one-best-way" principle**.
- Know the **characteristics of Ford's line** and **why it and Taylorism had to be replaced**.
- Know that **Lean = Toyota Production System = Ohno**, and that it is a **philosophy**, not a single tool.

---

# Unit 2 — Structure of Integrated Production Systems (the "IPS House")

**Why it matters:** This is the **conceptual backbone** of the whole course. Expect a question that asks you to describe the IPS house and/or explain why elements must be considered **collectively**.

### Definition
> An **integrated production system** is the **classification that logically structures the methodical standards within production**. A production system **fixes how to produce.**

It does three things:
- Describes **style guides, methods and standards**.
- Realizes a **lean factory** across four goal dimensions: **variability, quality, speed, profitability**.
- **Measures continuous improvement** of processes with appropriate **operating figures (KPIs)**.

**Key rule:** *IPS can only exist if every individual element is strong enough and coincides with the others.* → This is exactly why one of the embedded mock questions asks you to name IPS elements and explain the **goal conflicts** if they are implemented in isolation.

### The "House" representation
The company-specific IPS is drawn as a **house**:
- **Roof = the goals** (lowest costs, highest quality, shortest lead times, highest safety — plus adaptability, high working morale).
- **Pillars = the main topic areas** (e.g. Elimination of Waste, Standardized Processes, Total Quality Management, etc.). The pillars **stand side by side as equals**.
- **Foundation = Stability + company-specific basic principles.**
- Cross-cutting base themes: **People and Teamwork, Process Orientation, Continuous Improvement.**

### Modular construction — the 3 levels of each pillar
Each pillar of the IPS house is built from **three levels**:
1. **Level 1 — Principles** (the "why", the culture, e.g. Kaizen).
2. **Level 2 — Design principles / Methods** (the "what").
3. **Level 3 — Tools** (the concrete "how").

> Note: there **need not** always be a difference between level 2 and 3 — some design principles are implemented **directly by a tool**. *Example from the slides: the 8D-Report integrates level 2 and 3, for Kaizen (level 1).*

### Activities: Waste vs Value-adding vs Additional work
A central classification you will be asked to apply (there's a mock question on classifying **an engineer's office tasks**):
- **Value-adding activity** — anything the **customer is willing to pay for**; changes the product toward what the customer wants.
- **Waste (Muda)** — any step that does **not** add value from the customer's view. Adds cost, not value → should be **eliminated**.
- **Additional work (necessary non-value-adding)** — does not add value **but is currently necessary** (e.g. set-up, inspection, transport that can't yet be removed). You try to **minimize** it.

**How to translate customer value into the process:** constantly ask *"Is this what the customer wants?"* and *"Is this step necessarily needed?"*

### Introducing IPS affects stakeholders
Rolling out IPS affects **not only your own company but also suppliers and partners** (there is a **dispositive effort** — planning/coordination cost — for introducing single methods).

### Industry 4.0 context
IPS spread at the **start of the 21st century**. We know **three industrial revolutions**; we may be close to the **fourth (Industry 4.0)** — new technologies + organizational principles.

### Exam focus — Unit 2
- **Define an IPS** in one sentence ("...fixes how to produce").
- **Draw / describe the IPS house**: roof (goals), pillars (equal topic areas), foundation (stability).
- **The 3 levels** (principle → method → tool) and the **8D-report example**.
- **Classify activities** into waste / value-adding / additional work **with a practical example** — practise on an office task.
- Explain **why elements can't be isolated** (goal conflicts).

---

# Unit 3 — Continuous Improvement Process (CIP / Kaizen)

**Why it matters:** CIP is one of the **three core principles** and one of the biggest method-toolboxes in the course. The embedded mock questions ask you to explain the **principles of CIP/Kaizen**, list **methods/tools** (Ishikawa, Pareto, VSM…), and name **barriers** to CIP.

### The core idea
A consistently implemented **CIP** is a **very effective** way to improve productivity — **more effective than any single revolutionary idea and cheaper than any automation solution.**

**Kaizen** = Japanese: **改 ("kai") = "change" + 善 ("zen") = "good"** → *"change for the better."* Philosophy: **no day passes without improvement.**

Kaizen principles:
- Ongoing **change for the better**, in **small steps**.
- Simple, fast, **cost-effective** problem solving.
- Permanent focus on **customer benefit and value**.
- **Avoidance of the 3 MU: Muda (waste), Muri (overload), Mura (unevenness).**
- **Participation of all employees** (managers and staff); improvement ideas from **every** employee.
- Improvements must be **holistic and across all levels**.
- CIP requires a mindset of **long-term, permanent, sustainable success.**

### The 3 MU (memorize these)
- **Muda = Waste** (non-value-adding activity).
- **Muri = Overload** (of people or machines).
- **Mura = Unevenness / fluctuation** (in workload or flow).

### Kaizen vs Kaikaku
- **Kaizen** = continuous, **small** improvements; low resource requirement; *cannot* accomplish extensive changes alone.
- **Kaikaku** = **radical, large-scale** change/reengineering; high resource + labor requirement; removes **large obstacles** to reach **strategic goals**.
- **Recommended: combine both.** Kaizen for the many small barriers; Kaikaku for the big strategic jumps. (Source cited: Yamamoto, *Kaikaku in production*, 2010.)

### PDCA and SDCA cycles
- **PDCA (Deming cycle)** — the roadmap to *improve* systematically:
  - **P**lan → **D**o → **C**heck → **A**ct.
  - **W. Edwards Deming** is the "father of modern quality control"; he developed PDCA to put Kaizen into practice.
  - Logic chain in the slides: *improved quality → improves productivity → decreasing costs → competitive prices → safe market share → stabilization → safe jobs → safe company.*
- **SDCA (Standardize–Do–Check–Act)** — the roadmap to *hold* the gains:
  - Purpose: **save the achieved level** before running PDCA again.
  - Successful measures must first be **established as standards** (SDCA), *then* you improve again with PDCA. Standards are "not only maintained, but always improved in small steps."

### CIP tools and methods (the toolbox)

**Visual management** — provide information quickly and detect errors/problems fast on the shop floor.

**Value Stream Mapping (VSM)** — a **four-phase** method to analyze the **flow of materials and information** from raw material to the customer's hands. (Also appears in Unit 4; details there.) Reveals value-adding vs non-value-adding time and the causes of waste.

**Process Mapping / Makigami**
- **Process Mapping**: analyze/design/document a process with standard symbols (process step, decision, comment, data, etc.).
- **Makigami**: especially good for **lean administration** processes; visualizes corporate processes and makes **process times, cycle times and losses** visible; each step judged **value-adding or not** in teamwork.
- **Rule of thumb:** *Process Mapping / Makigami → administration processes; VSM → production processes.*

**A3 Report** (invented by **Toyota**)
- All info to investigate, solve and document a problem fits on **one A3 sheet**.
- Based on **Deming's PDCA**; has **8 sections** (problem description → implementation plan).
- Benefits: forces a **concise story**, builds **team consensus**, is a reusable **knowledge base**; can be presented in **5–10 min**.
- Rule: the more **visual** the better; avoid tiny text (<10 pt).

**5-Why method (5W)** — ask **"why?" five times** to reach the **root cause**.
- Classic example: machine stops → fuse blown → overload → not lubricated → no filter → metal splinters fell in. The *real* fix is the missing filter, not the fuse.

**Ishikawa diagram (fishbone / cause-and-effect)**
- Breaks down **root causes** contributing to one **effect**.
- Problem = the "head"; causes collected in a group using the **6M method** (e.g. Man, Machine, Material, Method, Measurement, Milieu/Environment) via brainstorming.
- Main causes are identified and highlighted. (Slide example: reasons for **delayed airplane departures**.)

**Pareto analysis (80/20)**
- **80 % of effects come from 20 % of causes** (Vilfredo Pareto: *"80 % of a nation's wealth is owned by 20 % of the population"*).
- Solving the top 1–2 causes can remove ~60 % of all errors.

**ABC analysis** (developed from Pareto)
- **Group A:** ~5–10 % of elements → ~70–80 % of results.
- **Group B:** ~15–20 % of elements → ~15–20 % of results.
- **Group C:** ~70–80 % of elements → ~5–10 % of results.

**ABC-XYZ analysis** (double ABC)
- Combine ABC (value/volume) with **XYZ (consumption predictability)**:
  - **X-goods:** constant consumption, minor fluctuation (predictable).
  - **Y-goods:** some fluctuation/trend/seasonality.
  - **Z-goods:** irregular, hard to predict.
- Plot both in one **matrix** → used for **strategic decisions** (warehouse design, portfolio streamlining).

### Barriers to CIP
- **Piece-work wages** are a key barrier: skilled piece-workers **don't want change** because it threatens their earnings/known routine. This directly **contradicts CIP ideas**.

### Exam focus — Unit 3
- Define **Kaizen** (kai + zen) and the **3 MU (Muda/Muri/Mura)**.
- **Kaizen vs Kaikaku** — when to use each; why combine them.
- **PDCA vs SDCA** — improve vs hold-the-gain.
- Name and explain **≥3 CIP tools** — Ishikawa (6M), Pareto/ABC, 5-Why, VSM, A3. (This is an actual mock question.)
- **VSM four phases** and what data is collected (see Unit 4).
- **Barriers to CIP** (piece-work wages).

---

# Unit 4 — Process Orientation in Production Systems

**Why it matters:** Process orientation is the **second core principle** and the practical heart of "flow." Mock questions ask you to **compare technology-oriented vs process-oriented production**, and explain **push vs pull** and elements like Kanban, one-piece-flow, U-layout, takt time, SMED.

### Technology-oriented vs Process-oriented production

**Technology-oriented (traditional, batch) production**
- Machines grouped by **technology** in **shop floors** (all lathes together, all mills together…).
- Work moves in **batches**; an **optimum batch size** is chosen to reduce set-up times and storage cost.
- Each machine optimized **individually** for high utilization.
- **Disadvantages:** long **throughput times**, large **buffers/inventory**, long **transport distances**, single workpiece **waits** a lot, higher danger of **serial defects** (a whole batch processed before inspection), lots of work-in-process (WIP).

**Process-oriented (lean) production**
- Machines arranged **in the sequence of the process** (by product flow, not by technology).
- Core elements: **one-piece flow**, **short transport**, **minimized set-up**, **Kanban**, **U-layout**, **takt time**.
- **Result:** minimum transport time, high space utilization, shorter throughput time, less inventory, defects caught early.
- **Comparison result to memorize:** technology-oriented = **bigger inventory + longer throughput time**; process-oriented = the opposite.

**Limits of pure process orientation:** high **variety** or long **processing times** are limitations — some variants need a different sequence or have unavoidable high set-up times, so not everything can flow directly.
- **Fix:** **cluster the product portfolio into product families** with similar production sequences; create **flowing lines** per family; **U-layouts**; connect lines with **Kanban**.

### Push vs Pull
- **Push principle:** a production order is pushed to a station regardless of downstream demand → builds inventory.
- **Pull principle:** downstream pulls from upstream **only when needed** → controlled by **Kanban**.

### Kanban
- A **technique within Just-in-Time** to control process and material by **autonomous control using the pull principle**.
- A **Kanban card** (a simple paper card) carries a few key pieces of info.
- **Rules:**
  - The subsequent process **takes** parts from the previous process per the card.
  - Workers produce **strictly** per the card's info.
  - **No card → no production and no transport.**
  - Cards are attached to **containers** (except on return).
  - **Only 100 %-quality parts** are forwarded; on error the line stops.

### Just-in-Time (JIT) and Just-in-Sequence (JIS)
- **JIT:** deliver material **synchronized with current demand**, **as late as possible.**
  - Benefits: **lower inventory / capital tied up**, shorter throughput times.
  - Requirements: **demand-oriented, centrally controlled**, **deep supplier–customer integration** (also IT), information across the whole supply chain.
- **JIS** (further development of JIT): delivers material **in the exact production sequence**, aligned to customer demand; deeply integrates material + information flow; enables **constant changing of variants**.
- Not every material suits JIT/JIS → you must **identify** which materials are suitable.

### U-Layout (and "Chaku-Chaku")
- **U-shaped** arrangement **minimizes distances** and **increases flexibility**.
- Work stations arranged **counterclockwise** in processing sequence (supports right-hand operation).
- **Input and output** handled by **one person**; **several stations operated by one worker**; number of workers can be **scaled to order volume**.
- Value-adding (assembly) is **separated** from waste (logistics).
- Based on Japanese principle **"Chaku-Chaku"** (= "loading, loading") — supports **one-piece flow**; flow must be **immediately recognizable** to everyone.

### Material supply concepts
- **Milkrun:** a route that **sequentially collects freight from multiple sources** and delivers directly to the receiving line (internal **tugger train** or external suppliers). Improves **reverse logistics** (empty containers).
- **Supermarket:** a controlled store that provides lines with **small quantities at high frequency**, enabling minimal space (supports Chaku-Chaku).

### Takt time vs Throughput time
- **Takt time:** the time **between completion of two consecutive products** — set by **customer demand**; it is the **key to synchronizing the whole factory** (every step produces in takt).
- **Throughput time:** time between **start and finish** of a production = **sum of all takt times**.

### SMED — Single-Minute Exchange of Die
- Technique to **reduce change-over (set-up) time** (source: Shigeo Shingo, *A Revolution in Manufacturing: The SMED System*, 1985).
- **Distinguish internal vs external set-up:**
  - **External setup:** can be done **while the machine still runs** (before it stops).
  - **Internal setup:** can only be done while the machine is **stopped**.
- **Levels/steps:**
  1. Ensure all **external** setups happen while the machine still runs.
  2. **Separate** internal vs external setup; ensure each part functions; improve transport of dies/parts.
  3. **Convert internal setup into external** setup.
  4. **Continuously improve** all setup actions.
- Run improvements as a **SMED workshop**: film changeovers, use a **spaghetti diagram** to detect waste, classify activities, **visualize internal/external** (waterfall diagram), then **eliminate / combine / redistribute / simplify**, then **standardize** and manage deviations.

### Heijunka — production leveling & smoothing
- Levels and **smooths fluctuations** in production planning; **decouples customer demand from production orders** to reduce fluctuation.
- Partitions volume into a **mix of small, even lots in a determined sequence**; exploits available capacity; improves predictability for support processes.
- Typically for **large-scale production (high volume, low mix)**; it's a **prerequisite for efficient pull control** (pull alone breaks under heavy fluctuation).
- For **low-volume / high-mix**, a special leveling procedure exists using the **EFEI ("every family every interval")** value — the period within which **every product is manufactured once** (source: Bohnen, Buhl, Deuse, 2012).

### Gemba
- **"GEMBA" = Japanese for "the real place"** — where the **value-adding activity** actually happens (the shop floor).
- Rule: *when a problem (abnormality) arises, **go to gemba first**, observe the **real conditions**, and take **temporary counter-measures on the spot.***

### Exam focus — Unit 4
- **Compare technology-oriented vs process-oriented** production (inventory, throughput time, layout, defect risk). *(Mock question.)*
- **Push vs Pull**; the **Kanban rules** ("no card, no production").
- **JIT vs JIS** differences.
- **Takt time vs throughput time** (definitions + relationship).
- **SMED**: internal vs external setup and the conversion idea.
- **Heijunka**: what leveling/smoothing does and why pull needs it.
- **U-layout / Chaku-Chaku**, **milkrun**, **supermarket**, **Gemba**.

---

# Unit 5 — Lean Global Production & Supply Chain Management

**Why it matters:** Zooms out from the factory to the **global network**. Mock questions ask you to **compare producing in Germany vs relocating to Asia**, explain **mass customization types**, and **compare sourcing strategies**.

### Why globalize?
- Three phases of globalization historically.
- **Main drivers:** **cost saving** and **new-market expansion**. Production/assembly **follow markets and labor costs**.
- **Reasons to still produce in Germany:** well-trained engineers, technology, quality — but **markets + labor costs** push production toward **emerging markets**. (Labor costs in Germany are ~**20× higher** than in China per the slides.)

### Site selection
- Determined by **location parameters** weighted by **process parameters**.
- Decision criteria structured into groups (e.g. set-up, start-up, support, coordination costs); compared using a **benchmarking matrix**.

### Supply Chain fundamentals
- **Supply Chain:** the progression of processes and organizational units material passes through **from the first supplier to the end customer**, including all product-flow activities *and* the crucial **information flow**.
- **Supply Chain Management (SCM):** internal + network-oriented integrated activities (supply, waste management, plus money and information flows).
- **Global SCM (GSCM):** ensures saleable-quality goods are made and transported **safely, cost-effectively, on time**, continuously **adding value** (vendor management, EDI order receipt, advance shipment notice, etc.).

### SCOR model
- **SCOR = Supply-Chain-Operations-Reference model** — standardizes SC processes and measures them with **key figures**. Core process types: **Plan, Source, Make, Deliver, Return** (evaluate supply, receive/inspect/store, manufacture, manage orders/distribution, handle returns).

### Incoterms
- **Incoterms** (International Chamber of Commerce, e.g. Incoterms 2010) define **freight conditions** — who pays and delivers.
- Two extremes to know: supplier **pays freight and delivers to the doorstep** vs customer **pays freight, supply ex factory**. They split **duties of buyer/seller**.

### Automotive supply network
- **OEM (Original Equipment Manufacturer)** — e.g. the carmaker; **initiator and controller** of the network, highest development + assembly competence.
- **Tier-1, Tier-2, … Tier-n suppliers.** Lower tiers are often **SMEs** with little/no data connection → need an **information window** into demand forecasts (otherwise they get **delayed** demand info).

### The Bullwhip effect
- **Rising variance of orders and stock** as you move **upstream** in the supply chain.
- **Cause:** each domain plans **locally** → demand information is **delayed and distorted**.
- **Consequences:** greater **safety stocks**, inefficient production, excess stock, higher storage/transport costs, negative financial effects.

### Cooperation strategies
- **Vertical cooperation:** with **upstream (supplier)** or **downstream (customer)** value-added steps.
- **Horizontal cooperation:** at the **same** value-added step (between competitors).
- **Coopetition:** portmanteau of **cooperation + competition.**

### Mass Customization (two types)
- Customizing that occurs at the **final stage** of production. The two types differ in **where** the variant is created (e.g. modular assembly vs late-stage differentiation). *(Mock question: name the two types and give a living example of each.)*

### Sourcing strategies (learn the pairs)
- **Global sourcing vs Local sourcing** — exploit economy/growth differences (global) vs proximity/reliability (local).
- **Single sourcing vs Multiple sourcing** — one supplier (deeper integration, higher risk) vs several (resilience, more coordination).
- **Vertical integration level:** high vs low.
- **Procurement types:** **JIT/synchronous**, **stockpiling** (buy cheap, hold stock, shift risk to inventory), **demand-driven** (only when needed).
- **Purchasing-portfolio analysis:** classifies purchased parts by **strategic significance** and **supply risk**.

### Exam focus — Unit 5
- **Germany vs Asia** production trade-off (mock question) — engineers/quality vs labor cost/markets.
- **SCOR** (Plan-Source-Make-Deliver-Return) and **Incoterms** basics.
- **Bullwhip effect**: definition, cause (local planning → distortion), consequence (safety stock).
- **Vertical vs horizontal cooperation**, **coopetition**.
- **Mass customization types** + example each; **sourcing strategy** pairs (mock questions).

---

# Unit 6 — Total Quality Management (TQM)

**Why it matters:** TQM is a **whole pillar** of the house. Mock questions ask **what tools/methods realize TQM** and how to **introduce** it.

### Definition & idea
- **TQM** = the **organization-wide effort** to deliver **high-quality products and services** to customers.
- Driven by the shift from a **seller's market to a buyer's market** — customers can choose, so satisfying **rising expectations** keeps you competitive.
- Quality is the responsibility of **everyone involved** in creating or consuming the product. **TQM is continuous**, not a one-time task.

### Three orientations of TQM
1. **Customer orientation**
   - **Customer satisfaction** = result of a benchmark between expectation and experience.
   - **Proactive complaint management:** encourage customers to report problems → tears down barriers, shortens communication paths, retains customers.
2. **Employee orientation**
   - Employees are the **real asset**. Motivated employees focus on customer satisfaction.
   - **Quality circles:** teams designing/improving their own working environment → big motivation + improvement potential.
   - Sobering figures cited: ~**85 %** of non-conformance costs and ~**30 %** of work resources tied to **error correction**.
3. **Process orientation**
   - All workflows defined as **processes** (input → output); **all process links seen as customer–supplier relationships**.
   - **Benchmarking:** systematic performance comparison to find **best practice**; broader scope → more valuable information; regulated by a **Code of Conduct** for external benchmarking.

### Collaboration & standards
- **PPAP (Production Part Approval Process) / ISO/TS 16949** — **initial sample inspection** in automotive: proves requirements understood, product meets them, and the **process (incl. sub-suppliers) is capable**.
- **8D Report** — 8 disciplines to handle complaints:
  1. **Establish a team** (with the right knowledge).
  2. **Define/describe the problem** (quantitatively).
  3. **Immediate/interim actions** (limit damage, short-term fix).
  4. Find and verify **root cause**.
  5. Choose/verify **permanent corrective actions**.
  6. **Implement** corrective actions per plan.
  7. **Prevent recurrence**.
  8. **Recognize the team** (formally thank them).
- **EFQM (European Foundation for Quality Management)** — an excellence model spanning leadership, strategy, employees, partnerships, resources, processes.
- **Balanced Scorecard** — combines **four perspectives: financial, customer, employee, process**.

### Exam focus — Unit 6
- Define **TQM** + the **seller→buyer market** driver.
- The **three orientations** (customer / employee / process) with one method each.
- **8D report** — be able to list the disciplines and what each does. (Recall the 8D also integrates house **levels 2+3** from Unit 2.)
- **Benchmarking**, **PPAP/ISO-TS 16949**, **EFQM**, **Balanced Scorecard (4 perspectives)**.

---

# Unit 7 — Low Cost Automation (LCA) & Jidoka

**Why it matters:** Answers *"how do we get flexibility cheaply?"* Mock focus: **Jidoka**, **Poka Yoke**, **Andon**, **Chaku-Chaku**, and the LCA design rules.

### Context
- Product **variety is rising** → need more **flexibility** to react faster to change, achieved mainly through the **employee's flexibility** rather than expensive rigid automation.

### Jidoka (autonomation)
- **Jidoka = "autonomation" = automation with a human touch.**
- Origin: **Toyoda Sakichi (1924)** enabled looms to **minimize faulty products** by stopping automatically on a fault.
- Principle: **when a problem occurs, stop the process immediately.** By stopping you avoid:
  - Waste of **production capacity** on defective products.
  - Waste of **transport** on defective material.
  - Waste from **inventory** (space, capital, handling).
- Benefits: **top-level quality**, higher **quality consciousness**, lower **equipment failure rate**, better **customer satisfaction**, lower costs.

### Poka Yoke (mistake-proofing)
- **Poka Yoke** = prevention technique that avoids fitting/mounting mistakes.
- **Hard Poka Yoke:** kinetic prevention — the mistake **physically cannot** be made (e.g. a **USB plug** only fits one way; asymmetric geometry prevents wrong positioning).
- (Soft Poka Yoke: warns/signals but doesn't physically block.)

### Andon
- **Andon** = light-signal board that displays the **current condition of the production line** to employees (few but very important signals; indicates the position/status of a problem).

### Low Cost Automation (LCA) principle
- Highly automated facilities are often **too static and expensive**. LCA makes production **react fast at reasonable cost** by leaning on the employee's **universal applicability**.
- **Design rules:**
  - Avoid complicated motion sequences/functions/structures.
  - Use **simple mechanical elements** (rotational/linear) and **basic physical laws** (gravity, parallelogram of forces).
  - Use **simple, widely-used, cheap materials/components** (e.g. **Creform**), and **recycle** disassembled parts.
  - Use **Poka Yoke** to support manual assembly.
  - Use **modular** components/equipment; develop equipment **internally**, customized.

### Chaku-Chaku line (Loading-Loading)
- 5 basic steps to build a **"Chaku-Chaku" (Loading-Loading) line**:
  - Machines/equipment placed **in assembly order** (ideally **U-shape**).
  - Parts produced **within the process flow**.
  - **Full responsibility** given to the work station for the whole cycle.
  - Employee controls the station and part delivery; **path synchronized to work flow**.
- Design details: parts **automatically ejected** and placed in the **next** loading device ("a hand is no feeding device"); everything within the operator's reach ("**Best Point**"); loading automated via **pneumatics/hydraulics**; use **ramps** for height differences; keep the **pull principle**; container ratio **full:empty = 1:1**.

### Exam focus — Unit 7
- **Jidoka** — definition (autonomation), **Toyoda Sakichi/1924**, "stop on defect," and the wastes avoided.
- **Poka Yoke** — **Hard vs Soft**, USB-plug example.
- **Andon** — what it displays.
- **LCA design principles** (simple, cheap, modular, gravity, Creform).
- **Chaku-Chaku** — U-shape, one worker, parts thrown/ejected, "a hand is no feeding device."

---

# Unit 8 — Total Productive Maintenance / Management (TPM)

**Why it matters:** TPM is **Case Study 3** and a favorite for **calculations (OEE, MTBF/MTTR)**. Learn the **8 pillars**, **autonomous maintenance steps**, and the **OEE formula** cold.

### What TPM is
- **Total Productive Management/Maintenance** — a comprehensive management system to **identify losses and waste and eliminate them permanently**, boosting value added.
- Started ~50 years ago focused on **maintenance**, evolved into a full **management system**. Management action is **crucial**.
- Benefits (from Case 3): **productivity improvement** (fewer losses), **quality improvement**, **cost reduction**, **employee ownership** (via Autonomous Maintenance), **customer satisfaction** (delivery performance).

### The 8 pillars of TPM (know the main ones)
1. **Autonomous Maintenance** — operators do basic maintenance (cleaning, lubricating, inspection); gives **ownership**.
2. **Focused Improvement** (Kobetsu Kaizen) — maximize **efficiency + effectiveness** of machines by attacking specific losses.
3. **Planned Maintenance** — scheduled by maintenance personnel to reach **"zero defect"**; done when equipment is **not scheduled for production**.
4. **Quality Maintenance** — target **quality defects** at their **root source**; QM-matrix links process steps to quality requirements.
5. **Early Equipment / Initial Phase Management** — new equipment reaches performance **faster**, fewer start-up issues (early design phases cause ~**70 %** of problems).
6. **Education & Training** — build a **skill matrix** of current qualifications.
7. **Office TPM** (support sections) — apply TPM techniques to **non-producing** areas.
8. **Safety, Health & Environment** — often neglected but essential.

### OEE — Overall Equipment Effectiveness (**core calculation!**)

$$\text{OEE} = A \times P \times Q$$

- **Availability (A)** — *"What ratio of planned production time is really used?"*
  $$A = \frac{\text{Actual Production Time}}{\text{Planned Production Time}}$$
  (Equivalently, using mean times: $A = \dfrac{MTBF}{MTBF + MTTR}$.)
- **Performance (P)** — *"What ratio of the possible speed does the machine achieve?"*
  $$P = \frac{\text{Actual output}}{\text{Theoretical output}} = \frac{\text{Actual cycle rate}}{\text{Planned cycle rate}}$$
- **Quality (Q)** — *"What ratio of produced parts is first-time good?"*
  $$Q = \frac{\text{Good Parts}}{\text{Actual Parts}}$$

**Worked example (from Case Study 3):**
- 2 shifts × 6 h = 12 h; minus 60 min planned breaks → **Planned Production Time = 660 min**.
- 5 malfunctions × 6 min = 30 min downtime → **Actual Production Time = 630 min**.
- **A = 630 / 660 = 95.45 %.**
- Planned rate = 10 parts/min → theoretical = 6300 parts; actual = 6000 parts.
- **P = 6000 / 6300 = 95.24 %.**
- Bad parts = 500 → good = 5500. **Q = 5500 / 6000 = 91.67 %.**
- **OEE = 95.45 % × 95.24 % × 91.67 % = 83.33 %.**

> ⚠️ Exam trap: careful which downtime counts against **Availability** (unplanned stops) vs which is **planned** (breaks reduce planned time, they are not availability losses). Follow the case-study convention exactly.

### Loss elimination & maintenance figures
- Identify loss **causes** systematically and eliminate them in a **PDCA-like** approach.
- **Autonomous Maintenance** is implemented in **7 steps** (initial clean/inspect → eliminate contamination sources & hard-to-reach spots → set cleaning/inspection standards → training → autonomous inspection → standardization → full CIP).
- **One-Point-Lessons (OPL):** a single sheet, communicated in **5–10 min**, based on **5W1H**, documenting one standardized process/skill (transferable to a wiki).
- **Planned maintenance figures:**
  - **MTBF = Mean Time Between Failures** (reliability — longer is better).
  - **MTTR = Mean Time To Repair** (maintainability — shorter is better).

### Exam focus — Unit 8
- **8 pillars** — be able to name them and explain Autonomous, Planned, Quality maintenance.
- **OEE = A × P × Q** — memorize each ratio and **be able to compute it** (this is a near-certain exam calculation; practise the Case 3 numbers).
- **MTBF vs MTTR** and $A = MTBF/(MTBF+MTTR)$.
- **Autonomous maintenance** ownership idea; **OPL / 5W1H**; ~70 % of problems from early phases.

---

# Unit 9 — Material and Energy Efficiency

**Why it matters:** This is **Case Study 2**. Learn **Energy Value Stream**, the **DIN EN ISO 50001** reference, KPIs, and the CO₂ figures.

### Core ideas
- Extends lean thinking to **material and energy** as forms of waste.
- **Energy Value Stream Analysis / Mapping (EVSM):** an **extension of the Value Stream Method** that integrates **process energy** into the value-stream picture (energy consumed per process step, base load vs processing load).
- **DIN EN ISO 50001** — the **energy management standard** underpinning a continuous improvement process focused on **energy efficiency**.
- **Base load** (energy consumed even when not producing, e.g. machines in standby) is a **big saving potential** — switching off during breaks/idle.

### KPIs (energy)
- Energy used (**kWh**) per part/unit.
- Energy **savings (kWh)** per year / per part.
- **Savings (€/$)** and **CO₂ savings** per improvement.
- Return on **investment in more efficient machinery**.

### Figures to remember (from Case 2)
- **CO₂ per kWh:** **Germany ≈ 525–600 g CO₂/kWh**; **France ≈ 25–100 g CO₂/kWh** (France is far lower — nuclear-heavy grid). Be ready to explain *why* the difference exists (energy mix).

### Exam focus — Unit 9
- Define **Energy Value Stream Mapping** as an extension of VSM.
- **DIN EN ISO 50001** as the energy-management reference.
- **Base load** saving potential (switch-off during idle).
- The **Germany vs France CO₂/kWh** comparison and the reason (grid mix).
- Typical **energy KPIs**.

---

# Unit 10 — Information Efficiency

**Why it matters:** Extends waste-elimination to **information flows**. Lighter on calculations; expect *explain/why* questions.

### Core ideas
- Information is a **production factor**: the right information, at the right time, in the right place avoids waste (waiting, wrong decisions, rework).
- Ties directly to **Industry 4.0** (Unit 2): digital data connection across the supply network, real-time monitoring.
- Recall from Unit 5: lower-tier suppliers need an **"information window"** — without it they get **delayed/distorted** demand data (a cause of the **bullwhip effect**).
- Tools that support information efficiency reappear here: **visual management**, **top-level reports**, **web-based monitoring** (e.g. the 3D-monitoring of assembly mentioned under TPM), and **wiki-based One-Point-Lessons**.

### Exam focus — Unit 10
- Why **information is a form of value/waste** and how transparency reduces waste.
- Link to **Industry 4.0** and to the **information window / bullwhip** problem.

---

# Unit 11 — Lean Development

**Why it matters:** Applies lean **upstream**, in product development, where early decisions lock in most cost/quality.

### Core ideas
- **~70 % of all problems originate in early design phases** (also stated under TPM's early-equipment pillar) → tackle development **strategically**.
- **Simultaneous / concurrent engineering:** overlap development activities and involve **suppliers early** (recall Unit 6: shared development process; supplier needs fabrication + product know-how; both partners enrich know-how).
- Bring **production, maintenance and engineering experience** into development so new equipment/products reach performance **faster** (initial-phase management → better **start-up curves**).
- Apply lean principles to development: **eliminate waste** (rework, waiting for decisions), **standardize**, **flow**, and **modularity** (modular products enable variety with low complexity — see Unit 7).

### Exam focus — Unit 11
- The **70 %-of-problems-from-early-phases** argument for lean development.
- **Concurrent engineering** + **early supplier involvement**.
- How **modularity / standardization** support variety at low cost.

---

# Unit 12 — Lean Administration

**Why it matters:** Applies lean to **office/administrative** processes. Key methods: **Makigami**, **Office-TPM**.

### Core ideas
- Waste exists in offices too (waiting, searching, unnecessary approvals, rework).
- **Makigami** (from Unit 3) is **the** administration-process tool: visualizes corporate processes and exposes **process times, cycle times and losses**; each step judged **value-adding or not** in teamwork.
- **Process Mapping** also suits administration (standard symbols).
  - **Rule again:** *Process Mapping / Makigami → administration; VSM → production.*
- **Office-TPM** (Unit 8, pillar 7): apply TPM techniques to non-producing sectors — homogeneous rules/standards (filing, meetings, procedures), visualize key figures/targets, optimize resource usage, and **benchmark** against leading companies.
- **5S** applies directly to the office/desk (Sort, Set in order, Shine, Standardize, Sustain).

### The 5S technique (know all five S)
1. **Seiri (Sort)** — eliminate unnecessary tools/parts/instructions; keep only essentials.
2. **Seiton (Set in order)** — a place for everything, everything in its place; easy access.
3. **Seiso (Shine)** — clean the workspace and equipment; keep it clean.
4. **Seiketsu (Standardize)** — consistent, standardized work practices; anyone can work at any station.
5. **Shitsuke (Sustain)** — make the previous 4 the **new normal / self-discipline**.

### Exam focus — Unit 12
- **Makigami vs VSM vs Process Mapping** — which for admin, which for production, and the pros/cons.
- **Office-TPM** 7-step idea.
- **5S** — list and briefly explain all five (there's a mock question: *"in some steps explain how to implement 5S in your office/lab"*).

---

# Unit 13 — Repetition (Exam Preparation)

This unit re-summarizes the course. Use it as a **final checklist**. The exam expects you to:
- Understand the **meaning of an IPS** and **draw the house**.
- Assess **lean principles in context** (not memorize tools in isolation).
- **Choose, assess and apply** the right method/tool for a given problem.
- Connect methods across units (e.g. Kanban⇄JIT⇄Heijunka⇄Takt; Ishikawa⇄5-Why⇄Pareto⇄A3; OEE⇄TPM⇄MTBF/MTTR).

### The lecturer's own embedded mock questions (collected)
These appeared inside the slides — treat them as **high-probability exam questions**:

**Structure (Unit 2)**
1. Name several **key elements of an IPS** and explain **potential goal conflicts** if implemented in isolation.
2. The IPS-house divides activities into **waste / added value / additional work** — explain why each is necessary and give a **practical example** (method/tool/principle) for each.
3. Using a **daily office task of an engineer**, classify activities into **waste / value-adding / additional work**.

**CIP (Unit 3)**
4. What are the **basic principles of CIP**, and how does **Kaizen** relate?
5. Which **methods/tools** are used in CIP to identify improvements? Describe **≥3** (e.g. **Ishikawa**, …).
6. Explain the steps of creating a **Value Stream Map**, what data is collected in each phase, and how a **future state** is developed.
7. What **barriers** hinder CIP implementation?

**Process orientation / lean fundamentals (Unit 3/4)**
8. What is the **ultimate goal of lean production** and how is it achieved? *(→ value creation through elimination of waste, the 3 MU.)*
9. Differences between **technology-oriented and process-oriented** production.
10. Explain how to implement **5S** in your office/lab.

**Global production / SCM (Unit 5)**
11. For one industry, compare **reasons to produce in Germany vs relocate to Asia**; give your recommendation.
12. Differences among **types of mass customization** — with a living example of each.
13. Compare **sourcing strategies**: global vs local, single vs multiple.

**TQM (Unit 6)**
14. Which **tools/methods** realize **Total Quality Management**?

Practise writing **full answers** to all 14 — they map almost one-to-one onto likely exam questions.

---

# Case Study Walkthroughs

The case studies are where the **calculations** live. Master these three.

## Case Study 1 — Process Orientation (Braunmeier Group)
- Centered on **reading an income statement** and connecting financial performance to process/lean improvements.
- Key financial lines to interpret (2006–2012 for the Braunmeier Group): **Net Sales, Cost of Goods Sold (COGS), Gross Profit & Gross-Profit Margin, SG&A (% of sales), R&D, EBIT.**
- **What to be able to do:** compute **gross-profit margin = Gross Profit / Net Sales**; watch **SG&A as % of sales fall** as the company scales (a sign of improving efficiency); read the swing from **negative EBIT to positive** as the lean/process improvements take hold.
- **Link to theory:** improved **process orientation** → lower COGS ratio, shorter throughput/inventory → better margins.

## Case Study 2 — Energy Efficiency & Sustainability (EKM GmbH)
- **Part 1 — concepts:** define **Energy Value Stream Analysis** (extension of VSM integrating process energy); reference **DIN EN ISO 50001**; identify **base-load** saving potential.
- **Key figures:** **CO₂ per kWh — Germany ≈ 525–600 g; France ≈ 25–100 g** (explain via energy mix).
- **Part 2 — EVSM (Energy Value Stream Mapping):** map energy per process step, separate **base load vs processing load**, quantify savings in **kWh, €, and CO₂**, and justify **investment in more efficient machinery** with the KPIs from Unit 9.

## Case Study 3 — Total Productive Maintenance (OEE + Process Capability)
This is the **most calculation-heavy** case. Two blocks:

**(a) OEE** — computed exactly as in Unit 8 (worked example there): **OEE = A × P × Q = 95.45 % × 95.24 % × 91.67 % = 83.33 %.** Know how each downtime is classified.

**(b) Process Capability — Cp and Cpk**
- **Mean:** $\mu = \frac{1}{n}\sum x_i$
- **Standard deviation (sample):** $\sigma = \sqrt{\frac{1}{n-1}\sum (x_i-\mu)^2}$
- **Cp** — *"ratio of allowed scattering to actual scattering":*
  $$c_p = \frac{USL - LSL}{6\sigma}$$
- **Cpk** — *"ratio of allowed one-sided scattering to actual scattering":*
  $$c_{pk} = \min\!\left(\frac{USL - \mu}{3\sigma},\; \frac{\mu - LSL}{3\sigma}\right)$$
- **Worked example (Case 3):** data 2,3,4,5,3,4,3,2,3 reduced to the set used → $\mu = 3$, $\sigma = 0.707$, with **USL = 4, LSL = 2** →
  - $c_p = \frac{4-2}{6\cdot 0.707} = 0.471$
  - $c_{pk} = \min(0.471, 0.471) = 0.471$
- **Capability rule:** the process is **capable if Cp and Cpk > 1.33** (thresholds of 1, 1.3 or 2 are also used depending on the specification). Here **0.471 < 1.33 → the process is NOT capable.**

> **Interpretation to state in an exam:** **Cp** measures whether the spread *could* fit within the tolerance if perfectly centered; **Cpk** accounts for **off-centering**. If **Cpk < Cp**, the process is off-center. If either is **< 1.33**, it isn't capable.

---

# Master Glossary (keep terms exact)

- **IPS** — Integrated Production System; company-specific structure of standards/methods that fixes *how to produce*.
- **Lean Production / TPS** — Toyota Production System (Ohno); philosophy of eliminating all unnecessary work, producing in the customer's takt.
- **3 MU** — **Muda** (waste), **Muri** (overload), **Mura** (unevenness).
- **Muda / Value-adding / Additional work** — the three activity classes.
- **Kaizen** — "change for the better"; small continuous improvement.
- **Kaikaku** — radical/large-scale change (reengineering).
- **PDCA** — Plan-Do-Check-Act (Deming); improve.
- **SDCA** — Standardize-Do-Check-Act; hold the gain.
- **Gemba** — "the real place" (shop floor); go there first.
- **Jidoka** — autonomation; stop automatically on defect (Toyoda Sakichi, 1924).
- **Poka Yoke** — mistake-proofing; **Hard** (physically impossible) vs **Soft** (warns).
- **Andon** — light-signal status board.
- **Kanban** — pull-control card; "no card, no production."
- **JIT / JIS** — Just-in-Time / Just-in-Sequence.
- **Heijunka** — production leveling & smoothing; prerequisite for stable pull.
- **Takt time** — customer-demand rhythm; synchronizes the factory. **Throughput time** = sum of takt times.
- **SMED** — Single-Minute Exchange of Die; convert **internal→external** setup (Shingo, 1985).
- **U-layout / Chaku-Chaku** — U-shaped, one-worker, one-piece-flow cell.
- **Milkrun / Supermarket** — material-supply concepts.
- **VSM** — Value Stream Mapping (production); 4 phases, PQR analysis first.
- **Makigami / Process Mapping** — administration-process visualization.
- **A3 report** — one-sheet PDCA problem-solving (Toyota); 8 sections.
- **5-Why / Ishikawa (6M) / Pareto (80-20) / ABC / ABC-XYZ** — CIP analysis tools.
- **TQM** — organization-wide quality effort; customer/employee/process orientation.
- **8D report** — 8-discipline complaint handling.
- **PPAP / ISO-TS 16949 / EFQM / Balanced Scorecard (4 perspectives)** — quality standards/models.
- **SCOR** — Supply-Chain-Operations-Reference (Plan-Source-Make-Deliver-Return).
- **Incoterms** — freight-condition rules (buyer/seller duties).
- **Bullwhip effect** — upstream demand-variance amplification.
- **Coopetition** — cooperation + competition.
- **TPM** — Total Productive Maintenance/Management; **8 pillars**.
- **OEE = A × P × Q** — Overall Equipment Effectiveness.
- **MTBF / MTTR** — Mean Time Between Failures / To Repair; $A = \frac{MTBF}{MTBF+MTTR}$.
- **Autonomous Maintenance / OPL (5W1H)** — operator maintenance / one-point-lesson.
- **EVSM / DIN EN ISO 50001** — Energy Value Stream Mapping / energy-management standard.
- **Cp / Cpk** — process-capability indices; capable if **> 1.33**.
- **5S** — Sort, Set-in-order, Shine, Standardize, Sustain.

---

# One-Page Rapid-Revision Cheat Sheet

**The 3 core principles:** (1) eliminate waste (2) process orientation/flow/JIT (3) continuous improvement (CIP).

**The house:** Roof = goals (cost, quality, lead time, safety). Pillars = topic areas (equal). Foundation = stability. Each pillar = 3 levels (principle → method → tool).

**History:** Handcraft → Manufactory → **Taylor** (planning/execution split, one-best-way) → **Ford** (line, one interruption blocks all) → overcome (Volvo groups, VW automation) → **Toyota/Lean (Ohno).**

**3 MU:** Muda / Muri / Mura. **Kaizen** (small) + **Kaikaku** (radical). **PDCA** (improve) + **SDCA** (hold).

**CIP tools:** 5-Why, Ishikawa (6M), Pareto (80/20)→ABC→ABC-XYZ, VSM (4 phases, PQR first), A3 (8 sections), Makigami (admin).

**Flow toolkit:** Push vs Pull; **Kanban** ("no card, no production"); **JIT/JIS**; **Takt** (= customer rhythm) vs **throughput** (= Σ takt); **SMED** (internal→external); **Heijunka** (level & smooth); **U-layout/Chaku-Chaku**; **milkrun/supermarket**; **Gemba** first.

**Global/SCM:** drivers = cost + markets; **SCOR** (P-S-M-D-R); **Incoterms**; **OEM/tiers + information window**; **bullwhip** (local planning → distortion → safety stock); vertical/horizontal/**coopetition**; sourcing pairs (global/local, single/multiple).

**TQM:** buyer's market driver; customer/employee/process orientation; **8D**; PPAP/ISO-TS16949; EFQM; Balanced Scorecard (4 views).

**LCA/Jidoka:** Jidoka = stop-on-defect (Toyoda 1924); Poka Yoke (Hard vs Soft, USB); Andon; LCA = simple/cheap/modular/gravity/Creform; Chaku-Chaku ("a hand is no feeding device").

**TPM:** 8 pillars; **OEE = A×P×Q**; A = MTBF/(MTBF+MTTR); autonomous maintenance = ownership; ~70% problems from early phases.

**Energy:** EVSM = VSM + energy; ISO 50001; base-load savings; **Germany ~525–600 vs France ~25–100 g CO₂/kWh**.

**Calculations to drill:** **OEE (=83.33% in Case 3)**, **Cp/Cpk (=0.471, not capable)**, availability from MTBF/MTTR, gross-profit margin.

*Good luck — if you can explain each keyword above in one sentence and reproduce the OEE and Cp/Cpk calculations, you're in excellent shape for the exam.*
