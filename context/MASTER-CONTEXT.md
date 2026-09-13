# MASTER-CONTEXT.md — What This Business Is

This is the top-level context file for the AI Creative Studio. Every agent
(human or AI) should be able to read this one file and understand what the
business is, how it works, and what matters.

## What this is

The AI Creative Studio is an **owned AI creator / IP business**.

- The Studio owns and operates AI creator personas ("digital talent").
- AI creators are **IP assets** — they belong to the Studio, not to a client.
- Content is the **distribution mechanism** for those assets, not the product.
- Audience/attention is an **asset** the Studio builds and owns over time.
- **Monetisation is the objective** — not reach, not vanity metrics.

**This is NOT primarily a human creator agency.** The Studio is not in the
business of representing human influencers or managing client brand accounts
as its core model. Any such work is secondary and must be clearly labelled as
such if it exists.

## The core flywheel

```
AI Creator
   → Content
      → Distribution
         → Attention
            → Monetisation
               → Data
                  → Improvement
                     → Repeat
                        → Scale
```

Each AI creator is meant to run this loop. The loop only compounds if
monetisation is real — fabricated or assumed revenue breaks the flywheel's
usefulness as a signal.

## Operating model

| Role | Function |
|---|---|
| **Founder / Creative Director** | Final decision-maker. Owns creative direction and IP. Approves all credit-consuming generations. |
| **ChatGPT** | Strategic brain — business architecture, prioritisation, mission definition. |
| **Trello** | Mission control — roadmap, execution status, revenue scoreboard. |
| **Orca** | Execution/orchestration environment. |
| **Claude Code** | Primary builder/operator. |
| **Codex** | Secondary reviewer. |
| **Git repository (this repo)** | Persistent institutional memory and source of truth for Studio context. |
| **Higgsfield** | Primary AI creative production engine. |
| **Dreamina** | Secondary creative engine, used where a specific model/workflow is better suited. |

## Core principles

1. Revenue before infrastructure.
2. Prove one strong AI creator before creating multiple creators.
3. Do not build SaaS, portals, complex agent systems, unnecessary MCP
   infrastructure, licensing platforms, or elaborate analytics unless a proven
   bottleneck justifies them.
4. Protect Higgsfield credits.
5. Never fabricate revenue, customers, partnerships, or results.
6. Clearly distinguish speculative/portfolio work from real client work.
7. Persistent business decisions belong in the repository.
8. Agents must read project context before acting.
9. Agents must report meaningful changes.
10. Never spend credits, activate paid services, publish content, or contact
    third parties without the appropriate Founder approval.

## How the pieces fit together

- **Repository (`context/`)** is where truth lives between sessions: current
  state, business model, the Creator-001 framework, Higgsfield rules, and the
  decision log. Any agent picking up work should be able to reconstruct full
  context from these files alone.
- **Trello** is where day-to-day execution and the revenue scoreboard live —
  this repository is not a task tracker and should not duplicate Trello's job.
- **ChatGPT** sets strategy and priority; this repository records the
  decisions that result, so they don't need to be re-derived.
- **Claude Code / Codex** build and review inside this repository, strictly
  within the current objective and core principles.

## Where to look next

- Current status and next milestone: `context/CURRENT-STATE.md`
- How the Studio actually makes money: `context/BUSINESS-MODEL.md`
- The Creator-001 framework (not yet filled in): `context/CREATOR-SPEC.md`
- Rules for any Higgsfield generation: `context/HIGGSFIELD-RULES.md`
- Settled decisions, not to be re-litigated: `context/DECISIONS.md`
