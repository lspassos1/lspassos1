<div align="center">

# Lucas Passos

### Builder — application security · OSINT & intelligence dashboards · geospatial data viz

[Mapa da Violência Brasil](https://mapa-da-violencia-brasil.vercel.app) · [GitHub](https://github.com/lspassos1)

</div>

---

### 👋 Overview

I build data-heavy products end to end — from typed RPC backends and statistical scoring to map-based frontends — with a strong focus on **application security** and on turning **messy public data into trustworthy intelligence**.

Most of my recent work lives at the intersection of **OSINT, geospatial visualization, and security hardening**: near-real-time dashboards that aggregate noisy sources (news, official datasets, third-party APIs) and present them **honestly** — always separating verified *signal* from unverified *indication*.

---

### 🧭 Specialties

- **Application security & hardening** — SSRF/XSS mitigation, CSP / COOP-COEP, request-spoofing defenses, sandbox isolation by nonce, dependency & CVE patching.
- **Full-stack feature delivery** — Protocol Buffers + typed RPC services, statistical scoring, reusable widgets, maps, and the test suites around them.
- **Geospatial & data viz** — MapLibre GL / deck.gl, choropleth layers, near-real-time georeferenced data.
- **OSINT & intelligence pipelines** — multi-source ingestion, keyword-first + LLM classification, deterministic deduplication, source-credibility framing.

---

### 🌐 Open source

**Core contributor to [koala73/worldmonitor](https://github.com/koala73/worldmonitor)** — the open-source real-time global intelligence dashboard (AGPL-3.0). I shipped the **"Resilience" intelligence dimension end to end**: proto service + stub handlers, country dimension scorers and shared statistical utilities, score/ranking RPC handlers with premium gating, a reusable deep-dive widget with a **choropleth map layer**, and dedicated scorer/ranking test suites. I also contributed extensive **security hardening** across the gateway, sidecar and widget layers (private-target fetch blocking, header-spoofing fixes, sandbox nonce gating, CSP headers, base-image CVE patches).

---

### 📌 Featured project

**[Mapa da Violência Brasil](https://github.com/lspassos1/mapa-da-violencia-brasil)** — a near-real-time **gun-violence radar** for Brazil: live georeferenced shootings (Fogo Cruzado) + a national **OSINT news layer** (keyword-first + dictionary geocoding, no LLM where avoidable) + an **anomaly radar** that flags where official statistics may be unreliable. Built with Next.js · TypeScript · MapLibre · Supabase. AGPL-3.0.

---

### 🛠 Stack

TypeScript, Next.js, React, Node.js, Protocol Buffers / typed RPC, PostgreSQL / Supabase, MapLibre GL · deck.gl, Tailwind CSS, Python (data/ETL), Docker, Vercel.

---

<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=lspassos1&show_icons=true&theme=github_dark&hide_border=true&bg_color=0D1117&text_color=C9D1D9&icon_color=58A6FF" width="48%" alt="GitHub stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=lspassos1&layout=compact&theme=github_dark&hide_border=true&bg_color=0D1117&text_color=C9D1D9&title_color=58A6FF&langs_count=8" width="48%" alt="Top languages" />
</div>
