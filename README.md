# Seth Croot

**Integration Analyst** who directs autonomous agents to build and operate production systems. Vancouver, BC.

I don't write every line of code myself. I direct AI agents that do. My skill is in the orchestration: defining architecture, specifying behaviour, reviewing output, and holding the system accountable. The repos on this profile were built this way. The code is real, the systems run in production, and I'm responsible for all of it.

---

## Projects

### [Agent Automation Suite](https://github.com/SethCroot/agent-automation-suite)
Cron-driven automation layer for AI agent platforms. System health monitoring with auto-recovery, CalDAV calendar integration, encrypted backup rotation, memory lifecycle management, and vault integrity auditing. Silent by design: scripts produce output only when something needs attention. **Bash, Python.**

### [Agentic Job Search](https://github.com/SethCroot/agentic-job-search)
LLM-powered job discovery and scoring pipeline. Scrapes job boards, enriches descriptions, scores fit against a resume using configurable weighted rubrics, and generates tailored cover letters as PDFs. **Python, FastAPI, SQLite, multi-provider LLM orchestration.**

### [Apple Watch Health MCP](https://github.com/SethCroot/apple-watch-health-mcp) (fork)
Fork of the original MCP server for Apple Watch health data. Added a self-hosted Python backend (677 lines, pure stdlib, SQLite persistence) that accepts Health Auto Export webhooks directly, eliminating the paid Cloudflare Workers dependency. Extended the Worker to accept HAE payloads alongside the original format, backwards compatible. Debugged auth header and payload format mismatches against real HAE v2 exports. **Python, Cloudflare Workers, MCP.**

### [ApplyPilot (fork)](https://github.com/SethCroot/ApplyPilot)
Fork of [Pickle-Pixel/ApplyPilot](https://github.com/Pickle-Pixel/ApplyPilot). Added a 7th pipeline stage that exports scored jobs to an Obsidian vault as structured markdown with YAML frontmatter, and rewrote the scoring engine with a weighted location/experience/skills rubric. **Python.**

---

## Background

5 years at Cotton On Group (Australia) as Integration Analyst, managing 80+ enterprise integrations across 9 countries. REST API triage, vendor coordination (Oracle, UKG, Maersk, Adyen), major incident response, and change impact assessment for global retail, payroll, and logistics systems.

That background is why agent orchestration works for me. I know how systems break, how APIs behave under load, how to diagnose a failing integration at 2am. The agents handle the implementation. I handle the judgment.

**Education:** B.IT (Cybersecurity), Deakin University | Business Analyst Certification, RMIT

---

## Tech Stack

| Domain | Technologies |
|--------|-------------|
| AI / LLM | Agent orchestration, prompt engineering, multi-provider workflows, MCP |
| Languages | Python, Bash, SQL, TypeScript |
| Backend | FastAPI, SQLite, PostgreSQL, REST APIs, OAuth 2.0 |
| Infrastructure | Linux, Docker, systemd, Cloudflare Tunnel, Tailscale |
| Integration | API troubleshooting, vendor management, change impact assessment |

---

## Currently

Building AI automation systems. Open to **AI automation, agent orchestration, and integration engineering** roles in Vancouver, BC.
