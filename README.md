# humansegmentation-project

Hi everyone here to read and evaluate my work
This repository aims to discover the landscape of google merchandise sample dataset.



# GA4 User Segmentation Project

This repository contains the analysis performed on the
`bigquery-public-data.ga4_obfuscated_sample_ecommerce` dataset,
with the goal of segmenting users into **New, Active, Dormant, and Lost** buckets.

## Repository Structure
├─ _documents/                  # Final deliverables
│  ├─ Recommendations.*         # Marketing & sales recommendations
│  └─ Automations.*             # Automation plan (segment computation & activation)
├─ _sql/                        # SQL (as .txt) used to manipulate data in GCP BigQuery
│  ├─ Extraction_and_unnesting/
│  │  ├─ unflatten_query_v1.txt
│  │  └─ unflatten_query_v2.txt   # Two alternative unnesting approaches, used at different times
│  └─ Analysis/
│     └─ Segmentation.txt   # First segmentation d
└─ _notebook/
   └─ notebook_link.txt         # Link to the GCP notebook used for the core analysis


## Deliverables
1. Code for user segmentation (SQL + Python notebooks)
2. Recommendations (docs/recommendations.md)
3. Automation plan (docs/automation.md)

## How to Use This Repo

Start with _documents to understand the conclusions (Recommendations & Automations).

- Open _notebook/notebook_link.txt and view the notebook in GCP to see the full analysis and final segmentation.

If needed, consult _sql:

- Use Extraction_and_unnesting queries to reproduce the unnesting step in BigQuery.


## How to Run
- Open the queries in `_sql` and the notebooks in `_notebooks` directly in BigQuery Console
