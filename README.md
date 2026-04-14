# 👋 Hey, I’m Srijan

I’m a **builder** that builds software - mostly infra, AI, or infra-AI stuff these days.

Been building since May 2016.

---

## 🛠️ Technologies & Tools
- **Languages:** Python, Go, Bash, JavaScript
- **Cloud:** AWS, GCP, Azure
- **Infra & Ops:** Kubernetes, Terraform, Helm, Ansible, Flux, Docker 
- **Databases & Caches:** MySQL, PostgreSQL, Redis, MongoDB, Memcached
- **Observability:** Prometheus, Grafana, Loki, Tempo, VictoriaMetrics  

## 🛠️  LLM toolkit
- Pi Agent || Claude Code with Opus 4.6 || codex || Cursor > everything else
- Trickery: Subagents, Clean and Precise Context everytime, SKILL.md > MCPs for most cases.

---

## 📌 Projects

### AI/LLM

| Project | Description |
|---|---|
| [xray](https://github.com/srijanshukla18/xray) | structural code intelligence for AI assistants using ast-grep. |
| [contextgraph](https://github.com/srijanshukla18/contextgraph) | decision audit ledger for AI agents - captures "why" as queryable data. |
| [alpha](https://github.com/srijanshukla18/alpha) | IAM policy rightsizing agent with AI-powered risk signals and instant rollback. |
| [claude-memory-viz](https://github.com/srijanshukla18/claude-memory-viz) | memory visualization for Anthropic's Claude memory MCP. |
| [wiki-in-a-box](https://github.com/srijanshukla18/wiki-in-a-box) | offline wikipedia with hybrid no‑index RAG - powered by gpt-oss:20b |

### Kubernetes/Infra

| Project | Description |
|---|---|
| [kubectl-smart](https://github.com/srijanshukla18/kubectl-smart) | turns noisy Kubernetes debugging into signal-first workflows. |
| [logsieve](https://github.com/srijanshukla18/logsieve) | log deduplication sidecar using Drain3 algorithm, reduces volumes ~90%. |
| [scx-slo](https://github.com/srijanshukla18/scx-slo) | eBPF CPU scheduler enforcing latency SLOs via Earliest Deadline First. |
| [softcron](https://github.com/srijanshukla18/softcron) | Kubernetes CronJob controller with Prometheus gating, pacing, and jitter. |

### macOS

| Project | Description |
|---|---|
| [murmur](https://github.com/srijanshukla18/murmur) | live streaming voice-to-text using whisper.cpp with Metal acceleration. |


---

## 🎤 Talks
- **[Slow down Disk I/O](https://www.youtube.com/watch?v=y0gDoi63yRg)** → Flash talk on preventing `rm` from nuking SSDs, deep dive into `ionice`, `rsync`, and cgroups v2.  

---

## 🌱 A bit more
- Builder, heavy action-bias
- Co-founded a startup, led small teams, and still ship code. In another life.

---

💬 Reach me on [LinkedIn](https://www.linkedin.com/in/srijanshukla18) or check out my projects here.

---

## Project Inventory

### Public Repos (18)

| # | Project | Description |
|---|---|---|
| 1 | [podcast-watcher](https://github.com/srijanshukla18/podcast-watcher.git) | Open-source attempt to replicate Gemini-style long-form YouTube understanding: extract MP3 audio with ffmpeg, build timestamped transcripts, detect only meaningful frame changes, and feed the useful video/audio context into an LLM. I found the visual path added little value, so it effectively converged into an audio-first podcast/video understanding pipeline. |
| 2 | [netwatchrs](https://github.com/srijanshukla18/netwatchrs.git) | Rust network diagnostics toolkit I built while debugging inconsistent Wi-Fi and suspected service-quality issues on my own machine; the goal was to see what was actually happening under the hood instead of relying on vague network status indicators. |
| 3 | [kubectl-smart](https://github.com/srijanshukla18/kubectl-smart.git) | turns noisy Kubernetes debugging into signal-first workflows. |
| 4 | [softcron](https://github.com/srijanshukla18/softcron.git) | Kubernetes CronJob controller with Prometheus gating, pacing, and jitter. |
| 5 | [logsieve](https://github.com/srijanshukla18/logsieve.git) | log deduplication sidecar using Drain3 algorithm, reduces volumes ~90%. |
| 6 | [scx-slo](https://github.com/srijanshukla18/scx-slo.git) | eBPF CPU scheduler enforcing latency SLOs via Earliest Deadline First. |
| 7 | [chorus-ai](https://github.com/srijanshukla18/chorus-ai.git) | Frontend-only take on the LLM ensemble pattern: bring your own API/OpenRouter key, run multi-model workflows from the client side, and experiment with model comparison/choreography without needing to stand up a backend. |
| 8 | [alpha](https://github.com/srijanshukla18/alpha.git) | IAM policy rightsizing agent with AI-powered risk signals and instant rollback. |
| 9 | [contextgraph](https://github.com/srijanshukla18/contextgraph.git) | decision audit ledger for AI agents - captures "why" as queryable data. |
| 10 | [murmur](https://github.com/srijanshukla18/murmur.git) | live streaming voice-to-text using whisper.cpp with Metal acceleration. |
| 11 | [xray](https://github.com/srijanshukla18/xray.git) | structural code intelligence for AI assistants using ast-grep. |
| 12 | [wiki-in-a-box](https://github.com/srijanshukla18/wiki-in-a-box) | offline wikipedia with hybrid no‑index RAG - powered by gpt-oss:20b |
| 13 | [claude-memory-viz](https://github.com/srijanshukla18/claude-memory-viz.git) | memory visualization for Anthropic's Claude memory MCP. |
| 14 | [ita-kg](https://github.com/srijanshukla18/ita-kg.git) | Learning project to understand knowledge graphs by ingesting the Indian Income Tax Act into graph form, where every section-to-section reference becomes an explicit relationship that an AI agent can traverse, query, and reason over. |
| 15 | [vigil](https://github.com/srijanshukla18/vigil) | Watch your codebase breathe; TUI for real-time file change monitoring with inline diffs |
| 16 | [extract-lessons-book](https://github.com/srijanshukla18/extract-lessons-book) | Ebook/document normalizer with optional OCR and LLM-generated advice + flowcharts. It also became a practical OCR evaluation project for me: for most books, plain PDF text extraction worked better than heavy OCR, so GLM OCR ended up as a fallback reserved for noisy pages, scans, or extraction failures. |
| 17 | [chat-harvest](https://github.com/srijanshukla18/chat-harvest) | Local-first CLI to import and normalize AI chat transcripts from multiple agents into a single archive; I want to use it as the substrate for running DSPy/GEPA-style optimization loops over my own LLM chat traces. |
| 18 | [hashlines-mcp](https://github.com/srijanshukla18/hashlines-mcp) | MCP server for hashline-anchored safe file read/edit workflows |

### Private Repos (13)

| # | Project | Description |
|---|---|---|
| 1 | [f1-fun](https://github.com/srijanshukla18/f1-fun.git) | Infra/gameplay utility repo |
| 2 | [kund](https://github.com/srijanshukla18/kund.git) | Client-side infra tooling repo |
| 3 | [obelisk](https://github.com/srijanshukla18/obelisk.git) | Observability/infra repo |
| 4 | [ebpf-fabric](https://github.com/srijanshukla18/ebpf-fabric.git) | eBPF tooling / fabric layer |
| 5 | [signalfoundry](https://github.com/srijanshukla18/signalfoundry.git) | Signal/notification orchestration repo |
| 6 | [table-tennis-viz](https://github.com/srijanshukla18/table-tennis-viz.git) | Table tennis visualizer |
| 7 | [money](https://github.com/srijanshukla18/money.git) | Money/finance workflow tool |
| 8 | [droprush](https://github.com/srijanshukla18/droprush.git) | Shopify app for merchant recovery |
| 9 | [global-publish](https://github.com/srijanshukla18/global-publish.git) | generates platform-native content for 12 platforms from a single source. |
| 10 | [xp-tracker](https://github.com/srijanshukla18/xp-tracker.git) | XP tracker utility |
| 11 | [gtd-cc](https://github.com/srijanshukla18/gtd-cc) | Git-backed Getting Things Done for coding agents |
| 12 | [hermes-bus](https://github.com/srijanshukla18/hermes-bus) | Minimal private bus for two Hermes instances |
| 13 | [autoprio](https://github.com/srijanshukla18/autoprio) | Solopreneur Focus Engine & AI Agent PM |

