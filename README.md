# 👋 Hey, I’m Srijan

I build AI systems, agent workflows, and developer infra.

Lately I’ve been deep in Claude Code, Pi Agent, codex, subagents, retrieval-first context, and turning messy workflows into fast, LLM-native tools.

Been building since May 2016.

---

## 🛠️ Stack
- **Languages:** Python, Go, Bash, JavaScript, Rust
- **Infra & Ops:** Kubernetes, Terraform, Helm, Docker, Ansible, Flux
- **Cloud:** AWS, GCP, Azure
- **Data & Observability:** PostgreSQL, MySQL, Redis, MongoDB, Prometheus, Grafana, Loki, Tempo, VictoriaMetrics

## 🤖 AI build toolkit
- **Tools:** Pi Agent, Claude Code, codex, Cursor, OpenRouter
- **Trickery:** Subagents, Clean and Precise Context everytime, SKILL.md > MCPs for most cases.

---

## 📌 Selected Projects

### AI / Agentic workflows

| Project | Description |
|---|---|
| [xray](https://github.com/srijanshukla18/xray) | structural code intelligence for AI assistants using ast-grep. |
| [chorus-ai](https://github.com/srijanshukla18/chorus-ai.git) | Frontend-only LLM ensemble interface with bring-your-own OpenRouter/API keys and client-side multi-model workflows. |
| [chat-harvest](https://github.com/srijanshukla18/chat-harvest) | Local-first archive for AI chat traces across agents, designed as a substrate for DSPy/GEPA-style optimization loops. |
| [ita-kg](https://github.com/srijanshukla18/ita-kg.git) | Knowledge-graph representation of the Indian Income Tax Act so agents can traverse section-to-section relationships explicitly. |
| [hashlines-mcp](https://github.com/srijanshukla18/hashlines-mcp) | MCP server for hashline-anchored safe file read/edit workflows inspired by this archived write-up: https://web.archive.org/web/20260412162933/https://blog.can.ac/2026/02/12/the-harness-problem/ |
| [contextgraph](https://github.com/srijanshukla18/contextgraph) | (WIP) decision audit ledger for AI agents - captures "why" as queryable data. |
| [alpha](https://github.com/srijanshukla18/alpha) | (WIP) IAM policy rightsizing agent with AI-powered risk signals and instant rollback. |

### Infra / Systems

| Project | Description |
|---|---|
| [kubectl-smart](https://github.com/srijanshukla18/kubectl-smart) | turns noisy Kubernetes debugging into signal-first workflows. |
| [logsieve](https://github.com/srijanshukla18/logsieve) | log deduplication sidecar using Drain3 algorithm, reduces volumes ~90%. |
| [scx-slo](https://github.com/srijanshukla18/scx-slo) | eBPF CPU scheduler enforcing latency SLOs via Earliest Deadline First. |
| [softcron](https://github.com/srijanshukla18/softcron) | Kubernetes CronJob controller with Prometheus gating, pacing, and jitter. |


## 🎤 Talks
- **[Slow down Disk I/O](https://www.youtube.com/watch?v=y0gDoi63yRg)** → Flash talk on preventing `rm` from nuking SSDs, deep dive into `ionice`, `rsync`, and cgroups v2.  



💬 Reach me on [LinkedIn](https://www.linkedin.com/in/srijanshukla18) or check out my projects here.

---

### Other Fun Projects

| Project | Description |
|---|---|
| [podcast-watcher](https://github.com/srijanshukla18/podcast-watcher.git) | Open-source attempt to replicate Gemini-style long-form YouTube understanding: extract MP3 audio with ffmpeg, build timestamped transcripts, detect only meaningful frame changes, and feed the useful video/audio context into an LLM. I found the visual path added little value, so it effectively converged into an audio-first podcast/video understanding pipeline. |
| [netwatchrs](https://github.com/srijanshukla18/netwatchrs.git) | Rust network diagnostics toolkit I built while debugging inconsistent Wi‑Fi and suspected service-quality issues on my own machine; the goal was to see what was actually happening under the hood instead of relying on vague network status indicators. |
| [murmur](https://github.com/srijanshukla18/murmur.git) | Wispr Flow OSS - live streaming voice-to-text using whisper.cpp with Metal acceleration. |
| [wiki-in-a-box](https://github.com/srijanshukla18/wiki-in-a-box) | offline wikipedia with hybrid no‑index RAG - powered by gpt-oss:20b |
| [claude-memory-viz](https://github.com/srijanshukla18/claude-memory-viz.git) | memory visualization for Anthropic's Claude memory MCP. |
| [vigil](https://github.com/srijanshukla18/vigil) | Watch your codebase breathe; TUI for real-time file change monitoring with inline diffs |
| [extract-lessons-book](https://github.com/srijanshukla18/extract-lessons-book) | Ebook/document normalizer with optional OCR and LLM-generated advice + flowcharts. It also became a practical OCR evaluation project for me: for most books, plain PDF text extraction worked better than heavy OCR, so GLM OCR ended up as a fallback reserved for noisy pages, scans, or extraction failures. |
