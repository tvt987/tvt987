<h1 align="center">Truong Van Tinh — TVT Studio</h1>
<h3 align="center">Senior Full-Stack .NET 10 / Python FastAPI & Applied AI Architect | 26/26 Full-Stack Production Monorepos · 29 Live Web Apps · 12 Free Pro Tools · 2,873 Live CI Tests (3,000+ Across GitHub)</h3>

<p align="center">
  <a href="https://tvt987.github.io" target="_blank"><img src="https://img.shields.io/badge/Portfolio-Hyperion%20v11.0%20(56kB)-6366f1?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Interactive Portfolio" /></a>
  <a href="https://tvt987.github.io/tvt-studio/" target="_blank"><img src="https://img.shields.io/badge/TVT%20Studio%20v8.0-26%20Systems%20%2B%20CMS-ff4d00?style=for-the-badge&logo=vercel&logoColor=white" alt="TVT Studio Storefront" /></a>
  <a href="https://tvt987.github.io/tvt-tools/" target="_blank"><img src="https://img.shields.io/badge/TVT%20Pro%20Tools%20v2.0-12%20Free%20Engines-f59e0b?style=for-the-badge&logo=vite&logoColor=white" alt="TVT Pro Tools" /></a>
  <a href="https://tvt987.github.io/orbitalflow-saas/" target="_blank"><img src="https://img.shields.io/badge/OrbitalFlow-.NET%2010%20B2B%20SaaS-4f46e5?style=for-the-badge&logo=dotnet&logoColor=white" alt="OrbitalFlow SaaS" /></a>
  <a href="https://tvt987.github.io/vectradoc-rag/" target="_blank"><img src="https://img.shields.io/badge/VectraDoc-FastAPI%20Hybrid%20RAG-9b2c2c?style=for-the-badge&logo=fastapi&logoColor=white" alt="VectraDoc AI RAG" /></a>
  <a href="https://tvt987.github.io/aegispulse-distributed-sre/" target="_blank"><img src="https://img.shields.io/badge/AegisPulse-.NET%2010%205K%20RPS-0d9488?style=for-the-badge&logo=redis&logoColor=white" alt="AegisPulse SRE" /></a>
  <a href="mailto:tinhkun102@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

### 26 / 26 Full-Stack Production Monorepos (`18` `.NET 10` Clean Arch + `8` `Python 3.12 FastAPI` + `React 19`)

Every single repository below ships a **locally compiled & tested backend** (`dotnet test` with `TreatWarningsAsErrors=true` or `pytest`), **multi-stage `Dockerfile` + `docker-compose.yml`**, **OpenAPI 3.1.0 specification**, **2 Architecture Decision Records (`ADR-001/002`)**, **aggressive `React.lazy` code-splitting (`37–147 kB` initial entry JS)**, **Strict CSP**, **0 SAST findings**, and **0-error Playwright E2E at `1440px` & `390px`**.

#### Core Enterprise, AI/RAG, Distributed Systems & Data Platforms (`10` Flagships)

