# vittori-newsletter

The complete AI context repository for The Vittori Letter — a weekly dispatch from the frontier of how extraordinary things are made.

**Private. Confidential. Feed to AI before every edition.**

---

## What This Repo Is

This is not a content archive. This is the AI's brain.

Every time the Finalization Agent writes a newsletter, it loads this repository first. The brand documents here are permanent context — the difference between an AI that writes like a $2.5M hypercar brand and one that accidentally sounds like a garage project.

---

## Structure

```
vittori-newsletter/
├── brand/
│   ├── brand-bible.md          ← LOAD FIRST. Every word written under the Vittori name.
│   ├── content-framework.md    ← Strategic positioning. Edition 02 vs 03 diagnosis.
│   ├── content-pipeline.md     ← Six-stage workflow. 80+ sources. Transformation examples.
│   └── voice-and-emotion.md    ← What the newsletter needs to DO. 6 emotions. Raw openings.
├── prompts/
│   ├── finalization-agent-prompt.md  ← Master prompt for the writing AI (v3.0)
│   └── research-agent-prompt.md     ← Prompt for the research/scoring AI
├── templates/
│   └── newsletter-template.html     ← HTML email template
├── editions/
│   ├── edition-01/
│   ├── edition-02/             ← The anti-template. Wrong framing.
│   └── edition-03/             ← The benchmark. Enzo/crankshaft. Get here every time.
└── README.md
```

---

## The One Rule

Edition 03 is the benchmark. Every edition is measured against it.

Edition 02 is the anti-template. If the draft sounds like Edition 02, reframe it.

The difference: Edition 02 says "the tools are cheap, anyone can do this." Edition 03 says "AI is powerful but not sufficient — only 7 people alive can do this." Same themes. Opposite messages.

---

## Quick Reference

**The Reframe Rule:** Every story moves from "what anyone CAN do" → to "what only the extraordinary CHOOSE to do with it." Always write from step 3, never step 1.

**The One Test:** Would someone who will never buy a $2.5M car still forward this to a friend?

**The Benchmark Sentence:** *"The tools are universal. The judgment of what to do with them is not."*

**Banned forever:** affordable, accessible, cheap, budget, supercar, customers, factory, content, democratise, iterate, MVP, lean, pivot, cutting-edge, groundbreaking, revolutionary, exciting, amazing, incredible

**Use instead:** hypercar, patrons, collectors, atelier, workshop, master, mastery, craft, artisan, precision, judgment, irreplaceable, convergence, frontier, commission, allocation, heritage, lineage

---

## For the AI (Make.com Integration)

When the Finalization Agent is triggered:

1. Fetch `brand/brand-bible.md` from this repo via GitHub API
2. Load as system prompt context
3. Receive team brief (research data + editorial angle + voice memo)
4. Draft using `prompts/finalization-agent-prompt.md`
5. Run pre-publication checklist before returning output

The brand bible is permanent. The team brief changes every week. The voice never does.

---

*Version 1.0 — March 2026*
*This repository is alive. Update it when the brand evolves.*
