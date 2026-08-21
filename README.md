# WW Run 2 Leptonic PPS — Analysis Status

Public, high-level progress dashboard for a Run 2 leptonic diboson analysis with forward proton tagging.

**Public dashboard:** https://jgomespi.github.io/WWRun2LeptonicPPS-Analysis-Status/  
**Current phase:** 2018 blinded statistical-model validation.  
**Milestone progress:** 3 of 7 major phases complete; phase 4 is active.  
**Last updated:** 21 August 2026.

## Public scope

This repository is intentionally limited to project-management information. It does **not** publish analysis code, storage paths, event counts, yields, selection thresholds, fitted numerical results, limits, coupling values, dataset inventories, internal review material, or other unpublished analysis details.

The public dashboard is designed to answer one question: **where is the analysis in the workflow?**

## Milestones

| Phase | Status | High-level deliverable |
|---|---|---|
| 1. Scalable workflow and reproducibility | ✅ Complete | Partitioned processing, provenance, bounded-memory execution |
| 2. 2018 nominal analysis and validation | ✅ Complete | Nominal reconstruction, control-region validation, blinded signal-region handling |
| 3. 2018 kinematic reconstruction | ✅ Complete | Signal-region kinematic reconstruction and completeness audit closed |
| 4. 2018 blinded statistical model | 🔵 In progress | Derived-production closure, templates, datacards, workspaces and expected-only inference are operational; model-consistency audits remain active |
| 5. Full systematic closure | ⏳ Planned | Validate detector, reconstruction, migration and normalization uncertainties |
| 6. Full Run 2 combination | ⏳ Planned | Extend to all Run 2 periods and audit inter-year correlations |
| 7. Final review and observed result | 🔒 Gated | Freeze the analysis, complete review, then proceed to approved unblinding |

## Workflow

```mermaid
flowchart LR
    A[Workflow redesign\nComplete] --> B[2018 nominal validation\nComplete]
    B --> C[2018 kinematic reconstruction\nComplete]
    C --> D[2018 blinded statistical model\nValidation active]
    D --> E[Systematic closure\nPlanned]
    E --> F[Full Run 2 combination\nPlanned]
    F --> G[Final review and observed result\nGated]
```

## Current focus

The corrected 2018 derived production has completed its closure checks while preserving the validated central nominal reconstruction. The blinded statistical-model chain is now operational through template construction, datacard generation, combined workspaces and expected-only inference. Current work is focused on model-consistency and systematic-closure audits before the 2018 model is frozen and the workflow is extended to the remaining Run 2 periods.

Production provenance for the completed 2018 campaigns has also been consolidated in the private analysis workflow so that the reconstruction, validation and statistical-model steps remain traceable and reproducible.

## Status policy

This public status page is updated only when a major project-management milestone changes state or when the active gate within a milestone materially changes. Technical details remain in the private analysis repository.

### Status legend

- ✅ **Complete** — milestone closed for the current scope.
- 🔵 **In progress** — active production or validation.
- ⏭ **Next** — immediate downstream milestone.
- ⏳ **Planned** — scheduled after earlier gates close.
- 🔒 **Gated** — requires analysis freeze/review approval before proceeding.

## GitHub Pages

The site is deployed from this repository using GitHub Actions and is intended to remain a sanitized public project-status view only.