| Monorepo | Live Production Demo | Backend & Verified Tests | Key Engineering Proof |
| :--- | :--- | :--- | :--- |
| **[OrbitalFlow SaaS v2.0](https://github.com/tvt987/orbitalflow-saas)** | **[Live B2B SaaS](https://tvt987.github.io/orbitalflow-saas/)** | **`.NET 10`** · `85` FE + `18` BE = **`103`** | Multi-tenant RBAC `403`, Drag-Drop Kanban + `Ctrl+Z` Undo, CPM Gantt SVG, 2-Tab `BroadcastChannel` Sync, Stripe Proration & HMAC Webhooks. |
| **[VectraDoc AI v2.0](https://github.com/tvt987/vectradoc-rag)** | **[Live Hybrid RAG](https://tvt987.github.io/vectradoc-rag/)** | **`FastAPI`** · `98` FE + `22` BE = **`120`** | Pure-TS `.pdf` FlateDecode parser, 4-Way A/B Matrix (`Recall@5 100%`, `MRR 100%`, `NDCG@5 94.9%`), Chunk Minimap, Luhn PII Guard & BYOK Streaming. |
| **[FleetPulse GIS v2.0](https://github.com/tvt987/fleetpulse-gis)** | **[Live GIS Dispatch](https://tvt987.github.io/fleetpulse-gis/)** | **`.NET 10`** · `93` FE + `20` BE = **`113`** | Click-on-Map Add Stops solving CVRP Clarke-Wright + 2-Opt (`-28.6%` km in `<1ms`), `08:00–17:00` Shift Scrub, Live Geofence Editor & PostGIS/MQTT. |
| **[MedCore EHR v2.0](https://github.com/tvt987/medcore-ehr)** | **[Live Clinical EHR](https://tvt987.github.io/medcore-ehr/)** | **`FastAPI`** · `92` FE + `22` BE = **`114`** | 3-Channel Canvas ICU Monitor (`ECG Lead-II + SpO2 + EtCO2`), RCP NEWS2, 1-Click Safe Drug Auto-Substitute, Admission Wizard & HL7 FHIR R4 `$everything`. |
| **[AegisPulse SRE v4.0](https://github.com/tvt987/aegispulse-distributed-sre)** | **[Live SRE Arena](https://tvt987.github.io/aegispulse-distributed-sre/)** | **`.NET 10`** · `83` FE + `35` BE = **`118`** | **Con Cung 700-Store Proof**: 500-Req Concurrent Voucher Race (`Redis Lua + ROWVERSION` `0.00%` leak, `p99 36.6ms`, `5,381 RPS`), 100-way xUnit race & `k6` 5K script. |
| **[Verdict Graph v4.0](https://github.com/tvt987/verdict-graph)** | **[Live Agent Firewall](https://tvt987.github.io/verdict-graph/)** | **`FastAPI`** · `91` FE + `50` BE = **`141`** | OWASP LLM01–LLM10 Prompt Firewall, Token Budget Circuit Breaker (`HARD_STOP`/downgrade), Time-Travel Fork (`-52.2%` cost), DAG Replay & MCP/A2A. |
| **[Nexus Lake v4.0](https://github.com/tvt987/nexus-lake)** | **[Live OLAP Lakehouse](https://tvt987.github.io/nexus-lake/)** | **`FastAPI + MCP`** · `84` FE + `37` BE = **`121`** | 500K-row DuckDB-WASM OLAP, Interactive SVG Bronze→Silver→Gold Medallion Lineage, Dual-Layer Read-Only SQL AST + SQLite C Authorizer (`403`). |
| **[Helios Quant v2.0](https://github.com/tvt987/helios-quant-terminal)** | **[Live Quant Exchange](https://tvt987.github.io/helios-quant-terminal/)** | **`FastAPI`** · `127` FE + `26` BE = **`153`** | Deterministic FIFO L2 Orderbook (`15×15`, incl. `VN30F1M`), 60fps Candlesticks, `6×6` Sharpe Grid-Search Heatmap (`7.7ms`), 6-Asset Correlation & Depth OFI. |
| **[AeroForge 3D v2.0](https://github.com/tvt987/aeroforge-digital-twin)** | **[Live 3D CAD SCADA](https://tvt987.github.io/aeroforge-digital-twin/)** | **`.NET 10`** · `105` FE + `28` BE = **`133`** | Daylight CAD 3D Factory, Programmable 6-Axis CNC G-Code Sequencer (`Z < 120mm` collision interlock, `.nc` export), FLIR IR & ISO 10816 FFT Maintenance ROI. |
| **[CodaHR Payroll v3.0](https://github.com/tvt987/coda-hr-payroll)** | **[Live HRIS 2026](https://tvt987.github.io/coda-hr-payroll/)** | **`.NET 10`** · `73` FE + `33` BE = **`106`** | Vietnam Law 109/2025 5-Bracket PIT Payroll Engine, Drag-Drop 5-Stage Kanban ATS, Gross↔Net Offer Modeler & Org Salary Band Heatmap. |

#### Industry Verticals, 3D WebGL Configurators, FinTech, POS & Commerce (`16` Full-Stack Monorepos)

| Monorepo | Live Demo | Stack & Tests | Highlight Capabilities |
| :--- | :--- | :--- | :--- |
| **[Velox EV Motors v4.0](https://github.com/tvt987/velox-ev-motors)** | **[Live 3D EV](https://tvt987.github.io/velox-ev-motors/)** | `.NET 10` · **`107`** | Widebody 3D HDRI Hypercar, Matrix LED + Active Wing, 3-Circuit Telemetry Lab & 12-way parallel Idempotent Slot Lock (`409`). |
| **[Chronos 3D Watch v2.0](https://github.com/tvt987/chronos-horology)** | **[Live Tourbillon](https://tvt987.github.io/chronos-horology/)** | `.NET 10` · **`126`** | Geneva Ivory 3D Tourbillon (`28,800 vph`), Witschi Acoustic Timegrapher Canvas, 7-Layer Exploded Inspector & HMAC Serial Passport Vault. |
| **[Maison Véra v5.0](https://github.com/tvt987/maison-vera)** | **[Live 3D Eyewear](https://tvt987.github.io/maison-vera/)** | `.NET 10` · **`112`** | Optical Rx Validator (`SPH/CYL/AXIS`), 1.50 vs 1.74 Sagitta Cross-Section & Spectral Curve, Lazy PMREM 3D (`-77.2%` entry) & 16-way Fitting Lock. |
| **[Aether Acoustics v4.0](https://github.com/tvt987/aether-acoustics)** | **[Live 3D Audio](https://tvt987.github.io/aether-acoustics/)** | `.NET 10` · **`110`** | Room Standing-Wave Axial Mode & Sabine/Eyring RT60 Optimizer, Auto-Correction IIR EQ, Biquad DSP API & `59kB` Lazy Entry (`-88.9%`). |
| **[Meridian Logistics v3.0](https://github.com/tvt987/meridian-logistics)** | **[Live Freight Tower](https://tvt987.github.io/meridian-logistics/)** | `.NET 10` · **`107`** | Port Disruption Reroute Lab (Ocean vs Sea-Air vs Air), 3D Container CG X/Y/Z + SOLAS e-VGM Pass/Fail & EVFTA/CPTPP Customs API. |
| **[Lumina MedSpa v3.0](https://github.com/tvt987/lumina-medspa)** | **[Live Clinic Portal](https://tvt987.github.io/lumina-medspa/)** | `.NET 10` · **`101`** | 12-Week Fitzpatrick I–VI Clinical Treatment Roadmap, 0% Installment Comparator, 10-way Doctor/Room Slot Lock (`409`) & `41.8kB` Entry (`-89.7%`). |
| **[Atelier Canvas v5.0](https://github.com/tvt987/atelier-canvas)** | **[Live Design Studio](https://tvt987.github.io/atelier-canvas/)** | `.NET 10` · **`96`** | Real 2-Tab Live Collaborative Vector Canvas (`BroadcastChannel`), 4-Target Token Compiler (`CSS/TS/SwiftUI/Compose`) & Optimistic Concurrency API. |
| **[Aurelia Resort v3.0](https://github.com/tvt987/aurelia-resort)** | **[Live Resort PMS](https://tvt987.github.io/aurelia-resort/)** | `.NET 10` · **`95`** | 30-Day RevPAR Yield Studio (Direct vs 18% OTA), Bespoke Villa Itinerary Sync & 10-way Interval-Overlap Reservation Lock (`409`). |
| **[PulsePOS F&B v3.0](https://github.com/tvt987/pulse-pos-fnb)** | **[Live POS ↔ KDS](https://tvt987.github.io/pulse-pos-fnb/)** | `.NET 10` · **`87`** | Sunlit Daylight Café POS, Real 2-Tab Live POS ↔ Kitchen KDS Sync (`<50ms`), Floorplan Designer, Atomic Stock Lock (`409`) & VietQR CRC-16. |
| **[Zenith Wealth v3.0](https://github.com/tvt987/zenith-wealth-fintech)** | **[Live Private Bank](https://tvt987.github.io/zenith-wealth-fintech/)** | `FastAPI` · **`86`** | Tax-Loss Harvesting, 4-Currency FX Hedging Lab (`VND/USD/EUR/Gold`), Markowitz 40-Node Frontier & 30-Year Glidepath Drawdown. |
| **[Kinetix PropTech v3.0](https://github.com/tvt987/kinetix-proptech)** | **[Live PropTech](https://tvt987.github.io/kinetix-proptech/)** | `.NET 10` · **`82`** | Saigon Sun-Path Solar Orientation Lab, 10-Year Cash vs 70% Leverage Net IRR Matrix, +4% Stress Test & 10-way Idempotent Unit Escrow (`409`). |
| **[Veritas Legal v2.0](https://github.com/tvt987/veritas-legal-firm)** | **[Live Legal Studio](https://tvt987.github.io/veritas-legal-firm/)** | `FastAPI` · **`82`** | Pure LCS Word-Level Contract Clause Redline Diff (Zero `innerHTML`), Decree 13/2023 PDPD Compliance Scorer, Conflict Check (`409`) & `37kB` Entry. |
| **[Nordic Atelier v2.0](https://github.com/tvt987/nordic-home-atelier)** | **[Live Interior CAD](https://tvt987.github.io/nordic-home-atelier/)** | `.NET 10` · **`82`** | 2D AABB Furniture Collision & Ergonomic Clearance (`>=800mm`) API, Circadian Kelvin & Embodied Carbon Optimizer, Target Budget Auto-Fit & `51.7kB` Entry. |
| **[Kuro Omakase v2.0](https://github.com/tvt987/kuro-omakase)** | **[Live Omakase](https://tvt987.github.io/kuro-omakase/)** | `.NET 10` · **`81`** | 14-Seat Hinoki Anti-Orphan Seating Lock (`409`), 18-Course Allergen Substitution & SVG Flavor Arc, Tea/Sake Pairing & `50.7kB` Entry. |
| **[Vanguard Fitness v2.0](https://github.com/tvt987/vanguard-fitness)** | **[Live Bio-Club](https://tvt987.github.io/vanguard-fitness/)** | `.NET 10` · **`81`** | 12-Week Periodized Mesocycle Builder (ACWR Safety Cap), Atomic Class Capacity Lock + Automatic FIFO Waitlist Promotion & `49kB` Entry. |
| **[Solaris Academy v2.0](https://github.com/tvt987/solaris-academy)** | **[Live Oxford LMS](https://tvt987.github.io/solaris-academy/)** | `FastAPI` · **`74`** | Daylight Oxford Academic Redesign, Step-Through Algorithm Visualizer (`Binary Search / QuickSort / Dijkstra`), Zero-Eval AST Grader (10/10 probes blocked) & HMAC Certs. |

---

### Core Hubs: Commercial Storefront, Portfolio Command Center & 12 Local-First Pro Tools

- **[TVT Studio v8.0](https://tvt987.github.io/tvt-studio/)** (`49/49` CI · `83.06 kB` lazy entry `-86.5%`): 26-System Commercial Storefront, Executive Admin Analytics (14d SVG Charts), Live Supabase Cloud CMS CRUD (`tvt_products`), 6-Table Zero-Trust RLS, Google OAuth & Live 1–3s MBBank ↔ SePay Auto-Pay.
- **[TVT Pro Tools v2.0](https://tvt987.github.io/tvt-tools/)** (`73/73` CI · `40.32 kB` lazy entry `-91.3%`): **12 Free 100% Client-Side Engines** — `VietQR EMVCo CRC16`, `VN Gross↔Net Law 109/2025`, `A4 PDF Invoice`, `Canvas WebP Cropper`, `Mortgage & Startup Runway`, **`B2B Freelance Rate & Deel/Wise Margin`**, `JSON→TS/C# 10/Pydantic`, `WebCrypto JWT HS256`, `Regex & ReDoS Guard`, `SQL Linter & SVG ERD`, `OKLCH WCAG AAA`, and **`JSON/OpenAPI Diff & SLA Latency Waterfall`**.
- **[Hyperion Atelier v11.0](https://tvt987.github.io/)** (`20/20` CI · `56.57 kB` lazy entry `-86.8%`): Global Freelance Portfolio featuring all 28 Showcase Apps, Direct Hero Contact + 3 Updated 2026-11-28 CV PDFs, Built-in Local Hybrid RAG AI Twin & JD Fit Matcher, and Distributed Systems Lab.

---

### Commercial Engineering Background & Remote Availability

- **Full-Stack Developer @ Con Cung Corporation** *(Nov 2023 – Present · 700+ Retail Stores Nationwide)*: Core **.NET 8/10 + Dapper + SQL Server + Redis** high-concurrency voucher & retail ERP workflows (`5,000+ RPS`, `ROWVERSION` optimistic concurrency, `0` double-spending), **Keycloak OAuth 2.0 / OIDC** RBAC, Vector Semantic Search & **n8n / MCP Agent** pipelines.
- **Frontend Intern @ FPT Software** *(Sep 2023 – Nov 2023)*: Angular / JavaScript e-commerce modules & REST API integration.
- **Direct Remote B2B / Freelance Contracting**: `UTC+7` with `4–6h` daily US (EST/PST) / EU overlap · B2B Invoice / Deel / Wise / Wire (`0` payroll compliance overhead) · **[tvt987.github.io](https://tvt987.github.io)** · **[tinhkun102@gmail.com](mailto:tinhkun102@gmail.com)** · Zalo/Phone `+84 931 467 024` · **[LinkedIn](https://www.linkedin.com/in/tr%C6%B0%C6%A1ng-v%C4%83n-t%C3%ACnh-651b12289/)**
