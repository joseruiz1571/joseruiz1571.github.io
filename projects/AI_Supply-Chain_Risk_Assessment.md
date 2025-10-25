# AI Supply Chain Risk Assessment

**Vendor:** Horizon Labs (AI-Enabled SaaS Provider)  
**Client:** Oscorp Industries – R&D Division  
**Analyst:** Jose Ruiz-Vazquez  
**Assessment Type:** Third-Party AI Risk Assessment (TPRM + AI Governance)  
**Frameworks Applied:** NIST AI RMF 1.0, NIST Cybersecurity Framework 2.0, ISO/IEC 42001 (AI Management System), CIS Controls v8.1

---

## 🧾 Executive Summary

Horizon Labs provides AI-driven data analytics services supporting Oscorp’s bioengineering research.  

Because the SaaS platform processes **scientific and potentially health-related data** through **machine learning models**, the engagement expanded beyond traditional cybersecurity risk to include **AI-specific governance, transparency, and data-integrity risks**.

The assessment, aligned with **NIST AI RMF** and **ISO/IEC 42001**, identified governance and technical gaps across data provenance, model monitoring, and security control maturity.  

While Horizon Labs demonstrates awareness of baseline security practices, its lack of formal AI risk management and model oversight introduces potential **compliance, reputational, and safety risks**.

| Risk Area                        | Severity  | NIST CSF Domain | NIST AI RMF Function                        | ISO/IEC 42001 Clause          | CIS Control v8.1 | Notes                                     |
| -------------------------------- | --------- | --------------- | ------------------------------------------- | ----------------------------- | ---------------- | ----------------------------------------- |
| Lack of AI governance policy     | 🔴 High   | Govern          | **GOV-1** – Establish accountability        | §5.3 Leadership               | 17.3             | No defined Responsible AI oversight       |
| Missing data lineage             | 🔴 High   | Identify        | **MAP-2** – Document data inputs            | §8.2.2 Data management        | 3.1              | Risk to model integrity & reproducibility |
| No bias or explainability review | 🟠 Medium | Protect         | **MEA-1** – Assess AI trustworthiness       | §8.2.3 Model development      | 10.2             | Transparency & ethical risk               |
| No vuln. mgmt / pen-testing      | 🔴 High   | Protect         | **MAN-2** – Mitigate system vulnerabilities | §8.2.4 Security controls      | 7.3 / 18.1       | Technical debt in model infrastructure    |
| Informal AI incident response    | 🟠 Medium | Respond         | **MAN-4** – Respond to AI failures          | §8.3 Monitoring & improvement | 17.1             | No defined AI failure escalation path     |

---

## 📊 Risk Visualization

![Horizon Labs AI Risk Heatmap](assets/images/Horizon_Labs_AI_TPRM_Heatmap.png)

**Figure: Horizon Labs AI Supply Chain Risk Heatmap**  
This visualization maps vendor control gaps across **AI RMF** and **CSF** categories, emphasizing the overlap between traditional cybersecurity and AI system governance.  

High-impact findings cluster in **Govern** (accountability and oversight) and **Manage** (incident response and resilience), reflecting early-stage maturity common to emerging AI vendors.

---

## 🧠 Analyst Commentary

- **AI Governance Integration:**  
    The lack of formal AI oversight mechanisms—such as a Responsible AI policy or model documentation—creates systemic risk as AI becomes central to Oscorp’s R&D operations.
    
- **Data & Model Integrity Risks:**  
    Absence of data provenance tracking reduces the ability to detect data poisoning or model drift, critical to ensuring trustworthy AI outcomes.
    
- **Bridging Cyber & AI Controls:**  
    Mapping AI RMF’s **Govern–Map–Measure–Manage** functions alongside NIST CSF clarified how cybersecurity baselines extend into AI governance—especially in ensuring confidentiality, integrity, and explainability.
    

---

## 📈 Recommended Next Steps

1. **Establish a Responsible AI Governance Policy:**  
    Define roles, accountability, and model oversight procedures (AI RMF GOV-1, ISO/IEC 42001 §5.3).
    
2. **Implement Data Provenance and Model Documentation:**  
    Maintain lineage records and publish model cards summarizing data sources, bias checks, and limitations.
    
3. **Adopt Continuous Vulnerability and Model Risk Management:**  
    Integrate both cybersecurity and AI-specific monitoring (e.g., adversarial testing, dataset validation).
    
4. **Develop AI-Incident Response Playbook:**  
    Include procedures for handling model errors, ethical escalations, and retraining events.
    
5. **Align with ISO/IEC 42001 Certification Path:**  
    Position Horizon Labs for compliance with emerging AI management system standards.
    

---

## 🎓 Learning Reflection

- Extending a traditional **TPRM engagement into an AI supply chain context** revealed how **AI systems amplify existing vendor risks**—from data handling to accountability gaps.
    
- Applying **NIST AI RMF** in tandem with **NIST CSF** demonstrated the importance of **integrating trustworthiness, transparency, and security** into vendor evaluations.
    
- This project reinforced that **AI governance is not separate from cybersecurity GRC**—it is its natural evolution.
    

---

## 🧩 References

- [NIST AI Risk Management Framework 1.0](https://www.nist.gov/itl/ai-risk-management-framework)
    
- [ISO/IEC 42001:2023 – AI Management System Standard](https://www.iso.org/standard/81230.html)
    
- [NIST Cybersecurity Framework 2.0](https://www.nist.gov/cyberframework)
    
- [CIS Controls v8.1](https://www.cisecurity.org/controls)
    
- [ENISA AI Threat Landscape 2023](https://www.enisa.europa.eu/publications/artificial-intelligence-threat-landscape)
    

**Artifact Type:** AI Supply Chain Risk Assessment Report  
**Estimated Effort:** 4–5 hours  
**Learning Focus:** AI RMF mapping, Responsible AI governance, vendor risk assessment
