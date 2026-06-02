# Multi-Framework Control Matrix

A cross-reference matrix aligning **NIST CSF 2.0**, **NIST 800-53 Rev 5**, **ISO 27001:2022**, **SOC 2 TSC**, and **CIS Controls v8**.

Designed for organizations managing multiple compliance frameworks.

## Overview

- **Total Controls**: 30
- **Frameworks**: 5
- **Domains**: 6 (Identify, Govern, Protect, Detect, Respond, Recover)

## Legend

| Domain | Meaning |
|--------|---------|
| **ID** | Identify |
| **GV** | Govern |
| **PR** | Protect |
| **DE** | Detect |
| **RS** | Respond |
| **RC** | Recover |

**SOC 2**: `CC#.#` = Common Criteria `A1.#` = Availability

**Priority**: High (H) • Medium (M) • Low (L)

---

## Control Matrix

| Domain | Control | Description | NIST CSF 2.0 | NIST 800-53 r5 | ISO 27001:2022 | SOC 2 TSC | CIS v8 | Priority |
|--------|---------|-------------|--------------|----------------|----------------|-----------|--------|----------|
| **ID** | Asset inventory | Hardware & software asset tracking | ID.AM-01, ID.AM-02 | CM-8, PM-5 | A.5.9, A.5.10 | CC6.1, CC6.3 | 1, 2 | **H** |
| **ID** | Business environment | Mission, objectives, stakeholder dependencies | ID.BE-01, ID.BE-02 | PM-11, SA-14 | A.5.29, A.5.30 | CC1.1, CC1.2 | 1 | M |
| **ID** | Risk assessment | Threat identification and risk scoring | ID.RA-01, ID.RA-03, ID.RA-05 | RA-3, RA-5 | A.6.1, A.8.8 | CC3.1, CC3.2 | 4, 18 | **H** |
| **ID** | Supply chain risk | Third-party and vendor risk management | ID.SC-01, ID.SC-02 | SA-9, SR-3 | A.5.19, A.5.20 | CC9.2 | 15 | M |
| **ID** | Improvement | Lessons learned, process improvements | ID.IM-01, ID.IM-02 | CA-7, PM-31 | A.5.27 | CC4.1, CC4.2 | 18 | L |
| **GV** | Organizational context | Mission, legal, regulatory obligations | GV.OC-01, GV.OC-02, GV.OC-03 | PL-1, PM-1 | A.5.1, A.5.31 | CC1.1, CC2.1 | 4 | **H** |
| **GV** | Risk management strategy | Risk appetite, tolerance, and strategy | GV.RM-01, GV.RM-02, GV.RM-06 | PM-9, RA-1 | A.5.1, A.6.1 | CC3.1, CC9.1 | 4 | **H** |
| **GV** | Roles & responsibilities | CISO, security team structure, accountability | GV.RR-01, GV.RR-02, GV.RR-04 | PS-7, PM-2 | A.5.2, A.5.3 | CC1.3, CC1.4 | 4 | **H** |
| **GV** | Policy | Enterprise cybersecurity policies | GV.PO-01, GV.PO-02 | PL-1, PL-4 | A.5.1 | CC2.2 | 4 | M |
| **GV** | Oversight | Audit, review, board-level reporting | GV.OV-01, GV.OV-02, GV.OV-03 | CA-2, CA-7 | A.5.35, A.5.36 | CC4.1, CC4.2 | 18 | M |
| **PR** | Identity & access management | User auth, MFA, least privilege | PR.AA-01, PR.AA-02, PR.AA-05 | AC-2, IA-2, IA-5 | A.5.15, A.5.16, A.5.17 | CC6.1, CC6.2, CC6.3 | 5, 6 | **H** |
| **PR** | Privileged access management | Admin accounts, PAM controls | PR.AA-05, PR.AA-06 | AC-6, AC-17 | A.5.15, A.8.2 | CC6.3, CC6.7 | 5 | **H** |
| **PR** | Data protection | Encryption at rest and in transit | PR.DS-01, PR.DS-02, PR.DS-10 | SC-8, SC-28 | A.8.11, A.8.24 | CC6.7, CC6.8 | 3 | **H** |
| **PR** | Data classification | Labeling and handling standards | PR.DS-01, PR.DS-10 | RA-2, MP-3 | A.5.12, A.5.13 | CC6.1 | 3 | M |
| **PR** | Secure configuration | Hardening baselines, configuration management | PR.PS-01, PR.PS-02 | CM-2, CM-6, CM-7 | A.8.8, A.8.9 | CC7.1 | 4, 12 | **H** |
| **PR** | Network security | Segmentation, firewall, DMZ | PR.IR-01, PR.IR-02 | SC-7, SC-5 | A.8.20, A.8.21, A.8.22 | CC6.6, CC6.7 | 12, 13 | **H** |
| **PR** | Endpoint protection | EDR, antimalware, device controls | PR.PS-01, PR.PS-04 | SI-3, SI-4 | A.8.7 | CC6.8 | 10 | **H** |
| **PR** | Patch management | Vulnerability remediation cadence | PR.PS-02, PR.MA-01 | SI-2, MA-2 | A.8.8 | CC7.1, CC7.2 | 7 | **H** |
| **PR** | Security awareness training | Training programs, phishing simulation | PR.AT-01, PR.AT-02 | AT-2, AT-3 | A.6.3, A.6.8 | CC1.4, CC2.2 | 14 | M |
| **PR** | Physical security | Facility access and environmental controls | PR.IR-01, PR.PS-01 | PE-1, PE-3 | A.7.1, A.7.2, A.7.3 | CC6.4 | 3 | M |
| **PR** | Secure development / SDLC | AppSec, code review, SAST/DAST | PR.PS-02, PR.PS-03 | SA-3, SA-11, SA-15 | A.8.25, A.8.27, A.8.28 | CC8.1 | 16 | M |
| **DE** | Continuous monitoring | SIEM, log collection, alerting | DE.CM-01, DE.CM-06, DE.CM-09 | AU-2, AU-12, SI-4 | A.8.15, A.8.16 | CC7.2, CC7.3 | 8 | **H** |
| **DE** | Vulnerability management | Continuous scanning and assessment | DE.CM-08 | RA-5, CA-7 | A.8.8 | CC7.1 | 7 | **H** |
| **DE** | Anomaly & event analysis | Behavioral analytics, UBA/UEBA | DE.AE-02, DE.AE-03, DE.AE-06 | SI-4, AU-6 | A.8.16 | CC7.3, CC7.4 | 8, 13 | M |
| **DE** | Audit logging | Log integrity, retention, review | DE.CM-03, DE.AE-03 | AU-3, AU-9, AU-11 | A.8.15 | CC7.2 | 8 | **H** |
| **RS** | Incident response plan | IR policy, roles, playbooks | RS.MA-01, RS.MA-02, RS.MA-03 | IR-1, IR-4, IR-8 | A.5.24, A.5.25 | CC7.4, CC7.5 | 17 | **H** |
| **RS** | Incident analysis | Forensics, RCA, evidence handling | RS.AN-03, RS.AN-06, RS.AN-08 | IR-4, AU-9 | A.5.28 | CC7.4 | 17 | M |
| **RS** | Containment & mitigation | Isolation, eradication, remediation | RS.MI-01, RS.MI-02 | IR-4, SI-7 | A.5.26 | CC7.5 | 17 | **H** |
| **RS** | Communication & disclosure | Stakeholder notification, regulatory reporting | RS.CO-02, RS.CO-03 | IR-6, PT-8 | A.5.24, A.6.8 | CC2.3 | 17 | M |
| **RC** | Recovery planning | BCP/DRP, RTO/RPO objectives | RC.RP-01, RC.RP-02 | CP-2, CP-9 | A.5.29, A.8.13 | A1.2, A1.3 | 11 | **H** |
| **RC** | Backup & restoration | Backup frequency, integrity testing | RC.RP-03, RC.RP-04 | CP-9, CP-10 | A.8.13 | A1.2 | 11 | **H** |
| **RC** | Recovery communication | Stakeholder updates during recovery | RC.CO-03, RC.CO-04 | CP-2, IR-6 | A.5.29 | CC2.3 | 17 | L |

---

## Methodology Note

Mappings are **example alignments** based on common organizational risk appetite and represent one valid interpretation. Many controls span multiple categories; only primary mappings are shown.

**GRC practitioners should validate** these mappings against their specific environment.

### Version References
- NIST CSF 2.0 (February 2024)
- NIST SP 800-53 Revision 5
- ISO/IEC 27001:2022 Annex A
- SOC 2 Trust Services Criteria (2017, updated 2022)
- CIS Controls v8

---

**Interactive Version:** [Multi-Framework Control Matrix](https://cyberlav.io/Multi-Framework_Control_Matrix)  
*(with search and filters)*
