# Thomas Peyrusaubes

**Cybersecurity work-study student at Retengr · Bachelor in Cybersecurity, Ynov Toulouse**

Focused on **cloud security and DevSecOps**. I design and secure reproducible infrastructure: Infrastructure as Code, system hardening, least-privilege access, monitoring, and CI/CD pipelines with built-in security controls.


🇫🇷 [Version française plus bas](#-en-français)

---

## Featured projects

### Cloud security & infrastructure

| Project | What it shows |
|---|---|
| **[nordis-infra-aws](https://github.com/thomaspeyr31/nordis-infra-aws)** | The full IT system of an 80-employee company on AWS with **Terraform**: OPNsense firewall, redundant **Active Directory**, hardening GPOs, WSUS, centralized logs, tested backups — then **encrypted, filtered DNS** with DoH/DoT bypass detection. |
| **[taskflow](https://github.com/thomaspeyr31/taskflow)** | API on **ECS Fargate** behind an ALB, **modular Terraform** (VPC, RDS), encrypted remote state (S3 + DynamoDB), **GitHub Actions with OIDC** (no static keys): test → build → plan on PR → deploy. |
| **[aws-private-vm-access](https://github.com/thomaspeyr31/aws-private-vm-access)** | Taking a VM **off the Internet** and still administering it: Terraform + Ansible case study, comparison of SSM, EC2 Instance Connect Endpoint, bastion and VPN, tag-based IAM access. |
| **[ymmo-aws-multisite](https://github.com/thomaspeyr31/ymmo-aws-multisite)** | Head office + branches in **Terraform + Ansible over SSM**: one VPC per site, **hub-and-spoke via Transit Gateway**, Active Directory, IPsec VPN, Network Firewall, AWS Backup — deployed from scratch with one script. |

### Development

| Project | What it shows |
|---|---|
| **[kine-site](https://github.com/thomaspeyr31/kine-site)** | Full platform for a physiotherapy practice: online booking, **Stripe** payments, PDF invoices, patient records, GDPR features. Strict CSP, CSRF protection, rate limiting, Docker + automatic HTTPS. |
| **[cocktail-bar](https://github.com/thomaspeyr31/cocktail-bar)** *(team of 2)* | Node.js API with roles, React front end, PostgreSQL and Nginx orchestrated with **Docker Compose**, integration tests in CI. |

---

## Skills

| Area | Technologies |
|---|---|
| Security | Linux & Windows hardening (key-based SSH, Fail2ban, UFW, GPO), bastion, least-privilege IAM, IaC configuration review |
| Cloud / IaC | AWS (VPC, EC2, ECS Fargate, RDS, S3, Transit Gateway), Terraform, Ansible |
| DevSecOps / CI-CD | GitHub Actions (OIDC), Docker, Checkov, Trivy, Dependabot |
| Networking | VLAN, OSPF, ACL, NAT, IPsec VPN, OPNsense, pfSense |
| Systems | Linux (Debian, Ubuntu), Windows Server (AD DS, DNS, DHCP, WSUS), Prometheus, Grafana |
| Code | Bash, PowerShell, Python, Go, JavaScript (Node, React), Java, PHP, SQL |

## Contact

- Email: thomassspe@gmail.com
- LinkedIn: [thomas-peyrusaubes](https://www.linkedin.com/in/thomas-peyrusaubes-335397338)

---

## En français  🇫🇷

**Alternant en cybersécurité chez Retengr · Bachelor Cybersécurité, Ynov Toulouse**

Orienté **sécurité cloud et DevSecOps**. Je conçois et sécurise des infrastructures reproductibles : Infrastructure as Code, durcissement des systèmes, accès au moindre privilège, supervision, et pipelines CI/CD avec des contrôles de sécurité intégrés.


**Projets phares**

- **[nordis-infra-aws](https://github.com/thomaspeyr31/nordis-infra-aws)** — SI complet d'une PME sur AWS avec Terraform : OPNsense, Active Directory redondé, GPO, WSUS, journaux centralisés, sauvegarde testée, puis DNS chiffré et filtré avec détection du contournement.
- **[taskflow](https://github.com/thomaspeyr31/taskflow)** — API sur ECS Fargate, Terraform modulaire, état distant chiffré, pipeline GitHub Actions avec OIDC (aucune clé statique).
- **[aws-private-vm-access](https://github.com/thomaspeyr31/aws-private-vm-access)** — Rendre une VM injoignable depuis Internet et l'administrer quand même : SSM, EC2 Instance Connect Endpoint, bastion, VPN.
- **[ymmo-aws-multisite](https://github.com/thomaspeyr31/ymmo-aws-multisite)** — Siège + agences en Terraform + Ansible via SSM, hub-and-spoke via Transit Gateway, Active Directory, VPN IPsec, Network Firewall, AWS Backup.
- **[kine-site](https://github.com/thomaspeyr31/kine-site)** — Plateforme complète pour un cabinet de kiné : RDV en ligne, paiement Stripe, factures PDF, RGPD, sécurité web (CSP, CSRF, limitation des tentatives).
- **[cocktail-bar](https://github.com/thomaspeyr31/cocktail-bar)** *(en binôme)* — API Node.js, front React, PostgreSQL et Nginx orchestrés avec Docker Compose.

**Contact** : thomassspe@gmail.com · [LinkedIn](https://www.linkedin.com/in/thomas-peyrusaubes-335397338)
