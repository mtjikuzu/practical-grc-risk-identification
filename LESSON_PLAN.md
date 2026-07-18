# Lesson Plan: Practical Risk Identification
## Cause → Event → Impact (Scenario-Based Walkthrough)

**Duration:** 2 hours 45 minutes – 3 hours  
**Format:** Live interactive walkthrough (Twitch / YouTube)  
**Primary Tools:** Risk Register template (Excel/Google Sheets), Case Study document, Inputs Checklist

This session is deliberately substantial. The extra time is used for real facilitation practice, live refinement of risk statements, quality challenges, and connecting identification work to how organizations actually operate (audit, vulnerability management, change management, ownership).

---

### Learning Objectives

By the end of this session, participants will be able to:

1. Explain how real organizations identify risks during major technology change initiatives and why the Cause → Event → Impact format is preferred for auditability and actionability.
2. Write clear, specific, and business-relevant risk statements using the Cause → Event → Impact structure.
3. Extract useful risk insights from imperfect organizational inputs (project plans, audit findings, incident logs, architecture diagrams, vulnerability scans).
4. Populate a professional Risk Register with proper categorization, impact categories, initial scoring, ownership, and sources.
5. Critically evaluate risk statement quality and refine weak statements into strong ones.
6. Understand how identified risks feed into later stages (analysis, treatment, monitoring) and into related processes such as Vulnerability Management and Change Management.

---

### Pre-Session Preparation (Facilitator)

**Mandatory**
- [ ] Fully internalize the Apex Financial Services Case Study (be able to summarize it without looking).
- [ ] Open the blank Risk Register template and have it ready to screen-share.
- [ ] Open the Risk Identification Inputs Checklist.
- [ ] Prepare 6–8 strong example risks in Cause → Event → Impact format (use as backup only — build most live).
- [ ] Prepare 3–4 deliberately weak / vague risk statements to use as live refinement exercises.
- [ ] Test screen sharing of Excel/Google Sheets + Markdown documents.
- [ ] Prepare OBS scenes: Main (spreadsheet + chat), Documents, Notes / examples.

**Recommended**
- Have one short anonymized real risk register example ready to show (even if redacted).
- Have a simple one-page process diagram of the risk identification workflow.

---

### Detailed Timed Agenda

#### 00:00 – 00:18 | Context & Real-World Alignment
**Goal:** Establish credibility and show why this is not academic.

- Welcome, session objectives, and expected outcomes.
- Why organizations perform structured risk identification:
  - Regulatory and audit expectation (evidence of a systematic process)
  - Informed decision-making under resource constraints
  - Prioritization of limited security and compliance effort
  - Ability to demonstrate due care when something goes wrong
- How this activity fits into ISO 27001 Clause 6.1 and the broader risk management process (identification → analysis → evaluation → treatment → monitoring).
- The practical difference between a living risk register and “risk register theater”.
- Show a short “lived-in” example of a real (anonymized) risk register so participants can see the end product and the level of specificity expected.

**Screen share:** Blank Risk Register + one completed / lived-in example.

**Interactive moment:** Ask chat: “In your experience, what is the biggest problem you see with risk registers?” Capture 2–3 answers and come back to them later.

---

#### 00:18 – 00:45 | The Practical Process Organizations Actually Use
**Goal:** Demystify the real workflow and show the inputs that actually drive identification.

Walk through the real-world sequence in detail:

1. **Trigger** — Change initiatives, new projects, major findings, regulatory pressure, or the annual cycle.
2. **Define scope and objectives** of the risk identification exercise (what is in / out of scope and why).
3. **Gather available inputs** (this is where most of the value is created):
   - Asset and process inventories
   - Architecture and data-flow diagrams
   - Project plans and constraints (timeline, budget, skills)
   - Previous risk registers and residual risks
   - Internal / external audit findings and management actions
   - Incident and near-miss logs
   - Vulnerability scan and penetration test results
   - Threat intelligence relevant to the technology and sector
   - Third-party / supplier information
   - Regulatory requirements and recent enforcement actions
4. **Facilitate identification** (workshop, structured interviews, or hybrid).
5. **Document** using a consistent structure (Cause → Event → Impact).
6. **Assign preliminary Risk Owners** (roles, not individuals where possible).
7. **Capture sources and notes** for auditability and future review.

**Deep practical discussion points:**
- Perfect information almost never exists. How mature organizations work with incomplete data.
- Difference between asset-based and scenario-based identification (and why we are using scenario-based here).
- Common organizational failure modes at this stage (too vague, too technical, no owners, no sources, never reviewed again).

**Screen share:** Risk Identification Inputs Checklist.  
Walk through each major category and give concrete examples of how that input type generates risk statements.

**Mini-exercise (5–7 min):** Take one input type (e.g., recent audit findings on change management or a vulnerability scan summary) and have chat suggest 1–2 possible risks. Refine one live into Cause → Event → Impact format.

---

#### 00:45 – 02:05 | Live Hands-On Demo (Core of the Session)
**Goal:** This is the main value of the stream. Participants should leave able to run a similar exercise themselves.

**1. Introduce the Case Study (7–8 min)**  
Summarize Apex Financial Services in detail:
- Organization profile and regulatory context
- The two major change components (new mobile banking app + public cloud migration)
- Aggressive 4-month timeline and business drivers
- Real constraints (skills, third parties, existing process maturity)
- Available inputs that will be used during the exercise

**2. Confirm and Refine Scope (5 min)**  
Explicitly state what is in scope and what is out of scope for this identification exercise. Discuss why certain categories (e.g., pure strategic business risks) are excluded. Invite chat to challenge the scope if they see gaps.

