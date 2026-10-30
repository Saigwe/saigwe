# Hi, I'm Stanley Igwe

Analytics engineer and data leader based in Lisbon, with 9+ years building trusted data products across enterprise, consulting and B2B technology (Bose, McKinsey, PwC). I design data models and pipelines, set the metric definitions teams agree on, and increasingly apply AI to data work, always grounded in governed, tested data.

**Core stack:** SQL · dbt · Snowflake · BigQuery · Python · PySpark · Dagster · Airflow · Kafka · Terraform · Docker · Kubernetes · Power BI · Tableau · Claude API

**Portfolio:** [saigwe.github.io](https://saigwe.github.io): 34 projects, each with the numbers, tests and design choices, plus two [case studies](https://saigwe.github.io/case-studies.html) from client work.

## Featured projects

Every project runs end to end with tests and CI. Each README says which data is real (public datasets such as CMS claims, Iowa sales, NERC reports and SECOM) and which is synthetic, and why.

### Analytics engineering & data platforms

| Project | What it shows |
|---|---|
| [dbt SaaS Metrics](https://github.com/Saigwe/dbt-saas-metrics) | MRR bridge, churn and account metrics with 16 tests, including a reconciliation test; runs on DuckDB or BigQuery |
| [PySpark Lakehouse Pipeline](https://github.com/Saigwe/pyspark-lakehouse-pipeline) | Bronze → silver → gold pipeline with quarantined bad rows, a dimensional model and quality gates; Databricks-ready |
| [Kafka Streaming Pipeline](https://github.com/Saigwe/kafka-streaming-pipeline) | Deduplication, watermarked windows and a dead-letter topic; alerts caught a planted incident with no false alarms |
| [Retail Enterprise Warehouse](https://github.com/Saigwe/retail-enterprise-warehouse) | 9.3M real Iowa sales lines in one Kimball warehouse: five business units on shared KPIs, within 0.12% of the regulator's total |
| [Health Claims & Pre-Authorisation Warehouse](https://github.com/Saigwe/health-claims-warehouse) | Kimball claims warehouse with SCD2 members, a pre-auth accumulating snapshot and masking enforced by tests |
| [UK Markets & Macro Lakehouse](https://github.com/Saigwe/uk-markets-lakehouse) | Every release of UK monthly GDP on Iceberg with write-audit-publish and time travel |
| [Real-Time Payments Anomaly Stream](https://github.com/Saigwe/payments-anomaly-stream) | 284,807 real card transactions replayed with late and duplicate delivery; trained on day 1, catches 85.8% of day-2 fraud |
| [Real-Time Device Telemetry Stream](https://github.com/Saigwe/device-telemetry-streaming) | 30.7M events through Kafka with event-time windows, a watermark and a late-data output, reconciled to batch |
| [dbt-trust-tests](https://github.com/Saigwe/dbt-trust-tests) | A versioned dbt package of reconciliation, answer-key, SCD2, point-in-time and privacy tests, used by other projects |
| [Data Platform Cost & Reliability Monitor](https://github.com/Saigwe/platform-cost-observability) | Real CI history, warehouse cost spikes and connector incidents, with a daily digest |
| [Data Discovery & Governance](https://github.com/Saigwe/data-discovery-governance) | Profiles PostgreSQL, MongoDB and JSON; finds keys and cross-system links, classifies PII, scores data confidence |
| [Ingestion & Orchestration](https://github.com/Saigwe/ingestion-orchestration) | CDC including deletes, a flaky API with retries and reverse ETL to the CRM, orchestrated hourly in Dagster |
| [Platform as Code](https://github.com/Saigwe/platform-as-code) | Snowflake in Terraform with a spending cap on every warehouse, a dbt image, Kubernetes CronJobs and policy checks in CI |
| [Data Contracts & Observability](https://github.com/Saigwe/data-contracts-observability) | Contracts, anomaly checks and lineage impact analysis that hold only the dashboards an incident affects |
| [Data Governance & Privacy](https://github.com/Saigwe/data-governance-privacy) | PII discovery, role-based masking views and an audited GDPR erasure workflow |
| [Warehouse FinOps](https://github.com/Saigwe/warehouse-finops) | Finds 52% savings on a Snowflake bill ($104k a year) and explains them in an executive memo |

### AI applied to data

| Project | What it shows |
|---|---|
| [Semantic-Layer AI Agent](https://github.com/Saigwe/semantic-layer-ai-agent) | A Claude agent that answers business questions only through governed dbt metrics, with an audit trail and eval set |
| [LLM Data Quality Assistant](https://github.com/Saigwe/llm-data-quality-assistant) | Turns dbt test results into grounded, plain-English briefings for data owners |
| [Text Dedup & Quality Pipeline](https://github.com/Saigwe/text-dedup-quality-pipeline) | MinHash + LSH near-dedup and quality filters for AI training data; 100% precision, 96.7% recall |
| [Ask the Warehouse](https://github.com/Saigwe/ask-the-warehouse) | 14 governed metrics, a dashboard check and an AI agent that gets metrics and no SQL; 44/44 benchmark answers |
| [Semiconductor Yield & Test Analytics](https://github.com/Saigwe/semiconductor-yield-analytics) | 1,567 real wafer runs: yield defined once, a p-chart, a wafer triage list and a guarded Claude agent |

### Finance, risk & controls

| Project | What it shows |
|---|---|
| [Revenue-to-GL Reconciliation](https://github.com/Saigwe/revenue-gl-reconciliation) | Ties a multi-currency revenue sub-ledger to the GL with $0 unexplained variance on all 26 account-months |
| [Receivables & Cash Analytics App](https://github.com/Saigwe/receivables-analytics-app) | AR aging, DSO and a collections worklist that ties to the GL on every screen |
| [Merchant Risk-Rating Controls](https://github.com/Saigwe/merchant-risk-controls) | Maker-checker overrides, period locks and an audit log the warehouse re-audits |
| [Payments Fraud & Continuous-Audit Mart](https://github.com/Saigwe/fraud-analytics-mart) | Six audit controls scored for precision and recall on 6.36M transactions |
| [Credit Risk PD Scorecard & IFRS 9 ECL](https://github.com/Saigwe/credit-risk-ifrs9) | A points scorecard and three-stage IFRS 9 allowance on 30,000 real card accounts |
| [IT General Controls & Access-Risk](https://github.com/Saigwe/itgc-access-analytics) | Seven access controls with KRIs on the CERT insider-threat benchmark, tested against its answer key |
| [Procurement Spend Cube](https://github.com/Saigwe/procurement-spend-cube) | $7.48B of real federal spend: supplier matching, classification and a Pareto of the tail |

### Operational, quality & product analytics

| Project | What it shows |
|---|---|
| [Marketing Mix Model & Attribution](https://github.com/Saigwe/marketing-mix-attribution) | Seven attribution models on Google's real GA4 sample, and a marketing mix model scored against known truth |
| [Ops Root-Cause Analysis](https://github.com/Saigwe/ops-root-cause-analysis) | Pinpoints an SLA drop to one site, queue and staffing change, sizes the effect and recommends a fix |
| [SPC Control Charts](https://github.com/Saigwe/spc-control-charts) | XmR charts with NHS Making Data Count rules, plus variation and assurance icons |
| [Product Usage, Retention & Experiments](https://github.com/Saigwe/product-analytics-experiments) | Product metrics defined once and an A/B toolkit validated on real visitors |
| [Experimentation Platform](https://github.com/Saigwe/experimentation-platform) | A/B readouts with SRM checks, CUPED and guardrails; ships a +6.0% winner and refuses a broken test |
| [Forecasting & Scenario Planning](https://github.com/Saigwe/forecasting-scenario-planning) | Backtested forecasts turned into hiring and cross-training decisions |
| [Telecom Churn Feature Store](https://github.com/Saigwe/telecom-churn-feature-store) | Point-in-time features with training and serving proven identical |
| [People & Training Analytics](https://github.com/Saigwe/people-training-analytics) | Training cost per head, a competency-gap matrix and attrition by training, with a live report |
| [Device Fleet Reliability](https://github.com/Saigwe/device-fleet-reliability) | Failure rates and survival curves on 30.6M real drive-days |

### Energy & utilities

| Project | What it shows |
|---|---|
| [Day-Ahead Load Forecasting](https://github.com/Saigwe/load-forecasting-ops) | A daily self-running forecast that beats the grid operator's own (2.69% vs 2.78% MAPE) |
| [Smart-Meter Revenue Protection](https://github.com/Saigwe/smart-meter-revenue-protection) | A theft inspection list from 167.8M real London smart-meter readings |
| [Grid Reliability GIS](https://github.com/Saigwe/grid-reliability-gis) | 2.04M London households on the open network map, with SAIDI and SAIFI by substation |
| [Nigerian DisCo Performance Scorecard](https://github.com/Saigwe/nigeria-disco-performance) | Billing, collection and ATC&C loss for all 11 Nigerian DisCos, extracted from the regulator's reports |

## How they connect

`dbt-saas-metrics` is the governed source of truth for the newest projects: the AI agent answers questions from its marts, and the data quality assistant reads its test results after every build. `dbt-trust-tests` packages the reconciliation and control tests the finance and healthcare projects use.

## Certifications

PMP® · Microsoft Certified: Data Analyst Associate · Microsoft Certified: Azure Fundamentals · Microsoft Certified Trainer · Alteryx Core Designer

## Connect

[LinkedIn](https://www.linkedin.com/in/stanleyaigwe) · [Portfolio](https://saigwe.github.io)
