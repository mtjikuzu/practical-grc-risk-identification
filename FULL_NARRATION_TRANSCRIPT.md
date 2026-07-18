# Full Narration Transcript & Facilitator Script
## Practical Risk Identification Workshop
### Cause → Event → Impact Method (Expanded 2h45m – 3h Version)

**Repository:** https://github.com/mtjikuzu/practical-grc-risk-identification

**Intended Use:**  
This is a complete, speakable narration script for live streaming or in-person workshops. It includes timing cues, what to show on screen, chat prompts, facilitation notes, and suggested phrasing. Use it as your primary guide while remaining responsive to chat/audience energy.

**Pacing Notes:**  
- Speak naturally at ~130–150 words per minute.  
- Pause intentionally after questions.  
- The live risk-building section is the heart — protect that time.  
- Total runtime target: 2h45m – 3h including natural interaction.

---

## 00:00 – 00:18 | Context & Real-World Alignment

**On Screen:**  
- Title slide with repo link and objectives  
- Then switch to a clean example of a “lived-in” Risk Register (anonymized)

**Narration Script:**

"Good evening everyone, and welcome to this practical Risk Identification workshop.

My name is [Your Name], and over the next two hours and forty-five minutes to three hours, we’re not going to talk *about* risk identification in theory. We’re going to *do* it — the way real organizations actually do it when something important is changing.

Tonight we’re using the Cause → Event → Impact method. This isn’t academic fluff. This is the format that holds up in audits, that boards understand, and that actually drives treatment decisions instead of sitting in a spreadsheet nobody ever looks at again.

Before we dive in, I want to set the stage with something very real.

[Show lived-in Risk Register example]

Look at this register. This is not a theoretical document. This came from an actual organization going through a major change. Every line here has a clear owner. Every line has a source. Every line is written so that someone who wasn’t in the room can understand what could go wrong and why leadership should care.

Most risk registers you see in the wild don’t look like this. They’re full of vague statements like ‘Cloud risk’ or ‘Third-party risk’ with no cause, no specific event, and no business impact. Those registers become shelfware.

Our goal tonight is simple but ambitious: by the end of this session, you will be able to run a risk identification exercise in your own organization that produces *this* level of quality — specific, actionable, and defensible.

Let’s start with a quick question for the chat:

**Chat Prompt:**  
“What’s the biggest problem you see with risk registers in your organization right now?”

[Wait 60–90 seconds, acknowledge 2–3 answers live]

Common answers I hear are: too vague, no owners, never updated, too many risks, or nobody actually uses them for decisions.

All of those problems usually start at the identification stage. If we identify risks poorly, everything downstream suffers.

That’s why we’re spending almost three hours on this. Identification is not a 30-minute checkbox activity. When done properly, it sets up everything else — analysis, treatment, monitoring, and audit evidence.

Alright, let’s move into how real organizations actually run this process."

**Facilitation Notes:**  
- Keep energy high but grounded.  
- Acknowledge chat answers genuinely.  
- Transition smoothly into the process section.

---

## 00:18 – 00:45 | The Practical Process Organizations Actually Use

**On Screen:**  
- Risk Identification Inputs Checklist (mark items live)  
- Simple process flow diagram (optional)

**Narration Script:**

"Most frameworks show risk identification as a clean box in a diagram. In reality, it’s messy, iterative, and triggered by change more often than by the annual calendar.

Here’s how mature organizations actually do it:

**Step 1: Trigger**  
Something is changing — a new system, a cloud migration, a regulatory deadline, a major incident, or a strategic initiative. That trigger tells us it’s time to identify risks deliberately.

**Step 2: Define Scope**  
What’s in scope and what’s out? Are we looking only at information security risks? Operational risks? Third-party risks? Being explicit here prevents scope creep later.

**Step 3: Gather Inputs**  
This is where most of the value is created — and where most people shortcut.

[Show Inputs Checklist on screen and walk through categories]

We pull from:
- Asset inventories and architecture diagrams
- Project plans and known constraints (timeline, budget, skills gaps)
- Previous risk registers and residual risks
- Internal and external audit findings
- Incident and near-miss logs
- Vulnerability scans and penetration test results
- Threat intelligence relevant to our technology and sector
- Third-party information and contracts
- Regulatory requirements and recent enforcement actions

