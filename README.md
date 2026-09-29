# Awesome-Behavioral-Health-EHR

# Top Behavioral Health EHR Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Mental Health Practice Management, Clinical Documentation & Patient Engagement*  
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Behavioral Health Electronic Health Records (EHR)**. These tools manage clinical documentation, scheduling, billing, telehealth, and patient engagement for therapists, psychiatrists, counselors, and behavioral health clinics.

**Examples** include Valant, SimplePractice, TheraNest, Kareo Behavioral Health, AdvancedMD Behavioral Health, ICANotes, Qualifacts, InSync Healthcare, NextGen Behavioral Health, and Credible (the category leaders).

**Open-source emphasis**: This section is expanded with active projects for self-hosting, custom clinical workflows, and transparent patient data management — ideal for solo practitioners, small clinics, researchers, and developers building vendor-independent behavioral health solutions. Note that the open-source ecosystem for behavioral health EHR remains fragmented, with most projects being general-purpose medical EHRs adapted for mental health, academic prototypes, or niche tools for specific workflows like psychotherapy documentation.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Valant](https://www.valant.com/)**  
  Behavioral health EHR with clinical documentation, scheduling, billing, and telehealth designed specifically for mental health practices.

- **[SimplePractice](https://www.simplepractice.com/)**  
  Practice management platform used by over 185,000 health and wellness professionals, covering scheduling, billing, notes, and telehealth .

- **[TheraNest](https://www.theranest.com/)**  
  Mental health practice management software with scheduling, billing, notes, and telehealth for therapists and counselors.

- **[Kareo Behavioral Health](https://www.kareo.com/)**  
  EHR and practice management with behavioral health specialization, covering billing, scheduling, and clinical documentation.

- **[AdvancedMD Behavioral Health](https://www.advancedmd.com/)**  
  Comprehensive behavioral health EHR with telehealth, patient portal, and revenue cycle management.

- **[ICANotes](https://www.icanotes.com/)**  
  Behavioral health EHR known for clinical content and note-generation capabilities for mental health providers.

- **[Qualifacts](https://www.qualifacts.com/)**  
  EHR solutions for behavioral health, human services, and rehabilitative care organizations.

- **[InSync Healthcare](https://www.insynchcs.com/)**  
  Behavioral health and human services EHR with mobile access and clinical documentation tools.

- **[NextGen Behavioral Health](https://www.nextgen.com/)**  
  Enterprise behavioral health EHR with integrated practice management and population health tools.

- **[Credible](https://credibleinc.com/)**  
  Behavioral health EHR with clinical, billing, and reporting capabilities for mental health and addiction treatment providers.

## Open-Source GitHub Projects

- **[OpenEMR](https://github.com/openemr/openemr)**  
  The most popular open-source electronic health records and medical practice management solution, with 3,378+ stars and active development . ONC Complete Ambulatory EHR certified, translated into 35+ languages, and used in 100+ countries . For behavioral health, workflows can be customized with templates for intake/consent, outcomes tracking, and role-based access . Features native TOTP-based two-factor authentication, LDAP/Active Directory integration, and OAuth2/OpenID Connect support . GPLv3 licensed.

- **[OpenMRS](https://github.com/openmrs/openmrs-core)**  
  Community-developed, open-source enterprise electronic medical record system platform designed for resource-constrained settings. Built around a configurable Concept Dictionary (CIEL) that adapts to any specialty or country-specific data requirement . The newer O3 frontend uses React-based microfrontends for easier custom module development . MPL 2.0 licensed (permissive file-by-file). Strongest for global health and NGO deployments.

- **[Bahmni](https://github.com/Bhamni/bahmni)**  
  Open-source distribution integrating OpenMRS (EMR), ERPNext (billing + inventory), OpenELIS (laboratory), and DCM4CHEE (radiology/PACS) into one deployment . Originally incubated by Thoughtworks for low-resource hospital settings, with production deployments in children's hospitals across Africa and the Middle East . Best for turnkey hospital information system needs.

- **[GNU Health](https://github.com/gnuhealth)**  
  Python-based system focused on public health and hospital information management, built on the Tryton framework . GPL-2.0 licensed. Authentication relies on basic Tryton framework with username/password, lacking native MFA and OAuth2 support . Best suited for public health and hospital management contexts.

- **[Oscar EMR](https://github.com/Oscar-EMR/Oscar-EMR)**  
  Canadian-developed open-source EMR focused on primary care practice management, with substantial deployment in Canadian clinics . Features TOTP-based 2FA compatible with standard authenticator apps and SHA-256 password hashing . Can be adapted for behavioral health workflows.

- **[Medplum](https://github.com/medplum/medplum)**  
  Developer-friendly, FHIR-native healthcare platform with TypeScript + React frontend and Node.js + PostgreSQL backend . Apache-2.0 licensed (permissive for closed-source commercial clinical SaaS) . HL7 FHIR R4 compliance for interoperability. Best for building custom clinical applications rather than deploying off-the-shelf.

- **[ERPNext Healthcare](https://github.com/frappe/erpnext)**  
  Healthcare module inside the broader ERPNext ERP. Patient management, appointments, encounters, lab tests, ePrescribing, drug inventory, and billing integrated with ERPNext's HR, Accounting, and CRM modules . Python + Frappe + Vue stack. GPLv3 licensed. Ideal when wanting one ERP for the whole hospital.

- **[Akello](https://github.com/akello-io/akello)**  
  FastAPI-based server for electronic health records with HIPAA, mental health, population health, and primary care focus . Apache-2.0 licensed. Python + React + TypeScript stack. 25 stars with 374 downloads last month, first released 11 months ago .

- **[My Practice](https://github.com/dholbach/my-practice)**  
  Self-hosted practice management software for therapy and coaching, built as a Django 6 monolith with PostgreSQL . Features client management with per-client hourly rates, session-linked invoice items, batch invoicing, PDF generation (bilingual DE/EN), and clinical notes encrypted with Fernet (separate key from disk encryption) . Includes Focus Queue for tasks, analytics dashboard, Google Calendar import, and bank statement CSV import . GDPR-compliant with privacy notices and record of processing activities templates .

- **[Clinical OS](https://github.com/Danihu98/clinical-os)**  
  Local-first clinical operating system for psychologists, built as an Obsidian plugin . Manages patients, visual case formulations (Tolin, ACT, Basic CBT models), session and fee tracking, safety plans, and clinical snapshots . 100% offline with no cloud connections, external APIs, or telemetry . MIT licensed.

- **[prontuario-psicologico](https://github.com/thiagopando/prontuario-psicologico)**  
  Psychological records system developed for psychologists to record and manage clinical information with focus on confidentiality, organization, and usability . Web application with Node.js backend, SQLite database, and responsive HTML/Tailwind CSS interface . Features psychologist authentication, patient registration, session records (prontuários), print functionality, and access restriction so each psychologist only views their own data .

- **[Behavioral Health Vault (BHV)](https://github.com/KathiraveluLab/BHV)**  
  Minimal Python-based application enabling healthcare networks to store and retrieve patient-provided images (photographs and scanned drawings) along with associated textual narratives . Complements traditional EHRs by capturing the recovery journey of people with serious mental illnesses . Admin-level access for system administrators, straightforward email-based signups, and single-command execution .

- **[Hope Cope Heal (HCH)](https://github.com/UTDallasEPICS/hch)**  
  Full-stack behavioral-health operations platform built as a Nuxt 4 single codebase . Manages end-to-end lifecycle from prospective client intake to active telehealth sessions and audited clinical documentation . Features Client Portal (task-based intake), Clinician Workspace (caseload-scoped notes and calendars), and Admin Command (clinic-wide governance, metrics, final note approvals) . SQLite with Prisma ORM, Better Auth email OTP passwordless login, TipTap rich text editor, and FullCalendar integration .

### Additional Strong Open-Source Options

- **Sessions Health** — Cloud-based free EHR built for mental health professionals with therapy-focused workflows (progress notes, intake forms, clinically focused templates). Free for up to 3 clients; paid plans from $39/mo .
- **CarePatron** — Cloud-based free EHR for solo practitioners and small teams with unlimited clients on the free plan. HIPAA-compliant document management with electronic signatures .
- **CharmHealth** — Cloud-based free EHR and practice management for small clinics. Free for up to 50 patient encounters per month; paid from $25/mo .
- **Healthie** — Virtual-first EHR for wellness, nutrition, and mental health providers. Free for up to 10 active clients; paid from $49/mo .
- **Clinical OS (Obsidian Plugin)** — Local-first clinical operating system for psychologists with visual case formulations, session tracking, and safety plans. 100% offline, MIT licensed .

**Frameworks for building custom behavioral health EHR solutions**: For general-purpose EHR with behavioral health customization, **OpenEMR** provides the most mature foundation with ONC certification and extensive module ecosystem . For solo practitioners wanting self-hosted practice management, **My Practice** offers a production-ready Django monolith with encrypted clinical notes and GDPR compliance tools . For local-first, offline psychotherapy documentation, **Clinical OS** provides an Obsidian-based approach with visual case formulation . For developer teams building custom clinical SaaS, **Medplum** offers a permissive Apache-2.0 FHIR-native platform . For small clinics wanting a complete operations platform, **HCH** demonstrates a modern Nuxt 4 stack with client portal, clinician workspace, and admin governance . Note that true behavioral health EHR with specialized clinical content (DSM-5, treatment planning, outcomes measurement) remains largely commercial territory; open-source stacks provide general EHR capabilities that require significant customization for behavioral health workflows.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Behavioral health EHR tools must comply with HIPAA, 42 CFR Part 2 (for substance use disorder records), GDPR, and applicable state privacy laws regarding mental health data.
- Self-hosted open-source solutions require proper infrastructure, security hardening, and ongoing maintenance. Clinical data encryption at rest and in transit is essential but often requires manual configuration in open-source systems .
- The open-source ecosystem provides strong general-purpose EHR capabilities, but specialized behavioral health functionality (DSM-5 coding, treatment plan templates, outcomes measurement, insurance billing for mental health) remains primarily a commercial offering.

---

**Made for therapists, psychiatrists, counselors, behavioral health clinics, and mental health technologists.**  
Let's make behavioral health EHR more open, transparent, and clinician-friendly.
