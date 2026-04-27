---
name: lex-legal-brief
description: "Brazilian legal drafting workflow: transform facts, documents, claims, and procedural posture into a structured legal brief or petition plan."
version: 0.1.0
author: Lex
license: MIT
metadata:
  hermes:
    tags: [legal, brazil, drafting, litigation, pje, documents]
    related_skills: [pje-bridge]
---

# Lex Legal Brief

Use this skill when the user asks for legal analysis, a petition/recurso plan,
argument mapping, document review, or a first draft strategy for a Brazilian
case.

## When to Use

Use this skill for:

- Petitions, appeals, defenses, motions, notices, and legal memos.
- Turning process facts/documents into arguments.
- Identifying missing facts, evidence, deadlines, or procedural risks.
- Preparing a drafting outline before generating a final document.
- Reviewing a legal document for weak points, contradictions, or missing
  requests.

## When Not to Use

Do not use this as the final authority for:

- Filing anything in PJe.
- Confirming legal deadlines without source data.
- Inventing jurisprudence, citations, facts, or process movements.
- Acting without lawyer review.

Use `pje-bridge` when the next step requires consulting, opening, downloading,
or filing in PJe through the Windows Lex app.

## Workflow

1. Identify the area of law, procedural stage, parties, court, and goal.
2. Extract facts, documents, deadlines, claims, defenses, evidence, and gaps.
3. Ask for missing critical facts if the request is under-specified.
4. Build an argument map:
   - thesis
   - legal basis to verify
   - evidence
   - likely counterargument
   - risk
5. Produce a drafting plan before writing a final piece.
6. Mark every unverified legal authority or deadline as needing verification.

## Output Shape

Prefer this structure:

```markdown
## Objective

## Case Snapshot

## Missing Information

## Argument Map

## Evidence Checklist

## Draft Structure

## Risks And Verification

## Next Action
```

For short requests, answer directly but keep the same safety rules.
