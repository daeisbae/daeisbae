<div align="center">

# Daehyung Kwak (Dae)

Cloud security engineer in training, SOC analyst co-op, and Computing Science student at Simon Fraser University.

[![Portfolio](https://img.shields.io/badge/Portfolio-daehyung.dev-0EA5E9?style=for-the-badge&logo=googlechrome&logoColor=white)](https://daehyung.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Daehyung%20Kwak-2563EB?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/daehyung-kwak)
[![Email](https://img.shields.io/badge/Email-kda56%40sfu.ca-14B8A6?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kda56@sfu.ca)

</div>

---

## About

I build cloud security labs that connect identity, detection engineering, and incident response. My work is mostly around Microsoft Sentinel, Microsoft Entra ID, AWS IAM, CloudTrail, GuardDuty, Terraform, and KQL.

Current focus:

- Investigating identity and endpoint alerts in Microsoft Sentinel.
- Building hybrid Active Directory and Entra ID security labs.
- Testing AWS IAM privilege escalation paths and writing guardrails.
- Turning cloud audit logs into detections, workbooks, and response workflows.

## Skills

| Area | Tools and topics |
|---|---|
| Cloud security | AWS IAM, Organizations, S3, EC2, Lambda, GuardDuty, CloudTrail, CloudWatch, Config, IAM Access Analyzer |
| Microsoft security | Microsoft Sentinel, Defender, Entra ID, RBAC, Conditional Access, PIM, AD DS, GPO, Kerberos |
| Detection and response | KQL, log correlation, alert triage, CloudTrail analysis, identity investigation |
| Infrastructure and automation | Terraform, PowerShell, Bash, Python, GitHub Actions |
| Systems and network | Windows, Linux, switch configuration, firewall rules, backup and recovery |
| Programming | Python, Java, SQL, KQL, Bash, PowerShell, Terraform |

## Featured Projects

### [AWS Secure Container Delivery and Detection Pipeline](https://github.com/daeisbae/AWS-Secure-Container-Delivery-And-Detection-Pipeline)

Implementing Security Pipeline with SAST, DAST, SCA which will deployed to ECS automatically.

- Built a GitHub Actions pipeline using Trivy, Opengrep, and OWASP ZAP to scan source and the built container, blocking failed
gates before ECR push or ECS Fargate deployment.
- Validated and remediated 5 OS/Python CVEs, SQL injection, and 2 security header issues across 3 experiments.
- Configured GitHub OIDC for short-lived AWS credentials and Cosign for signed, digest-pinned ECS Fargate updates.


### [Hybrid Active Directory and Entra Security Lab](https://github.com/daeisbae/Hybrid-Active-Directory-and-Entra-Security-Lab)

Hybrid identity security lab connecting Active Directory Domain Services with Microsoft Entra ID.

- Validated OU-based user and group sync, password hash sync, domain-joined Windows management, GPO baselines, and least-privilege admin groups.
- Integrated Entra audit logs, sign-in logs, AD administrative events, Azure Activity Logs, and Defender for Cloud findings into Microsoft Sentinel.
- Wrote KQL detections and Logic App workflows for privilege changes, failed sign-in spikes, policy drift, and suspicious identity activity.

### [AWS IAM Privilege Escalation and Guardrails Lab](https://github.com/daeisbae/aws-iam-security)

AWS IAM lab for testing privilege escalation paths and least-privilege controls.

- Tested escalation paths across `sts:AssumeRole`, `iam:CreateAccessKey`, `iam:AddUserToGroup`, and `iam:PassRole`.
- Built AWS Organizations SCP guardrails in a Sandbox OU to restrict sensitive IAM changes and admin role passing.
- Collected audit evidence with CloudTrail, AWS Config, GuardDuty, and IAM Access Analyzer.

### [Flaws.cloud CloudTrail Logs Detection Lab with Microsoft Sentinel](https://github.com/daeisbae/flaws.cloud-cloudtrail-logs-detection-with-sentinel)

AWS CloudTrail detection lab using the flaws.cloud dataset and Microsoft Sentinel.

- Built a CloudTrail ingestion path with Log Analytics, S3, SQS, and IAM OIDC.
- Analyzed 2.34M CloudTrail events across 9,310 source IPs and 172 AWS event sources.
- Detected failed authentication, role assumption, access key creation, S3 activity, IAM privilege escalation, and network security changes.

### [Open Repo Wiki](https://github.com/daeisbae/open-repo-wiki)

Developer tool for turning source repositories into readable architecture and implementation notes.

- Built with Python and repository parsing workflows.
- Designed for faster codebase orientation during project handoffs, reviews, and security analysis.

## Experience

| Period | Role |
|---|---|
| May 2026 - Dec 2026 | Cybersecurity SOC Analyst Co-op, WorkSafeBC |
| Sept 2024 - Present | Director of Events and CTF Member, SFU Cybersecurity Club |
| June 2022 - Feb 2024 | IT Operations Technician, Republic of Korea Navy |

## Certifications

| Certification | Date |
|---|---|
| AWS Certified Solutions Architect - Associate | Sept 2025 |
| AWS Knowledge: Security Champion - Training Badge | Jan 2026 |
| AWS Cloud Quest: Security - Training Badge | Jan 2026 |
| Cisco Certified Network Professional Security (CCNP Security) | July 2023 |
| Cisco Certified Network Associate (CCNA) | June 2022 |

## GitHub Activity

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=daeisbae&theme=github_dark" width="100%" alt="GitHub profile summary" />

| Stats | Languages |
|:---:|:---:|
| <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=daeisbae&theme=github_dark" width="100%" alt="GitHub stats" /> | <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=daeisbae&theme=github_dark" width="100%" alt="Repository languages" /> |

| Streak | Git Animals |
|:---:|:---:|
| <img src="https://streak-stats.demolab.com?user=daeisbae&theme=tokyonight&hide_border=true" width="100%" alt="GitHub streak" /> | <a href="https://www.gitanimals.org/"><img src="https://render.gitanimals.org/farms/daeisbae" width="100%" alt="Git Animals farm" /></a> |

</div>

<img width="100%" alt="Footer wave" src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:14B8A6,55:2563EB,100:020617" />
