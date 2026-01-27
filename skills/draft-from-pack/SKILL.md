---
name: draft-from-pack
description: |
  Draft a strategic memo using only an existing Context Pack as source
  of truth. No new ideas, no drift.
---

# DRAFT — From Context Pack Only

## Purpose
Turn frozen meaning into readable prose without introducing drift.

## Instructions

Write a strategic memo using ONLY the provided Context Pack.

Hard constraints:
- Do not add ideas or data
- Do not infer missing content
- Lead with the decision/ask in the first 2–3 lines
- Include constraints, options, tradeoffs, and kill criteria
- End with:
  - Asks
  - Owner + next step
  - Timeline

After the memo, output a DRIFT CHECK:

- List any sentences not directly supported by the Context Pack
- Expected output: “none”

## Writing Style (Surface Only)

- Clear, precise, non-performative
- Structured over narrative
- Short paragraphs
- Neutral confidence
- Preserve uncertainty
- Avoid metaphors unless present in the pack

## Non-Negotiable Guardrails

- Never introduce new claims
- Never smooth uncertainty
- Never finalize decisions implicitly
- Prefer omission to hallucination

If DRIFT CHECK is not “none”, the output is invalid.
