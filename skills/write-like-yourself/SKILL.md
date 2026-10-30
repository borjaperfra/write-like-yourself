---
name: write-like-yourself
description: Build a personal writing voice guide from the user's original writing and explicit edits; or use an existing VOICE.md to draft, edit, or review writing while preserving personal voice. Use when asked to identify writing style, build a voice guide, write in the author's established style, or revise text without making it sound artificial.
license: MIT
metadata:
  version: "1.2"
---

# Write like yourself

This is an **editorial workflow**, not a generic text-polisher. First determine the task.

## 1. Decide the mode

- **BUILD:** The user wants to discover/document their voice. Read [editorial-method.md](references/editorial-method.md) and create a draft `VOICE.md`.
- **WRITE:** The user wants a new piece in *their own* established voice. Read their `VOICE.md` if available, and the task brief; write using grounded facts.
- **EDIT:** The user gives a draft and asks for a rewrite. Apply **minimal, justified changes**; preserve structure, stance, characteristic phrasing and all factual constraints.
- **REVIEW:** The user wants critique, not a rewrite. Give concrete findings with examples and optional edits; do not replace the entire text.
- **EVALUATE:** The user requests comparison/testing. Read [evaluation.md](references/evaluation.md). Clearly distinguish illustrative examples from independently generated, blind comparisons.

## 2. Find the voice guide

Look for a user-supplied `VOICE.md` or equivalent in the working context. If absent:
- For BUILD, make one from evidence supplied by the user, following the method.
- For other modes, use the author's actual draft as the main anchor and **do not silently adopt** the public Borja example as the user's voice.
- If the only available examples are very limited, work conservatively and label any inferred preferences as tentative.

Never claim access to earlier conversations, personal files or approvals you cannot verify. Never fabricate source excerpts.

## 3. Editorial invariants

1. **Author and audience first:** determine who signs, who reads, medium and purpose.
2. **Preserve what works.** Do not edit just to demonstrate activity.
3. **Decisions over tics:** learn why the author deleted a phrase, not a phrase to repeat.
4. **Specificity:** prefer concrete facts, actions, consequences over abstractions.
5. **Rhythm:** vary sentences and paragraphs naturally; do not mechanically alternate lengths.
6. **Humor:** preserve humor that comes from the situation; do not add jokes as proof of personality.
7. **No inventions:** do not add fabricated experiences, claims, citations, numbers or approvals.
8. **Uncertainty stays visible:** mark missing facts; do not convert hypotheses into certainty.
9. **Source discipline:** separate author-written samples, explicit feedback, coedited comparisons and AI-proposed edits.
10. **Do not copy someone else:** public example `examples/borja/` is only a demonstration.

## 4. Output by mode

- BUILD: `VOICE.md` draft, evidence-linked editorial decisions, unclear rules for author validation.
- WRITE: complete draft; note only material assumptions or missing facts.
- EDIT: revised draft with original sections preserved unless asked otherwise; optionally a brief change summary.
- REVIEW: highest-impact observations with specific suggested changes.
- EVALUATE: comparison plus the procedure, limitations and what was *actually* tested.

## 5. Optional background material

- [Editorial method](references/editorial-method.md)
- [Evaluation rules](references/evaluation.md)

No scripts, network access, fine-tuning or vendor-specific APIs are required. Skill discovery/install behavior depends on the host agent.
