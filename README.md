# 🛡️ Risk Management Framework (RMF) — Enterprise Security Case Study

This project presents a complete, enterprise-grade **Risk Management Framework (RMF)** aligned with
- **ISO 27005 (Risk Management)**
- **NIST SP 800-30 (Risk Assessment Guide)**
- **NIST RMF**
- **ISO 27001 Annex A Controls**
- **CIS Controls**

This framework demonstrates your capability as a **Cybersecurity Consultant** to identify, assess, treat, and monitor risks within an organizational environment.

---

# 📘 1. Project Summary

The purpose of this RMF project is to:

- Identify critical assets  
- Analyze threats & vulnerabilities  
- Quantify cybersecurity risks  
- Build a complete enterprise risk register  
- Recommend appropriate mitigation actions  
- Track residual risks  
- Provide governance-level reporting  

This project mirrors **real-world consulting** work performed for compliance, audits, and risk governance boards.

---

# 🎯 2. Objectives

- Build a structured cyber risk management process  
- Provide a clear methodology for risk scoring  
- Create a complete risk register  
- Map treatment plans to ISO controls  
- Provide business-aligned decision-making support  
- Reduce organizational exposure to cyber threats  

---

# 🧩 3. Methodology Used

This RMF follows a hybrid of **NIST** and **ISO 27005**:

### ✔ Step 1 – Asset Identification  
### ✔ Step 2 – Threat Identification  
### ✔ Step 3 – Vulnerability Identification  
### ✔ Step 4 – Impact & Likelihood Scoring  
### ✔ Step 5 – Risk Calculation (R = I × L)  
### ✔ Step 6 – Risk Treatment  
### ✔ Step 7 – Residual Risk Evaluation  
### ✔ Step 8 – Risk Monitoring & Review  

---

# 🖼️ 4. RMF Architecture Diagram (ASCII)

       ┌────────────────────────┐
       │     Asset Inventory    │
       └───────────┬────────────┘
                   │
         ┌─────────▼─────────┐
         │ Threat & Vulnerability │
         │      Identification     │
         └─────────┬─────────┘
                   │
         ┌─────────▼─────────┐
         │   Risk Analysis    │
         │ Impact × Likelihood│
         └─────────┬─────────┘
                   │
         ┌─────────▼─────────┐
         │   Risk Treatment   │
         │ Avoid/Reduce/Share │
         └─────────┬─────────┘
                   │
         ┌─────────▼─────────┐
         │ Residual Risk Eval │
         └─────────┬─────────┘
                   │
         ┌─────────▼─────────┐
         │Continuous Monitoring│
         └────────────────────┘

---

# 🏛️ 5. Asset Inventory

| Asset | Type | Value | Owner |
|-------|------|--------|--------|
| Customer Database | Information | High | IT/DB Team |
| Web Application | System | High | DevOps |
| Employee Laptops | Endpoint | Medium | IT |
| Active Directory | Identity | High | Security |
| Cloud VM (Prod) | Infrastructure | High | Cloud Ops |

---

# 🔍 6. Threat & Vulnerability Identification

### ✔ Top Threat Categories
- Malware attacks  
- Phishing  
- Unauthorized access  
- Insider threats  
- Ransomware  
- Data leakage  
- Misconfigurations  
- Denial of service (DoS)  

### ✔ Example Vulnerabilities
- Weak passwords  
- Misconfigured firewall rules  
- Missing patches  
- Insecure APIs  
- Lack of MFA  
- Unencrypted backups  

---

# 📊 7. Risk Scoring Methodology

Both **Likelihood** and **Impact** are scored from **1 to 5**:

| Score | Likelihood | Impact |
|--------|-------------|----------|
| 1 | Rare | Negligible |
| 2 | Unlikely | Minor |
| 3 | Possible | Moderate |
| 4 | Likely | Major |
| 5 | Almost Certain | Critical |

### ✔ Risk Formula  
RISK = Likelihood × Impact

---

# 🔥 8. Risk Heat Map

Impact →
5 | H H C C C
4 | M H H C C
3 | L M H H C
2 | L L M M H
1 | L L L L M
1 2 3 4 5
Likelihood →
*L = Low, M = Medium, H = High, C = Critical*

