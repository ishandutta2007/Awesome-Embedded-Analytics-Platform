# Awesome-Embedded-Analytics-Platform

# Top Embedded Analytics Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on White-Label BI, Customer-Facing Dashboards, Multi-Tenant Analytics & SDK-Based Embedding*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Embedded Analytics**. These tools help SaaS vendors, product teams, and developers embed interactive dashboards, reports, and visualizations directly into their applications—enabling customer-facing analytics without building a BI platform from scratch.

**Examples** include Looker Embedded, Sisense, GoodData, Domo Everywhere, Qlik Embedded Analytics, ThoughtSpot Embedded, Reveal BI, Yellowfin BI, Logi Analytics, Bold BI, Sigma Embedded, Luzmo, Metabase Embedded, Logi Symphony, and Domo Everywhere (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom embedding SDKs, and transparent analytics infrastructure—ideal for engineering-led teams that need full control over their embedded analytics stack without per-user SaaS fees or vendor lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Looker Embedded](https://looker.com/)**
  Google Cloud's embedded analytics platform. Primarily iframe-based with a JavaScript Embed SDK for programmatic control (filtering, drill-downs, resizing). Strong semantic modeling via LookML. Best for organizations already invested in BigQuery and Google Cloud. Embedded tier pricing starts at $100K–$1.77M+/year .

- **[Sisense](https://www.sisense.com/)**
  In-memory embedded analytics engine (ElastiCube) with white-labeling and drag-and-drop interface. Offers Compose SDK and Sisense.js for native embedding without iframes. Targets product teams wanting turnkey embedded analytics with fast query performance. Starts from approximately $21K/year .

- **[GoodData](https://www.gooddata.com/)**
  Developer-first embedded analytics platform with React-based SDK (GoodData.UI) that renders dashboards as native DOM components—no iframes. Token-based authentication, custom theming via your own design system, and per-workspace multi-tenant architecture. Starts from $1,500/month. Best for SaaS vendors serving hundreds or thousands of tenants .

- **[Domo Everywhere](https://www.domo.com/)**
  Domo's embedded analytics offering, strictly iframe-based. Uses server-side embed tokens for authorization with row-level or user-specific permissions. JS API for filtering and data export. Simple to deploy and secure, but limited UI cohesion with host application .

- **[Qlik Embedded Analytics](https://www.qlik.com/)**
  Associative engine enabling free-form exploration in embedded scenarios. Robust APIs (Capability API, Nebula.js) for custom analytics experiences. Supports iframe embeds and mashups. Insight Advisor provides AI-generated insights. Enterprise-level pricing .

- **[ThoughtSpot Embedded](https://www.thoughtspot.com/)**
  Search-driven analytics embedded platform (formerly ThoughtSpot Everywhere). Provides interactive drill-through navigation with semantic model reuse across embedded dashboards. Focuses on guided drill paths for non-technical users .

- **[Reveal BI](https://www.revealbi.io/)**
  Embedded analytics SDK for .NET, Java, and JavaScript. Tenant-aware embedding runtime with REST-based binding. Focuses on dependable PDF output within tenant-aware embedded flows. Couples tenant-aware request context with parameterized dashboard filters .

- **[Yellowfin BI](https://www.yellowfinbi.com/)**
  Embedded analytics platform with white-labeling, multi-tenancy, and row-level security. Provides dashboards, reports, and data storytelling capabilities.

- **[Logi Analytics](https://www.logianalytics.com/)**
  Embedded analytics platform (now part of insightsoftware). Offers Logi Symphony for OEM and SaaS embedding with customizable dashboards and self-service analytics.

- **[Bold BI](https://www.boldbi.com/)**
  Embedded analytics platform with self-service and embedded capabilities. Features row-level security, SSO, trusted authentication, multi-tenancy, and white-labeling. Noted for strong visualization options and collaboration tools .

- **[Sigma Embedded](https://www.sigmacomputing.com/)**
  Cloud-native embedded analytics built on cloud data warehouses. Provides unlimited viewer access on some plans. Pricing around $1,000/year per creator/explorer role .

- **[Luzmo](https://www.luzmo.com/)**
  Embedded analytics platform designed for SaaS companies. MAU-based subscription tiers: Starter from €495/month, Premium from €1,995/month. Emphasizes PDF output tied to embedded runtime state and tenant-aware embedding .

- **[Metabase Embedded](https://www.metabase.com/)**
  Open-source BI platform with embedded analytics offering (Embedded Analytics Pro). Pricing: $575/month platform fee + $12/month per user (first 10 included). Enterprise plans start at $20K/year. Best for engineering-led teams with simpler or narrower needs .

## Open-Source GitHub Projects

- **[Helical Insight](https://github.com/helicalinsight/helicalinsight)**
  Free, open-source BI platform with AI conversational analytics (BYO-LLM), pixel-perfect paginated reports, interactive dashboards, SSO, embedding, multi-tenancy, and row-level security. Every feature free in Community Edition. Self-hosted, Docker-ready. Java 25 + Spring backend, React frontend, Python/LangChain Instant BI module. Zero-configuration Docker deployment via `docker compose up`. Modern alternative to JasperReports, BIRT, Pentaho, and Crystal Reports . **Community Edition free**.

- **[Shaper](https://github.com/taleshape/shaper)**
  Minimal embedded analytics and data platform powered by DuckDB. Open-source, SQL-driven data dashboards. Available via `npx @taleshape/shaper` or Docker for production. Lightweight alternative for teams wanting embeddable dashboards without a full BI platform. Mozilla Public License 2.0 .

- **[bi-report-kit](https://github.com/bi-report-kit/bi-report-kit)**
  Embeddable BI reporting toolkit for React/Next.js. Provides saved queries, collections, and dashboards as installable npm package that owns its own storage (two tables in your existing PostgreSQL). Mount one route, render UI, done. Read-only against your data by design—no create/update/delete path into business tables. Supports CSV/PNG/PDF export. Designed for teams that want Rails BI gem-style building blocks in JavaScript .

- **[NexusBI](https://github.com/HeyderHesenov/NexusBI)**
  AI-powered natural-language BI platform: NL→SQL→dashboard plus power-user SQL editor, root-cause analysis, proactive AI digest, agentic copilot, semantic/trust layer, workspaces + RBAC + row-level security, embedded analytics + white-label, and FP&A scenario planning. FastAPI + React stack. Docker deployment with PostgreSQL + Redis. Demo mode runs fully offline with rule-based engine .

- **[DataEase](https://github.com/dataease/dataease)**
  Open-source BI tool with 500K+ downloads. Supports 20+ data sources, dataset creation via table joins, data dashboards, and interactive dashboards with drag-and-drop chart building. Includes SQLBot for natural language data querying and template marketplace with retail, finance, manufacturing, and other industry templates. GPL v3 license. Self-hosted with multi-platform installation .

- **[Embeddable](https://github.com/embeddable)**
  Open-source embedded analytics framework. Browser-native dashboards running on DuckDB-WASM over Apache Arrow data plane for near-zero cost per view. One-tag embedding, JWT auth, server-enforced row-level security. LLM/MCP-authorable. Open-core model .

### Additional Strong Open-Source Options

- **Lightweight BI**: **Metabase** (open-source, easy setup, good for engineering-led teams), **Apache Superset** (enterprise-grade, SQL-first, embedding via SDK) .
- **AI-Native Analytics**: **NexusBI** (NL→SQL with copilot), **DataEase** (SQLBot智能问数) .
- **Embedding Kits**: **bi-report-kit** (React/Next.js embeddable toolkit), **Shaper** (DuckDB-powered dashboards) .
- **Dashboard Frameworks**: **Grafana** (embeddable dashboards via iframe or panel embedding), **Apache Superset** (embedded SDK with row-level security).

**Frameworks for building custom systems**: Combine **Helical Insight** or **DataEase** for the core BI engine, **bi-report-kit** for React/Next.js embedding, **Shaper** for DuckDB-powered lightweight dashboards, and **PostgreSQL** for persistence. Add **Ollama** for self-hosted LLM-powered natural language querying and **Docker** for deployment.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Embedded analytics platforms handle sensitive business data; ensure proper access controls, row-level security, and compliance with data protection regulations.
- Self-hosted open-source solutions require significant operational investment in infrastructure, security, and maintenance. The license is free; the platform is not.

---

**Made for SaaS product teams, platform engineers, data product managers, and embedded analytics developers.**
Let's make embedded analytics more open, customizable, and developer-friendly.
