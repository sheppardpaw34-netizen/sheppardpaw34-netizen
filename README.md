# Zihad Rahman 👋
**Analytics Engineer | Bangladesh**

I bridge raw event streams and billing schemas into business-readable SaaS metrics. Focused on fixing revenue friction, modeling MRR mechanics, and building production-grade dbt pipelines.

---

### 🎯 Business Value & Problem Solving

| What SaaS Businesses Suffer From | What I Engineer & Deliver |
| :--- | :--- |
| **Silent MRR Bottlenecks:** Broken proration, unhandled mid-cycle upgrades, and misaligned date spines distorting MRR. | **100% Precise MRR Waterfalls:** Robust dbt date-spine models tracking New, Expansion, Contraction, Churn, and Reactivation. |
| **Flawed Event Attribution:** Broken identity resolution and async webhooks distorting trial-to-paid signals. | **Bulletproof Attribution Schemas:** Clean event pipelines connecting user activity directly to Stripe billing objects. |
| **Dashboard Distrust:** Ad-hoc SQL and untested models leading to conflicting executive metrics. | **Production Data Layer:** Modular dbt models with automated freshness checks, custom tests, and GitHub Actions CI/CD. |

---

### 🛠️ Workflow & Technical Stack

* **Transformation & Modeling:** `dbt-core` (Jinja, Macros, Testing), SQL (CTE Architecture, Window Functions, Date Spines)
* **Databases & Engines:** DuckDB (Local Execution Engine), PostgreSQL, BigQuery
* **Automation & CI/CD:** Python (Ingestion Pipelines & API Glue), Git / `gh` CLI, GitHub Actions CI/CD
* **Semantic & BI Layer:** MetricFlow, Lightdash, Evidence.dev
* **Dev Environment:** VS Code (Terminal-First CLI), Windows, Notion

---

### ⚡ Core Areas of Mastery

#### 1. B2B SaaS Revenue Mechanics
Deep expertise in modeling complex subscription dynamics:
* **Waterfalls & Health KPIs:** Calculating NRR, GRR, Cohort Retention, LTV:CAC, and MRR movements accurately across time boundaries.
* **Billing Schema Modeling:** Resolving co-termed subscriptions, multi-currency conversions, and Stripe webhook payload edge cases.

#### 2. Event Attribution & User Journey
Constructing reliable frameworks to map user actions to monetary outcomes:
* **Identity Resolution:** Stitching anonymous product analytics events to paid user accounts.
* **Conversion Funnels:** Tracking trial-to-paid conversions, Product-Qualified Leads (PQLs), and event deduplication.
