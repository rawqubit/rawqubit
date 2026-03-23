<div align="center">

# Srinikhil Chakilam

**AI Security Engineer · Systems Builder · Technical Writer**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/srinikhilchakilam)
[![X](https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/rawqubit)
[![Website](https://img.shields.io/badge/rawqubit.com-111111?style=flat-square&logo=cloudflare&logoColor=white)](https://rawqubit.com)
[![CommPlus](https://img.shields.io/badge/commplus.app-6366f1?style=flat-square&logo=sparkles&logoColor=white)](https://commplus.app)

</div>

---

I build tools at the intersection of **AI and security** — LLM pipelines that defend against prompt injection, passive recon engines, CVE triage systems, and entropy-based secrets scanners built to ship in production.

I also write deep technical posts on LinkedIn: LLM infrastructure (KV Cache, Ring Attention, Quantization), distributed systems, and AI security (RAG prompt injection, vector search internals).

Currently writing two books:

- **[ML Math: Zero to Hero](https://rawqubit.com/books/ml-math)** — 20-chapter interactive course covering ML mathematics from first principles. Scalars to diffusion models.
- **[Claude Code: The Complete Guide](https://rawqubit.com/books/claude-code)** — 17-chapter guide to mastering Claude Code professionally. Plan Mode through Agent Teams and cost optimization.

---

## Flagship Projects

| Project | What it does |
|---------|-------------|
| [**llmguard-cli**](https://github.com/rawqubit/llmguard-cli) | Real-time prompt injection + jailbreak detector. Multi-layer: 20+ heuristic signatures + LLM meta-reasoning. HTTP API included. 0.94 F1 on adversarial benchmarks. |
| [**gitleaks-ai**](https://github.com/rawqubit/gitleaks-ai) | AI-enhanced secrets scanner. Shannon entropy analysis + LLM false-positive elimination. ~73% fewer false positives vs regex-only. >99% recall. |
| [**shadowmap**](https://github.com/rawqubit/shadowmap) | Passive attack surface mapper. Zero active scanning — cert transparency, DNS, AI risk analysis. Finds what shodan misses. |
| [**cvewatch**](https://github.com/rawqubit/cvewatch) | CVE monitoring daemon. Polls NVD API 2.0, filters by your stack using AI relevance scoring, delivers enriched Slack/Discord alerts. |
| [**yaraforge**](https://github.com/rawqubit/yaraforge) | AI-powered YARA rule generator and optimizer. Built for threat hunters and malware analysts who need rules that actually compile and match. |
| [**spring-api-scanner**](https://github.com/rawqubit/spring-api-scanner) | REST API security scanner for OpenAPI 3.x specs. AI-powered OWASP API Top 10 vulnerability analysis. |
| [**ai-siem-triage**](https://github.com/rawqubit/ai-siem-triage) | SOC alert triage assistant. Classifies SIEM events, prioritizes by severity, and recommends response actions. |

---

## AI Security Arsenal

Tools for analysts, researchers, and defenders.

| Tool | What it does |
|------|-------------|
| [ai-cve-analyzer](https://github.com/rawqubit/ai-cve-analyzer) | CVE risk assessment with NVD data — attack scenarios, patch urgency, remediation |
| [ai-threat-intel](https://github.com/rawqubit/ai-threat-intel) | Raw intel → TTPs, IOCs, MITRE ATT&CK mappings |
| [ai-phishing-detector](https://github.com/rawqubit/ai-phishing-detector) | URL and email phishing analysis with heuristic + LLM reasoning |
| [ai-malware-explainer](https://github.com/rawqubit/ai-malware-explainer) | Sandbox report → MITRE ATT&CK behavior mapping |
| [ai-pentest-report](https://github.com/rawqubit/ai-pentest-report) | Raw pentest findings → professional client-ready reports |
| [ai-packet-analyzer](https://github.com/rawqubit/ai-packet-analyzer) | pcap / tcpdump → C2, exfiltration, lateral movement detection |
| [ai-secrets-scanner](https://github.com/rawqubit/ai-secrets-scanner) | Codebase scan → hardcoded API keys, credentials, sensitive data |

---

## AI Developer Toolkit

Tools that automate the software development lifecycle.

| Tool | What it does |
|------|-------------|
| [ai-code-reviewer](https://github.com/rawqubit/ai-code-reviewer) | Automated code review — bugs, best practices, security issues |
| [ai-commit-gen](https://github.com/rawqubit/ai-commit-gen) | Staged diff → conventional commit message |
| [ai-test-gen](https://github.com/rawqubit/ai-test-gen) | Source file → unit tests for multiple frameworks |
| [ai-doc-gen](https://github.com/rawqubit/ai-doc-gen) | Code → structured documentation |
| [ai-sql-gen](https://github.com/rawqubit/ai-sql-gen) | Natural language → SQL query |
| [ai-log-analyzer](https://github.com/rawqubit/ai-log-analyzer) | Log files → error patterns and anomaly detection |
| [ai-regex-explainer](https://github.com/rawqubit/ai-regex-explainer) | Regex → plain English explanation |
| [ai-shell-assistant](https://github.com/rawqubit/ai-shell-assistant) | Natural language → shell command |
| [ai-api-mock](https://github.com/rawqubit/ai-api-mock) | Schema / description → realistic API mock responses |
| [ai-readme-optimizer](https://github.com/rawqubit/ai-readme-optimizer) | README → improved clarity, structure, and completeness |

---

## Rust Utilities

Systems-level CLI tools built for precision and speed.

| Tool | What it does |
|------|-------------|
| [rust-grep-tool](https://github.com/rawqubit/rust-grep-tool) | Blazing fast recursive file search with pattern highlighting |
| [rust-sys-monitor](https://github.com/rawqubit/rust-sys-monitor) | Real-time CPU/Memory/Disk monitor with visual bars |
| [rust-config-transformer](https://github.com/rawqubit/rust-config-transformer) | JSON ↔ YAML ↔ TOML format converter |

---

## Java / Spring

| Project | What it does |
|---------|-------------|
| [spring-jwt-auth](https://github.com/rawqubit/spring-jwt-auth) | Production-ready JWT auth microservice — refresh rotation, RBAC, Spring Boot 3.2 |
| [spring-api-scanner](https://github.com/rawqubit/spring-api-scanner) | OpenAPI 3.x security scanner — OWASP API Top 10 analysis |
| [springboot-microservice](https://github.com/rawqubit/springboot-microservice) | Multi-cloud Spring Boot microservice — service registry, cloud gateway |

---

## Recent Writing

Technical deep-dives published on [LinkedIn](https://linkedin.com/in/srinikhilchakilam/recent-activity/all/) — systems design and LLM infrastructure explained from first principles.

| Post | Topic |
|------|-------|
| [Ring Attention: How 1M-Token Contexts Work](https://linkedin.com/in/srinikhilchakilam/recent-activity/all/) | Distributed Systems |
| [LLM Quantization: From 4 A100s to 1 GPU](https://linkedin.com/in/srinikhilchakilam/recent-activity/all/) | LLM Inference |
| [KV Cache From First Principles](https://linkedin.com/in/srinikhilchakilam/recent-activity/all/) | LLM Infrastructure |
| [Zero-Click Prompt Injection in RAG Agents](https://linkedin.com/in/srinikhilchakilam/recent-activity/all/) | AI Security |
| [Speculative Decoding: The Serialization Problem](https://linkedin.com/in/srinikhilchakilam/recent-activity/all/) | LLM Inference |
| [Vector Search From First Principles](https://linkedin.com/in/srinikhilchakilam/recent-activity/all/) | RAG |
| [How Kafka Actually Works](https://linkedin.com/in/srinikhilchakilam/recent-activity/all/) | Distributed Systems |
| [LangChain From First Principles](https://linkedin.com/in/srinikhilchakilam/recent-activity/all/) | AI Engineering |
| [All Authentication Methods Explained](https://linkedin.com/in/srinikhilchakilam/recent-activity/all/) | Security |
| [Karpathy's autoresearch: 47 Experiments While He Slept](https://linkedin.com/in/srinikhilchakilam/recent-activity/all/) | ML Research |

---

## GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=rawqubit&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=rawqubit&layout=compact&theme=github_dark&hide_border=true&langs_count=8)

</div>

---

<div align="center">

**The best security tool is the one that fits your workflow.**

[rawqubit.com](https://rawqubit.com) · [commplus.app](https://commplus.app)

</div>
