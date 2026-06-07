---
name: agency-client-report
description: >
  Generate professional weekly client performance reports for marketing agencies.
  TRIGGER: client weekly report, agency report, marketing report, performance report,
  client update, weekly client summary, generate client report, client data analysis,
  marketing KPI report, campaign performance report.
  DO NOT trigger for: internal team reports, financial statements, personal analytics,
  academic research papers, investor reports, pitch decks.
---

# Agency Weekly Client Report Engine · V2

> Deep Service Edition
>
> Not a dashboard. A **story your client believes in.**
>
> The goal: agency owner opens this report, screenshots it, sends to client.
> Client reads it and thinks: "They know what they're doing. Money well spent."

## Service Philosophy

Agency owners don't need another data dashboard. They need three things:

1. **Conviction.** "This week was good / bad / mixed — and HERE'S WHY." Not just numbers, interpretation.
2. **Language.** "Here's exactly how to explain this to your client." They should be able to copy-paste key sentences directly into WeChat.
3. **Forward motion.** "Here's what we recommend doing next — and WHY it makes sense." So the client sees progress week over week, not just reports.

A great weekly report doesn't report on the past. It **builds confidence for the future.**

## What Makes V2 Different

| V1 (Dashboard) | V2 (Client Story) |
|:---|:---|
| Reports what changed | **Explains WHY it changed** |
| Lists recommendations | **Shows the STRATEGY behind each rec** |
| Generic tone | **Ready to screenshot and send to client** |
| No context | **Every section answers "what does this mean for YOUR business"** |
| Retrospective only | **Forward-looking: "One thing we're watching next week"** |

## Execution Workflow

### Phase 1: Data Intake
1. Ask the user to provide data. Options:
   - Upload CSV exports (GA, Meta Ads, Google Ads, CRM)
   - Paste raw metrics
   - Connect via file path to a data folder
2. **NEW**: Before analyzing, ask:
   - "What's the client's #1 goal right now? (e.g., more leads, lower CPA, brand awareness)"
   - "Any context I should know? (launched new creative, holiday week, competitor move, etc.)"
   - "What's their business? (helps me connect numbers to their reality)"
3. Confirm: "Working with [Client Name]'s data for [Date Range]. Their #1 goal is [Goal]. Correct?"

### Phase 2: Core Analysis
For each data source, extract and analyze:

**Paid Advertising** (Google Ads / Meta Ads):
- Impressions, Clicks, CTR, Cost, Conversions, CPA, ROAS
- Week-over-week and month-over-month change (calculate automatically)
- **NEW**: Compare against client's stated goal. Is ROAS moving toward or away from target?

**Organic/Website** (Google Analytics):
- Sessions, Users, Page Views, Avg Session Duration, Bounce Rate
- Traffic sources breakdown
- Top landing pages

**CRM / Leads**:
- New leads this week, qualified leads, conversion rate
- Lead-to-opportunity pipeline movement
- **NEW**: Sales velocity — are leads moving faster or slower through the pipeline?

### Phase 3: Narrative Generation (The Deep Service Step)

This is THE critical step. Don't just list changes. Build a story.

For each significant change (>20%):
1. **What changed** — the number
2. **Why it changed** — analysis based on data patterns + user-provided context
3. **What it means for THEIR business** — connect to client's real-world outcome
4. **What we're doing about it** — demonstrate agency proactivity

For the overall narrative:
- If it's a good week: "Here's what worked, here's why, here's how we scale it."
- If it's a bad week: "Here's what happened, here's why (no excuses), here's exactly what we're doing."
- If it's mixed: "Here's the signal in the noise."

### Phase 4: Format & Deliver

Output in this exact structure:

---

# [Client Name] · Weekly Report
**Period**: [Mon DD – Sun DD, YYYY]

---

## 📍 The Story This Week
*A 2-sentence summary your client actually wants to read.
Copy-paste ready. Send this to WeChat.*

[2 sentences. First sentence = the big picture. Second sentence = what we're doing next. No jargon. No numbers unless it's THE key number.]

---

