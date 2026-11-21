# Rubén Oliveros

**Automation Engineer · RPA, Python, SQL · Medellín, Colombia**

I design and run automations and data pipelines for US companies in finance, lending, healthcare and entertainment. Close to 20 years in engineering: industrial maintenance, teaching, team leadership, and since 2020, automation and AI. What I care about most is that a project gets finished, adopted by the people who use it, and keeps running.

## Production work, rebuilt as open samples

Each repository below is a working project very similar to one I delivered in production: same architecture, same failure handling, same design decisions, running on synthetic data so anyone can clone it and see how I work.

| Repository | What it does | The production project it mirrors |
|---|---|---|
| [ledger-pipeline](https://github.com/rubenoliveros/ledger-pipeline) | ERP-to-consolidation ledger load with staging and audit schemas, idempotent reruns by RunID, a batch-load benchmark, and an LLM review loop with human approval for edge cases | SAP to Oracle FCCS/HFM pipeline: about 170,000 transactions a month, 99.9% classified by SQL rules, load time cut from 15 minutes to 42 seconds, full close process from 7 days to 30 minutes |
| [bot-fleet-monitor](https://github.com/rubenoliveros/bot-fleet-monitor) | Operations dashboard for a bot fleet: health, SLA timers, incident queue, a debounce filter for false alerts, and a triage assistant that cites runbooks | Governance of 75+ production bots under strict SLAs, including 104 healthcare bots; a 200 ms debounce filter that cut false alerts by 85% |
| [docflow-extractor](https://github.com/rubenoliveros/docflow-extractor) | Invoice field extraction with OCR, rules and an LLM step, validated JSON output and per-field accuracy reports | Document Understanding workflows across 25 enterprise automations delivered at 99.8% accuracy |
| [playwright-flow-validator](https://github.com/rubenoliveros/playwright-flow-validator) | Validation of multi-step dynamic web journeys with robust selectors, retries, traces and CI reports | Proof-of-concept AI agent for dynamic web journey validation |
| [uipath-reframework-plus](https://github.com/rubenoliveros/uipath-reframework-plus) | REFramework extended with SQL run logging, config validation at start-up and separate retry policies for system and business exceptions | REFramework state machines in enterprise lending and healthcare automations |

## Tools and labs

| Repository | What it does |
|---|---|
| [messaging-reliability-labs](https://github.com/rubenoliveros/messaging-reliability-labs) | RabbitMQ and Kafka labs with browser simulators ([live site](https://rubenoliveros.github.io/messaging-reliability-labs/)): idempotent consumers, retries, dead-letter queues, replay and reconciliation |
| [ops-mcp-server](https://github.com/rubenoliveros/ops-mcp-server) | MCP server that lets an AI assistant query bot health, open incidents, runbooks and pipeline runs |
| [pdftoany](https://github.com/rubenoliveros/pdftoany) | Python CLI that converts PDFs to Markdown, plain text or page images |
| [job-finder](https://github.com/rubenoliveros/job-finder) | Deterministic job-to-profile matching with skill dictionaries, TF-IDF and n-grams |

## How I build

- **Audit first.** Every run gets an ID, every record can be traced, and reruns never duplicate data.
- **People approve what AI suggests.** LLM output is structured, limited to known options, explained, and logged next to the human decision so accuracy can be measured.
- **Measure before and after.** Performance and quality claims come with a number and a way to reproduce it.
- **Built to be handed over.** Clear docs, tests and CI, so the next person can run it without me.

## Stack

**Automation:** UiPath (REFramework, Orchestrator, Document Understanding, AI Center, Test Suite) · Power Automate and Power Automate Desktop · Playwright
**Data and backend:** Python · SQL Server · SQLite · REST APIs · Docker · GCP
**AI:** Azure OpenAI in production with human approval and auditing
**Integrations:** SAP GUI · Oracle FCCS/HFM · Power BI · MeridianLink · Encompass · EPIC · PeopleSoft

## Background

B.S. Electronic Engineering · Postgraduate studies in Automation and Control · Holberton School software development · 23+ UiPath certifications · Spanish (native), English (C2)

## Contact

[LinkedIn](https://www.linkedin.com/in/rubenoliveros) · [rubenoliveros.github.io](https://rubenoliveros.github.io) · ruben.oliveros@gmail.com
