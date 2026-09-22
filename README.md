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