Notice something important: perfect information almost never exists. Mature organizations work with the best available data and document their assumptions.

**Mini-Exercise (Live – 5–7 minutes)**

Let me show you how this works in practice.

[Pick one realistic input — e.g., “Recent internal audit finding: Change management process has gaps in rollback procedures”]

Chat, look at this input. What risk could this create in a major cloud migration project?

[Take 2–3 suggestions from chat]

Good. Now let’s refine one of them together into proper Cause → Event → Impact format.

[Model the refinement live]

See how much more useful that becomes once we make the cause specific and the business impact explicit?

This is the muscle we’re going to build over the next hour and a half.

**Step 4–7: Facilitate, Document, Assign Owners, Capture Sources**

Once we have inputs, we facilitate — usually in workshops or structured interviews. We document using the Cause → Event → Impact structure. We assign preliminary owners (roles, not just names). And we always capture the source so an auditor or future reviewer can understand where the risk came from.

Common failure modes at this stage:
- Being too vague
- Staying purely technical instead of business-focused
- Leaving risks without owners
- Never recording sources
- Treating identification as a one-time event instead of something triggered by change

That’s the real process. Now let’s put it into action with our case study."

**Facilitation Notes:**  
- Mark items on the Inputs Checklist live as you discuss them.  
- Run the mini-exercise with real energy — this builds confidence before the main case.  
- Keep the tone practical and encouraging.

---

## 00:45 – 02:05 | Live Hands-On Demo (Core of the Session)

**On Screen:**  
- Case Study summary (first 5 min)  
- Then Risk Register template (main working view for 60–70 min)  
- Inputs Checklist (occasionally)

**Narration Script:**

"Now we move into the heart of the session — the live hands-on risk identification using the Apex Financial Services case study.

**Introduce the Case Study (7–8 minutes)**

Apex Financial Services is a mid-sized regulated financial organization with about 850 employees. They’re in the middle of a high-pressure digital transformation:

- Launching a new native mobile banking app (iOS + Android) with biometric login, transfers, bill payments, etc.
- Migrating customer-facing services and data to a major public cloud provider
- Decommissioning selected on-premise infrastructure afterward

Timeline: Aggressive 4-month target driven by a fixed marketing launch date.

Constraints: Limited internal cloud security expertise, relatively basic existing vulnerability and change management processes, multiple third parties involved, and full regulatory compliance must be maintained.

Available inputs for us tonight:
- High-level project plan and architecture overview
- Partial asset inventory
- Recent internal audit findings on change management
- Sample vulnerability scan results
- Regulatory requirements around customer data and operational resilience
- Incident log from the past 18 months

This scenario is excellent because it naturally surfaces cyber, operational, third-party, compliance, and change-management risks all at once.

**Confirm Scope (5 minutes)**

Before we start identifying risks, let’s be explicit.

In scope for tonight: Information security risks, operational risks tied to the change, third-party risks, compliance/regulatory risks arising from the migration and app launch, and change management / go-live risks.

Out of scope: Pure strategic or financial business risks unrelated to technology or security, and detailed residual risk calculation (that comes in the next session on analysis and treatment).

Any questions or scope challenges from the chat before we begin?

**Review Available Inputs in Context (10–12 minutes)**

Let’s quickly mark which inputs we actually have in this scenario and what kind of risks each one tends to surface.

[Walk through Inputs Checklist live, marking items]

For example:
- The recent internal audit findings on change management are gold for identifying rollback and go-live risks.
- The incident log from the past 18 months often reveals patterns around authentication or privileged access.
- The architecture overview helps us spot data flow and privacy mapping gaps.

**Live Risk Identification – Build 6–7 Risks (60–70 minutes)**

This is the core. We’re going to build risks live together using the Cause → Event → Impact format.

For each risk I will:
1. Identify a plausible cause grounded in the case study and our inputs
2. Define the specific event
3. Articulate the business impact (financial, regulatory, operational, reputational, customer)
4. Write the full statement in the Risk Register
5. Assign category, affected assets/processes, and impact categories
6. Give initial Likelihood and Impact ratings with justification
7. Assign a realistic Risk Owner (role)
8. Record the source

