I build AI and data systems that have to be right: LLMs that can only execute validated actions, pipelines gated by golden tests, and agents whose guardrails are regression-tested.

### Now · AI Engineer at [got2eat](https://got2eat.app) · Aug 2026 – present

A community map of complete meals under $15 in NYC, live on the web and on iOS via TestFlight. **Base44 Accelerator Champions.** The code is private, so here is what I own:

- **LLM assistant:** a server-side model turns free-text meal and transit requests into a typed query. Off-schema output is discarded and rate limits fail closed: the model proposes, validation disposes.
- **Transit routing:** subway and PATH routing derived from public GTFS timetables, with door-to-door, one-transfer ETAs drawn on MapLibre layers.
- **iOS app:** Capacitor shell with push notifications and native Apple / Google sign-in, shipping through TestFlight.
- **Partner side:** a restaurant dashboard for listings, deals, and occupancy, plus a loyalty stamp-card pilot I redesigned after watching staff use the first version.
- **Data repairs:** reversible, audit-logged fixes with dry runs and read-back verification.

### Before · Software Engineer Intern at SAIL GTX · Sep 2025 – May 2026

An AI-native trade-compliance startup backed by Cornell Tech's Runway Startup Studio. Private code.

- Solely owned the HTS duty-calculation pipeline (Python, SQLite, Parquet, FastAPI), from versioned ingestion through duty math.
- Designed a deterministic tariff-revision engine: ≥95% accuracy, 1,000+ relevant changes surfaced per release, across 166 HTS releases (2018–2026).
- Drove 97% pipeline run reliability. Golden-test harnesses caught tariff-stacking regressions before customer releases.
- Co-built, with the CTO, a production classification model that maps product descriptions to tariff codes.

**Earlier:** Tagwebs Technologies (2023–24). Shipped 15+ Python / Django apps for international clients and provisioned 500+ schools onto the [Edliy.com](https://edliy.com) EdTech platform in 90 days.

### Published

**American Sign Language Alphabet Recognition Using Teachable Machine** · IEEE ICCCNT 2024 · [IEEE Xplore](https://ieeexplore.ieee.org/document/10725877)<br>
<sub>Co-author. IEEE prints my surname as "Palanisamy".</sub>

### Toolkit

| | |
|---|---|
| **AI / ML** | PyTorch · Hugging Face Transformers · LoRA / PEFT · RAG · agents · MCP · Claude Agent SDK |
| **Data** | Python · SQL · PySpark · Dagster · dbt · DuckDB · SQLite · Parquet |
| **Product** | TypeScript · React · FastAPI · Deno · MapLibre GL · GTFS · Capacitor |
| **Quality** | pytest · golden tests · schema validation · GitHub Actions |

---

**Open to full-time AI / ML engineering roles in New York.** US work-authorized (F-1 OPT, STEM-OPT eligible) · MS Computer Engineering, NYU, GPA 3.965 · [Resume (PDF)](https://nishanthgp.me/resume.pdf)
