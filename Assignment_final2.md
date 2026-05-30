# PharmaTech Ingredients Pvt. Ltd. — Operation Diagnostic & Intervention Design

---

## PART A — Operation Diagnostic

---

### Situation A — The Alert Nobody Responds To

#### Stated Problem

The CEO states he has no visibility over the day-to-day process of the manufacturing plant.  
The Analysts, Anil and Karthik, stated there was no follow-up or response to the alert sent to all on a daily basis.

---

#### What's Actually Going On

The daily alert email is an **information broadcast message and status poster** — not a monitoring system or workflow as requested by the CEO. The CEO does receive notifications regarding overall process handling in various areas, but the alert email doesn't provide in-depth information.

The alert email covers information to Mr. R regarding *what* is wrong, but not:
- What action is being taken
- Who is responsible
- Escalation updates or feedback

As no individual is directly held accountable, there is no trigger, no point of contact, and no immediate response or action plan. This generates anxiety for the CEO — he only sees the *status* of what's wrong and how much delay it would cause, with no one's name on the line, which waters down the importance of the alert email.

**The alert email shows no progress.** For example, consider this entry:

| System | Department | Status | Pending Items | Days Overdue |
|---|---|---|---|---|
| Supply Chain Mgmt | Purchase | 🔴 RED | 4 POs pending approval | 3 days |

The most important detail missing from this entry is *when the issue was actually raised* — there is no mention of date or how many days the issue has persisted.

**History is an important metric missing from this alert email.** We are unaware whether this was raised yesterday or 3 weeks ago. Having an organised record of each issue would allow us to answer questions such as:
- Is this a new issue or a recurring one?
- Does this issue occur under specific conditions?

More organised records would allow us to understand *why* issues keep occurring and address the root cause.

**Lastly, the alert email lacks an escalation architecture.** If the above issue persists for more than 3 days, there is no procedure stating what happens next or who will step in. This causes Anil and Karthik to manually follow up with each department to present findings to the CEO — and even then, all they receive is a binary resolved/not-resolved status, with no insight into *how* progress is being made or *who* is responsible.

---

#### Evidence from the Scenario

- The alert shows department names, not individual names. The senior advisor explicitly flagged this: *"If I see Warehouse delayed, who feels the pressure? Nobody."*
- The email lacks trend data, day-over-day changes, and escalation history.
- Anil: *"Most of my time goes into follow-ups. I attend the daily meeting, take notes, document action items, then go department to department making sure people do what they committed to."*
- The tracker shows task status but **"no individual accountability"**.

---

#### Summary

The alert system acts as a **reporting system without accountability**. It provides information on *what's* the status but has no information regarding:
- Who is taking charge?
- What is the plan of action?
- What is the progress of the situation?

---

### Situation B — The Blank Field

#### Stated Problem

Anil and Karthik state people are not disciplined enough to fill the blank entries of the deviation tracker, whereas the supervisors state this is not a discipline issue but a **company cultural issue**.

---

#### What's Actually Going On

The analysts observed that **70% of entries for root causes in the deviation tracker were empty**. Upon further discussion, two supervisors revealed that filling up the entries creates more problems for them rather than arriving at a quick solution.

Rather than finding a solution to the issue at hand, even *mentioning* an issue opens the person up to additional interrogation during the review meeting. This also leads to the **public calling out of employees on the production floor in front of peers** — functioning as a humiliation ritual that everyone dreads. This fosters a toxic workplace rather than a collaborative one.

Supervisors take responsibility to fix issues quietly without filling out details, to avoid anyone getting punished or humiliated.

The deviation tracking system — established to provide transparency — is **functioning opposite to its intended purpose**. It sends the message that *transparency has consequences*. This leads to bigger issues: production employees become hesitant to ask for help, creating an untrustworthy workplace. The CEO, receiving no feedback, states there is no visibility.

---

#### Why Anil and Karthik Missed It

Anil and Karthik did identify *what* was wrong with the deviation tracker but misdiagnosed the *why*.

As trained analysts from a non-toxic corporate background, they received training on compliance and the importance of data entry. They perceive enquiries from higher-ups as formal meetings in closed conference rooms — not public shaming events.

