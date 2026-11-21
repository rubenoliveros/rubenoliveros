# Rubén Oliveros

Automation engineer in Medellín, Colombia. I build bots and data pipelines that move information between ERPs, databases, and web apps so nobody has to copy it by hand.

### Shipped in production

- **Financial close pipeline**: SAP GUI to Oracle FCCS/HFM with Power Automate Desktop, Python, and SQL Server. 170,000+ ledger entries per run, run time cut from 15 min to 42 sec. Audit schema with per-run logging.
- **Bot fleet operations**: governed 75+ UiPath bots for US clients, including 104 bots across EPIC, GHX, and PeopleSoft for a healthcare network, under strict SLAs.
- **Enterprise automations**: 25 delivered at Neostella (71 processes, 99.8% accuracy), including a MeridianLink API integration and Document Understanding workflows.

Client code stays private. The repos below rebuild the same patterns with synthetic data.

### Stack

**Automation:** UiPath (REFramework, Document Understanding, AI Center, Test Suite) · Power Automate Desktop · Playwright
**Data & backend:** Python · SQL Server · SQLite
**Infra:** Docker · GCP (Cloud Logging)
**Background:** B.S. Electronic Engineering · Holberton School software development · 23+ UiPath certifications

### Building and learning now

- `ledger-pipeline`: 170k-row ledger load into SQL Server with staging and audit schemas, benchmarked
- `job-finder`: deterministic job-to-profile matching (TF-IDF, n-grams) without per-query LLM cost
- `github-bookmark-manager`: zero-dependency Python + SQLite FTS5 dashboard for my GitHub stars

### Contact

[LinkedIn](https://linkedin.com/in/rubenoliveros) · ruben.oliveros@gmail.com · Spanish (native), English (C2)