I want you in chat to challenge me, improve the wording, suggest additional causes, and question whether the impact is specific enough.

Let’s start with the first one.

**Risk 1: Cloud Misconfiguration / IAM (10–12 min)**

Cause: Insufficient cloud security expertise combined with an aggressive migration timeline and pressure to meet the marketing launch date.

Event: Improperly configured storage buckets or overly permissive IAM roles expose customer financial data in the cloud environment.

Impact: Regulatory fines, mandatory breach notification costs, significant reputational damage, potential temporary suspension of digital services, and loss of customer trust.

[Enter into Risk Register live]

Chat — how would you strengthen this? Is the cause specific enough? Is the impact business-focused enough?

[Incorporate good suggestions live. Refine on screen.]

Good. Now let’s rate it.

Likelihood: I’m putting 4 (Likely) because rushed cloud migrations with limited expertise are a known pattern.

Impact: 5 (Severe) — regulatory action, customer data exposure, and trust damage in a financial organization is existential.

Owner: Cloud Migration Lead / CISO

Source: Project timeline pressure + known skills gap + architecture overview

[Continue this pattern for Risks 2–7]

**Risk 2: Mobile Application Security Weaknesses (due to timeline pressure)**  
**Risk 3: Third-Party / Supply Chain Compromise**  
**Risk 4: Change Management & Go-Live Failure**  
**Risk 5: Incomplete Data Flow Mapping & Privacy Gaps**  
**Risk 6: Expanded Privileged Access Without Controls**  
**Risk 7: Skills Gap / Monitoring Blind Spots (chat-driven or from incident log)**

For each risk, pause and actively pull from chat. Refine live. Show the before-and-after when someone suggests something vague.

**Mid-Session Quality Review (10–12 minutes)**

Alright, let’s step back and look at the register we’ve built so far.

[Scroll through the Risk Register on screen]

I want us to evaluate against clear quality criteria:
- Is every statement specific enough that someone outside this room could understand it?
- Does every risk have a clear, business-relevant impact (not just technical)?
- Does every risk have a realistic owner (role)?
- Is the source recorded?
- Are there obvious duplicates or overlaps we should consolidate?
- Are there any major risk areas from the case study we’ve completely missed?

Chat — pick one or two risks and tell me what you would improve.

[Facilitate live refinement of 2–3 risks based on chat input]

This quality review step is what separates good identification from great identification. Never skip it."

**Facilitation Notes:**  
- This is the longest and most important block. Protect the energy here.  
- Be generous with chat — incorporate good ideas visibly.  
- When someone gives a weak suggestion, kindly refine it on screen rather than rejecting it.  
- Aim for 6–7 high-quality risks, not 15 weak ones.

---

## 02:05 – 02:35 | Real-World Challenges, Quality Practices & Linkages

**On Screen:**  
- Side-by-side weak vs strong risk statement example  
- Risk Register from the live session  
- Simple diagram showing linkages to Vulnerability Management and Change Management

**Narration Script:**

"Now that we’ve done the work, let’s talk about why this matters in the real world and where most organizations still fall down.

**Quality of Risk Statements**

[Show 2–3 weak vs strong examples]

Weak: “Cloud risks”  
Strong: The full Cause → Event → Impact statement we built earlier.

The difference is night and day for anyone who has to act on it or defend it in an audit.

Common anti-patterns I see constantly:
- Vague titles with no cause
- Purely technical impacts (“data breach”) with no business consequence
- No owners assigned
- Risks written so broadly that they’re impossible to treat
- “All risks are high” — which tells leadership nothing

**Ownership and Accountability**

Assigning a role matters enormously. When no one owns a risk, nothing happens. When the wrong person owns it, the wrong treatment gets chosen.

In our session tonight, we assigned roles like Cloud Migration Lead, CISO, Programme Manager, Data Protection Officer. These are real roles that exist in organizations. That’s what makes the register actionable.

**Risk Register Theater vs Living Registers**

Most risk registers are maintained only for audit. They get updated once a year, risks are copied forward, and nobody uses them for actual decisions.

Mature organizations treat the risk register as a living tool. It’s triggered by change. It’s reviewed regularly. It’s integrated with vulnerability management, change advisory boards, and third-party risk processes.

**Linkages to Other Processes**

This is where identification pays off.

Take one of the risks we identified tonight — for example, the change management and go-live risk.

How does that risk affect Vulnerability Management? It tells us we need to prioritize scanning and testing of the new cloud environment and mobile app before go-live.

How does it affect the Change Advisory Board? It raises the bar for rollback procedures, training, and hypercare support.

How does it affect third-party risk management? It highlights the need for stronger oversight of the cloud provider and mobile development partner during the transition.

When you identify risks well, they naturally flow into these other processes instead of living in isolation.

**Scoring Realism**

The Likelihood and Impact scores we gave tonight are provisional. They will be refined during the analysis phase with more data. The danger is over-scoring everything as Critical or High just to get attention. That destroys credibility.

Be honest. A 3x4 risk is still worth managing.

**Interactive Element**

Chat — pick one risk from the register we built tonight. Tell me how you think it should influence either vulnerability management priorities or the go-live decision.

[Take 2–3 answers and discuss briefly]

This is the thinking that turns identification from a compliance exercise into a decision-support tool."

**Facilitation Notes:**  
- This section can run longer if energy is high.  
- Use real examples from the risks the group just built.  
- Keep the tone honest and practical — call out common organizational failures without shaming.

---

## 02:35 – 03:00 | Wrap-up, Artifacts, Practice Challenge & Next Steps

**On Screen:**  
- Summary slide with key takeaways  
- All artifacts (templates, case study, lesson plan) with links  
- Practice Challenge slide

**Narration Script:**

"Let’s bring this home.

Tonight we did real work. We didn’t just talk about risk identification — we practiced it at the level that actually matters in organizations.

**Key Takeaways**

1. Risk identification is triggered by change more often than by the calendar.
2. The quality of your inputs determines the quality of your risks. Don’t shortcut this step.
3. Cause → Event → Impact is the format that survives audits and drives action.
4. Ownership and sources are non-negotiable if you want the register to be useful.
5. Quality review is where good becomes great. Never skip it.
6. Well-identified risks naturally connect to Vulnerability Management, Change Management, third-party oversight, and audit evidence.

**Artifacts – All Free**

Everything we used tonight is in the repository:

- The expanded Lesson Plan
- This Facilitator Guide
- The Apex Financial Services Case Study
- Blank and populated Risk Register templates
- Inputs Checklist

Link is in the chat and description. Clone it, use it, adapt it.

**Your Practice Challenge**

Here’s what I want you to do this week:

Take one real initiative that is currently happening or planned in your organization. It can be a system upgrade, a cloud migration, a new application, a process change — anything with some complexity.

Using the method we practiced tonight, write 4–5 real risks in Cause → Event → Impact format. Assign owners and sources. Then ask yourself: Would these risks actually help someone make a decision?

Do that exercise. It will be uncomfortable at first. That’s how you get better.

**Next Session Tease**

In our next session we’ll move from identification into Risk Analysis and Evaluation — how we turn these identified risks into prioritized, decision-useful information with proper scoring and treatment options.

**Final Q&A**

We have some time left. What questions do you have? What felt unclear? What do you want to explore more deeply?

[Run Q&A naturally]

Thank you so much for spending almost three hours with me tonight. If you do the practice challenge, I promise you’ll see a difference in how your organization thinks about risk.

Stay safe, keep building, and I’ll see you in the next one.

Repo link is in the chat. Go download everything and start using it this week."

**Facilitation Notes:**  
- End on a high, encouraging note.  
- Strongly reinforce the practice challenge — this is the highest-ROI takeaway.  
- Thank participants genuinely.

---

## Closing Notes for Facilitator

- Total runtime target: 2h45m – 3h with natural chat interaction.
- The live risk-building block (60–70 min) is sacred — protect it.
- When in doubt, slow down and let chat participate rather than rushing to the next slide.
- Record the session if possible so participants can revisit the live refinements.
- The goal is not perfection. The goal is building the muscle of high-quality, business-relevant risk identification.

**End of Full Narration Transcript**

---

*This transcript is designed to be used alongside the Lesson Plan, Case Study, and templates in the repository. Adapt the wording to your voice and the energy of your audience while keeping the structure and depth intact.*