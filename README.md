# Thomas Peyrusaubes

**Alternant en cybersécurité chez Retengr · Bachelor Cybersécurité, Ynov Toulouse**

Orienté **sécurité cloud et DevSecOps**.

Je conçois et sécurise des infrastructures reproductibles : Infrastructure-as-Code,
durcissement des systèmes, accès au moindre privilège, supervision, et pipelines
CI/CD avec des contrôles de sécurité intégrés.

🎯 Je cherche une **alternance en sécurité cloud / DevSecOps** pour mon Mastère, à partir de **septembre 2027**.

---

## Compétences

| Domaine | Technologies |
|---|---|
| Sécurité | Durcissement Linux et Windows (SSH par clé, Fail2ban, UFW, GPO), bastion, IAM au moindre privilège, audit de configuration IaC |
| Cloud / IaC | AWS (VPC, EC2, ECS Fargate, RDS, S3, Transit Gateway), Terraform, Ansible |
| DevSecOps / CI-CD | GitHub Actions (OIDC), Docker, Checkov, Trivy, Dependabot |
| Réseau | VLAN, OSPF, ACL, NAT, VPN IPSec, OPNsense, pfSense |
| Systèmes | Linux (Debian, Ubuntu), Windows Server (AD DS, DNS, DHCP, WSUS), Prometheus, Grafana |
| Code | Bash, PowerShell, Python, Go, C# / .NET, JavaScript (Node, React), Java, PHP, SQL |

---

## Projets

### Sécurité cloud et infrastructure

**[taskflow](https://github.com/thomaspeyr31/taskflow)** — Déploiement sécurisé sur AWS

API conteneurisée sur **ECS Fargate** derrière un ALB, **Terraform modulaire** (VPC, RDS),
state distant chiffré (S3 + DynamoDB), pipeline **GitHub Actions sans clé statique (OIDC)**
avec audit des dépendances, scan de l'IaC (Checkov) et de l'image (Trivy).

**[nordis-infra-aws](https://github.com/thomaspeyr31/nordis-infra-aws)** — Infrastructure Windows / Linux d'une PME

Pare-feu **OPNsense**, Active Directory sur deux contrôleurs, **GPO de durcissement**, WSUS,
centralisation des journaux (WEF + rsyslog), RAID/LVM et sauvegarde avec restauration testée,
le tout sur AWS avec Terraform.

**Infrastructure cloud multi-sites AWS** *(code privé)*

Infrastructure d'entreprise siège + agences en **Terraform + Ansible** : VPC segmentés,
interconnexion **hub-and-spoke via Transit Gateway**, Active Directory, habilitations au moindre privilège.

### Développement

**[TaskBoard](https://github.com/thomaspeyr31/TaskBoard)** — Kanban collaboratif en temps réel *(en binôme)*

**ASP.NET Core**, **SignalR**, authentification JWT, Entity Framework Core, tests et CI.

**[cocktail-bar](https://github.com/thomaspeyr31/cocktail-bar)** — Application conteneurisée *(en binôme)*

API Node.js, front React, PostgreSQL et Nginx orchestrés avec **Docker Compose**, déployés sur un VPS.

---

## Contact

- Email : thomassspe@gmail.com
- LinkedIn : [thomas-peyrusaubes](https://www.linkedin.com/in/thomas-peyrusaubes-335397338)
