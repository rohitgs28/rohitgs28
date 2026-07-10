# Rohit Gollarahalli

**Senior Software Engineer & Tech Lead · Toronto, Canada**

I build small, sharp developer tools — single binaries over clusters, clear docs
over clever code, and things you can actually run in five minutes. Currently
working across **Go, Rust, and Python**, with a focus on security and tooling for
the **Model Context Protocol (MCP)** ecosystem.

![Go](https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)

---

### 🔭 What I'm building

**[mcpx](https://github.com/rohitgollarahalli/mcpx)** — a lightweight **MCP security gateway** in Go.
Auth (incl. OAuth 2.1), rate limiting, tool-level access control, audit logging, and
tool-integrity pinning that defends against rug-pull tool mutation
([CVE-2025-54136](https://nvd.nist.gov/vuln/detail/CVE-2025-54136)) — all in a single
~10 MB binary with one YAML config. No Kubernetes, no Docker Desktop required.

**[querywise](https://github.com/rohitgollarahalli/querywise)** — an **AI-powered terminal
database client** in Rust. Ask in plain English, get SQL back; failed queries
self-heal and retry. Postgres / MySQL / SQLite, and it runs fully offline with Ollama.

**[claude-skills](https://github.com/rohitgollarahalli/claude-skills)** — a curated set of
reusable **Agent Skills** for software engineering and product work, installable as a
Claude Code plugin marketplace, with CI that validates every skill.

### 🌱 Open source

- **[cisco-ai-defense/skill-scanner](https://github.com/cisco-ai-defense/skill-scanner)** — security scanner for AI agent skills. Made SARIF output emit scan-root-relative artifact URIs ([#118](https://github.com/cisco-ai-defense/skill-scanner/pull/118)), taught the recursive scanner to discover symlinked skill directories ([#128](https://github.com/cisco-ai-defense/skill-scanner/pull/128)), and fixed a never-converging dataflow fixpoint that hung behavioral scans on large files — ~40× faster, with truncated analysis surfaced instead of silently passing ([#130](https://github.com/cisco-ai-defense/skill-scanner/pull/130)).
- **[stylelint/stylelint #8468](https://github.com/stylelint/stylelint/pull/8468)** — fixed `custom-property-pattern` false negatives for `@property` preludes.

### 📫 Reach me

[LinkedIn](https://www.linkedin.com/in/rohitgollarahalli/) · [rohit.gs28@gmail.com](mailto:rohit.gs28@gmail.com)
