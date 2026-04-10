# NIST AI RMF Gap Assessment Tool

**Live Demo:** [nist-ai-rmf-assessment.chrisolowolafe.workers.dev](https://nist-ai-rmf-assessment.chrisolowolafe.workers.dev)  
**Built by:** [Chris Olowo, PMP®](https://chris-olowo-grc-portfolio.pages.dev) — GRC Analyst & Risk Practitioner

---

## Overview

A fully interactive, browser-based NIST AI Risk Management Framework (AI RMF 1.0) gap assessment tool. Evaluates AI governance maturity across all four core functions — **Govern, Map, Measure, Manage** — using a 0–4 maturity scale, identifies gaps against a target maturity of 3 (Defined), and generates a prioritized remediation roadmap mapped to ISO 42001:2023 and the EU AI Act 2024.

---

## Features

### Gap Assessment
- **72 practices** across all four NIST AI RMF core functions
- 5-level maturity scale: 0 (Not Implemented) → 4 (Optimized)
- Target maturity: 3 — Defined (industry standard baseline)
- Per-practice notes field for assessor observations
- Function progress tracking with completion indicators
- Live overview cards showing current maturity per function

### Results & Gaps
- Overall maturity score and per-function breakdown
- **Radar chart** — current vs target maturity visualization
- Prioritized gap list sorted by severity (Critical / High / Medium)
- Function-level progress bars with colour-coded readiness

### Roadmap Report
- Executive-ready AI governance gap assessment report
- Three-tier remediation roadmap:
  - 🔴 Critical — Implement Immediately (score = 0)
  - 🟠 High Priority — Address within 90 days (score = 1)
  - 🟡 Medium Priority — Address within 6 months (score = 2)
- ISO 42001 and EU AI Act control references per gap
- Export to JSON / Print to PDF

### Organization Context
- Organization / AI system name
- Assessor field
- EU AI Act risk tier classification (Unacceptable / High / Limited / Minimal)

---

## NIST AI RMF Coverage

| Function | Subcategories | Practices |
|---|---|---|
| **GOVERN** | GV.1 Policies · GV.2 Accountability · GV.3 Culture · GV.4 Teams · GV.5 Organizational Policies · GV.6 Risk Policies | 18 |
| **MAP** | MP.1 Context · MP.2 Scientific Basis · MP.3 Categorization · MP.4 Risk Tolerance · MP.5 Impacts | 16 |
| **MEASURE** | MS.1 AI Risks · MS.2 AI Systems · MS.3 Bias & Fairness · MS.4 Feedback | 14 |
| **MANAGE** | MG.1 Prioritization · MG.2 Strategies · MG.3 Monitoring · MG.4 Incidents | 11 |
| **Total** | | **59 practices** |

---

## Framework Alignment

| Framework | Version | Mapping |
|---|---|---|
| NIST AI RMF | 1.0 (January 2023) | Primary framework — all four functions |
| ISO 42001 | 2023 | Per-practice ISO clause references |
| EU AI Act | 2024 | Per-practice Article references |
| ISO 27001 | 2022 | Supporting information security controls |
| NIST CSF | 2.0 | Complementary cybersecurity framework |

---

## Security Architecture

All security headers enforced server-side via Cloudflare `_headers`:

| Header | Value |
|---|---|
| `X-Frame-Options` | `DENY` |
| `X-Content-Type-Options` | `nosniff` |
| `Referrer-Policy` | `strict-origin-when-cross-origin` |
| `Strict-Transport-Security` | `max-age=63072000; includeSubDomains; preload` |
| `Content-Security-Policy` | Strict allowlist |
| `Permissions-Policy` | Geolocation, microphone, camera, payment denied |

Additional: HTTPS enforcement, GitHub Pages redirect, Chart.js SRI integrity hash, Chart.js safety stub, XSS prevention on all input, localStorage try/catch, prefers-reduced-motion, no cookies, no tracking, no analytics.

---

## Repository Structure

```
nist-ai-rmf-assessment/
├── index.html    ← Full application
├── _headers      ← Cloudflare security headers
└── README.md     ← This file
```

---

## Running Locally

```bash
git clone https://github.com/chrisolowolafe-sys/nist-ai-rmf-assessment.git
cd nist-ai-rmf-assessment
open index.html
```

---

## Part of the GRC Portfolio

| Project | Status |
|---|---|
| [ShomriTech GRC Platform](https://chris-olowo-grc-portfolio.pages.dev/grc-platform) | ✅ Live |
| [Vendor Risk Assessment Tool](https://vendor-risk-assessment-tool.chrisolowolafe.workers.dev) | ✅ Live |
| [User Access Review Tracker](https://user-access-review-tracker.chrisolowolafe.workers.dev) | ✅ Live |
| [SOC 2 Evidence Tracker](https://soc2-evidence-tracker.chrisolowolafe.workers.dev) | ✅ Live |
| **NIST AI RMF Gap Assessment** *(this repo)* | ✅ Live |

---

## Author

**Chris Olowo, PMP®**  
GRC Analyst & Risk Practitioner · Calgary, Canada  
ISO 27001 Lead Auditor · NIST CSF 2.0 · ISO 42001 · GRC · PrivacyOps · PMP®

[Portfolio](https://chris-olowo-grc-portfolio.pages.dev) · [LinkedIn](https://www.linkedin.com/in/chris-o-742316135)

---

*For demonstration and educational purposes only. Based on NIST AI RMF 1.0 (January 2023). Not legal or compliance advice. Framework references are paraphrased for educational purposes.*
