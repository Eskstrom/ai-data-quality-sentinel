# AI Data Quality Sentinel

**Status: Concept brief.** The features below are proposed; this repository does not yet contain an implemented application or measured results.

[Portfolio](https://eskstrom.github.io/) · [Related projects](https://eskstrom.github.io/?category=healthcare-operations#library)

## Product brief

A monitoring dashboard that detects data drift, missingness, schema changes, and outlier values before they affect an AI-enabled workflow.

## Design focus

Connect data-quality alerts to reproducible checks and the people who can act.

## Proposed scope

- Two synthetic dataset snapshots.
- Checks for missing values, category shifts, schema changes, and outliers.
- Alert feed with severity and recommended owner/action.
- Run history and data-quality scorecard.

## Validation targets

- Every alert links to a reproducible check and affected fields.
- Demonstrate a known bad-data scenario from end to end.

## Potential implementation

Python, Pandas, Great Expectations or custom checks, Streamlit.

[Implementation planning notes](notes/IMPLEMENTATION-NOTES.md)

<!-- portfolio-future-plans:start -->
## Future plans and PRD direction

*Planning review: 24 September 2026. These are proposed next steps, not completed work or measured outcomes.*

**Priority recommendation:** Recommend consolidation before further standalone development.

Preserve missingness, schema-change and outlier checks within Eligibility Reconciliation Workbench or AI Deployment Command Center.

### Next scope

- [ ] Inventory unique requirements and planning notes before moving anything.
- [ ] Use Eligibility Reconciliation Workbench or AI Deployment Command Center as the proposed destination; record the destination and retained source history after an actual migration.
- [ ] Update incoming portfolio links before considering archive status. No consolidation or archival is implied by this planning note.

### Validation and decision criteria

Reproduce a known data-quality problem and identify its affected fields and next owner. Reopen a standalone PRD only if user discovery establishes a distinct problem that the retained project cannot cover.
<!-- portfolio-future-plans:end -->
