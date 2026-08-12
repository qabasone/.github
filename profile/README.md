# QabasOne

**Operational software for [Al Qabasy Trading](https://www.qabas.one)** — commerce workflows, fleet logistics (**AlQabasyGo**), and day-to-day operations, with self-hosted **Odoo** as the system of record.

QabasOne is the product surface operators use: dashboards, driver tooling, APIs, and shared UI. Odoo remains the authority for partners, products, inventory, chart of accounts, and official financial reporting.

---

## What we build

| Area | Role |
| --- | --- |
| **Operations** | Transaction lifecycle, operational entities, and posting into Odoo |
| **Logistics** | AlQabasyGo — fleet and driver workflows across Egypt |
| **Platform** | API, dashboards, mobile clients, shared packages, deploy & DR |

### Product surfaces

| Surface | URL |
| --- | --- |
| Company site | [qabas.one](https://www.qabas.one) |
| Operations dashboard | [dash.qabas.one](https://dash.qabas.one) |
| Drivers (AlQabasyGo) | [app.qabas.one](https://app.qabas.one) |

---

## Repositories

Most application repositories are **private** (product source). Public work lives here when it is safe to share.

### Public

| Repository | Description |
| --- | --- |
| [`qabasone-ui`](https://github.com/qabasone/qabasone-ui) | Reusable React UI components and layout primitives for QabasOne apps |
| [`qabasone`](https://github.com/qabasone/qabasone) | Public presence for qabas.one / QabasOne |
| [`.github`](https://github.com/qabasone/.github) | This organization profile |

### Platform (private)

| Repository | Description |
| --- | --- |
| `qabasone-api` | Operations API — domain services and Odoo integration |
| `qabasone-dash` | Internal operations dashboard |
| `qabasone-app` | AlQabasyGo drivers web app |
| `qabasone-go` | React Native mobile client |
| `qabasone-shared` | Shared TypeScript types, API client, tokens, and constants |
| `qabasone-deploy` | Infra & deploy source of truth (Terraform, Ansible, K3s) |
| `qabasone-backup` | Backup, restore, and disaster recovery |
| `qabasone-atlas` | Engineering atlas — architecture, domain model, governance |

---

## How we work

- **Atlas governs engineering.** Architecture, domain boundaries, API contracts, and contribution rules are defined in `qabasone-atlas`. Deviations require an ADR.
- **Private by default.** Product and ops repos stay private; publish only packages and docs intended for wider use.
- **CI before merge.** Protected `main` branches expect green quality gates.

### Contributing

- **External contributors:** open an issue on a public repo (for example [`qabasone-ui`](https://github.com/qabasone/qabasone-ui)) describing the change. We are selective about outside PRs while the core platform remains private.
- **Internal / invited collaborators:** follow Atlas contribution governance and each repo’s `AGENTS.md` / `CODEOWNERS` where present.

---

## About Al Qabasy

Al Qabasy Trading (القبسي للتجارة) is an agricultural commodities business based in **Desouk, Kafr El-Sheikh, Egypt** — rice, wheat, seeds, and logistics. QabasOne is the software we build to run those operations.

**Website:** [https://www.qabas.one](https://www.qabas.one)
