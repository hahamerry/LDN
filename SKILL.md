---
name: sales-call-research
description: >
  Cold call preparation research assistant for sales professionals.
  TRIGGER: prepare for sales call, research this company, sales research,
  prospect research, pre-call research, company briefing, lead research,
  prepare for demo, client background check.
  DO NOT trigger for: general company search (use web search instead),
  job interview research, investor research, competitor analysis for
  internal strategy (use competitor-analysis skill instead).
---

# Sales Call Research Assistant

Generates a comprehensive pre-call briefing in under 2 minutes.
Designed for B2B sales professionals, SDRs, and account executives
who spend 15-30 minutes manually researching every prospect.

## When to Use This Skill

The user is about to call, email, or demo a company and needs:
- Quick understanding of what the company does
- Recent news that matters for the conversation
- Decision-maker background and talking points
- Personalized opening hooks

## Execution Workflow

### Phase 1: Gather Input
1. Ask the user for the company name and website URL.
2. If the user only provides a name, infer the website.
3. Confirm: "Researching [Company Name] — is this correct?"

### Phase 2: Research (run in parallel)
Execute these searches simultaneously:

**Company Background:**
- "company name" industry products services overview
- "company name" funding series revenue employees

**Recent News:**
- "company name" news announcement 2026
- "company name" product launch partnership

**Decision Maker:**
- "company name" CEO CTO VP sales linkedin

**Pain Points:**
- "company name" challenges competitors market

### Phase 3: Analyze & Structure
From the research results, extract and organize:

1. **Company Snapshot** (3-4 lines)
   - What they do, size, funding stage, key products

2. **Recent Developments** (2-3 items)
   - News from the last 6 months that creates conversation hooks

3. **Decision Maker Intel** (2-3 items)
   - Key person, background, potential talking points

4. **Pain Point Hypotheses** (2-3 items)
   - Likely challenges based on industry and size

5. **Opening Hook** (1-2 sentences)
   - Personalized icebreaker based on recent news or shared connection

### Phase 4: Format & Deliver
Output the briefing in this exact structure:

---

# Pre-Call Briefing: [Company Name]

## 📋 Company Snapshot
[3-4 concise lines about what they do, size, and key facts]

## 📰 Recent News (conversation hooks)
1. [News item + how to reference it naturally]
2. [News item + how to reference it naturally]

## 👤 Decision Maker
- **Name/Title**: [if found]
- **Background**: [relevant experience]
- **Talk to them about**: [personalized angle]

## 🎯 Likely Pain Points
1. [Pain point] — [why relevant]
2. [Pain point] — [why relevant]

## 💬 Opening Hook
[1-2 sentence personalized icebreaker for the call/email]

## ⚡ Quick Stats
- Industry: [sector]
- Size: [employees, if known]
- Funding: [if applicable]

---

## Execution Rules

- **Always cite sources**: Include URLs for all factual claims.
- **Be honest about gaps**: If information is not found, say "Not publicly available" — never invent.
- **Prioritize recency**: News older than 12 months is less valuable; flag it as "Older news".
- **Tone**: Professional but conversational. This is for a sales call, not an academic paper.
- **Time target**: Research should complete in under 120 seconds.

## Quality Standards

| Criterion | Good | Bad |
|:---|:---|:---|
| Accuracy | All claims sourced | Made-up statistics |
| Relevance | Hooks tied to recent news | Generic "grow revenue" pitches |
| Actionability | User can immediately use the hook | Vague observations |
| Completeness | All 5 sections filled | Missing key sections |
| Conciseness | 300-500 words total | Long-winded history lessons |

## Edge Cases

- **Startup / Little Info**: Focus on founder background + industry trends. Flag "limited public information".
- **Enterprise / Too Much Info**: Prioritize most recent quarter and most relevant division.
- **Non-English Company**: Research in original language, output briefing in English.
- **Wrong Company**: If user corrects, restart from Phase 1.
- **Website Blocked**: Use cached versions or alternative sources.

---

*This skill transforms what used to take 20 minutes of Googling into a 2-minute automated briefing. Your prospects will notice the difference.*
