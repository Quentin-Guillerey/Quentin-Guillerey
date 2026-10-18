# 👋 Quentin Guillerey

**Customer Experience Manager · Support Operations & Order-to-Cash · Bilingual FR/EN**

[![Email](https://img.shields.io/badge/email-guillerey.finance%40gmail.com-blue)](mailto:guillerey.finance@gmail.com) [![LinkedIn](https://img.shields.io/badge/linkedin-quentinguillerey-blue)](https://www.linkedin.com/in/quentinguillerey)

I run the U.S. customer support team for a global leader in consumer robotics: order management, returns and RMAs, refunds, billing issues, SLAs and escalations. Before that I founded and ran Guillerey Finance SARL, a regulated mortgage and insurance brokerage in Lyon, France, for eight years and €250M+ in originations.

The repositories here are personal projects, built on my own time, on synthetic or mock data. None of them are deployed on a client account. Each README states plainly what is verified, what is manual, and what is not proven yet, because a prototype that overstates itself is worse than no prototype. I am not a software engineer. I specify, pressure test, and verify, and I know the operations problem well enough to say exactly what the software has to do.

---

## 🚀 What I do

- Lead a 10-agent U.S. team handling 3,000+ contacts a month at peak across voice, email and chat: 95% CSAT, 85% first-contact resolution, external escalations under 1% against a 3% contractual ceiling.
- Held 85% of calls answered within 30 seconds through five seasonal peaks.
- Designed a three-tier escalation framework, and cut average handle time 30% by rebuilding the knowledge base and order management SOPs.
- Handle customer orders and payment data in a PCI DSS Level 1 environment.
- Serve as subject matter expert for a 30+ agent team in Manila.
- Founded and ran a regulated brokerage: €250M+ originated, full P&L, KYC and AML ownership.

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
| **[AISCORE](https://github.com/Quentin-Guillerey/AISCORE)** | QA scoring engine for contact-center interactions. 14 weighted criteria scoped by channel, each carrying an explicit automation method (rule-based, model-based, or not automatable). Compliance violations override the base score rather than blending into it, and unrecoverable results are held for human review. | FastAPI, PostgreSQL, 55 tests in CI | Prototype, mock and manually entered data |
| **[Resolva](https://github.com/Quentin-Guillerey/Resolva)** | Self-maintaining knowledge base. Converts resolved tickets into plain-language entries any department can read, auto-publishes only routine IT-closed cases, and holds anything cross-departmental, management-involved, or legal-adjacent for SME review. Every legal-touching case is reviewed, enforced by a test. CRM ids are converted one-way to internal account numbers and discarded. | Claude API, Flask, SQLite, CSV audit log | Prototype, synthetic sanitized demo data |
| **[CSR Automation Toolkit](https://github.com/Quentin-Guillerey/csr-automation-toolkit)** | Query routing prototype. Rule-based classifier first, with an optional model fallback constrained to selecting one entry ID from a known catalogue. Editable response validation before send, hardened CSV audit log. | Python, Tkinter, pytest | Working prototype, not deployed |

---

## 💡 The through-line

Every one of these puts a human at the decision point, and each draws the line somewhere specific.

The CSR toolkit separates generating a response from sending one, and logs whether the agent edited it. Resolva auto-publishes only routine IT-closed tickets and holds every legal-touching case for SME review, with a test that fails the build if that ever stops being true. AISCORE draws its gate on recoverability rather than severity: a capped score publishes because the detail survives for audit, a zeroed score is held for a person because nothing is left to inspect.

Automation is for efficiency. It is not for decisions. In a regulated operation the approval and the accountability stay with people, and that is not a feature you add later.

---

## 🤝 Contact

Open to remote U.S. and Canada roles in customer success, operations, and service delivery.

📧 <guillerey.finance@gmail.com>
🔗 [linkedin.com/in/quentin-guillerey](https://www.linkedin.com/in/quentin-guillerey)
