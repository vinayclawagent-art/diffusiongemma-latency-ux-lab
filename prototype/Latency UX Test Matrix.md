# Latency UX Test Matrix

Source: [[DiffusionGemma as a Fast Local Inference Building Block]]

This is a fillable benchmark plan for testing when faster generation beats smarter generation in product UX. No model claims are validated until a real run attaches logs.

## Test setup

- Hardware/runtime:
- DiffusionGemma variant:
- Baseline autoregressive model:
- Quantization / serving stack:
- Prompt set location:

## Product tasks

| Task | Why latency matters | Input size | Output target | Quality bar | DiffusionGemma latency | Baseline latency | Winner | Notes |
|---|---|---:|---|---|---:|---:|---|---|
| Inline rewrite | User waits in editor | | crisp rewrite | preserves meaning | | | | |
| Markdown table repair | Agent fixes structured docs | | valid table | no row loss | | | | |
| JSON/schema repair | UI needs valid object fast | | valid JSON | no hallucinated fields | | | | |
| Code infill | Developer flow | | small patch | tests/lint still pass | | | | |
| Bulk summarization | Throughput | | bullets | factual enough | | | | |

## Decision rule

- **Use DiffusionGemma-style model** when latency improves the interaction and quality remains above the task bar.
- **Use stronger autoregressive model** when factual accuracy, reasoning, or code correctness dominates perceived speed.

## Product wedges to explore

- Instant markdown/doc repair for Obsidian or Git-backed docs.
- Local-first coding assistant for tiny structured patches.
- Fast pre-pass model that drafts candidates before a stronger verifier.