## 📊 At a Glance

| Metric | This Week | Last Week | ±% | Signal |
|:---|---:|---:|---:|:---:|
| Spend | $X,XXX | $X,XXX | +X% | |
| Conversions | XXX | XXX | ±X% | |
| CPA | $XX.XX | $XX.XX | ±X% | |
| ROAS | X.Xx | X.Xx | ±X% | |

*Signal legend: 🟢 Good trend | 🟡 Watch | 🔴 Needs attention*

---

## 🏆 What Worked
*The wins. Show the client you're paying attention.*

**1. [Win Title]**
- What happened: [Specific data point]
- Why it worked: [1-sentence analysis — show your expertise]
- Next step: [What we're doing to build on this]

**2. [Win Title]**
- Same structure

---

## ⚠️ What We're Watching
*Not "problems." Things we noticed and are acting on.*

**1. [Concern]**
- What's happening: [Data + trend]
- Why it matters: [What it means for THEIR business goal]
- Our plan: [Concrete action — show you're on it]

---

## 🎯 This Week's Moves
*Not a generic to-do list. Strategy, then action.*

| Move | Why | Expected Result |
|:---|:---|:---|
| [Specific action] | [Strategic reason tied to data] | [Measurable expectation] |
| [Specific action] | [Strategic reason] | [Measurable expectation] |
| [Specific action] | [Strategic reason] | [Measurable expectation] |

---

## 🔮 One Thing To Watch Next Week
*Forward-looking. Shows you're thinking ahead.*

[One trend, event, or test result we're tracking. Ties back to their #1 goal.]

---

## 📎 Supporting Data
[Optional: Raw data tables, charts, screenshots. Only include if asked.]

---

## Execution Rules

### The "Screenshot Test"
Every report must pass this test: Can the agency owner screenshot it and send it to the client on WeChat with ZERO edits? If any section needs explaining or reformatting, it fails.

### Writing Rules
- **Client's language, not agency jargon.** Write "your customers are finding you through Instagram" not "Meta platform traffic share increased 12%."
- **Own the bad weeks.** If numbers are down, say "Here's what happened and here's exactly what we're doing." Never hide or spin.
- **Connect to their goal.** Every analysis should tie back to "and this matters for YOUR [goal] because..."
- **Numbers are evidence, not the story.** Lead with insight. Support with data. Not the other way around.

### Quality Standards

| Criterion | Great (V2) | OK (V1) | Bad |
|:---|:---|:---|:---|
| **Client-readiness** | Screenshot → send, zero edits | Needs minor cleanup | Needs full rewrite |
| **Narrative quality** | Clear story with cause-and-effect | Numbers with labels | Raw data dump |
| **Action ownership** | "We're doing X because Y" | "Recommend doing X" | "Consider X" |
| **Business connection** | Every insight ties to client's goal | Some tied to goal | Pure metric reporting |
| **Confidence transfer** | Client feels informed and reassured | Client sees data | Client is confused or worried |

### Edge Cases

- **First week (no baseline)**: Generate a "Starting Point" report. No comparisons yet. Focus on establishing baselines and setting expectations for what we'll track.
- **Holiday / seasonal week**: Always flag it. "⚠️ This week included [holiday] — expect a natural dip in [metric]. We'll compare against the same week last year for context."
- **All-red week**: Don't panic. Don't hide. Structure: 1) What happened (honest), 2) Root cause analysis (our best assessment), 3) Action plan (specific, in motion), 4) What we need from the client (if anything).
- **Multiple clients**: Each client gets their own report. Never mix. Each report should feel like it was written specifically for that client — because it was.
- **Client asks "why should I keep paying you?"**: The entire report structure is designed to answer this question BEFORE they ask it. Every section demonstrates value.

---

## The Difference

- **V1**: "Here's your data." → Client reads it. Meh.
- **V2**: "Here's what happened, why it matters for your business, and what we're doing next." → Client thinks "these people are worth every cent."

---

*This isn't a reporting tool. It's a client retention engine. Every report is a renewal conversation you don't have to have.*
