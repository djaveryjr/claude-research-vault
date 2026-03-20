# Research Vault

Personal research repository for Dave & Donna. Maintained with Claude Code.

## What This Is

A structured knowledge base for tracking research, comparing options, and logging decisions across home, baby, legal, work, and personal topics.

## How It Works

- One markdown file per research topic
- Each file tracks context, options, recommendation, decision, and a research log
- Connected to the Life Triage system (Claude.ai) via the `Life Triage Ref` field in each file
- Claude Code reads and writes files during research sessions

## File Status Types

| Status | Meaning |
|--------|---------|
| Active Research | Currently being researched |
| Decision Made | Research complete, decision logged |
| Backlog | Queued but not started |
| Abandoned | No longer pursuing — reason noted in file |

## Current Open Topics

| Topic | Priority | Owner |
|-------|----------|-------|
| Construction Defect Lawyers | Urgent | Dave |
| Bathroom Contractors | Urgent | Dave |
| Flooring Inspectors | Urgent | Dave |
| Baby Strollers | Medium | Both |
| Diaper Brands | Medium | Both |

## Usage

Open a Claude Code session and say:
- `"Research [topic]"` — start or continue research on a topic
- `"Update [filename]"` — add findings to an existing file
- `"Decision made on [topic]"` — log a final decision and close the topic
- `"What's the status of [topic]?"` — get a summary of current findings

## Connection to Life Triage

Research tasks originate in the Life Triage project (Claude.ai). When a decision is made here, the Research Log will note `Decision ready — update Life Triage: [reminder title]` as the signal to close the loop.
