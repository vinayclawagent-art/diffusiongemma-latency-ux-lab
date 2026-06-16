# Post-Trial Promotion Decision Card — DiffusionGemma Latency UX Lab

Status: template-ready, evidence pending.

Use this after one real sandbox Colab/local run. Do not choose an outcome until the latency matrix and evidence attachment card contain real logs, quality notes, and comparison artifacts.

## Required evidence links

- Filled test matrix: [[Latency UX Test Matrix]]
- Proof bundle: [[Latency Evidence Attachment Card]]
- Trial date:
- Hardware / runtime:
- Model/checkpoint/config:
- Raw command log or notebook run:
- Per-task latency table:
- Quality review notes:
- Baseline comparison:
- UX observation notes:

## Promotion gates

| Gate | Evidence to inspect | Pass / fail / unknown | Notes |
|---|---|---|---|
| Interaction latency | The perceived edit/repair loop is meaningfully faster than the baseline for at least one real workflow. |  |  |
| Output usefulness | Speed does not erase enough quality that a stronger/slower model would be better. |  |  |
| Repeatability | Commands, inputs, and hardware/runtime are clear enough for a second run. |  |  |
| Failure visibility | Bad generations, stalls, or quality regressions are captured rather than hidden. |  |  |
| Product fit | The result maps to a specific UX surface such as instant rewrite, structured repair, or local assistant draft. |  |  |
| Cost/hardware fit | The run is plausible for VinClawLabs constraints, not only a lab demo. |  |  |

## Decision

Choose one after the evidence is attached:

- [ ] **Promote** — turn the latency lab into a reusable local-model UX benchmark workflow.
- [ ] **Pilot-only** — keep it for one constrained low-latency interaction surface.
- [ ] **Iterate** — adjust tasks, baselines, prompts, or measurement method and rerun.
- [ ] **Hold** — latency is interesting, but quality/product-fit proof is not strong enough.

## Patch queue if promoted or iterated

- README change needed:
- Prototype matrix change needed:
- Skill draft or script change needed:
- Next real workflow to test:

## Decision log

- 2026-06-15: Card created for the next sandbox run; prepared, not validated.
