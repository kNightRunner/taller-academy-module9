# Taller Academy — Module 9: Write the Plan

**Capstone:** Your Path Forward  
**Plan period:** November 2, 2026 – January 30, 2027 (90 calendar days, inclusive)  
**Project area:** Backend Engineering / GraphQL  
**Evidence boundary:** This is a personal development plan. Calendar events, messages to stakeholders, certifications, and future results are not claimed as completed.

## Exercise 1 — Honest Baseline

Scale: **1** = never done; **2** = tried once or twice; **3** = do when it comes up; **4** = do reliably and well; **5** = could teach it.

| Area | Competency | Rating |
| --- | --- | ---: |
| Visibility | My work is findable and understandable by others | 4 |
| Visibility | I write closing comments describing outcomes and decisions | 4 |
| Visibility | I create tickets for work I identify myself | 3 |
| Visibility | I send written updates beyond my immediate team | 3 |
| AI fluency | I maintain a project context file | 3 |
| AI fluency | I explore and plan before implementing | 4 |
| AI fluency | I systematically verify AI-generated code | 4 |
| AI fluency | I have shipped a feature that calls a model | **1** |
| Communication and business | I describe work at user and business levels | 4 |
| Communication and business | I know the key product metrics | 2 |
| Communication and business | I know what a good quarter means to my client manager | 2 |
| Communication and business | I flag risks early in writing | 4 |
| Ownership | I resolve and report unspecified decisions | 4 |
| Ownership | I own an initiative nobody assigned to me | 3 |
| Ownership | My collaboration and support work is recorded | 4 |

### Blocking gap and strongest skill

**Blocking gap — production-style AI feature delivery (1/5).** I regularly use AI during development, but have not shipped a complete application feature that calls a language model and includes an evaluation set, structured output handling, and a safe failure path. This is the first capability I want to develop. A standalone demonstration does not equal deployment to a client's production environment.

**Strength — AI-generated code verification (4/5).** I reliably review code changes, assess compatibility, and consider edge cases. My rating is 4, not 5: I can use this practice to build an evaluated product feature without claiming teaching-level mastery.

**Secondary gaps (2/5):** My understanding of product-area KPIs and the client manager's quarterly success criteria. Questions raised in Module 7 remain pending; I will continue to follow up, without adding separate large goals to this 90-day plan.

## Exercise 2 — Access and dependencies

| Item | Status | Action |
| --- | --- | --- |
| Client-licensed AI assistant | **Have it** | Follow client-specific approved usage. |
| Taller Academy | **Have it** | Continue structured learning. |
| Client policies on tools, codebases, and data leaving the environment | **Need to find out** | Request written clarification before working with any client data or repositories. |
| Available Academy certifications and eligibility | **Need to find out** | Ask the Academy contact for the current catalog and access process. |

**Status of requests:** Not yet reported as sent. No client access permissions or certification availability are assumed.

**Immediate free learning:** Use public vendor documentation and synthetic examples on evaluation datasets, structured outputs, prompt versioning, and fallback design. Do not move client data into the public demo.

## Exercise 3 — The 90-Day Plan

### One habit — weekly written update

**Habit:** Send an update with four sections: **Moved**, **Helped**, **Watching**, **Learned**.

**When:** Every **Friday at 16:00, Argentina time (America/Argentina/Cordoba)**.

**Starting:** **Friday, November 6, 2026**.

**Who sees it:** Technical Lead.

**Verification:** A sent weekly update, or a transparently logged missed update, for each scheduled week. The most valuable section is **Watching**, which flags risks while there is still time to act.

### One capability — evaluated AI ticket classifier

**Capability:** Build and deliver a standalone ticket-classification feature that makes a real LLM call, validates its response, evaluates accuracy, and handles errors safely.

**Target categories:** Feature; Bug; Investigation; Troubleshooting; Documentation; Other / Needs Review.

**Success criteria, independently checkable:**

