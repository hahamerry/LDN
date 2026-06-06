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

# Agency Weekly Client Report Engine

Automatically transforms raw marketing data into polished, client-ready weekly reports.
Designed for marketing agencies, freelancers, and consultants who spend 5-10 hours
per week per client manually pulling data and writing reports.

## What Makes This Different

Unlike existing tools that just "fill a template with numbers":

- **Multi-source data pull**: Reads from Google Analytics, Meta Ads, Google Ads, CRM exports
- **AI-driven narrative**: Understands data trends and writes insightful commentary
- **Client-ready output**: Formatted, branded, directly deliverable — no cleanup needed
- **Bilingual**: Output in English or Chinese based on client preference

## Execution Workflow

### Phase 1: Data Intake
1. Ask the user to provide data. Options:
   - Upload CSV exports (GA, Meta, Google Ads, CRM)
   - Paste raw metrics
   - Connect via file path to a data folder
2. Confirm: "Working with [Client Name]'s data for [Date Range]. Correct?"
3. If no data provided, ask: "What platform exports do you have? (GA / Meta / Google Ads / Other)"

### Phase 2: Core Analysis
For each data source, extract and analyze:

**Paid Advertising** (Google Ads / Meta Ads):
- Impressions, Clicks, CTR, Cost, Conversions, CPA, ROAS
- Week-over-week change (calculate automatically)
- Flag: anything with >20% change as "significant movement"

**Organic/Website** (Google Analytics):
- Sessions, Users, Page Views, Avg Session Duration, Bounce Rate
- Traffic sources breakdown
- Top landing pages

**CRM / Leads**:
- New leads this week, qualified leads, conversion rate
- Lead-to-opportunity pipeline movement

### Phase 3: Insight Generation
Based on the numbers, generate:

1. **Top 3 Wins**: Highest positive changes with specific numbers
   - Example: "Meta Ads ROAS jumped 34% to 3.8x after the new creative launch"

2. **Top 2 Concerns**: Largest negative changes with context
   - Example: "Google Ads CPA rose 22% to $47 — competitive pressure in [keyword group]"

3. **3 Actionable Recommendations**: Specific, doable this week
   - Example: "Increase Meta budget by 15% on the winning ad set ([ID: xyz]) — current ROAS supports scaling"

### Phase 4: Format & Deliver
Output the report in this exact structure:

---

# Weekly Performance Report: [Client Name]
**Period**: [Mon DD – Sun DD, YYYY] | **Prepared**: [Date]

## 📊 Executive Summary
[3 sentences max — the single most important thing the client needs to know this week]

## 📈 Key Metrics at a Glance

| Metric | This Week | Last Week | Change |
|:---|---:|---:|---:|
| Spend | $X,XXX | $X,XXX | +X% |
| Impressions | XXX,XXX | XXX,XXX | ±X% |
| Clicks | X,XXX | X,XXX | ±X% |
| Conversions | XXX | XXX | ±X% |
| CPA | $XX | $XX | ±X% |
| ROAS | X.Xx | X.Xx | ±X% |

## 🏆 Top 3 Wins
1. **[Win Title]** — [Specific data + why it matters]
2. **[Win Title]** — [Specific data + why it matters]
3. **[Win Title]** — [Specific data + why it matters]

## ⚠️ Areas to Watch
1. **[Concern]** — [Data + context + severity]
2. **[Concern]** — [Data + context + severity]

## 🎯 Recommendations for Next Week
1. **[Action]** — [Why + expected impact]
2. **[Action]** — [Why + expected impact]
3. **[Action]** — [Why + expected impact]

## 📝 Notes
[Optional: upcoming changes, tests running, external factors affecting performance]

---

## Execution Rules

- **Numbers only, no fluff**: Every claim backed by data. No "good performance" without the number.
- **Missing data**: Mark "Data unavailable" — never estimate or make up numbers.
- **Change threshold**: Flag changes >20% as significant. Changes 5-20% as notable. <5% as stable.
- **Tone**: Professional, direct, actionable. Think "consultant advising a client", not "reporting to boss".
- **Word count**: 350-600 words.

## Quality Standards

| Criterion | Good | Bad |
|:---|:---|:---|
| Data accuracy | All numbers from source data | Rounded or estimated numbers |
| Insight quality | Specific, contextual, actionable | "CTR went up" without explanation |
| Recommendation value | Concrete, doable this week | "Improve performance" |
| Client readiness | Deliverable without edits | Needs reformatting or cleanup |
| Time saved | User saves 1-3 hours per client | User still needs to rewrite |

## Edge Cases

- **Multiple clients**: Generate separate reports. Don't mix data.
- **First week (no comparison data)**: Generate baseline report without change columns. Note "Baseline — comparison available next week."
- **Holiday/seasonal anomaly**: Flag with "⚠️ Note: [Holiday/Event] may have affected this week's numbers."
- **Disaster week (all red)**: Be honest but constructive. Focus on "what we're doing about it."
- **Empty data source**: Skip that section, note "No [Platform] data available for this period."

---

*Stop spending Sunday nights writing reports. Let the AI handle the numbers while you focus on strategy.*