**3. Review Available Inputs in Context (10–12 min)**  
Screen-share the Inputs Checklist and mark which sources are realistically available in the Apex scenario. For each major available input, briefly discuss:
- What kind of risks it typically surfaces
- How to extract Cause → Event → Impact statements from it
- Common mistakes when interpreting that input type

**4. Live Risk Identification (60–70 min)**  
Build 6–7 risks live on screen. This is the heart of the session.

For **each risk** follow this disciplined sequence:
- Identify a plausible Cause grounded in the case study and available inputs
- Define the specific Event that would occur
- Articulate the business Impact (Financial, Regulatory, Operational, Reputational, Customer)
- Write the full Cause → Event → Impact statement
- Enter it into the Risk Register
- Assign Category, Affected Assets / Processes, Impact Categories
- Assign initial Likelihood and Impact ratings with a short justification
- Assign a realistic Risk Owner (role)
- Record the source of the risk

**Facilitation techniques during this block:**
- Frequently pause and ask chat to improve the wording.
- When someone suggests a risk, force it into Cause → Event → Impact format live.
- When a statement is too technical, push for the business consequence.
- When a statement is vague, ask “What specifically could go wrong and why would the Board or regulator care?”
- Occasionally present a deliberately weak statement and have the audience strengthen it.
- Keep a running quality checklist visible (specific, business impact, owner, source).

**Recommended risk themes to cover (order flexible):**
1. Cloud misconfiguration / IAM during migration
2. Mobile application security weaknesses due to timeline pressure
3. Third-party / supply-chain risk (cloud provider + development partner)
4. Change management and go-live failure
5. Incomplete data flow mapping and privacy/compliance gaps
6. Expanded privileged access without corresponding controls
7. One additional risk driven by chat or a specific input (e.g., skills gap, monitoring gaps, rollback readiness)

**5. Structured Quality Review of the Register (10–12 min)**  
After building the set of risks, step back and review the whole register against quality criteria:
- Is every statement specific enough to drive action?
- Does every risk have a clear business impact (not just a technical one)?
- Are owners realistic and appropriate?
- Are sources recorded so an auditor can understand the origin?
- Are there obvious duplicates or overlapping risks that should be consolidated?
- Are there any major risk areas from the case study that are still missing?

Invite chat to critique 1–2 statements.

---

#### 02:05 – 02:35 | Real-World Challenges, Quality Practices & Linkages
**Goal:** Move from “how to write risks” to “how this actually works (or fails) in organizations”.

Deep coverage of:

**1. Quality of Risk Statements**
- Side-by-side examples of weak vs strong Cause → Event → Impact statements.
- Common anti-patterns: vague titles, purely technical impacts, missing causes, missing owners, “all risks are high”.

**2. Ownership and Accountability**
- Why assigning a role matters.
- What happens when no one owns a risk.
- How ownership interacts with treatment decisions later.

**3. Risk Register Theater vs Living Registers**
- Signs that a register is only maintained for audit.
- What mature organizations do differently (triggers for review, integration with other processes, regular challenge).

**4. Linkages to Other Processes**
- How identified risks should inform Vulnerability Management prioritization.
- How they interact with Change Management and go-live readiness.
- How they feed into third-party risk management and residual risk decisions.
- What auditors typically look for when they examine risk identification evidence.

**5. Scoring Realism**
- Brief discussion of why initial Likelihood and Impact scores are provisional and will be refined during analysis.
- Danger of over-scoring everything as high.

**Interactive element:** Take one risk from the live register and discuss how it would (or would not) influence vulnerability prioritization or a go-live decision.

---

#### 02:35 – 03:00 | Wrap-up, Artifacts, Practice Challenge & Next Steps

- Summarize the key takeaways (method, quality criteria, ownership, sources, linkages).
- Share all artifacts clearly:
  - Blank Risk Register template
  - Sample populated Risk Register
  - Case Study
  - Inputs Checklist
  - This Lesson Plan and Facilitator Guide
- **Practice challenge for participants:**  
  “Take one real initiative currently happening (or planned) in your organization. This week, write 4–5 risks using Cause → Event → Impact, assign owners and sources, and see how it feels compared to your current register.”
- Tease the next session: Risk Analysis / Evaluation (how we turn these identified risks into prioritized, decision-useful information) and Risk Treatment.
- Open Q&A (allow time for real questions about facilitation, scoring, organizational pushback, auditor expectations, etc.).

---

### Facilitation Principles (Keep Visible)

- Energy stays practical and conversational, never lecture-heavy.
- Every risk suggested in chat is refined live into Cause → Event → Impact format.
- Business impact is non-negotiable. Purely technical statements get pushed.
- Ownership is never left blank.
- Sources are always captured.
- Quality over quantity — 6–7 strong risks are better than 15 weak ones.
- When energy dips, move to a live refinement exercise or quality critique.

---

### Success Indicators

By the end of the session:
- Participants can independently write a clear Cause → Event → Impact statement.
- The live Risk Register contains specific, business-relevant risks with owners and sources.
- Chat has actively refined multiple statements.
- Viewers understand how this work connects to audit, vulnerability management, and change decisions.
- Participants leave with concrete next actions and the templates to execute them.

---

### After the Stream

- Upload the populated register (anonymized if needed) as a community resource.
- Share the GitHub repository link prominently.
- Collect feedback on which parts of the process were most useful or most difficult.
- Note common questions for refinement of future sessions.