1. A runnable TypeScript backend accepts a *synthetic* ticket description and calls an authorized language model.
2. The classification prompt is version-controlled.
3. A labeled evaluation set contains **at least 20** synthetic examples, including ambiguous and out-of-scope cases.
4. A repeatable evaluation command reports actual classification accuracy and representative failure cases (no invented pass rate).
5. Output is checked against an explicit schema/category whitelist.
6. Invalid responses, API timeouts, and provider failures produce a documented fallback or human-review path.
7. Another developer can run the demonstration and tests by following the README with their own authorized credentials.
8. The report distinguishes a local demonstration from any real production release.

**Deadline:** **January 30, 2027**.

**Blocked learning time:** Every **Tuesday, 09:00–11:00**, Argentina time, starting **November 3, 2026**. Calendar booking **pending**.

### One artifact — reusable public demonstration

**Artifact:** A public repository containing the classifier, prompt, >=20-case evaluation dataset, evaluation command, tests, known failure cases, and setup/usage documentation.

**Planned location:** `taller-academy-ai-ticket-classifier` (repository to be created as a future deliverable; not represented as already published).

**Completion test:** An external engineer can follow the instructions, run the program with synthetic input, and reproduce measured evaluation results.

## Milestones and evidence

| Date | Goal | Evidence to produce |
| --- | --- | --- |
| **December 1, 2026 — Day 30** | Define categories; run an initial model-call prototype; write >=20 labeled synthetic examples. | Prototype commit and evaluation cases. |
| **December 31, 2026 — Day 60** | Add structured output validation, repeatable evaluation, timeout/error behavior, and fallback. | Automated tests and measured interim evaluation. |
| **January 30, 2027 — Day 90** | Finalize documentation, demonstrations, and report. | Public repository and actual evaluation results. |

### Monthly 15-minute reviews

**Cadence:** First Monday of each month.

1. **November 2, 2026:** Kickoff and baseline.
2. **December 7, 2026:** First progress review.
3. **January 4, 2027:** Second progress review.

**At each review:** Is the weekly habit happening? Is the classifier on track? Which evidence exists? What is blocked? What can be *cut* while preserving a usable, evaluated deliverable?

**Calendar status:** These are *planned* dates; the recurring Tuesday block and the three reviews have **not** been confirmed as added to a calendar.

### When the plan slips

A missed block during an unusually demanding week means resume at the next planned block. Consistently missed blocks mean the plan is too large: **reduce scope rather than stacking rescheduled sessions**. Protect the six-minute weekly update. Minimum viable scope is a working model call, a documented evaluation set and measured results, and a tested failure fallback.

## Accountability — three lines to send

Recipient: **Technical Lead** (or Taller point of contact).

> **Habit:** Every Friday at 16:00 I will send a short written update covering outcomes, collaboration, risks, and learning.  
> **Capability:** By January 30, 2027, I will build and evaluate a safe AI-powered ticket classifier using >=20 labeled synthetic cases and a documented fallback.  
> **Artifact:** I will publish a reusable demo repository containing source code, versioned prompts, evaluation scripts, tests, and measured results.

**Message status:** Prepared, **not sent**.  
**Acknowledgment:** Pending. No one else is represented as already informed.

## Self-check

- [x] Completed all 15 baseline ratings.
- [x] Identified a concrete blocking gap and a high-performing skill.
- [x] Recorded access status and outstanding dependencies.
- [x] Defined exactly one ongoing habit, one capability, and one artifact.
- [x] Chosen specific dates, weekly practice time, and three monthly checkpoint dates.
- [x] Made completion criteria observable by someone else.
- [x] Drafted the three-line accountability message.
- [ ] Confirmed client AI/data policy and certification options.
- [ ] Added Tuesday recurring blocks to the calendar.
- [ ] Added the three monthly review events to the calendar.
- [ ] Sent the commitments and recorded the recipient's acknowledgment.
- [ ] Completed and measured the classifier.

## Final reflection

The earlier modules helped me make technical work legible, explain its effects in business terms, handle ambiguity, and review AI-assisted changes critically. Over the next 90 days, I will preserve the communication habit while closing a specific gap: moving from *building with AI* to *building and evaluating an AI-enabled feature*.

This document is a **plan with explicit pending steps**, not a report of future work already accomplished. It includes no proprietary client material.
