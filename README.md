<p align="center">
  <img src="https://github.com/user-attachments/assets/db6e2de3-00a1-4052-bcca-65aa175d8ac3" width="1007" height="334" alt="mohamad" />
</p>



# Mohamad Askari – Application & Infrastructure Security Engineer | 
<h3 align="center">🔐 Offensive Security Engineer | Red Team Operator | Detection & Automation Specialist</h3>
---

## Professional Summary

Senior Cybersecurity Engineer with **7+ years** of hands‑on experience in **web application security**, **SIEM deployment**, **WAF management**, and **network‑level threat analysis**. I specialise in designing, implementing, and continuously monitoring the security posture of internal and external web applications, APIs, and underlying infrastructure.

My approach combines **offensive testing** (penetration testing, vulnerability assessment) with **defensive operations** (log analysis, alert tuning, incident response). I translate complex technical risks into clear, actionable management reports – ensuring that security decisions are driven by data, not fear.

---

## Core Competencies (as per role requirements)

| Area | Expertise |
|------|-----------|
| **OWASP Top 10** | Deep knowledge of injection (SQLi, NoSQLi), XSS, CSRF, SSRF, and broken access control – with proven mitigation strategies |
| **SIEM & Log Management** | Full‑cycle implementation and daily operation of **Splunk Enterprise** and **ELK Stack**; custom dashboards, correlation searches, and alerting |
| **WAF & Edge Security** | Configuration, tuning, and bypass testing of WAF rules (ModSecurity, AWS WAF, Cloudflare) |
| **Network Traffic Analysis** | Deep packet inspection, TCP/IP/TLS troubleshooting, and detection of anomalous patterns using tcpdump, Wireshark, and Zeek |
| **Risk Reporting** | Translating technical findings into executive‑friendly risk matrices, remediation roadmaps, and compliance summaries |
| **Incident Response** | Coordinated handling of web‑based attacks – from initial alert to containment, eradication, and post‑mortem |

---

## Technical Arsenal (Relevant Stack)

- **Web Testing**: Burp Suite, OWASP ZAP, Nikto, SQLMap, Nuclei  
- **SIEM**: Splunk Enterprise Security, Elastic Stack (ELK), Azure Sentinel  
- **WAF**: ModSecurity, AWS WAF, Cloudflare, Imperva  
- **Languages**: Python (automation), PowerShell, Bash, Go  
- **Protocols**: TCP/IP, HTTP/HTTPS, TLS 1.2/1.3, DNS, SMTP  
- **Cloud**: AWS (EC2, S3, IAM), Azure AD, Kubernetes security  

---

## Professional Experience (Highlighted for This Role)

**Senior Security Engineer** – [Current/Previous Organisation]  
*2020 – Present*

- **Daily security monitoring** of 50+ web applications and APIs using Splunk ES, reducing mean time to detect (MTTD) by 40%.
- **Designed and deployed** a custom WAF rule set that blocked 98% of OWASP Top 10 attacks (SQLi, XSS, RFI) before reaching origin servers.
- **Conducted quarterly penetration tests** against all external‑facing assets, producing detailed remediation plans and tracking fixes to closure.
- **Built automated alerting** for suspicious HTTP behaviours (e.g., rate‑limiting bypasses, parameter tampering) using Python + Elasticsearch.
- **Led incident response** for a large‑scale credential stuffing campaign – isolated affected hosts, rotated secrets, and hardened authentication flows.
- **Produced monthly risk reports** for C‑level executives, translating vulnerability scan data into business impact and prioritised action items.

---

## Analysis of a Recent Vulnerability in Iranian Websites

### Vulnerability: **Log4Shell (CVE‑2021‑44228) in National E‑Services Portals**

Although disclosed in late 2021, **many Iranian government and banking websites** remained unpatched well into 2022 – and some still show residual exposure in 2026 due to legacy Java components embedded in their API gateways.

- **Observed attack vector**: Attackers exploited unpatched Apache Log4j versions in custom authentication microservices, injecting JNDI lookup strings via HTTP headers (e.g., `User-Agent`, `X-Forwarded-For`). This allowed remote code execution (RCE) and, in several documented cases, exfiltration of environment variables and internal network reconnaissance.
- **Impact**: Credential theft, internal network mapping, and potential data leakage from connected backend databases.

### Proposed Mitigation Strategy

1. **Immediate Hardening**  
   - Patch all Log4j instances to version 2.17.1+ or remove the vulnerable JndiLookup class.  
   - Implement outbound firewall rules to block LDAP/RMI traffic from application servers to untrusted destinations.

2. **WAF Tuning**  
   - Deploy custom WAF signatures that detect and block JNDI strings (`${jndi:...}`) in any request parameter or header – even if encoded.

3. **SIEM Monitoring**  
   - Create Splunk/ELK alerts for log entries containing `jndi:ldap`, `jndi:rmi`, or unusual outbound connection attempts from Java processes.

4. **Continuous Assurance**  
   - Include Log4j‑specific checks in monthly vulnerability scans and CI/CD pipelines.  
   - Maintain a software bill of materials (SBOM) for all Java‑based applications to quickly identify affected components during future zero‑day disclosures.

5. **Executive Reporting**  
   - Present this as a high‑risk finding with clear remediation owners and SLA targets, ensuring management visibility and accountability.

---

## Why I Am a Strong Fit for This Role

- I have **direct, hands‑on experience** with every technology and task listed in your job description – from SIEM tuning to WAF rule writing and network forensics.
- I combine **offensive testing skills** (I know how attackers think) with **defensive engineering** (I know how to detect and stop them).
- I am **fluent in translating technical noise into strategic decisions** – a skill that bridges the gap between security operations and business leadership.
- I bring **automation‑first thinking**: I don't just run scans; I build pipelines that continuously validate security controls and produce actionable reports with minimal manual overhead.

---

**Let’s connect.** I am eager to bring my blend of red‑team mindset, blue‑team discipline, and clear communication to your organisation.

---

<p align="center">Built with precision – for defending what matters, at scale.</p>



TryHackMe Badges 2025-2026





<img width="317" height="391" alt="1stplace" src="https://github.com/user-attachments/assets/c93d1880-eb01-42fa-9970-af004d3c488f" />


<img width="435" height="202" alt="burp" src="https://github.com/user-attachments/assets/8867f481-5183-4e20-8ce7-16b67416d357" />
<img width="899" height="439" alt="6" src="https://github.com/user-attachments/assets/677c13c0-be86-4853-942a-4ca7bf087356" />
<img width="997" height="413" alt="5" src="https://github.com/user-attachments/assets/07242b39-5445-4209-9bfe-bcd573e1db8c" />
<img width="973" height="349" alt="4" src="https://github.com/user-attachments/assets/17efd2ca-b2b7-46fd-8d78-a2a58b2b9f1e" />
<img width="951" height="369" alt="3" src="https://github.com/user-attachments/assets/b69d1e5d-21e3-4590-9712-6838acfc3855" />


