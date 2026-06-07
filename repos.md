# Repositories

## Owned

| Name | URL | Type | Status | Why It Matters |
|---|---|---|---|---|
| Niki-Smart-Tools | https://github.com/Niki-Spatial-Art/Niki-Smart-Tools | core | active | ETF watchlist, market monitoring, and trading-discipline automation tied to the broader research workflow. |

## External References

| Name | URL | Type | Status | Why Track It |
|---|---|---|---|---|
| OpenBB | https://github.com/OpenBB-finance/OpenBB | platform | active | Open-source research stack for financial data, screening, APIs, and analyst-facing workflows. |
| Microsoft Qlib | https://github.com/microsoft/qlib | quant-platform | review | Mature quant research framework covering data pipelines, experiment workflows, and model-driven strategy research. |
| SEC EDGAR APIs | https://www.sec.gov/edgar/sec-api-documentation | official-docs | active | Official JSON/XBRL source for filings and company facts; useful for reproducible US fundamental-data ingestion. |
| SEC EDGAR XBRL Guide | https://www.sec.gov/file/xbrl-guide | official-docs | active | Official filing-guide companion for mapping Inline XBRL structures and validation expectations into a cleaner ingestion pipeline. |
| sec-edgar-downloader | https://github.com/jadchaar/sec-edgar-downloader | filing-ingestion | review | Practical Python layer for pulling SEC filings into local research workflows without rebuilding the downloader plumbing. |
| FinSight | https://github.com/RUC-NLPIR/FinSight | research-agent | review | Reference implementation for automated financial research pipelines, chart refinement, and report generation. |
| FinRobot | https://github.com/AI4Finance-Foundation/FinRobot | research-agent | review | Strong open-source baseline for multi-agent equity analysis, report generation, and data-tool orchestration. |
| x2strategy | https://github.com/ALAGENT-HKU/x2strategy | strategy-research | review | Useful reference for turning papers or notes into auditable strategy specs, executable backtests, and diagnosis loops. |
| OpenEDGAR | https://github.com/LexPredict/openedgar | filing-ingestion | review | Mature framework for constructing EDGAR-backed research databases when direct SEC endpoints need a reusable parsing layer. |

## Official References

| Name | URL | Type | Status | Why Track It |
|---|---|---|---|---|
| OpenBB Extensions Docs | https://docs.openbb.co/odp/python/extensions | official-docs | active | Useful for evaluating whether OpenBB should stay a reference only or become a modular connector layer in this workflow. |
| Qlib Documentation | https://qlib.readthedocs.io/en/stable/ | official-docs | active | Official usage and architecture reference for data preparation, experiments, and model lifecycle design. |
| SEC Accessing EDGAR Data | https://www.sec.gov/search-filings/edgar-search-assistance/accessing-edgar-data | official-docs | active | Canonical access patterns and archive paths for building filing ingestion without relying on unofficial mirrors. |

## Fork Candidates

| Name | URL | Decision | Notes |
|---|---|---|---|
| OpenBB | https://github.com/OpenBB-finance/OpenBB | monitor | Strong base if this repo later needs a reusable market-data connector layer. |
| Microsoft Qlib | https://github.com/microsoft/qlib | monitor | Candidate if this repo expands into reproducible factor research, experiment tracking, or model-assisted signal work. |
| sec-edgar-downloader | https://github.com/jadchaar/sec-edgar-downloader | monitor | Candidate to simplify SEC filing retrieval before deciding whether a heavier EDGAR ingestion stack is justified. |
| FinSight | https://github.com/RUC-NLPIR/FinSight | monitor | Worth revisiting if report-generation automation becomes a first-class workflow. |
| FinRobot | https://github.com/AI4Finance-Foundation/FinRobot | monitor | Candidate to borrow agent/report orchestration patterns without rebuilding the full stack from scratch. |
| x2strategy | https://github.com/ALAGENT-HKU/x2strategy | monitor | Candidate if the workflow expands from discretionary research notes into paper-to-backtest automation. |
