# 👋 Quentin Guillerey

**Customer Operations Manager · Founder-Operator · Bilingual FR/EN**

[![Email](https://img.shields.io/badge/email-guillerey.finance%40gmail.com-blue)](mailto:guillerey.finance@gmail.com) [![LinkedIn](https://img.shields.io/badge/linkedin-quentin--guillerey-blue)](https://www.linkedin.com/in/quentin-guillerey)

I run U.S. and Canada customer operations for the world leader in robotic mowing: service delivery, escalations, QA, and client coordination. Before that I founded and scaled a regulated mortgage brokerage in France to more than 250M€ in originations.

The repositories here are personal projects, built on my own time and on sanitized or generic data. None of them are deployed on a client account. I am not a software engineer. I specify, pressure test, and verify, and I know the operations problem well enough to say exactly what the software has to do.

---

## 🚀 What I do

- Run U.S. and Canada service delivery for a 12-agent team handling 3,000+ contacts a month at seasonal peak: 95% CSAT, 85% first contact resolution, 85% QA, external escalations under 1% against a 3% contract ceiling.
- Designed a 3-tier escalation framework that resolves the large majority of issues in house.
- Enforce PCI DSS compliance procedures on a live payment operation, monitoring agent adherence and coaching on gaps.
- Support and mentor SMEs across a 40+ agent offshore operation.
- Founded and scaled a regulated financial services business from zero to 250M€+ in originations.

---

## 🔑 Projects

| Project | What it does | Stack | Status |
|---|---|---|---|
| **[AISCORE](https://github.com/Quentin-Guillerey/AISCORE)** | QA scoring engine for contact-center interactions. Weighted rubric scoring, with every criterion explicitly classified as rule-based, model-based, or not automatable, and human override on anything touching compliance. | FastAPI, PostgreSQL | Early build, sanitized demo data |
| **[Resolva](https://github.com/Quentin-Guillerey/resolva)** | Self-maintaining knowledge base. Converts resolved tickets into structured entries, auto-publishes routine cases, routes legal and cross-team cases to a human reviewer, logs an audit entry on every publish. Customers referenced by internal ID kept separate from the CRM. | Claude API, Flask, SQLite | Early build, core workflow end to end |
| **[CSR Automation Toolkit](https://github.com/Quentin-Guillerey/csr-automation-toolkit)** | Query routing prototype. Rule-based classifier first, with an optional model fallback constrained to selecting one entry ID from a known catalogue. Editable response validation before send, hardened CSV audit log. | Python, Tkinter, pytest | Working prototype, not deployed |

---

## 💡 The through-line

Every one of these puts a human at the decision point.

The CSR toolkit separates generating a response from sending one, and logs whether the agent edited it. Resolva publishes routine entries automatically but routes anything legal or cross-team to a reviewer first. AISCORE refuses to score criteria it classifies as not automatable, and requires a logged human override on compliance failures.

Automation is for efficiency. It is not for decisions. In a regulated operation, the approval and the accountability stay with people, and that is not a feature you add later.

---

## 🤝 Contact

Open to remote U.S. and Canada roles in customer success, operations, and service delivery.

📧 <guillerey.finance@gmail.com>
🔗 [linkedin.com/in/quentin-guillerey](https://www.linkedin.com/in/quentin-guillerey)
