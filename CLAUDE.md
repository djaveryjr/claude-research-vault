# Research Vault — CLAUDE.md

## WHAT THIS REPO IS

This is a personal research repository maintained by Claude Code. It stores structured research, comparisons, and decisions across all areas of life — home, baby, legal, work, and personal.

It operates alongside the Life Triage system (Claude.ai project) which manages tasks and priorities. When Life Triage surfaces a research task, the findings live here.

---

## HOW THIS REPO WORKS

- One .md file per research topic
- Flat structure for now — organize into folders later as volume grows
- Every file is self-contained — context, findings, comparisons, and decision status all in one place
- Files are linked back to Life Triage via reminder title or triage date

---

## FILE NAMING CONVENTION

Use lowercase, hyphenated names:
- `baby-strollers.md`
- `construction-defect-lawyers.md`
- `diaper-brands.md`
- `bathroom-contractors.md`

---

## FILE TEMPLATE

Every research file follows this structure:

```md
# [Topic Title]

## Meta
- Created: [YYYY-MM-DD]
- Last Updated: [YYYY-MM-DD]
- Status: [Active Research | Decision Made | Backlog | Abandoned]
- Life Triage Ref: [Reminder title or triage date that spawned this]
- Owner: [Dave | Donna | Both]
- Priority: [urgent | high | medium | low]

## Context
[Why are we researching this? What problem does it solve?
Any constraints — budget, timeline, requirements.]

## Options Considered

### Option 1 — [Name]
- Price:
- Pros:
- Cons:
- Links:
- Notes:

### Option 2 — [Name]
- Price:
- Pros:
- Cons:
- Links:
- Notes:

## Recommendation
[Claude's recommendation based on research, or "Pending" if still gathering data]

## Decision
- Decision Made: [YYYY-MM-DD or "Pending"]
- Choice: [What was decided]
- Rationale: [Why]
- Next Action: [What happens now — order it, book it, etc.]

## Research Log
- [YYYY-MM-DD]: [What was found or done]
```

---

## CLAUDE CODE BEHAVIOR

When starting a session:
1. Ask what topic to research or which file to update
2. If new topic — create a new .md file using the template above
3. If existing topic — read the file first, then update with new findings
4. Always update "Last Updated" and "Research Log" on every session
5. When a decision is made — update Status to "Decision Made" and fill in the Decision section
6. Commit changes with a descriptive message after every session

When researching:
- Use web search to find current options, prices, and reviews
- Summarize findings objectively — pros and cons, not just positives
- Flag budget concerns or timeline risks explicitly
- Cross-reference Life Triage context where relevant

---

## LIFE TRIAGE INTEGRATION

- Every file includes a `Life Triage Ref` field linking back to the originating reminder title or triage session date
- When a decision is made, note in the Research Log: `Decision ready — update Life Triage: [reminder title]`
- Communication between projects is human-in-the-loop — Dave carries context between sessions
- Do not duplicate task management here — this repo is for research and decisions only, not action items

---

## CURRENT OPEN RESEARCH TOPICS

| File | Status | Priority | Owner | Life Triage Ref |
|------|--------|----------|-------|-----------------|
| construction-defect-lawyers.md | Active Research | urgent | Dave | Research Lawyers for House Dispute |
| bathroom-contractors.md | Active Research | urgent | Dave | Research Contractors for Bathroom Issues |
| flooring-inspectors.md | Active Research | urgent | Dave | Research Flooring Inspectors |
| water-damage-abatement.md | Active Research | urgent | Dave | Research Flooring Inspectors (water damage component) |
| baby-strollers.md | Active Research | medium | Both | Research Baby Strollers |
| diaper-brands.md | Active Research | medium | Both | Diaper Research |

---

## REPO CONVENTIONS

- Always use the file template — no freeform files
- Never delete files — mark Status as "Abandoned" with a reason if dropping a topic
- Keep the Open Research Topics table in this CLAUDE.md current
- One topic per file — no combining unrelated research
- Donna's input or preferences should be noted explicitly in relevant sections
