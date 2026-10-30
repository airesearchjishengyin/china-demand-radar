# China Demand Radar

A Codex-friendly, on-demand workflow for researching customer needs in mainland China, exploring evidence-backed product ideas, and assessing commercial feasibility without treating model scores as proof.

## Install

```bash
npx skills add airesearchjishengyin/china-demand-radar --skill china-demand-radar --agent codex
```

The skill runs only when the user requests a specific investigation. It does not create scheduled jobs or contact people.

## Scope

- Prioritizes mainland Chinese users, Chinese-language sources, and locally relevant platforms.
- Separates mainland, Hong Kong/Macau/Taiwan, overseas, and unknown-region evidence.
- Keeps source URLs, dates, evidence status, alternatives, and counterevidence.
- Produces one concrete next validation action.
- Uses standard `SKILL.md` instructions and optional OpenAI UI metadata; no model API, framework-specific runtime, account, or paid dependency is required.

See [`SKILL.md`](skills/china-demand-radar/SKILL.md) and its [report/evidence format](skills/china-demand-radar/references/report-and-evidence.md).