---

# 📒 9. Enterprise Risk Register (Detailed)

Below is a **consultant-level risk register** included in the project.

| ID | Risk Description | Likelihood | Impact | Risk Score | Treatment | Status |
|----|------------------|------------|---------|------------|-----------|--------|
| R1 | Weak Passwords → Account Compromise | 4 | 4 | 16 (High) | Mitigate: MFA + Password Policy | In Progress |
| R2 | Missing Patches → Exploitation | 3 | 5 | 15 (High) | Mitigate: Patch Management | Open |
| R3 | SQL Injection → Data Breach | 3 | 5 | 15 (High) | Mitigate: WAF + Input Validation | Open |
| R4 | No Backup Encryption → Data Leakage | 2 | 5 | 10 (Medium) | Mitigate: AES-256 Encryption | Completed |
| R5 | Insider Threat → Data Theft | 2 | 4 | 8 (Medium) | Reduce: RBAC + Monitoring | In Progress |
| R6 | DDoS Attack → Downtime | 3 | 4 | 12 (High) | Share: Anti-DDoS Service | Planned |
| R7 | Cloud Misconfiguration → Exposure | 4 | 5 | 20 (Critical) | Mitigate: Cloud Hardening | Urgent |
| R8 | Phishing → Credential Theft | 5 | 4 | 20 (Critical) | Mitigate: Awareness + Email Filter | In Progress |

---

# 🎛️ 10. Risk Treatment Options

### ✔ Avoid  
Disable insecure services, remove risky features.

### ✔ Mitigate  
Implement controls to reduce likelihood or impact.

### ✔ Transfer  
Use insurance, cloud services, or external providers.

### ✔ Accept  
Business signs off if risk falls within acceptable level.

---

# 🧠 11. Control Mapping (ISO 27001 Annex A)

| ISO Control | Applied Control |
|-------------|------------------|
| A.5 | Information Security Policy |
| A.6 | Governance & Roles |
| A.8 | Asset Classification |
| A.9 | Access Controls |
| A.12 | Patch Management |
| A.13 | Network Security |
| A.14 | Secure Development |
| A.16 | Incident Management |
| A.17 | Business Continuity |

---

# 🔒 12. Residual Risk Evaluation

After treatments:

| Risk ID | Initial Score | Residual Score | Residual Rating |
|---------|----------------|-----------------|------------------|
| R1 | 16 | 8 | Medium |
| R2 | 15 | 6 | Low |
| R3 | 15 | 6 | Low |
| R4 | 10 | 3 | Low |
| R5 | 8 | 4 | Low |
| R6 | 12 | 9 | Medium |
| R7 | 20 | 10 | Medium |
| R8 | 20 | 8 | Medium |

Residual risk is documented for governance review.

---

# 🔁 13. Monitoring & Continuous Improvement

- Quarterly risk reviews  
- Monthly vulnerability scans  
- Annual penetration testing  
- Automated alerting via SIEM  
- Continuous compliance checks  
- Control maturity tracking  

---

# 📦 14. Deliverables Included

This project folder includes:

- Full Risk Register  
- RMF Process Documentation  
- Risk Heat Map  
- Control Mapping  
- Threat/Vulnerability Inventory  
- Residual Risk Analysis  
- Treatment Plan Recommendations  

---

# 📈 15. Key Outcomes

- Full risk visibility across enterprise  
- Prioritization of high-impact risks  
- Control alignment with ISO/NIST frameworks  
- Strong executive-ready risk reporting  
- Reduced likelihood of major cyber incidents  
- Governance maturity improvement  

---

# 🧾 16. Conclusion

This Risk Management Framework demonstrates your capability to:

- Identify critical cyber risks  
- Perform quantitative & qualitative assessments  
- Build enterprise risk registers  
- Recommend effective controls  
- Communicate risks to executives  
- Support ongoing governance initiatives  

This is **consultant-level work** suitable for enterprise security roles and compliance-focused cybersecurity positions.

---

# 📬 Contact

**GitHub:** https://github.com/rajbharti-cyber  
**LinkedIn:** https://www.linkedin.com/in/rajbharti-cybersecurity/
