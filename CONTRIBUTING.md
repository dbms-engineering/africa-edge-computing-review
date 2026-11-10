# Contributing

Thank you for your interest in contributing to this review.

## How to Contribute

1. **Open an issue** describing the change (e.g., a missing study, a correction, a new search source).
2. **Fork** the repository and create a branch: `git checkout -b feature/short-description`.
3. **Make your changes** following the conventions below.
4. **Open a pull request** referencing the issue.

## Conventions

- **Search logs**: one file per search, named `YYYY-MM-DD_<database>.md`, recording the exact query, filters, date, and number of hits.
- **References**: export in BibTeX (`.bib`) or RIS (`.ris`); do not edit exports by hand.
- **Screening**: record every decision with a reason for exclusion, referencing the criteria in `protocol/inclusion-exclusion-criteria.md`.
- **Evidence**: use the columns defined in `evidence/extraction-template.csv`; do not rename columns.
- **Writing**: Markdown, one sentence per line where practical to keep diffs readable.

## Dual Review

Screening and appraisal decisions should be made independently by at least two reviewers, with disagreements resolved by discussion or a third reviewer.
