<p align="center">
  <a href="https://foundlab.com.br">
    <img src="https://img.shields.io/badge/FoundLab-000000?style=for-the-badge&logo=googlecloud&logoColor=white" alt="FoundLab"/>
  </a>
  <a href="https://linkedin.com/in/alex-bolson-941b1925a">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://g.dev/alexbolson">
    <img src="https://img.shields.io/badge/Google_Developer-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Google Developer Profile"/>
  </a>
</p>

# Alex Bolson — Infrastructure for Auditable Trust

**Founder & Chief Architect, FoundLab**

Building deterministic, cryptographically-verifiable infrastructure for regulated AI and financial systems.

> **Trust by physics, not by policy.**

---

## What I Build

**Auditable Trust Infrastructure** — systems where sensitive payloads disappear, but cryptographic evidence survives.

This means:
- ✅ Evidence-first architecture (regulatory posture should be evidenced, not asserted)
- ✅ Deterministic engines that can be audited by math, not auditors
- ✅ Zero-persistence processing (data never stored = LGPD by design)
- ✅ Event-driven, serverless-first, horizontally auditable
- ✅ Merkle chains, hash-based evidence, DecisionID lineage
- ✅ Real-time observability (OpenTelemetry, not black boxes)

---

## Canonical Work

### [secrecy-architecture](https://github.com/irelia0nerf/secrecy-architecture)
**Reference architecture for verifiable secrecy systems** (Shannon 1949).

Public design notes separating:
- **Secret handling** — ephemeral, zero-persistence processing boundaries
- **Policy enforcement** — deterministic decision gates, fail-closed under ambiguity
- **Cryptographic evidence** — Merkle chains, hash-based audit receipts, ECDSA signatures
- **Non-sensitive auditability** — OpenTelemetry tracing and analytical audit views

Includes Architectural Decision Records (ADRs), threat model documentation, and Python verifier examples for independent auditor validation.

