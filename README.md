# Africa Edge Computing Review

A systematic literature review of **edge computing in Africa**: its deployments, enabling infrastructure, use cases, challenges, and open research directions.

## Objectives

- Map the current state of edge computing research and deployment across African countries.
- Identify dominant application domains (e.g., agriculture, health, fintech, smart cities, IoT).
- Analyse infrastructural, economic, regulatory, and energy constraints specific to the region.
- Synthesise evidence into themes and highlight research gaps.

## Methodology

The review follows a structured protocol informed by **PRISMA 2020** reporting guidelines. See [`protocol/`](protocol/) for the full research protocol, research questions, search strategy, and inclusion/exclusion criteria.

## Repository Structure

```
africa-edge-computing-review/
├── README.md
├── LICENSE
├── CONTRIBUTING.md
├── protocol/            # Review protocol, RQs, search strategy, eligibility criteria
├── literature/
│   ├── search-logs/     # Database queries, dates, and hit counts
│   ├── references/      # Bibliographic exports (BibTeX, RIS)
│   └── screening/       # Title/abstract and full-text screening records
├── appraisal/           # Quality appraisal framework and scores
├── evidence/            # Data extraction template and evidence matrix
├── analysis/            # Thematic synthesis and research gaps
├── manuscript/          # Outline and drafts
└── figures/diagrams/    # PRISMA flow diagram and other figures
```

## Workflow

1. **Protocol** – define questions, scope, and eligibility criteria.
2. **Search** – run database queries; log every search in `literature/search-logs/`.
3. **Screening** – de-duplicate and screen records in `literature/screening/`.
4. **Appraisal** – assess study quality using `appraisal/appraisal-framework.md`.
5. **Extraction** – extract data into `evidence/extraction-template.csv` and consolidate into `evidence/evidence-matrix.csv`.
6. **Synthesis** – perform thematic synthesis and identify gaps in `analysis/`.
7. **Writing** – develop the manuscript in `manuscript/`.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

See [LICENSE](LICENSE).
