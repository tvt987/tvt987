<h1 align="center">Truong Van Tinh — TVT Studio</h1>
<h3 align="center">Principal Full-Stack .NET 10 / Python FastAPI & Applied AI Systems Architect | 10 Full-Stack Production Monorepos · 29 Live Web Apps · 2,003 Automated Tests Green</h3>

<p align="center">
  <a href="https://tvt987.github.io" target="_blank"><img src="https://img.shields.io/badge/Portfolio-Hyperion%20v10.0-6366f1?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Interactive Portfolio" /></a>
  <a href="https://tvt987.github.io/tvt-studio/" target="_blank"><img src="https://img.shields.io/badge/TVT%20Studio%20v7.5-26%20Systems%20%2B%20CMS-ff4d00?style=for-the-badge&logo=vercel&logoColor=white" alt="TVT Studio Storefront" /></a>
  <a href="https://tvt987.github.io/orbitalflow-saas/" target="_blank"><img src="https://img.shields.io/badge/OrbitalFlow-.NET%2010%20B2B%20SaaS-4f46e5?style=for-the-badge&logo=dotnet&logoColor=white" alt="OrbitalFlow SaaS" /></a>
  <a href="https://tvt987.github.io/vectradoc-rag/" target="_blank"><img src="https://img.shields.io/badge/VectraDoc-FastAPI%20Hybrid%20RAG-9b2c2c?style=for-the-badge&logo=fastapi&logoColor=white" alt="VectraDoc AI RAG" /></a>
  <a href="https://tvt987.github.io/fleetpulse-gis/" target="_blank"><img src="https://img.shields.io/badge/FleetPulse-.NET%2010%20GIS%20CVRP-0d9488?style=for-the-badge&logo=mapbox&logoColor=white" alt="FleetPulse GIS" /></a>
  <a href="https://tvt987.github.io/medcore-ehr/" target="_blank"><img src="https://img.shields.io/badge/MedCore-FastAPI%20HL7%20FHIR-0369a1?style=for-the-badge&logo=heart&logoColor=white" alt="MedCore Clinical EHR" /></a>
  <a href="mailto:tinhkun102@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

### 10 Full-Stack Production Monorepos (`.NET 10` / `Python FastAPI` + `React 19` + Docker + OpenAPI 3.1 + ADRs)

Every repository below ships a **real compiled & locally tested backend** (`dotnet test` / `pytest`), multi-stage `Dockerfile` + `docker-compose.yml`, OpenAPI 3.1 specification, Architecture Decision Records (`ADR-001/002`), code-split `React.lazy` bundles (`60–143 kB` entry), Strict CSP, and `0`-error Playwright E2E at `1440px` & `390px`.