The manufacturing workforce, composed largely of blue-collar workers directly involved on the manufacturing line, received different training and likely experienced this non-collaborative, toxic culture of public humiliation for an extended period. They developed their own coping mechanism, which Anil and Karthik mislabelled as a **compliance, discipline, and behavioural issue**.

---

#### Evidence from the Scenario

- **Supervisor 1:** *"If I write what actually went wrong, tomorrow in the review meeting they will ask me 50 questions. Why did this happen? Who was responsible? It becomes a blame game. So I leave it blank and handle it quietly."*
- **Supervisor 2:** *"Last time I wrote the real root cause — that the maintenance schedule was not followed because we didn't have the spare part — the maintenance head got called out in front of everyone. After that, nobody writes root cause honestly."*

---

### Situation C — The Meeting That Eats the Day

#### Stated Problem

The daily technical meeting with 12 HODs was allotted 30 minutes but consistently runs 60–90 minutes. After the meeting, everyone's schedules are pushed back by unplanned work — especially technical issues which take priority and need to be discussed.

---

#### What's Actually Going On

**The daily meeting fails at its agenda.**

The meeting is structured for individual discussion with all 12 HODs, each allocated 5–10 minutes. Mathematically, this requires at least 120 minutes for proper discussion. The meeting was scheduled for 60 minutes, then compressed to 30 — and yet still runs for 60–90 minutes of chaos, not 30 minutes of efficiency.

The meeting was originally intended to conduct discussion and follow-ups for the alert system. The rise of untimely technical problems led to the execution of unplanned work within the meeting itself. This disrupts workflow because:
- There is no **daily micro-plan** to distinguish planned from unplanned work
- No categorisation of planned, unplanned, and routine tasks exists
- This causes actual planned work to be put on hold

Additionally, all 12 HODs — including those from HR, IT, R&D, and other unaffected departments — must attend the entire meeting, because this is the **only coordination mechanism** available across the plant.

---

#### Evidence from the Scenario

- *"How many people attend this meeting?" "Twelve department heads." "How many minutes does each person get?" "Five to ten minutes." "So 12 times 10 is 120 minutes. Why is this meeting scheduled for 30 minutes?"*
- No daily micro-plan exists: *"So you have a monthly plan and a weekly plan, but no daily plan? Do the department heads have daily plans?" "No." "Then how do you know what's unplanned? If there's no plan for today, everything is unplanned."*
- The meeting was originally scheduled for 1 hour, then compressed to 30 minutes. It still runs 60–90 minutes daily.
- Technical issues (e.g., out-of-specification lab results) get discussed in this forum instead of being routed to a dedicated meeting.
- The advisor identified three types of daily activity: **routine** (scheduled meetings, recurring tasks), **planned** (project work with defined scope), and **unplanned** (deviations, breakdowns, ad-hoc demands). Nobody in the company was categorising or tracking these at the time of the diagnostic.

---

#### Summary

The organisation has **one coordination mechanism** — the daily meeting. There is no strict meeting structure, no daily planning, and no architecture or procedure to support technical issues. This makes it a high-stakes meeting trying to solve everything in 60 minutes, which returns no positive outcome.

---

### Summary of Three Situations

These are **not three separate problems** — they form a vicious cycle that repeats endlessly:

| Situation | Failure |
|---|---|
| **A** | Fails to provide feedback and highlight progress — no individual accountability |
| **B** | Fails to provide transparency and communication — toxic, punishing work culture |
| **C** | Fails to provide organisation and planning — no architecture or support procedure |

**The loop in plain terms:**

1. The CEO sees red items, demands more visibility, and applies pressure in meetings.
2. No one steps up to provide root causes — doing so leads to public humiliation and punishment.
3. Employees take it upon themselves to quietly solve technical issues — hampering the workflow, as meeting progress is never shared and no plans are made.
4. As employees solve issues informally and don't transmit status upward (due to fear of punishment), no progress is updated on the alert system — leaving the CEO with no visibility.
5. This agitates the CEO further, causing him to act more harshly in an attempt to discipline his workforce.

---

## PART B — Intervention Design

---

### Intervention for Situation A — The Alert Nobody Responds To

#### First Conversation with COO (Mr. B)

The COO was entirely absent from all diagnostic discussions — suggesting he is not actively involved in the overall process. This conversation is critical.

