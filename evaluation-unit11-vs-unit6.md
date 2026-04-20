# Evaluation: Unit 11 vs Unit 6 | SRM_PCOM7E
**Student:** Nankyer Dawuk | **Role:** Digital Lead

---

## Comparative Evaluation of Unit 6 and Unit 11 Deliverables

### Unit 6 – Risk Identification Report (Team)

The Unit 6 Risk Identification Report was a team-produced status document that applied:

- **STRIDE** for current IT infrastructure assessment
- **NIST SP 800-30** for digitalization risk evaluation
- A qualitative **1–3 severity-likelihood scale** to classify risks as High, Medium, or Low

The scope was limited to cybersecurity risks within Pampered Pets' IT systems and proposed digital initiatives. Disaster recovery was addressed only as a general recommendation to "deploy cloud services with DR capabilities," and GDPR compliance was covered in a single sentence. While the document provided a solid and structured foundation for risk identification, it did not produce measurable, financially quantified outputs that an organisation could act upon strategically.

---

### Unit 11 – Executive Summary (Independent)

The Unit 11 Executive Summary, authored independently, demonstrated advancement across every dimension:

**Methodology**
- Qualitative ratings were replaced by **FMEA-based Risk Priority Number (RPN)** calculations, scoring risks on Severity, Occurrence, and Detectability on a 1–10 scale each
- RPN scores reached up to **240** for supplier quality deviation
- **Monte Carlo simulation** of 10,000 iterations yielded a **74% annual probability** of at least one significant quality failure
- Annualised expected supply chain loss calculated at **£410,500**

**Risk Scope**
- Expanded from cyber-only to encompass product quality, supply chain disruption, geopolitical and regulatory risk, and full business continuity planning

**Disaster Recovery**
- Advanced from a conceptual mention to a fully specified **AWS active-active multi-region architecture** with sub-one-minute RTO and RPO
- Incorporated AWS Route 53, RDS Multi-AZ synchronous replication, Auto Scaling, Shield Standard
- Vendor lock-in mitigation through Docker, Kubernetes, and Terraform

**GDPR Compliance**
- Expanded from one sentence to a complete legal compliance framework covering:
  - Standard Contractual Clauses
  - Data Protection Officer appointment
  - Transfer Impact Assessments
  - Records of Processing Activities
  - Article 83 fine exposure of up to **4% of global annual turnover**

---

### Summary of Progression

The progression between the two documents demonstrates that the theoretical frameworks introduced across the module — Monte Carlo simulation from Units 7 and 8, disaster recovery architecture from Units 9 and 10, and enterprise risk governance from Unit 5 — were not merely studied but successfully internalised and applied independently to a more complex scenario. This represents the full arc of learning from initial risk identification to professional-grade quantitative risk management practice.

---

*University of Essex Online | MSc Cybersecurity | SRM_PCOM7E*
