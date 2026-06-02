# project_sec10k_rag

AD 698 final project: an industry-scoped SEC 10-K Retrieval-Augmented Generation (RAG) prototype for financial disclosure analysis.

## Product Goal

Build a reproducible, auditable, domain-coherent FinTech RAG system that allows analysts to ask structured questions about publicly traded companies in a selected NAICS industry and receive citation-backed answers from SEC 10-K filings.

## Project Scope

- NAICS code: TBD
- Industry: TBD
- Filing years: 2015–2025
- Companies: 5–10 public companies
- Primary workflow: Google Colab + Google Drive
- Version control: GitHub for code, notebooks, configs, and documentation

## Notebook Plan

1. `01_industry_company_selection_and_10k_download.ipynb`
2. `02_item_selection_cleaning_and_eda.ipynb`
3. `03_embeddings_and_rag_preparation.ipynb`
4. `04_rag_generation_and_evaluation.ipynb`

## Security Rules

- Do not commit `.env`
- Do not commit API keys
- Do not commit raw SEC HTML filings
- Do not commit embeddings
- Do not commit vector-store artifacts
