# WW Run 2 Leptonic PPS — Analysis Status

Public, high-level progress dashboard for a Run 2 leptonic diboson analysis with forward proton tagging.

**Public dashboard:** https://jgomespi.github.io/WWRun2LeptonicPPS-Analysis-Status/  
**Current phase:** 2018 end-to-end closure — kinematic-fit production in progress.  
**Milestone progress:** 2 of 7 major phases complete; phase 3 is active.  
**Last updated:** 18 August 2026.

## Public scope

This repository is intentionally limited to project-management information. It does **not** publish analysis code, storage paths, event counts, yields, selection thresholds, fitted numerical results, limits, coupling values, dataset inventories, internal review material, or other unpublished analysis details.

The public dashboard is designed to answer one question: **where is the analysis in the workflow?**

## Milestones

| Phase | Status | High-level deliverable |
|---|---|---|
| 1. Scalable workflow and reproducibility | ✅ Complete | Partitioned processing, provenance, bounded-memory execution |
| 2. 2018 nominal analysis and validation | ✅ Complete | Nominal reconstruction, control-region validation, blinded signal-region handling |
| 3. 2018 kinematic reconstruction | 🔵 In progress | Complete and audit the signal-region kinematic-fit production |
| 4. 2018 blinded statistical model | ⏭ Next | Build templates, datacards, workspace and expected-only inference |
| 5. Full systematic closure | ⏳ Planned | Validate detector, reconstruction and normalization uncertainties |
| 6. Full Run 2 combination | ⏳ Planned | Extend to all Run 2 periods and audit inter-year correlations |
| 7. Final review and observed result | 🔒 Gated | Freeze the analysis, complete review, then proceed to approved unblinding |

## Workflow

```mermaid
flowchart LR
    A[Workflow redesign\nComplete] --> B[2018 nominal validation\nComplete]
    B --> C[2018 kinematic reconstruction\nIn progress]
    C --> D[2018 blinded statistical model\nNext]
    D --> E[Systematic closure\nPlanned]
    E --> F[Full Run 2 combination\nPlanned]
    F --> G[Final review and observed result\nGated]
```

## Current focus

The active work is the production and validation of the 2018 signal-region kinematic reconstruction. The immediate gate after that is a completeness audit, followed by construction of the first blinded statistical model.

## Status policy

This public status page is updated only when a major project-management milestone changes state. Technical details remain in the private analysis repository.

### Status legend

- ✅ **Complete** — milestone closed for the current scope.
- 🔵 **In progress** — active production or validation.
- ⏭ **Next** — immediate downstream milestone.
- ⏳ **Planned** — scheduled after earlier gates close.
- 🔒 **Gated** — requires analysis freeze/review approval before proceeding.

## GitHub Pages

The site is deployed from this repository using GitHub Actions and is intended to remain a sanitized public project-status view only.
