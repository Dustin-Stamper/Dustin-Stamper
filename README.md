<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b26,50:414868,100:7aa2f7&height=200&section=header&text=Dustin%20Stamper&fontSize=60&fontColor=c0caf5&animation=fadeIn&desc=Building%20systems%20that%20run%20the%20real%20world&descSize=18&descAlignY=75" />

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=7AA2F7&center=true&vCenter=true&width=520&lines=Platform+Developer+%7C+QuickBase+%2B+ServiceNow;Solo+Architect+of+2+Production+Platforms;AI-Assisted+Dispatch+%26+Automation;Published+ServiceNow+Store+Developer" />

</div>

## 👋 About Me

I'm the sole developer behind the software layer that runs a national field-services company — two production platforms covering dispatch, work orders, warehouse inventory, invoicing, and AI-assisted scheduling, integrated live with QuickBooks, Autotask, ServiceNow, Datto RMM, and Hudu. I'm also a **ServiceNow partner with a published app in the ServiceNow Store**.

I build low-level: vanilla HTML/JS code pages, direct REST and XML API calls, no frameworks, no external dependencies — because in an operations environment, every page has to load fast and never break.

## 🚀 Flagship Projects

### 🛠️ Service Manager V2.1 — *Field Service SaaS Platform*
A full service-management platform built and operated solo, running live daily operations.
- **Modular single-page architecture** — a shell page dynamically loads feature modules over a shared API/config/theme foundation, so new features ship without touching the core
- Dispatch, ticketing, invoicing, customer portal, and a dedicated **accounting sublayer** synced with QuickBooks
- **Role-aware workspaces** — Program Manager, Project Manager, and Project Coordinator each get purpose-built home surfaces
- Rationalized the ticket lifecycle from **15 statuses down to 9** with structured hold-reason tracking — less ambiguity for field crews, cleaner reporting for management
- Strict design system: locked dark theme, zero hardcoded values in module pages

### 📦 WMS v1 — *Warehouse Management System*
Inventory and warehouse logistics platform linked live to the service layer, with a scripted **deploy / harvest / sync / schema** pipeline treating a no-code platform like a real codebase — version-controlled, repeatable, auditable.

### 🤖 KW Scheduler — *AI-Powered Dispatch Engine*
An LLM-driven field-service scheduler, delivered as a single self-contained code page.
- **Three sequential AI agents** — Logistics (scheduling), Operations (routes & costs), Mapping (geographic clustering) — with automatic per-tech batching on jobs above 40 sites
- 7-step planning wizard: SOW import → site upload → team selection → depot logistics → approach → analysis → results
- Live geocoding (OpenStreetMap Nominatim), interactive route maps (Leaflet), and one-click **dispatch schedule + hotel booking exports**
- Route-overlap detection in the works: automatically spotting when one truck roll can close two tickets

### 🏛️ PMO Governance Sublayer — *Enterprise Project Governance*
Designed and specced a portfolio-governance module — **13 new tables across 6 build phases** — covering demand intake, resource capacity planning, program & portfolio management, baselines, snapshots, and a RAID register. Written as an agent-executable implementation guide with strict non-disruption rules, shipped dark behind a role gate with warn-mode enforcement for safe rollout.

### 🌐 ServiceNow Store App *(published)* + Universal Overlay *(in development)*
One app already live in the ServiceNow Store; currently building a universal role-based dashboard overlay that installs into any customer instance — guided setup, generated per-persona workspaces, catalog ordering, Gantt views, exports, and alerting.

## 🤝 How I Work

- **AI-assisted engineering with guardrails** — I run agentic dev workflows (Claude, VS Code agents) against production systems: 22 scoped agent-executed tasks on the SM rebuild, verified with Playwright audits, under a governed conductor workflow where git is the archive of *finished* work only
- **Self-hosted MCP infrastructure** — wiring AI agents directly into QuickBase, GitHub, and PSA tooling through a gateway federating multiple backend servers
- **Integration-first mindset** — QuickBooks sync, Autotask PSA, ServiceNow, Datto RMM, Hudu docs; if it has an API, I'll connect it

## 📈 By the Numbers

| | |
|---|---|
| 🏗️ | **2 production platforms** built and operated solo (service management + WMS) |
| 🔌 | **5+ live system integrations** (QuickBooks, Autotask, ServiceNow, Datto RMM, Hudu) |
| 🧩 | **13-table governance module** designed across 6 phased rollouts |
| 🤖 | **3-agent AI pipeline** powering dispatch optimization |
| 🏪 | **1 published ServiceNow Store app** — with a second in development |

## 📊 GitHub by the Numbers

Most of my work ships to **private production repos** — so instead of widget cards that can't see it, here are the real figures:

<div align="center">

![Repositories](https://img.shields.io/badge/Repositories-30-7aa2f7?style=for-the-badge&labelColor=1a1b26)
![Commits](https://img.shields.io/badge/Commits-350%2B-7aa2f7?style=for-the-badge&labelColor=1a1b26)
![Active](https://img.shields.io/badge/Active%20This%20Quarter-7%20repos-7aa2f7?style=for-the-badge&labelColor=1a1b26)

![JavaScript](https://img.shields.io/badge/JavaScript-7%20repos-7aa2f7?style=for-the-badge&labelColor=1a1b26)
![Python](https://img.shields.io/badge/Python-6%20repos-7aa2f7?style=for-the-badge&labelColor=1a1b26)
![HTML](https://img.shields.io/badge/HTML-6%20repos-7aa2f7?style=for-the-badge&labelColor=1a1b26)
![TypeScript](https://img.shields.io/badge/TypeScript-3%20repos-7aa2f7?style=for-the-badge&labelColor=1a1b26)

<sub>*Counted from the actual account · September 2026*</sub>

</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7aa2f7,50:414868,100:1a1b26&height=100&section=footer" />
</div>
