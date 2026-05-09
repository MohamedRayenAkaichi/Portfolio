# Cybersecurity Portfolio – Mohamed Rayen AKAICHI

Welcome to my cybersecurity portfolio.  
I am a Master-level cybersecurity engineering student (CY Tech, double degree) focusing on Blue Team / SOC, vulnerability management, and security governance.

## About me

- 5th year (Bac+5) cybersecurity engineering student – looking for a 6‑month end-of-studies internship starting May 2026 (Paris/IDF or remote EU).
- Hands-on experience with SIEM (Wazuh/ELK), network security (firewalls, IDS/IPS), vulnerability management (CVSS), security awareness (GoPhish), and incident response basics.
- ISC2 Certified in Cybersecurity (CC), strengthening my foundations in security principles, access control, network security, security operations, and incident response/BCDR.

## Main skills

- **Security operations / Blue Team**: Wazuh SIEM, ELK, Suricata (IDS/IPS), CrowdSec, firewalls (OPNsense, iptables/nftables), Wireshark.
- **Web infrastructure security**: Nginx (reverse proxy, hardening), ModSecurity WAF (OWASP CRS), DDoS mitigation (Layer 4 & 7), Docker containerization.
- **Vulnerability management**: CVSS scoring, prioritization, remediation tracking, security reporting.
- **Governance / GRC**: ISO 27001, EBIOS RM, security policies and procedures, action plan follow-up.
- **Security awareness**: GoPhish phishing simulations, KPI tracking (click rates), recommendations and action plans.
- **Forensics & malware (basics)**: Autopsy, malware analysis in isolated lab environment.
- **Languages**: French (C1), English (C1), Arabic (native).

## Projects

This repository showcases a selection of my projects:

1. **Wazuh SIEM Lab – Detection & Incident Handling**  
   Deployment of a Wazuh-based SIEM home lab, custom detection rules, simulated attacks, and initial incident triage.

2. **Vulnerability Management – CVSS & Reporting**  
   Vulnerability tracking with CVSS scoring, prioritization, remediation tracking, and reporting templates.

3. **Phishing Awareness – GoPhish Campaigns & KPI**  
   Phishing simulation campaigns with GoPhish, KPI analysis (click/submit rates), recommendations and action plan.

4. **Malware Analysis – Static & Dynamic Analysis (Lab)**  
   Static and dynamic analysis of a malware sample in an isolated environment, IoC extraction, and detection recommendations.

5. **Web Infrastructure Security – Mitigating DDoS & Injection Attacks**  
   Design and deployment of a multi-layer Defense-in-Depth architecture protecting a vulnerable web application (DVWA) without modifying its source code. The solution covers:
   - **Layer 4 hardening**: Linux kernel tuning (SYN Cookies via sysctl) and dynamic per-IP rate limiting (iptables hashlimit) to neutralize SYN Flood attacks.
   - **Layer 7 protection**: Nginx reverse proxy hardening (aggressive timeouts) against Slowloris, and ModSecurity WAF with OWASP CRS v3 to block SQL injection, XSS, and XXE — including virtual patching of sensitive endpoints.
   - **Active response (IPS)**: CrowdSec behavioral detection (Leaky Bucket algorithm) automatically banning malicious IPs at the firewall level via IPSet upon threshold breach.
   - **SOC dashboard**: Metabase connected to CrowdSec's database for real-time threat visualization and KPI reporting.  
   Stack: Nginx, ModSecurity, CrowdSec, iptables, Docker, Metabase — 100% open-source.



## Contact

- Email: mohamedrayenakaichi@gmail.com  
- Location: Paris / Île-de-France (open to remote EU)  
- Looking for: 6‑month cybersecurity internship – Blue Team / SOC / GRC / Security Awareness
