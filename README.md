# Kwashawn Warren

### Security engineering and security management

I build security projects for secrets handling, detection, vulnerability scanning, identity and access, cloud baselines, and automation. I'm a U.S. Air Force Security Forces veteran and currently a field supervisor in physical security operations.

Dallas, TX · relocating to Chicago, IL in spring 2027

**Open to security engineering roles in Chicagoland from spring 2027.**

### Certifications

![CompTIA Security+](https://img.shields.io/badge/CompTIA-Security%2B-E2231A?style=flat&logo=comptia&logoColor=white)
![CompTIA Network+](https://img.shields.io/badge/CompTIA-Network%2B-E2231A?style=flat&logo=comptia&logoColor=white)
![CompTIA A+](https://img.shields.io/badge/CompTIA-A%2B-E2231A?style=flat&logo=comptia&logoColor=white)
![AWS Certified Cloud Practitioner](https://img.shields.io/badge/AWS-Cloud%20Practitioner-FF9900?style=flat&logo=amazonwebservices&logoColor=white)
![LPI Linux Essentials](https://img.shields.io/badge/LPI-Linux%20Essentials-FCC624?style=flat&logo=linux&logoColor=black)

### What I build

#### Security

- **[precommit-secrets-guard](https://github.com/shurugiken/precommit-secrets-guard)**: Scans staged changes with Gitleaks, supports warn and enforce modes, and records finding counts without matched values.
- **[trivy-repo-scanner](https://github.com/shurugiken/trivy-repo-scanner)**: Verifies a pinned Trivy release before scanning local repositories for vulnerabilities and secrets, retaining severity counts.
- **[linux-auditd-baseline](https://github.com/shurugiken/linux-auditd-baseline)**: Provides auditd rules for selected configuration changes and privileged sessions, with a read-only hardening audit.
- **[file-metadata-scrubber](https://github.com/shurugiken/file-metadata-scrubber)**: Creates checked copies of supported images and restricted Office documents with metadata removed, preserving originals.
- **[transcript-secret-scrubber](https://github.com/shurugiken/transcript-secret-scrubber)**: Finds exact known secrets in selected transcripts and logs; defaults to dry run and requires explicit application of replacements.
- **[agent-run-gate](https://github.com/shurugiken/agent-run-gate)**: Requires an approved review, an unchanged repository fingerprint, and a passing proof command before accepting agent output.
- **[webhook-auth-patterns](https://github.com/shurugiken/webhook-auth-patterns)**: Demonstrates shared-secret, HMAC-SHA256, and Ed25519 authentication, with timing and replay checks explained.
- **[m365-email-security](https://github.com/shurugiken/m365-email-security)**: Covers SPF, DKIM, DMARC, a scoped Entra mail app, and a Conditional Access cutover guide.
- **[dmarc-report-analyzer](https://github.com/shurugiken/dmarc-report-analyzer)**: Summarizes DMARC aggregate reports, including SPF and DKIM alignment and failing sources.
- **[cloudflare-tunnel-zero-trust](https://github.com/shurugiken/cloudflare-tunnel-zero-trust)**: Documents an outbound Cloudflare Tunnel for a local HTTP service, managed with systemd and no open inbound ports.
- **[secure-ai-microsoft365](https://github.com/shurugiken/secure-ai-microsoft365)**: Documents least-privilege Microsoft Graph access and credential handling for AI workflows using Microsoft 365 data.
- **[mcp-audit-otel](https://github.com/shurugiken/mcp-audit-otel)**: Defines MCP audit events, OpenTelemetry emission, and control mappings with explicit limits on what the audit stream establishes.

#### Cloud

- **[aws-cloud-projects](https://github.com/shurugiken/aws-cloud-projects)**: AWS labs for private S3 hosting through CloudFront and least-privilege IAM with CloudWatch monitoring.
- **[terraform-aws-secure-baseline](https://github.com/shurugiken/terraform-aws-secure-baseline)**: A Terraform module for an encrypted, versioned S3 bucket with public access blocked and IAM scoped to the bucket.
- **[cf-workers-ai-digest](https://github.com/shurugiken/cf-workers-ai-digest)**: Runs a scheduled Workers AI digest with a secret-gated preview and delivery to a chat webhook.
- **[homelab](https://github.com/shurugiken/homelab)**: An Ubuntu and Docker AI inference stack with Ollama and Open WebUI, accessed through Tailscale.

#### Automation

- **[powershell-it-toolkit](https://github.com/shurugiken/powershell-it-toolkit)**: PowerShell for Microsoft 365 account onboarding and offboarding, plus Windows health and maintenance tasks.
- **[ad-automation-toolkit](https://github.com/shurugiken/ad-automation-toolkit)**: Active Directory account lifecycle scripts and membership reports with input checks and `-WhatIf` support.
- **[net-triage](https://github.com/shurugiken/net-triage)**: Checks DNS, TCP connectivity, HTTP responses, and connection latency, with text and JSON reports.
- **[kb-health](https://github.com/shurugiken/kb-health)**: Reviews Markdown notes with an LLM for contradictions, stale claims, missing pages, and writing issues.
- **[job-alert-bot](https://github.com/shurugiken/job-alert-bot)**: Collects job postings, applies deterministic scoring, deduplicates in SQLite, and sends a Telegram digest.

#### AI agents

- **[building-ai-agents](https://github.com/shurugiken/building-ai-agents)**: A guide to agent loops, orchestration, evaluation, local models, and safeguards for agent output.
- **[multi-agent-research-pipeline](https://github.com/shurugiken/multi-agent-research-pipeline)**: Runs parallel research calls, challenges candidate claims, and synthesizes a brief from the claims that survive review.
- **[serverless-llm-webhook](https://github.com/shurugiken/serverless-llm-webhook)**: Authenticates an inbound event, summarizes it with an LLM, and delivers the summary through a chat webhook.

#### Web3

- **[evm-onchain-toolkit](https://github.com/shurugiken/evm-onchain-toolkit)**: Python examples for EVM balances, token queries, message signing, and transfer construction without broadcasting.
- **[wagmi-usdc-payments](https://github.com/shurugiken/wagmi-usdc-payments)**: A React and TypeScript demo for wallet connection, USDC balances, and transfers on Polygon with transaction status.

### Education

B.S. Cloud Computing, Western Governors University, in progress.

### Connect

**LinkedIn:** [linkedin.com and in and kwashawnwarren](https://www.linkedin.com/in/kwashawnwarren)