The conversation will focus on understanding his role and approach:
- What steps does he take after a red item alert is published?
- What is his thought process — who does he contact, what does he plan, and how does he achieve it?
- What happens if an item shows no progress — how does he escalate and what changes in his approach?

These questions will help us understand whether there is any set approach in place or whether everything is reactive. Findings and analysis will be shared with him, and we will **design an escalation path together**.

---

#### Week 1 Changes

The first priority is addressing **big ticket items: red items**. The goal is to track them and de-escalate them.

- Request the CEO to allow one week for improvements to the alert system.
- Sit with each HOD **individually** — not in a public setting — running 2 meetings per day to track all red items, understand how they are being handled, and estimate their time to closure.
- Share findings with the COO; let them take command of the approach for current issues and communicate how they are being tracked.
- Ensure the COO attends the daily meeting this week to monitor technical issues.
- At week's end, compile data: how many technical issues were handled, their time to closure, and how red items progressed.
- Share this report with both the CEO and COO and await feedback.

---

#### Week 2 Changes — Restructuring the Alert System

Introduce **new fields into the alert email system**:

| Field | Purpose |
|---|---|
| **Date Issue Raised** | Establishes a clear timeline |
| **HOD's Name** | Named departmental accountability |
| **Point of Contact (POC)** | The person directly handling the matter |
| **History / Trend** | How the issue progressed and was handled over time |
| **Escalation Level** | Maps whose attention this task requires |
| **Action Taken** | What is currently happening to de-escalate this |

**Revised alert table structure:**

| System | Department | HOD | Status | Date Issue Raised | POC | Action Taken | Days Overdue | Trend | Escalation Level |
|---|---|---|---|---|---|---|---|---|---|

POC name, action taken, and trend data can be collected via phone call or WhatsApp at the end of each day, functioning as a daily follow-up.

This allows higher-ups to monitor progress without additional frustration, and helps distinguish between **unique** and **recurring issues**. When a pattern is noticed, leadership can explore alternate workflows or fix the root cause.

---

#### Business Problems This Solves

1. Provides clarity to the CEO and other higher-ups — displaying daily progress made in the plant.
2. Helps distinguish between recurring and unique issues.
3. Reduces frustration among higher-ups and makes the workplace more collaborative.

---

#### Workflow

1. Each HOD updates their section in a **shared Excel tracker by 5 PM daily** — owner name, next action, and expected completion date (10 minutes max).
2. **PowerAutomate** pulls data at 6 AM, applies RAG logic and escalation rules, and generates the email.
3. Email is distributed to: CEO (full view), COO (full view + escalation highlights), and each HOD (their department only, plus cross-department dependencies).
4. Escalation notifications go **separately** to the specific HOD or COO — not broadcast to all 12.

---

#### Technology Stack

| Tool | Reason |
|---|---|
| **Excel (shared, on network)** | Already in use; past attempts to migrate failed — HODs know Excel |
| **PowerAutomate** | Already used by Anil/Karthik for the current pipeline; extending escalation logic is incremental |
| **WhatsApp (optional)** | Escalation nudges to HODs who don't check email frequently, via PowerAutomate → WhatsApp Business API |

> **Why this works:** The tool enforces individual accountability (names), provides organisational memory (trend, history), and defines escalation (what happens at Day 3, Day 5, Day 7). It converts a **passive broadcast** into an **active management workflow**.

---

### Intervention for Situation B — The Blank Field

#### First Conversation with Supervisor (Private)

An honest conversation with the supervisor is essential. The approach:

1. **Apologise and show empathy** towards the supervisor surviving a harsh and toxic work culture.
2. Keep the conversation **focused on observations** — not on why fields were left blank.
3. Give **reassurance that things will change** and communicate with higher-ups on crafting a more employee-friendly approach to handling deviations.
4. Propose a new deviation tracking approach to solve the preceding issues.

---

#### What Changes in the First 2 Weeks (No Tools)

