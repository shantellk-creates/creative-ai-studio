# HIGGSFIELD-RULES.md — Credit Protection Protocol

Higgsfield is the Studio's primary AI creative production engine. Higgsfield
credits are a **scarce, protected resource** and must never be spent casually.
Dreamina is the secondary creative engine, used only where a specific
model/workflow is demonstrably better suited — the same approval discipline
below applies to Dreamina generations too.

## Status as of foundation build (13 September 2026)

- **Higgsfield has NOT been activated.** No trial started, no subscription
  activated, no credits spent, no generations produced.
- This document defines the protocol for the future, controlled point at
  which generation begins — it does not authorise anything itself.

## The rule

**Before any credit-consuming generation, the operating agent must state all
of the following and obtain explicit Founder/Creative Director approval:**

1. **Purpose** — why this generation is needed, tied to a specific goal
   (e.g. a specific content piece for Creator-001, in service of the
   September revenue objective).
2. **Model** — which Higgsfield (or Dreamina) model/workflow will be used.
3. **Output** — what the expected output is (format, quantity, e.g. "1 image,
   9:16, character-consistent portrait").
4. **Expected credit cost** — the best available estimate of credits/cost for
   this generation.
5. **Justification** — why this generation is worth that cost right now, as
   opposed to waiting or not generating at all.

Only after the Founder/Creative Director has reviewed these five points and
given explicit approval may the generation proceed.

## What is never allowed without this process

- Activating the Higgsfield trial or any paid tier.
- Running any generation "to see what happens" or speculatively.
- Batch-generating multiple variations without approval of the batch as a
  whole (each batch needs its own purpose/model/output/cost/justification —
  not per-image approval, but explicit approval of the batch's scope).
- Treating a prior approval as a standing approval for future generations of
  a different purpose, model, or output.

## Recording approvals

When a generation is approved and run, record what happened as a decision or
state update:
- If it's a one-off operational approval, note it in
  `context/CURRENT-STATE.md` (Higgsfield status) when status changes.
- If it establishes a standing rule (e.g. "always use model X for Creator-001
  portraits"), record it in `context/DECISIONS.md` so it doesn't need to be
  re-approved every time.

## Explicit instruction for this foundation task

Per the Founder's instruction when this repository foundation was created:
**do not activate the Higgsfield trial or generate anything as part of
building this foundation.** This file exists to govern *future* generation
activity only.
