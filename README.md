# 🛡️ GRC Cybersecurity Platform

> A comprehensive, fully interactive **Governance, Risk & Compliance (GRC)** platform built as a self-contained single-page web application — no backend, no build step, no dependencies beyond Chart.js.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](index.html)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript&logoColor=black)](index.html)
[![Chart.js](https://img.shields.io/badge/Chart.js-4.4.1-FF6384?logo=chartdotjs&logoColor=white)](https://chartjs.org)

---

## 🚀 Quick Start

**Download → Open `index.html` in any browser. Done.**

No server. No install. No build step required.

---

## 📋 Project Overview

This platform was built as **three interconnected hands-on GRC projects**, covering the full cybersecurity governance lifecycle:

| # | Project | Description |
|---|---------|-------------|
| 1 | **GRC Risk Assessment Framework** | Risk register, 5×5 scoring matrix, treatment register with residual risk |
| 2 | **Compliance Audit Program** | ISO 27001:2013 mock audit across all 14 Annex A domains (38 controls) |
| 3 | **Governance Strategy Presentation** | Board-ready slides, RACI matrix, roadmap, 6 policy templates |

Expanded into **15 functional modules** total, covering risk, compliance, governance, incident response, security awareness training, vendor risk assessment, and formal audit reporting.

---

## ✨ Feature Modules

### 🎯 Risk Register
- 12 identified cyber threats with likelihood × impact (L×I) scoring
- Interactive 5×5 risk heatmap — Critical / High / Medium / Low
- Filter by risk level; track owner and remediation status
- Mitigation strategies mapped to each threat

### 💊 Risk Treatment Register
- Treatment strategy per risk: Mitigate / Transfer / Accept / Avoid
- Control effectiveness ratings (High / Medium / Low)
- Residual risk score and level after controls applied
- Average score reduction tracked across the register

### 📊 Risk Analytics
- Chart.js horizontal bar chart — risk score by threat, sorted descending
- Donut chart — risk level distribution (Critical / High / Medium / Low)
- Risk exposure table with visual inline progress bars

### 📋 ISO 27001 Compliance Audit
- Mock audit for **two organizations**: TechCorp Ltd (88%) and HealthFirst Inc (42%)
- 7 primary Annex A domains (A.5 – A.16) with expandable control detail
- Audit findings per control with evidence notes
- Domain-level compliance progress bars

### 📑 Extended ISO 27001 Domains (A.10 – A.18)
- 7 additional domains completing the full ISO 27001:2013 Annex A
- Cryptography, Physical Security, Communications, System Acquisition, Supplier Relationships, BCM, Compliance

### 📄 Statement of Applicability (SoA)
- All **14 Annex A domains**, **38 controls** assessed
- Implementation status: Implemented / Partial / Planned / Not Implemented / N/A
- Filter by status; SoA score weighted by implementation depth
- Required document for ISO 27001 certification

### 🔍 Gap Analysis & Remediation Tracker
- 21 prioritized remediation items (P1 → P4)
- Sourced from both risk register and compliance audit
- Filter by priority tier; effort level and target date per item
- Covers both TechCorp and HealthFirst findings

### 🏛️ Governance Strategy Presentation
- 6 board-ready slides: Title → Executive Summary → Policies → RACI → Roadmap → KPIs
- Interactive slide navigation with dot indicators
- Fully self-contained — no PowerPoint required

### 📜 Cybersecurity Policy Templates
- 6 full policy documents: IS Policy, Access Control, Incident Response, Data Classification, Acceptable Use, Business Continuity
- Each includes: Purpose, Scope, 5 policy statements, Roles & Responsibilities, Review cycle
- Expand/collapse all; copy-ready text

### 👥 Roles & Responsibilities (RACI)
- 9 security activities × 6 stakeholder roles
- Color-coded: Responsible / Accountable / Consulted / Informed

### 🗺️ Security Controls Roadmap
- Q1–Q4 2025 phased implementation plan
- Phase-colored items: Foundation → Detection → Advanced Controls → Optimize

### 📈 Executive Dashboard
- Side-by-side ISO 27001 compliance comparison (Chart.js grouped bar)
- Risk distribution donut chart
- 6 P1 priority action items with owners and target dates
- Consolidated GRC health metrics

### 🚨 Incident Response Playbook
- NIST SP 800-61r2 aligned 5-phase IR lifecycle
- Severity classification matrix (P1–P4) with response SLAs
- 4 scenario playbooks with full step-by-step procedures:
  - Phishing / Business Email Compromise
  - Ransomware attack
  - Data breach / Unauthorized access
  - Cloud misconfiguration / Exposure

### 📚 Security Awareness Training Program
- 12-module annual training calendar (ISO 27001 A.7.2.2 aligned)
- Quarterly phishing simulation results tracking
- Role-based delivery: All staff / IT / Developers / Procurement / Leadership
- Completion rate per module with visual progress bars

### 🤝 Vendor Risk Assessment (VRA) Questionnaire
- Interactive 25-question security questionnaire
- 6 domains: Governance, Access Control, Data Protection, Incident Response, BCM, Compliance
- Live scoring — answer Yes / Partial / No / N/A and get an instant risk rating
- Risk thresholds: ≥90% Low · 70–89% Medium · 50–69% High · <50% Critical

### 📑 Formal GRC Audit Report
- Switchable between TechCorp (88%) and HealthFirst (42%)
- 14-domain compliance heatmap
- Key findings, prioritized recommendations (P1/P2/P3), and executive conclusion
- Board-ready format

### 📉 Security Metrics & KPI Dashboard
- 6 core KPIs tracked with current vs target comparison
- On track / At risk / Off track status per KPI
- Trend indicators (improving / stable / declining)
- Management commentary for Q1 2025
- Metrics: MTTD, MTTR, Patch compliance, Training completion, Phishing rate, Critical vuln SLA

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| HTML5 / CSS3 | Structure and styling |
| Vanilla JavaScript (ES6+) | All interactivity and data logic |
| [Chart.js 4.4.1](https://www.chartjs.org/) | Compliance comparison bar + risk donut charts |
| [Tabler Icons](https://tabler-icons.io/) | UI icons throughout |
| CSS Custom Properties | Theme variables (light/dark mode compatible) |

**Zero build tools. Zero npm. Zero frameworks.** Open `index.html` in any modern browser.

---

## 🚀 Getting Started

### Option 1 — Download & open locally
```bash
git clone https://github.com/YOURUSERNAME/grc-cybersecurity-platform.git
cd grc-cybersecurity-platform
open index.html          # macOS
start index.html         # Windows
xdg-open index.html      # Linux
```
No server needed — open `index.html` directly in any modern browser.

### Option 2 — Host on GitHub Pages (free public URL)
```
1. Push repo to GitHub (set to Public)
2. Go to Settings → Pages
3. Source: Deploy from branch → main → / (root)
4. Your free live URL:
   https://YOURUSERNAME.github.io/grc-cybersecurity-platform
```

---

## 📁 Repository Structure

```
grc-cybersecurity-platform/
├── index.html                  # Complete self-contained platform
├── README.md                   # This file
├── LICENSE                     # MIT License
└── docs/
    ├── risk-methodology.md     # Risk scoring methodology (5×5 matrix)
    ├── iso27001-reference.md   # ISO 27001:2013 control reference guide
    └── screenshots/            # Platform screenshots
```

---

## 🗺️ GRC Framework Coverage

| Framework / Standard | Coverage in Platform |
|---------------------|---------------------|
| **ISO/IEC 27001:2013** | All 14 Annex A domains, 38 controls, Statement of Applicability |
| **NIST Cybersecurity Framework** | Identify, Protect, Detect, Respond, Recover mapped throughout |
| **NIST SP 800-61r2** | Incident response lifecycle and scenario playbooks |
| **NIST SP 800-50** | Security awareness training program structure |
| **GDPR / HIPAA** | Referenced in compliance findings and audit report |
| **CIS Controls** | Referenced in risk mitigation strategies |
| **ISO 22301** | BCM/BCP requirements in A.17 controls |

---

## 📸 Module Summary

| Module | Status | Key Metric |
|--------|--------|------------|
| Risk Register | ✅ Complete | 12 threats, 2 Critical |
| Risk Treatment | ✅ Complete | 0 residual Critical risks |
| Risk Analytics | ✅ Complete | Chart.js visualizations |
| ISO 27001 Audit | ✅ Complete | TechCorp 88% / HealthFirst 42% |
| Extended ISO Domains | ✅ Complete | 7 additional domains (A.10–A.18) |
| Statement of Applicability | ✅ Complete | 38 controls, certification-ready |
| Gap Analysis | ✅ Complete | 21 prioritized items |
| Governance Presentation | ✅ Complete | 6 board-ready slides |
| Policy Templates | ✅ Complete | 6 full policies |
| Executive Dashboard | ✅ Complete | Compliance comparison chart |
| IR Playbook | ✅ Complete | 4 scenario playbooks |
| Security Metrics | ✅ Complete | 6 KPIs with trend tracking |
| Training Program | ✅ Complete | 12 modules, quarterly sims |
| Vendor Risk Assessment | ✅ Complete | 25-question live scoring |
| Audit Report | ✅ Complete | Formal report, 2 organizations |

---

## 🔧 Customization

All data is defined in clearly labeled JavaScript arrays at the top of `index.html`:

```javascript
const RISKS = [...];          // Cyber threats — add/edit risk entries
const DOMAINS = [...];        // ISO 27001 controls — update audit findings
const TREATMENTS = [...];     // Risk treatment strategies
const POLICIES = [...];       // Policy template content
const TRAINING = [...];       // Training modules and schedule
const VRA_Q = [...];          // Vendor assessment questions
const REPORT = {...};         // Audit report content per organization
```

Update these arrays to tailor the platform to your organization.

---

## 👤 Author

**Malav Mehta**  
Cybersecurity Analyst | Cloud Developer | GRC Specialist

- 🔗 LinkedIn: [linkedin.com/in/yourprofile]www.linkedin.com/in/malavmehta-dev
- 💻 GitHub: [github.com/yourusername]https://github.com/malavmehta7101
- 📧 Email: malav.mehta@rocketmail.com/mehtamalav59@gmail.com

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.  
Free to use, adapt, and distribute with attribution.

---

## ⭐ Support

If this project helped you, please consider giving it a **star ⭐** on GitHub — it helps others discover it.

> *Built to demonstrate real-world GRC, cybersecurity, and full-stack development skills.*
