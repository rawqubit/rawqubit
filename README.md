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
| [**llmguard-cli**](https://github.com/rawqubit/llmguard-cli) | Real-time prompt injection + jailbreak detector. Multi-layer: 20+ heuristic signatures + LLM meta-reasoning. HTTP API included. |
| [**gitleaks-ai**](https://github.com/rawqubit/gitleaks-ai) | AI-enhanced secrets scanner. Shannon entropy analysis + LLM false-positive elimination. ~73% fewer false positives vs regex-only. |
| [**shadowmap**](https://github.com/rawqubit/shadowmap) | Passive attack surface mapper. Zero active scanning — cert transparency logs, DNS enumeration, AI risk analysis. |
| [**cvewatch**](https://github.com/rawqubit/cvewatch) | CVE monitoring daemon. Polls NVD API 2.0, filters by your stack using AI relevance scoring, delivers Slack/Discord alerts. |
| [**yaraforge**](https://github.com/rawqubit/yaraforge) | AI-powered YARA rule forge. Generates, validates, and deploys rules to Elastic, Splunk, and standalone YARA from one CLI. |
| [**ai-siem-triage**](https://github.com/rawqubit/ai-siem-triage) | SOC alert triage assistant. Classifies SIEM events, prioritizes by severity, recommends response actions. |

---

## AI Security Tools

Tools for analysts, researchers, and defenders.

| Tool | What it does |
|------|-------------|
| [ai-cve-analyzer](https://github.com/rawqubit/ai-cve-analyzer) | CVE risk assessment with NVD data — attack scenarios, patch urgency, remediation guidance |
| [ai-threat-intel](https://github.com/rawqubit/ai-threat-intel) | Raw intel reports → TTPs, IOCs, MITRE ATT&CK mappings |
| [ai-phishing-detector](https://github.com/rawqubit/ai-phishing-detector) | URL and email phishing analysis with heuristic + LLM reasoning |
| [ai-malware-explainer](https://github.com/rawqubit/ai-malware-explainer) | Sandbox reports → MITRE ATT&CK behavior mapping |
| [ai-pentest-report](https://github.com/rawqubit/ai-pentest-report) | Raw pentest findings → professional client-ready reports |
| [ai-packet-analyzer](https://github.com/rawqubit/ai-packet-analyzer) | pcap / tcpdump → C2, exfiltration, and lateral movement detection |
| [ai-secrets-scanner](https://github.com/rawqubit/ai-secrets-scanner) | Detects hardcoded API keys, credentials, and sensitive data in source code |
| [ai-log-analyzer](https://github.com/rawqubit/ai-log-analyzer) | Log file analysis — error pattern detection, anomaly identification, root cause hints |

---

## AI Developer Tools

| Tool | What it does |
|------|-------------|
| [ai-code-reviewer](https://github.com/rawqubit/ai-code-reviewer) | Automated code review — bugs, performance issues, style suggestions |
| [ai-test-gen](https://github.com/rawqubit/ai-test-gen) | Generates unit tests for any code file |
| [ai-commit-gen](https://github.com/rawqubit/ai-commit-gen) | AI-powered Git commit messages from staged changes |
| [ai-doc-gen](https://github.com/rawqubit/ai-doc-gen) | Generates documentation from code files |
| [ai-sql-gen](https://github.com/rawqubit/ai-sql-gen) | Natural language → SQL queries |
| [ai-shell-assistant](https://github.com/rawqubit/ai-shell-assistant) | Shell script help, debugging, and command explanation |
| [ai-terminal-assistant](https://github.com/rawqubit/ai-terminal-assistant) | Terminal assistant for debugging and command lookup |
| [ai-regex-explainer](https://github.com/rawqubit/ai-regex-explainer) | Explains any regular expression in plain English |
| [ai-readme-optimizer](https://github.com/rawqubit/ai-readme-optimizer) | Improves README clarity, completeness, and structure |
| [ai-api-mock](https://github.com/rawqubit/ai-api-mock) | AI-powered mock API response generator for testing |

---

## Rust CLI Tools

| Project | What it does |
|---------|-------------|
| [rust-grep-tool](https://github.com/rawqubit/rust-grep-tool) | Fast CLI file search built in Rust — ripgrep-style pattern matching |
| [rust-config-transformer](https://github.com/rawqubit/rust-config-transformer) | Convert config files between JSON, YAML, and TOML formats |
| [rust-sys-monitor](https://github.com/rawqubit/rust-sys-monitor) | Real-time system resource monitor — CPU, memory, disk in the terminal |

---

## Java / Spring

| Project | What it does |
|---------|-------------|
| [spring-api-scanner](https://github.com/rawqubit/spring-api-scanner) | AI-powered REST API security scanner — analyzes OpenAPI 3.x specs for OWASP API Top 10 vulnerabilities |
| [spring-jwt-auth](https://github.com/rawqubit/spring-jwt-auth) | Production-ready JWT auth microservice — refresh token rotation, RBAC, Spring Boot 3.2 |

---

## Research & ML

| Project | What it does |
|---------|-------------|
| [macro-crypto-correlator](https://github.com/rawqubit/macro-crypto-correlator) | Global macro indicators vs stablecoin liquidity and crypto volatility |
| [stable-depeg-predictor](https://github.com/rawqubit/stable-depeg-predictor) | AI early-warning system for stablecoin de-pegging events |
| [yield-alpha-optimizer](https://github.com/rawqubit/yield-alpha-optimizer) | AI-driven yield optimization for DeFi using on-chain data and ML forecasting |
| [nano-mind-reader](https://github.com/rawqubit/nano-mind-reader) | Mechanistic interpretability on a tiny GPT — visualizing internal thought patterns |
| [Image-Classifier](https://github.com/rawqubit/Image-Classifier) | Transfer learning image classifier with TensorFlow/Keras for multi-class recognition |

---

## Open Source & Web

| Project | What it does |
|---------|-------------|
| [devdash](https://github.com/rawqubit/devdash) | Developer portfolio template — glassmorphic design, dark theme, built with TypeScript |
| [snippet-vault](https://github.com/rawqubit/snippet-vault) | Local-first code snippet manager with tagging and full-text search |
| [workshop--exploring-assemblyscript-contracts](https://github.com/rawqubit/workshop--exploring-assemblyscript-contracts) | Hands-on workshop: building smart contracts for NEAR Protocol with AssemblyScript |

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
