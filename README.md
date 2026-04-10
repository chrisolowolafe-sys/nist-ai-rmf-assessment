# NIST AI RMF Gap Assessment Tool

**Live Demo:** [nist-ai-rmf-assessment.chrisolowolafe.workers.dev](https://nist-ai-rmf-assessment.chrisolowolafe.workers.dev)  
**Built by:** [Chris Olowo, PMP®](https://chris-olowo-grc-portfolio.pages.dev) — GRC Analyst & Risk Practitioner

---

## Overview

A fully interactive, browser-based NIST AI Risk Management Framework (AI RMF 1.0) gap assessment tool. Evaluates AI governance maturity across all four core functions — **Govern, Map, Measure, Manage** — using a 0–4 maturity scale, identifies gaps against target maturity of 3 (Defined), and generates a prioritized remediation roadmap mapped to ISO 42001:2023 and the EU AI Act 2024.

---

## Features

- **59 practices** across all four NIST AI RMF core functions
- **5-level maturity scale** — 0 (Not Implemented) → 4 (Optimized)
- **Target maturity: 3** — Defined (industry standard baseline)
- **Per-practice notes** for assessor observations
- **Radar chart** — current vs target maturity visualization
- **Prioritized gap list** — Critical / High / Medium by severity
- **Three-tier remediation roadmap** — Implement Immediately / 90 days / 6 months
- **ISO 42001 and EU AI Act** control references per practice
- **Export to JSON** / Print to PDF
- **EU AI Act risk tier** classification field

---

## NIST AI RMF Coverage

| Function | Subcategories | Practices |
|---|---|---|
| **GOVERN** | GV.1–GV.6 | 18 |
| **MAP** | MP.1–MP.5 | 16 |
| **MEASURE** | MS.1–MS.4 | 14 |
| **MANAGE** | MG.1–MG.4 | 11 |
| **Total** | | **59 practices** |

---

## Framework Alignment

| Framework | Version |
|---|---|
| NIST AI RMF | 1.0 (January 2023) |
| ISO 42001 | 2023 |
| EU AI Act | 2024 |
| ISO 27001 | 2022 |
| NIST CSF | 2.0 |

---

## Security Architecture

All security headers enforced server-side via Cloudflare `_headers`. Additional: HTTPS enforcement, GitHub Pages redirect, Chart.js SRI, safety stub, XSS prevention, localStorage try/catch, prefers-reduced-motion, no tracking.

---

## Repository Structure

```
nist-ai-rmf-assessment/
├── index.html    ← Full application
├── _headers      ← Cloudflare security headers
└── README.md     ← This file
```

---

## Complete GRC Portfolio

| Project | Live URL |
|---|---|
| 🏠 ShomriTech GRC Platform | [chris-olowo-grc-portfolio.pages.dev](https://chris-olowo-grc-portfolio.pages.dev) |
| 1️⃣ Vendor Risk Assessment Tool | [vendor-risk-assessment-tool.chrisolowolafe.workers.dev](https://vendor-risk-assessment-tool.chrisolowolafe.workers.dev) |
| 2️⃣ User Access Review Tracker | [user-access-review-tracker.chrisolowolafe.workers.dev](https://user-access-review-tracker.chrisolowolafe.workers.dev) |
| 3️⃣ SOC 2 Evidence Tracker | [soc2-evidence-tracker.chrisolowolafe.workers.dev](https://soc2-evidence-tracker.chrisolowolafe.workers.dev) |
| 4️⃣ **NIST AI RMF Gap Assessment** *(this repo)* | [nist-ai-rmf-assessment.chrisolowolafe.workers.dev](https://nist-ai-rmf-assessment.chrisolowolafe.workers.dev) |
| 5️⃣ Security Questionnaire Library | [security-questionnaire-library.chrisolowolafe.workers.dev](https://security-questionnaire-library.chrisolowolafe.workers.dev) |

---

## Author

**Chris Olowo, PMP®**  
GRC Analyst & Risk Practitioner · Calgary, Canada  
ISO 27001 Lead Auditor · NIST CSF 2.0 · ISO 42001 · GRC · PrivacyOps · PMP®

*Pro bono ISO 42001 AI governance consulting provided to non-profit organizations in Calgary.*

[Portfolio](https://chris-olowo-grc-portfolio.pages.dev) · [LinkedIn](https://www.linkedin.com/in/chris-o-742316135) · [GitHub](https://github.com/chrisolowolafe-sys)

---

*For demonstration and educational purposes only. Based on NIST AI RMF 1.0 (January 2023). Not legal or compliance advice.*
