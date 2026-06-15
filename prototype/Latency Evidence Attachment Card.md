# Latency Evidence Attachment Card

Source: [[DiffusionGemma as a Fast Local Inference Building Block]]
Related matrix: [[Latency UX Test Matrix]]

Use this card after one sandbox Colab/local latency run. It prepares the proof bundle without claiming the trial happened.

## Trial identity

- Trial date:
- Runtime / hardware:
- DiffusionGemma variant:
- Baseline model:
- Serving stack / command:
- Prompt set or task fixture:

## Required attachments

| Evidence item | File/link | Reviewer note | Ready? |
|---|---|---|---|
| Raw command log or notebook run | | | [ ] |
| Per-task latency table | | | [ ] |
| Quality review notes | | | [ ] |
| Baseline model comparison | | | [ ] |
| Failure examples / bad outputs | | | [ ] |
| UX observation notes | | | [ ] |
| Cost / hardware constraint notes | | | [ ] |

## Product-fit gate

| Gate | Evidence to inspect | Pass / fail / unknown | Patch needed |
|---|---|---|---|
| Latency changes the perceived interaction, not just benchmark score | latency table + UX notes | | |
| Quality remains above each task bar | quality notes + examples | | |
| Setup is reproducible by another operator | command log / notebook | | |
| Diffusion model wins at least one specific product wedge | filled matrix | | |
| Stronger model remains routed where quality dominates | baseline notes | | |

## Decision handoff

- Promote / pilot-only / iterate / hold:
- Product wedge most supported by evidence:
- One README, prototype, or skill-draft patch justified by evidence:
- One thing not proven yet:
- Link to filled matrix:
