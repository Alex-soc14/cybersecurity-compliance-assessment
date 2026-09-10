# Risk Register

## Risk Assessment Methodology

Risk is calculated using:

**Risk Score = Likelihood × Impact**

### Likelihood

| Score | Description |
|---|---|
| 1 | Rare |
| 2 | Unlikely |
| 3 | Possible |
| 4 | Likely |
| 5 | Almost certain |

### Impact

| Score | Description |
|---|---|
| 1 | Insignificant |
| 2 | Minor |
| 3 | Moderate |
| 4 | Major |
| 5 | Severe |

### Risk Classification

| Score | Level |
|---|---|
| 1–4 | Low |
| 5–9 | Medium |
| 10–16 | High |
| 17–25 | Critical |

---

## Risk Register

| ID | Asset | Threat | Vulnerability | Likelihood | Impact | Risk Score | Risk Level | Treatment | Residual Likelihood | Residual Impact | Residual Risk | Residual Level |
|---|---|---|---|---:|---:|---:|---|---|---:|---:|---:|---|
| RISK-001 | Customer Database | Ransomware | Backup restoration is not regularly tested and no formal disaster recovery procedure is defined | 3 | 5 | 15 | High | Updated backups, disaster recovery procedures, security awareness and phishing training | 2 | 3 | 6 | Medium |
| RISK-002 | Microsoft 365 / Corporate Accounts | Phishing / Credential Theft | MFA not implemented for all accounts | 4 | 5 | 20 | Critical | MFA for all accounts, Conditional Access, managed devices, encryption and access controls | 2 | 3 | 6 | Medium |