| Full-Stack Monorepo | Live Production Demo | Backend Stack & Verified Test Suite | Core Engineering Capabilities |
| :--- | :--- | :--- | :--- |
| **[OrbitalFlow SaaS v2.0](https://github.com/tvt987/orbitalflow-saas)** | **[Live B2B SaaS](https://tvt987.github.io/orbitalflow-saas/)** | **`.NET 10` Clean Arch** · `85` Vitest + `18` xUnit = **`103` Green** | Multi-tenant orgs, 4-role **RBAC** enforcement, Pointer Drag-Drop Kanban + **`Ctrl+Z` Undo/Redo**, Issue Drawer + Safe AST Markdown, **CPM Gantt** arrows, **2-Tab Realtime BroadcastChannel**, Stripe Proration & HMAC-SHA256 Webhooks. |
| **[VectraDoc AI v2.0](https://github.com/tvt987/vectradoc-rag)** | **[Live Hybrid RAG](https://tvt987.github.io/vectradoc-rag/)** | **`Python 3.12 FastAPI`** · `98` Vitest + `22` Pytest = **`120` Green** | Client-side **PDF FlateDecode parser**, **Okapi BM25 + TF-IDF Cosine + RRF + Reranker** (`Recall@5 100%`, `MRR 100%`, `NDCG@5 94.9%`), 4-Way A/B Comparator, Chunk Minimap, Luhn PII Guard, Optional RAM-only BYOK Streaming. |
| **[FleetPulse GIS v2.0](https://github.com/tvt987/fleetpulse-gis)** | **[Live GIS Dispatch](https://tvt987.github.io/fleetpulse-gis/)** | **`.NET 10` + PostGIS/MQTT** · `93` Vitest + `20` xUnit = **`113` Green** | Interactive Vector Corridor Map, **Click-to-Add Stops** re-solving **CVRP Clarke-Wright + 2-Opt (`-28.6%` km in `<1ms`)**, `08:00–17:00` Shift Scrub Timeline, Live Geofence Radius Editor, Cold-Chain `-18°C` physics & A4 Manifest. |
| **[MedCore EHR v2.0](https://github.com/tvt987/medcore-ehr)** | **[Live Clinical EHR](https://tvt987.github.io/medcore-ehr/)** | **`Python 3.12 FastAPI` FHIR** · `92` Vitest + `22` Pytest = **`114` Green** | 3-Column Hospital Workstation, **3-Channel Canvas Monitor (`ECG Lead-II + SpO2 + Capnography EtCO2`)**, RCP NEWS2 (`0–20`), **1-Click Safe Drug Auto-Substitute**, Cockcroft-Gault CrCl, Patient Admission Wizard & **HL7 FHIR R4 `$everything`**. |
| **[AegisPulse SRE v4.0](https://github.com/tvt987/aegispulse-distributed-sre)** | **[Live SRE & Race Arena](https://tvt987.github.io/aegispulse-distributed-sre/)** | **`.NET 10` + OTel + `k6`** · `83` Vitest + `35` Backend = **`118` Green** | **Living Con Cung 700-Store Proof**: **500-Req Concurrent Voucher Race Arena** (Naive leak vs **Redis Lua + SQL Server `ROWVERSION` `0.00%` double-spend at `p99 36.6ms`**), 100-way parallel xUnit race test, `k6` 5K RPS script & 5-Region Raft Chaos. |
| **[Helios Quant v2.0](https://github.com/tvt987/helios-quant-terminal)** | **[Live Quant Exchange](https://tvt987.github.io/helios-quant-terminal/)** | **`Python 3.12 FastAPI` Quant** · `127` Vitest + `26` Pytest = **`153` Green** | Deterministic **FIFO L2 Orderbook (`15×15`)** across 6 markets (incl. `VN30F1M`), 60fps Canvas Candlesticks, **`6×6` Sharpe Grid-Search Heatmap (`7.7ms`)**, 6-Asset Rolling Correlation Matrix & Order-Flow Imbalance Depth SVG. |
| **[AeroForge 3D v2.0](https://github.com/tvt987/aeroforge-digital-twin)** | **[Live 3D CAD SCADA](https://tvt987.github.io/aeroforge-digital-twin/)** | **`.NET 10` SCADA/FFT** · `105` Vitest + `28` xUnit = **`133` Green** | Precision Daylight CAD Workstation, Three.js 3D Factory, **Programmable 6-Axis CNC G-Code Sequencer** (`Z < 120mm` collision interlock, `.nc` export), FLIR Ironbow IR, ISO 10816 FFT + Maintenance Downtime ROI & EVN 3-Tier BESS. |
| **[Velox EV Motors v4.0](https://github.com/tvt987/velox-ev-motors)** | **[Live 3D EV Hypercar](https://tvt987.github.io/velox-ev-motors/)** | **`.NET 10` Dealership API** · `89` Vitest + `18` xUnit = **`107` Green** | Widebody sculpted 3D Hypercar (Matrix LED DRL, 14-fin OLED tailbar, glowing ceramic calipers, velocity active rear wing), **3-Circuit Physics Telemetry Lab**, 2.08s Launch Synth & **12-way parallel Idempotent Test-Drive Slot Locker (`409`)**. |
| **[Chronos 3D Watch v2.0](https://github.com/tvt987/chronos-horology)** | **[Live 3D Tourbillon](https://tvt987.github.io/chronos-horology/)** | **`.NET 10` Crypto Vault** · `106` Vitest + `20` xUnit = **`126` Green** | Geneva Ivory & Racing Emerald Boutique, 60fps Mechanical 3D Tourbillon (`28,800 vph`), **Witschi Acoustic Timegrapher Canvas**, 7-Layer Exploded Calibre Inspector & **HMAC-SHA256 Digital Authenticity Passport API**. |
| **[PulsePOS F&B v3.0](https://github.com/tvt987/pulse-pos-fnb)** | **[Live POS ↔ KDS SaaS](https://tvt987.github.io/pulse-pos-fnb/)** | **`.NET 10` Multi-Branch POS** · `63` Vitest + `24` xUnit = **`87` Green** | Sunlit Daylight Roastery POS, **Real 2-Tab Live POS ↔ Kitchen KDS Sync (`<50ms`)**, Interactive Floorplan Table Designer, **Atomic Recipe Stock Deduction (`409` + Auto-PO)** & NAPAS EMVCo VietQR CRC-16 API. |

---

### Storefront, Free Tooling Hub, Portfolio & 16 Additional Live Vertical Apps (`29 Live Apps Total`)

- **[TVT Studio v7.5](https://tvt987.github.io/tvt-studio/)** — 26-System Commercial Storefront, Executive Admin Analytics (14d SVG Charts), Live Supabase Cloud CMS CRUD, 1–3s MBBank ↔ SePay Auto-Pay & Source Vault (`47/47` CI).
- **[Hyperion Atelier v10.0](https://tvt987.github.io/)** — Global Freelance Portfolio featuring 28 Live Systems, Direct Hero Contact + 3 CV PDFs, AI Twin JD Fit Matcher & Live Compute Lab (`17/17` CI).
- **[TVT Pro Tools](https://tvt987.github.io/tvt-tools/)** — 10 Free 100% Local-First Business & Engineering Tools (`VietQR CRC16`, `VN Gross↔Net 2026`, `A4 Invoice`, `WebP Cropper`, `Mortgage/Runway`, `JSON→TS/C#/Pydantic`, `Web Crypto JWT`, `Regex ReDoS`, `SQL SVG ERD`, `OKLCH AAA` — `41/41` CI).
- **16 Additional Live Industry Platforms (`100% Strict CSP`, `0` Errors, `29/29` Clean)**: [Verdict Graph v3.0](https://tvt987.github.io/verdict-graph/) · [Nexus Lake v3.0](https://tvt987.github.io/nexus-lake/) · [Atelier Canvas v4.0](https://tvt987.github.io/atelier-canvas/) · [Zenith Wealth v2.0](https://tvt987.github.io/zenith-wealth-fintech/) · [CodaHR 2026 v2.0](https://tvt987.github.io/coda-hr-payroll/) · [Meridian Logistics v2.0](https://tvt987.github.io/meridian-logistics/) · [Aurelia Resort v2.0](https://tvt987.github.io/aurelia-resort/) · [Maison Véra v4.0](https://tvt987.github.io/maison-vera/) · [Kinetix PropTech v2.0](https://tvt987.github.io/kinetix-proptech/) · [Aether Acoustics v3.0](https://tvt987.github.io/aether-acoustics/) · [Nordic Home Atelier](https://tvt987.github.io/nordic-home-atelier/) · [Solaris Academy LMS](https://tvt987.github.io/solaris-academy/) · [Veritas Legal Studio](https://tvt987.github.io/veritas-legal-firm/) · [Lumina MedSpa v2.0](https://tvt987.github.io/lumina-medspa/) · [Kuro Omakase](https://tvt987.github.io/kuro-omakase/) · [Vanguard Fitness](https://tvt987.github.io/vanguard-fitness/).

---

### Commercial Engineering Background

- **Full-Stack Developer @ Con Cung Corporation** *(Nov 2023 – Present · 700+ Retail Stores Nationwide)*:
  - Engineered core **.NET 8/10 + Dapper + SQL Server + Redis** high-concurrency voucher & retail ERP workflows (**5,000+ RPS**, Optimistic Concurrency `ROWVERSION`, zero double-spending).
  - Implemented **Keycloak OAuth 2.0 / OIDC** RBAC, **Hybrid Vector Semantic Search**, and **n8n / MCP Agent** automation pipelines.
- **Frontend Intern @ FPT Software** *(Sep 2023 – Nov 2023)*: Angular / JavaScript e-commerce modules & REST API integration.

---

### Direct Freelance & Remote Contract Inquiry

- **Portfolio & 3 Specialized CVs**: [tvt987.github.io](https://tvt987.github.io)
- **Website Storefront & Instant Quote**: [tvt987.github.io/tvt-studio](https://tvt987.github.io/tvt-studio/)
- **Email**: [tinhkun102@gmail.com](mailto:tinhkun102@gmail.com) · **Hotline / Zalo**: `+84 931 467 024`
- **LinkedIn**: [linkedin.com/in/trương-văn-tình-651b12289](https://www.linkedin.com/in/tr%C6%B0%C6%A1ng-v%C4%83n-t%C3%ACnh-651b12289/)
- **Availability**: Remote B2B / Deel / Wire (`UTC+7` with `4–6h` daily US/EU overlap · Fixed-Scope Projects or `$50–$75/hr`)