[→ Read secrecy-architecture](https://github.com/irelia0nerf/secrecy-architecture)

---

## Active Infrastructure Projects

### [Spezzatura Lite](https://github.com/irelia0nerf/SpezzaturaLiteV1)
**Deterministic consistency validation for investment data** (Go).

Converts subjective declarations (cap tables, traction claims, corporate history) into reproducible consistency signals. Produces signals, not opinions. Proof-of-check artifacts.

- Deterministic TrustScore
- Inconsistency detection
- Audit-grade output with verifiable proofs

### [Veritas Protocol](https://github.com/irelia0nerf/foundlab-research)
**Cryptographic evidence substrate for financial decisions.**

Hash chaining, DecisionID assignment, Merkle proofs, policy snapshots. Whitepaper with reproducible schema and audit validation guide.

- Canonical whitepaper (Markdown → PDF)
- Cryptographic proof levels and regulatory mapping
- Reproducible audit methodology

### [FoundLab Terraform](https://github.com/irelia0nerf/foundlab-terraform)
**Cloud-native infrastructure scaffold for modular AI governance.**

GCP infrastructure-as-code: Cloud Run services, BigQuery analytical audit views, Vertex AI orchestration, CloudBuild CI/CD.

- Modular service architecture
- Terraform patterns for governance
- React frontend scaffold, API-first design

### [O Códice FoundLab](https://github.com/irelia0nerf/foundlabcodice)
**Institutional blueprint with claims, KPIs, and reproducible evidence.**

Evidence-first documentation, technical claims mapped to observable KPIs, public benchmark structure, audit manifests.

- JSON Schema for verifiable claims
- Proof-of-measurement artifacts
- GitHub Pages documentation

---

## Technical Stack

### Core Languages & Performance
- **Go** — Deterministic engines (Spezzatura, high-performance validation)
- **Python** — Data validation, ML ops, compliance pipelines
- **TypeScript** — Frontend, full-stack applications with React

### Cloud Infrastructure
- **Google Cloud** — Primary platform (Cloud Run, Vertex AI, Pub/Sub, KMS)
- **Storage** — Cloud Storage Bucket Lock for immutable evidence packages
- **BigQuery** — Analytical audit view (not root immutable ledger)
- **Cloud Spanner** — Chain head and strong consistency
- **Terraform** — Infrastructure-as-code, reproducible environments
- **Docker** — Containerized, immutable builds
- **CloudBuild** — CI/CD automation

### Data & Observability
- **Pub/Sub** — Event-driven processing
- **OpenTelemetry** — Full distributed tracing, SLO/SLA metrics
- **PostgreSQL / MongoDB** — Transactional and operational databases

### Security & Cryptography
- **SHA-256** — Hash chains for cryptographic evidence
- **ECDSA P-256** — Signatures for signed logs and DecisionID
- **Zero-persistence design** — Ephemeral containers, forced TTL, no data residue
- **Cloud KMS** — Key management and cryptographic operations

### AI & Governance
- **Vertex AI** — ML pipelines, drift guards, continuous learning
- **Gemini** — LLM integration with runtime governance
- **Explainability-by-design** — Models that produce interpretable decisions

---

## Engineering Principles

- **Evidence over narrative** — Show proof, not promises
- **Determinism as auditability** — Every decision must be reproducible
- **Sensitive payloads disappear; cryptographic evidence survives** — Zero-persistence is architecturally enforced
- **Fail-closed under ambiguity** — Uncertain paths don't execute; they escalate
- **Compliance evidence is produced by architecture** — Regulatory posture should be evidenced, not asserted
- **Audit is continuous, not forensic** — Every transaction produces an artifact
- **Secrets don't persist by default** — Data minimization through ephemeral processing

---

## Background

**Ex-lawyer** (Brazil Bar 53.705/SC) — specialized in market integrity, compliance automation, regulated fintech.

**Published:**
- *"Insider Trading: Crime de informação privilegiada"* — cited as legal precedent in Buenos Aires jurisprudence
- Featured: *"O Arquiteto Stealth: Como um Ex-Advogado Está Construindo a Próxima Infraestrutura 'Auditável' do Mercado Financeiro"* (2025)

**Affiliations:**
- Member, CQF Institute Societies New York
- Member, Google Cloud Innovators
- Member, NVIDIA Developer Program
- Active in quantum finance, market infrastructure, explainable AI

---

## Open to Collaboration

- **Auditable AI infrastructure** — organizations building trust infrastructure for regulated workloads
- **Cryptographic evidence systems** — teams exploring hash-based audit and proof mechanisms
- **Zero-persistence architecture** — regulated fintech solving LGPD/GDPR by design, not encryption
- **Deterministic scoring engines** — investment, credit, or compliance-grade validation systems

---

## Stack at a Glance

```
Infrastructure     → GCP (Cloud Run, Vertex AI, Pub/Sub, KMS), Terraform, Docker
Evidence Storage   → Cloud Storage Bucket Lock (immutable), BigQuery (analytical view)
Core Engines       → Go (deterministic), Python (ML ops), TypeScript (full-stack)
Security           → SHA-256, ECDSA P-256, zero-persistence, Merkle chains
Observability      → OpenTelemetry, audit-first logging, policy-as-code
AI/Governance      → Vertex AI, Gemini, explainability-by-design
```

---

## Connect

- **Website:** [foundlab.com.br](https://foundlab.com.br)
- **LinkedIn:** [alex-bolson-941b1925a](https://linkedin.com/in/alex-bolson-941b1925a)
- **Google Developer:** [g.dev/alexbolson](https://g.dev/alexbolson)
- **Research:** [foundlab-research](https://github.com/irelia0nerf/foundlab-research)
- **Architecture:** [secrecy-architecture](https://github.com/irelia0nerf/secrecy-architecture)

---

<p align="center">
  <strong>FoundLab — Sensitive Payloads Disappear. Cryptographic Evidence Survives.</strong>
</p>
