# 🏥 UAE Clinic Operations Skills — OpenClaw

**12 specialized OpenClaw skills for running a private medical clinic in the UAE.**

Built for: Dr Ahmed Al Mazrouei (@dralmazrouei)
Purpose: Autonomous AI agents for UAE private healthcare operations

---

## What Is This?

A collection of OpenClaw agent skills — each skill is a specialized instruction set that equips an AI agent to handle one domain of clinic operations. Each skill activates automatically when triggered by specific keywords.

---

## The 12 Skills

### 🏗️ Setup & Licensing
| Skill | What It Does |
|---|---|
| [`clinic-setup-uae`](skills/clinic-setup-uae/) | Full guide to opening a clinic in the UAE — legal structure, free zone vs mainland, feasibility, facility fit-out, pre-opening checklist |
| [`moh-licensing-uae`](skills/moh-licensing-uae/) | Professional licensing: DOH, DHA, MOHAP — Sheryan portal, DataFlow verification, license renewal, CME/CPD requirements |

### 💼 Operations & Compliance
| Skill | What It Does |
|---|---|
| [`clinic-compliance`](skills/clinic-compliance/) | DOH/DHA inspection prep, clinical governance, JCI/CBAHI accreditation, incident reporting, Civil Defence |
| [`clinic-operations`](skills/clinic-operations/) | Day-to-day management: appointment scheduling, SOPs, patient flow, front desk procedures, KPIs, no-show policy |
| [`clinic-quality`](skills/clinic-quality/) | Clinical quality management, patient safety, PDSA cycles, root cause analysis, M&M meetings, clinical dashboards |

### 👥 People & Patients
| Skill | What It Does |
|---|---|
| [`clinic-staffing`](skills/clinic-staffing/) | Hiring, employment contracts, WPS payroll, gratuity, UAE Labour Law, staff visas, PRO services |
| [`patient-management`](skills/patient-management/) | Patient registration, EMR, informed consent, Malaffi, confidentiality, referral letters, complaint handling |

### 💰 Finance & Revenue
| Skill | What It Does |
|---|---|
| [`clinic-financials`](skills/clinic-financials/) | P&L, budgeting, break-even analysis, VAT (5%), Corporate Tax (9%), cashflow, clinic valuation |
| [`medical-billing-uae`](skills/medical-billing-uae/) | Insurance claims: DAMAN, ADNIC, Thiqa, AXA, pre-authorization, ICD-10/CPT codes, DAMAN tariff, claim resubmission |

### 📱 Technology & Marketing
| Skill | What It Does |
|---|---|
| [`clinic-digital-health`](skills/clinic-digital-health/) | EMR selection, Malaffi (Abu Dhabi HIE), Nabidh (Dubai), telemedicine, FHIR integration, clinic apps |
| [`clinic-marketing-uae`](skills/clinic-marketing-uae/) | Patient acquisition: DOH/DHA advertising rules, SEO, Google Maps, social media, clinic launch, referral networks |

### 🗣️ Communication
| Skill | What It Does |
|---|---|
| [`clinic-arabic-comms`](skills/clinic-arabic-comms/) | Bilingual AR/EN patient communications: WhatsApp, SMS, appointment reminders, medical reports, consent forms, patient education |

---

## How the Skills Work

Each skill lives in its own directory:

```
skills/
├── clinic-setup-uae/      SKILL.md ← the skill definition
├── moh-licensing-uae/    SKILL.md
├── clinic-compliance/     SKILL.md
├── clinic-operations/     SKILL.md
├── clinic-quality/        SKILL.md
├── clinic-staffing/       SKILL.md
├── patient-management/    SKILL.md
├── clinic-financials/     SKILL.md
├── medical-billing-uae/   SKILL.md
├── clinic-digital-health/ SKILL.md
├── clinic-marketing-uae/ SKILL.md
└── clinic-arabic-comms/  SKILL.md
```

The SKILL.md file contains:
- **Trigger keywords** — what activates this skill
- **Domain knowledge** — UAE-specific rules, regulations, contacts
- **Workflows** — step-by-step operational procedures
- **Templates** — ready-to-use documents, checklists, forms

---

## UAE Regulatory Bodies

| Emirate | Authority | Portal |
|---------|-----------|--------|
| Abu Dhabi | Department of Health (DOH) | doh.gov.ae |
| Dubai | Dubai Health Authority (DHA) | dha.gov.ae |
| Sharjah + Northern Emirates | Ministry of Health (MOHAP) | mohap.gov.ae |
| Free Zones | DHCC, Dubai Science Park, ADQ FCZ | varies |

---

## Key UAE Regulations to Know

- **DOH (Abu Dhabi):** Clinic facility license, Malaffi HIE connection mandatory
- **DHA (Dubai):** Sheryan portal for all licensing, Nabidh HIE
- **MOHAP:** Federal licensing for Northern Emirates
- **DOH Inspection:** Unannounced; annual/biennial routine
- **VAT:** 5% — most medical services are zero-rated (0%)
- **Corporate Tax:** 9% on profits above AED 375,000
- **Health Insurance:** DAMAN/ADNIC/AXA panels common; pre-authorization required

---

## Owner

**Dr Ahmed Al Mazrouei** (@dralmazrouei)
UAE-based healthcare entrepreneur & AI automation architect

---

## License

MIT License — free to use, modify, and distribute