**Week 1:**
- Have the same private conversation with **3–4 supervisors from different departments** to confirm the pattern and build a coalition of people who want to write real root causes but are afraid to.
- Review the **last 3 months of deviation review meeting minutes** (via Anil and Karthik's MOMs), looking for specific instances where an honest root cause was written and the outcome was blame vs. problem-solving.
- Document these as **evidence for the conversation with the CEO**.

**Week 2 — Conversation with Mr. R:**

This is a high-stakes conversation. Not a presentation. A conversation.

> *"Mr. R, I looked at the deviation tracker. 70% of root cause fields are blank. Anil and Karthik think it's a discipline problem. It's not. I spoke to several supervisors. They told me — consistently — that when they write an honest root cause, it becomes a topic in the review meeting and the person responsible gets called out publicly. After that happened a few times, people stopped writing real root causes. They handle it informally instead.*
>
> *This means we have two systems running in parallel. A formal one that's mostly blank, and an informal one where problems actually get solved but nothing is documented. The formal system is useless for learning, trending, or prevention. And the informal one will break when we scale to 8 projects because it depends on the same 12 people remembering everything.*
>
> *What I want to propose is a small change to how deviations get reviewed. Instead of asking 'who is responsible,' we ask 'what in the system allowed this to happen?' Same data. Same meeting. Different question. If we do this for 4 weeks and track whether root cause completion improves, we'll know if it works."*

---

#### New Deviation Tracking Form

Creating a structured **form** (rather than a freeform report) to track and organise deviations:

| Field | Description |
|---|---|
| **Date** | When the deviation was first detected |
| **Department** | Name of department |
| **What Happened** | Dropdown list of past categorised issues (from analysis of previous deviation reports) |
| **Possible Reason for Occurrence** | Dropdown of past reasons + AI-assisted suggestion from historical records |
| **Severity** | Severity level |
| **Immediate Action Taken** | What was done to fix this |
| **Preventive Measures** | What to do to prevent recurrence |
| **Status** | Current status |

---

#### What the HOD Sees

A **weekly deviation dashboard** (auto-generated in Excel from entries) showing:
- Deviation count by **category** (not by person)
- Top 3 root cause categories this week
- Repeat deviations (same category, same equipment, same process — appearing more than twice in 30 days)
- Corrective actions: open vs. closed

The report mentions the possible cause without calling out anyone, how it was solved, and most importantly **how to prevent recurrence** — shifting the mentality from blame-shifting to action and prevention.

---

#### What the CEO Sees

A **weekly one-page summary** (auto-emailed via PowerAutomate) showing:
- Total deviations by severity
- Root cause distribution (pie chart — e.g., Equipment 35%, Process 28%, Material 20%, Planning 17%)
- Trend vs. last 4 weeks (is it improving?)
- Repeat offenders — **not people**, but systems, equipment, and processes that keep generating deviations

---

#### Workflow

1. Supervisor logs deviation using the **Excel form** (shared terminal or tablet on the shop floor).
2. Entry auto-populates the department tracker.
3. Deviations are reviewed in a **separate weekly deviation review meeting** — not the daily status meeting. Attendees: relevant HODs only (2–3 people), facilitated by Anil or Karthik.
4. Review question: **"What in the system allowed this? What's the fix?"** — Not: *"Who did this?"*
5. Weekly summary auto-generated and emailed to CEO/COO.

---

#### Technology Stack

| Tool | Reason |
|---|---|
| **Excel with structured drop-downs and data validation** | Supervisors already use Excel; dropdowns remove the writing burden |
| **PowerAutomate** | Weekly summary email and repeat-deviation flagging |
| **Future state (Month 3+)** | If root cause completion reaches >85%, migrate to Google Forms or PowerApps for mobile shop floor access |

---

#### Buy-In Approach — Script for a 15-Year Veteran

> *"I know why this field is blank. It's not because you don't know what happened — you probably fixed it before the form was even filled out. The problem is that writing it down has been risky. Write the real reason, get questioned. Leave it blank, move on quietly. That's rational.*
>
> *But here's what it costs. When the same thing breaks again next month, nobody remembers it happened before because it wasn't recorded. Your team ends up fighting the same fire twice. And when we scale to more projects, you won't be able to hold all of this in your head.*
>
> *I've redesigned the form. It's dropdowns, not essays. You pick from a list — 'Maintenance gap,' 'Vendor quality,' 'SOP inadequate' — and move on. It takes 2 minutes. And deviations are no longer reviewed in the big meeting. They're reviewed in a small room with just the relevant people, and the question is 'what system fix prevents this,' not 'whose fault is this.'*
>
> *Try it for two weeks. If it still feels like it creates problems for you, tell me and I'll fix it."*

---

### Intervention for Situation C — The Meeting That Eats the Day

#### First Conversation with Anil

Anil runs this meeting, takes the notes, and does the follow-up — he feels the pain most acutely.

**Ask Anil to do one thing differently in tomorrow's daily meeting:** Keep a tally for every item discussed, marking whether it was:
- **(a)** A status update that could have been shared in writing
- **(b)** A technical issue that needed real-time discussion
- **(c)** A cross-departmental coordination issue

Just tally marks on paper — no other changes. Then review together after the meeting.

> *"If the status updates were already in the tracker before the meeting started, and the technical issues had their own 15-minute slot, what would be left for the daily meeting?"*

---

#### What Changes in the First 2 Weeks (No Tools)

**Week 1:**

Anil tallies meeting content for 3 days. Hypothesis: **60–70% status updates** (already in the tracker), **20% technical issues** (wrong forum), **10% actual cross-functional coordination** (the real purpose of the meeting).

Propose a **three-tier structure** to Mr. B (COO) — not as a mandate, but as a **2-week pilot**:

| Tier | Format | Description |
|---|---|---|
| **Tier 1 — Async Status** | No meeting | HODs update the tracker by 5 PM. The morning email *is* the status meeting — no need to verbally repeat what's already written. |
| **Tier 2 — Daily Standup** | 15 minutes max | Only items requiring cross-departmental coordination or escalation. Standing meeting (literally standing). Only HODs with active cross-functional items attend. Format: *"I need [X] from [Department Y] by [date]. Can you commit?"* |
| **Tier 3 — Technical Review** | 30 minutes, 3× per week | OOS investigations, yield deviations, equipment issues. Only relevant HODs + technical leads — not all 12. |

**Week 2:**

Pilot runs. Attend every meeting, tracking duration, number of attendees, and whether unplanned work generated was truly unplanned or could have been anticipated with better daily planning.

Introduce a **daily micro-planning discipline** for Anil and Karthik first (lead by example): every evening, write three things:
1. Top 3 tasks for tomorrow
2. Any dependencies on others
3. One potential disruption anticipated

This takes 5 minutes. Encourage 2–3 friendly HODs to try the same during the pilot period.

---

#### Tool Design

**What the HOD sees — Tier 1 (Async Status):**

Three columns added to each task row in the existing Excel tracker:

| Task | Status RAG | Yesterday Progress | Today Plan | Blocker (if any) |
|---|---|---|---|---|

Each HOD fills these three columns by 5 PM — replacing the verbal update in the meeting. Total time: **10–15 minutes of writing replaces 10 minutes of talking in a 12-person room**.

**What the facilitator sees — Tier 2 (Daily Standup):**

A one-page **Standup Agenda** auto-generated from the tracker at 6 AM:

| Requesting Dept | Needs From | What | Deadline | Status |
|---|---|---|---|---|

Only these items are discussed in the standup — everything else was already communicated via the tracker.

---

#### Technology Stack

| Tool | Reason |
|---|---|
| **Excel (same tracker, extended)** | Async status updates — no new tools |
| **PowerAutomate** | Auto-generates standup agenda by filtering the tracker for cross-departmental dependencies or blockers |

> **No new tools.** The intervention is **structural** (tiered meetings) and **behavioural** (planning discipline), not technological.

---

#### Buy-In Approach — Script for a Sceptical HOD

> *"Right now you spend 10 minutes in the meeting giving your update, then you sit through 80 minutes of other people's updates. Most of it doesn't involve you. What I'm proposing is: you write your update in the tracker by 5 PM — same information, takes the same 10 minutes — and the daily meeting shrinks to 15 minutes of only the items that actually need your input.*
>
> *That gives you back roughly 45–60 minutes every morning. What would you do with that time?"*

**The frame:** Not adding a meeting or a process — **giving you an hour of your day back**. The cost is 10 minutes of writing in the evening instead of 10 minutes of talking in the morning. The math is obvious.

---

## PART C — Scale Thinking

### What Breaks First When the Company Scales from 2 to 8 CDMO Projects?

---

#### The Single Most Dangerous Failure Point: The Informal Coordination System

Right now, the organisation runs on **informal, person-to-person coordination**. The 12 HODs know each other. They've worked together for years. When a deviation happens, Supervisor 1 walks over to the maintenance shop and talks to Raju. When a vendor delivery is late, the purchase head calls the warehouse head directly.

This works at 2 projects because the **cognitive load is manageable**. Twelve people can hold 2 projects in their heads. At 8 projects, this breaks catastrophically.

---

#### Why It Breaks

**1. Cross-departmental dependencies multiply non-linearly.**

Each CDMO project involves Quality, Production, Purchase, Warehouse, Maintenance, and R&D at minimum.

| Projects | Approx. Active Cross-Departmental Dependencies |
|---|---|
| 2 projects | ~15–20 |
| 8 projects | ~60–80+ |

No single meeting, no single tracker, and no group of 12 people can hold this in their heads.

**2. The informal resolution system becomes a bottleneck.**

When Supervisor 1 has to coordinate with Maintenance on 4 simultaneous batches instead of 1, the *"walk over and talk to Raju"* approach doesn't scale. Raju is already talking to 3 other people. Queues form, information gets lost, priorities conflict, and there is no triage system.

**3. Anil and Karthik become a single point of failure.**

They're already acting as human middleware at 2 projects. At 8 projects, even with 3–4 more analysts, the follow-up model collapses. Each analyst would need to follow up on 50–80 items daily — becoming bottlenecks themselves.

**4. The meeting implodes.**

A 90-minute meeting for 2 projects becomes a 4-hour meeting for 8 — or, more likely, stays 90 minutes and critical items don't get discussed. Undiscussed items become untracked issues, which become batch failures, delivery delays, and client escalations.

**5. The deviation tracker becomes a compliance fiction.**

At 2 projects, supervisors can *"handle it quietly"* without documentation. At 8 projects, the same deviation happens on different batches and nobody knows it's the same root cause — because nothing was recorded the first time. Repeat failures multiply. Corrective actions are never systematic.

---

#### What System to Build Now (at 2 Projects) That Prevents This at 8

**A project-level dependency tracker with automated cross-departmental visibility.**

This is distinct from the existing task-level tracker. The current tracker shows individual tasks with department-level status. What's missing is a **project-level view** showing, for each CDMO project, what each department owes to that project, when it's due, and what depends on it.

**Structure — One Excel workbook, one sheet per active CDMO project:**

| Phase | Task | Owner (Name) | Dept | Depends On | Due Date | Status | Blocker |
|---|---|---|---|---|---|---|---|

**Summary "Portfolio View" sheet** auto-aggregates across all projects:

| Project | Phase | Overall RAG | Blocking Department | Days at Risk |
|---|---|---|---|---|

**What this gives at 8 projects:**
- Each HOD sees what they owe across all 8 projects, sorted by urgency.
- The CEO sees a one-page portfolio view: which projects are on track, which are at risk, and which department is the bottleneck.
- Dependencies are **explicit and predictive** — if Warehouse is late on RM release, the system shows that Production and QC Lab will also slip *before it happens*.
- The 3–4 new analysts each own 2 projects and manage the tracker for those projects, rather than doing generic follow-up across all departments.

**Technology:** Excel (tracker) + PowerAutomate (portfolio summary email and escalation triggers). Built now, at 2 projects, so the structure is tested and habits are formed before volume increases.

---

### Automate vs. Human — Where the Line Is Drawn

#### Automate

| Task | Reason |
|---|---|
| **Daily status aggregation and email** | Pure data aggregation; no judgment needed. PowerAutomate pulls from Excel, formats, and sends. |
| **RAG status assignment (with human override)** | Overdue by X days = Red is a rule. But HODs must be able to override with a note for valid exceptions (e.g., waiting on regulatory input). |
| **Escalation triggers** | *"If red for >3 days, notify HOD"* / *"If red for >5 days, notify COO"* — rules, not judgment. Don't make humans remember to escalate. |
| **Deviation trend analysis** | *"Same equipment, same deviation, 3rd time in 30 days"* is a pattern a formula can catch. Flag it automatically. |
| **Meeting agenda generation** | Filter the tracker for cross-departmental blockers and generate a 1-page agenda. Pure data filtering. |
| **WhatsApp escalation nudges** | *"Your task is 3 days overdue. Please update the tracker or escalate."* Prompts action — doesn't replace the conversation. |
| **Weekly deviation summary for CEO** | Aggregation and formatting: charts, trends, category breakdowns. Let the machine count; let the human interpret. |

#### Keep Human

| Task | Reason |
|---|---|
| **Deviation entry** | The supervisor must enter the deviation. Dropdowns reduce burden, but *"what happened"* and *"which category"* require shop floor knowledge no automation can replace. |
| **Root cause analysis** | Root cause determination is judgment, not data processing. The system can prompt with structured categories, but a human must decide. |
| **Cross-departmental dependency identification** | Only the HOD or project analyst knows *"this task depends on that one."* The system can visualise dependencies once entered — but it cannot discover them. |
| **Follow-up conversations** | When something is stuck, a human conversation uncovers the real reason. An automated reminder gets ignored (we already know this from Situation A). Anil and Karthik's value is in the *conversations*, not in sending reminders. |
| **Daily micro-planning** | Planning is a thinking exercise. The system can provide a template, but the HOD must think through *"what are my priorities today?"* |

---

> **The principle:** Automate data movement, aggregation, and rule-based triggers. Keep human everything that requires judgment, relationship, or contextual understanding. The supervisors don't need more automation — they need **better-designed touchpoints** that take 2 minutes instead of 20, and don't punish them for telling the truth.

---

### The Breaking Point at Scale

At 2 projects, the loop described across Situations A, B, and C is **barely sustainable**. At 8 projects, it doesn't slow down — it **accelerates**:

| Driver | Cascade Effect |
|---|---|
| More projects → more deviations | → more blank fields → less visibility |
| More projects → more coordination needed | → meeting overloads → more unplanned work |
| More projects → Anil/Karthik can't manually follow up on everything | → things fall through |

The **informal coordination system** — hallway conversations, personal relationships, institutional memory held in people's heads — cannot handle 4× the dependency volume. It was never designed to. It just happened to hold together at 2 projects.

---

### The Intervention Logic

Break the loop in this sequence:

```
Psychology layer first  →  Technology layer second  →  Business layer follows
(change how deviations     (structured forms,            (visibility, scalability,
 are reviewed)              individual accountability      capacity for improvement)
                            in alerts, tiered meetings)
```

**The sequence matters.**

If you build the dashboard before fixing the blame culture, you get a better-looking system that still produces lies.

> Technology amplifies whatever human dynamic it sits on top of.

Fix the dynamic first. Then build the tools that make the better dynamic scale.

---

## Anil and Karthik's Role Drift

This is arguably the **most urgent meta-problem** in the organisation.

Two people hired to build systems and drive cultural change have become **full-time follow-up machines**.

> Anil says it directly: *"By the time I'm done following up, there's no bandwidth to think about improvements or build new systems."*
> Karthik is fixing printers.

---

### How the Role Drift Happened

This drift is a **direct consequence** of the three situations, not a failure of Anil or Karthik:

| Situation | Consequence for Anil & Karthik |
|---|---|
| **A** — The alert doesn't drive action | They follow up manually to get status |
| **B** — The forms stay blank | They remind people to fill them in |
| **C** — The meeting generates unplanned work | They spend the day executing instead of designing |

Each situation individually adds load. Together, they consume all available bandwidth — leaving zero time for the system-building and process design these roles were created for.

---

### Why This Compounds at Scale

If this isn't corrected, the 3–4 new analysts hired for the expansion will **follow the same trajectory**.

Within 3 months, the company will have **5–6 people doing manual follow-up** instead of building the systems that would make follow-up unnecessary.

The org will have scaled its workaround, not its capability.

---

### Recommendation

**Explicitly redefine Anil and Karthik's roles:**

| Time Allocation | Function |
|---|---|
| **60%** | System-building and process design |
| **40%** | Coordination and facilitation |

The **follow-up function must be transferred to the HODs** — who should own their department's execution — through the accountability systems described in Part B.

Anil and Karthik's value is not in remembering who owes what. It's in **designing the systems that make remembering unnecessary**.
