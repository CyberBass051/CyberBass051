# Hi, I'm Pietro 👋
**Cloud & DevSecOps Engineer** · MSc Cybersecurity (Pentesting & Forensics)

Building secure, automated AWS infrastructure, and testing it the way an attacker would.

## 👨‍💻 About

Cloud and DevSecOps engineer with a security-first approach: I design AWS infrastructure as code, automate its guardrails, and probe it from the offensive side. Before moving full-time into security I worked for years as a professional bassist, which is where my discipline, precision and calm under pressure come from.

- 🔐 **Focus:** AWS security automation, Infrastructure as Code, DevSecOps, policy-as-code
- 🚀 **Co-founder of AparCar:** real-time parking-exchange app on an AWS serverless backend
- 🎓 **MSc in Cybersecurity** (Pentesting & Forensics), Grupo Atrium
- 📍 Málaga, Spain · open to remote and relocation

## 🧭 Start here

| If you're hiring for... | Look at |
|---|---|
| Cloud / DevOps / Platform | [☁️ Cloud & DevOps](#️-cloud--devops) |
| Cloud Security / DevSecOps / SecOps | [🛡️ Security](#️-security) |

---

## ☁️ Cloud & DevOps
Infrastructure as code, CI/CD and high availability on AWS.

| Project | Stack | What it proves |
|---|---|---|
| [serverless-secure-codepipeline](https://github.com/CyberBass051/serverless-secure-codepipeline) | CodePipeline, Lambda, API Gateway, Secrets Manager, Terraform | Hardened CI/CD: HMAC-verified webhook, least-privilege IAM, dev → manual approval → prod, documented incident postmortem |
| [alb-asg-ec2](https://github.com/CyberBass051/alb-asg-ec2) | Terraform, ALB, Auto Scaling | Highly available, self-scaling architecture with target-tracking policies |
| [ha-rds-inventory](https://github.com/CyberBass051/ha-rds-inventory) | Aurora Serverless v2, Python | Event-driven, highly available database design |

## 🛡️ Security
Security automation on AWS, plus hands-on offensive and forensic work.

**Cloud security & DevSecOps**

| Project | Stack | What it proves |
|---|---|---|
| [wazuh-auto-scaling](https://github.com/CyberBass051/wazuh-auto-scaling) | Terraform, Wazuh, Trivy, Python | Auto-scaling SIEM fleet in private subnets (IMDSv2, KMS) with policy-as-code remediation |
| [iam-audit-tool](https://github.com/CyberBass051/iam-audit-tool) | Python, GitHub Actions | Scheduled IAM least-privilege audit (MFA, key rotation) with JSON reporting |
| [vulnerability-management-and-risk-remediation](https://github.com/CyberBass051/vulnerability-management-and-risk-remediation) | Python | Scan reports in, prioritized CVE remediation plan and alerts out |

**Offensive security & forensics** (authorized targets and isolated labs only)

| Project | Stack | What it proves |
|---|---|---|
| [network-attack-detection-katas](https://github.com/CyberBass051/network-attack-detection-katas) | Scapy, tcpdump, tshark, PowerShell | 5 attack/detection pairs across TCP, ARP and DNS — SYN flood, RST injection, session hijacking, ARP spoofing (Linux + Windows detection), DNS spoofing |
| [web-exploitation-toolkit](https://github.com/CyberBass051/web-exploitation-toolkit) | Python, Requests, BeautifulSoup | Multithreaded command-injection and XSS exploitation against DVWA, paired with a passive log-based command-injection scanner |
| [web-recon-fingerprinting-spanish](https://github.com/CyberBass051/web-recon-fingerprinting-spanish) | OSINT, DNS, nmap | Full recon engagement with findings mapped to security impact (report in Spanish) |
| [phishing-simulation-report-spanish](https://github.com/CyberBass051/phishing-simulation-report-spanish) | GoPhish, Python, Wireshark | End-to-end phishing simulation with kill-chain analysis and mitigations (report in Spanish) |

---

## 🛠️ Tech stack
**Cloud & IaC:** AWS · Terraform · GitHub Actions · CodePipeline
**Languages:** Python · HCL · Bash
**Security tooling:** Wazuh · Trivy · Checkov · Kali Linux · nmap · Burp Suite · GoPhish · Wireshark

## 📫 Contact
📧 pietroolivieri.bass@gmail.com
