# FreshRoute Collective

**Supplier-neutral cold-chain order consolidation for independent UK food SMEs**  
**7001SOM Postgraduate Project — Route 3: Business Plan + Artefact**  
**Hemanth Reddy Annedla | Student ID 16880887 | Coventry University**

FreshRoute Collective is a feasibility project for a supplier-neutral coordination service that combines selected chilled order flows from local and specialist suppliers into controlled refrigerated routes for independent food SMEs.

The project does **not** assume that every food business is a potential customer or that the proposed service is already commercially proven. The model separates observed evidence, published evidence, planning assumptions and formula-derived outputs so that the proposed pilot can be assessed transparently.

## What this repository contains

This repository contains the final decision-support artefact and the supporting evidence trail used in the Route 3 business-plan analysis.

- **Excel decision artefact** — route capacity, 3PL cost envelope, pricing, margins, cash stress, compliance and stage-gate controls.
- **Interactive HTML artefact** — browser-based scenario model for testing the main commercial and operating assumptions.
- **Research log** — retained evidence, source routes, limitations, verification and decision use.
- **Evidence exports** — browser-readable CSV versions of the source register, assumptions, findings, method audit and secondary data.
- **Posters** — one-page summaries of the business model and decision model.

The assessed business-plan report and ethics documentation are submitted separately through Coventry University's assessment process and are intentionally not published in this repository.

## Core business model

1. Independent food SMEs continue to order from and pay their existing suppliers directly.
2. Suppliers prepare labelled, route-ready chilled orders for agreed collection windows.
3. FreshRoute coordinates eligibility, cut-offs, route data, custody records, temperature evidence and exceptions.
4. A contracted refrigerated third-party logistics provider (3PL) collects and delivers the compatible orders.
5. The initial pilot does not require FreshRoute to own speculative stock, a refrigerated fleet or a permanent warehouse.

## Key decision case

The artefact currently tests the following decision case:

| Item | Current value | Status |
|---|---:|---|
| Coventry FSA screening universe | 3,015 businesses | Observed |
| Planning ceiling | 14 SME drops per route-day | Derived |
| Current three-route physical ceiling | 21 SMEs | Derived |
| Contracted refrigerated 3PL cost | £275/day | Scenario |
| Current delivery-fee test | £25/drop | Scenario |
| EBITDA margin at 21 SMEs in this case | ~1.1% | Derived |
| Fee required for 10% margin | £27.89/drop | Derived |
| Fee required for 15% margin | £29.76/drop | Derived |

These values are **decision boundaries, not forecasts**. Customer willingness to pay, a qualified customer cluster, actual receiving windows and a contracted 3PL quotation remain pre-pilot validation requirements.

## Repository structure

```text
FreshRoute-Collective/
├── README.md
├── CITATION.cff
├── SHA256SUMS.txt
├── .gitignore
├── artefact/
│   └── FreshRoute_Final_Decision_Artefact.xlsx
├── research/
│   └── FreshRoute_Research_Log.xlsx
├── evidence/
│   ├── assumptions_register.csv
│   ├── findings_matrix.csv
│   ├── method_audit.csv
│   ├── secondary_data.csv
│   └── source_register.csv
├── docs/
│   ├── index.html
│   ├── ARTEFACT_GUIDE.md
│   ├── ASSUMPTIONS_AND_LIMITATIONS.md
│   └── REPOSITORY_MANIFEST.md
├── posters/
│   ├── FreshRoute_Business_Model.pdf
│   └── FreshRoute_Decision_Model.pdf
```

## How to use the artefact

Open `artefact/FreshRoute_Final_Decision_Artefact.xlsx` and begin with the **Dashboard** and **Artifact Guide** sheets. The most important analytical sheets are:

- `Route Feasibility`
- `3PL Cost Envelope`
- `Customer Cost Comparator`
- `Forecast`
- `Compliance Matrix`
- `Risk Register`
- `Assumptions Register`

The interactive version is available at `docs/index.html`. If GitHub Pages is enabled for the `/docs` folder, it can also be viewed directly in a browser as a project showcase.

## Decision logic

The business-plan recommendation is **pre-pilot validation rather than immediate full-scale launch**. A controlled pilot should only proceed after:

- an actual refrigerated 3PL quotation is obtained;
- a route-compatible customer cluster is qualified;
- registration, custody and compliance responsibilities are confirmed;
- product, payload and receiving-window constraints are validated; and
- the revised price/cost configuration demonstrates adequate operating headroom.

## Evidence discipline

The project uses four evidence classes:

- **Observed** — directly extracted data, such as the Coventry FSA screening count.
- **Published** — external research, official statistics or regulatory guidance.
- **Scenario** — planning inputs requiring commercial validation.
- **Derived** — formula outputs that are valid only if the input assumptions hold.

This classification is maintained throughout the workbook and supporting evidence exports.

## Reproducibility

See:

- [`docs/ARTEFACT_GUIDE.md`](docs/ARTEFACT_GUIDE.md)
- [`docs/ASSUMPTIONS_AND_LIMITATIONS.md`](docs/ASSUMPTIONS_AND_LIMITATIONS.md)
- [`docs/REPOSITORY_MANIFEST.md`](docs/REPOSITORY_MANIFEST.md)
- [`SHA256SUMS.txt`](SHA256SUMS.txt)
