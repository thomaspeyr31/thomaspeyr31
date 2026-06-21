# Thomas Peyrusaubes

Étudiant en **Infrastructure & Développement** (Ynov), orienté **DevOps / Cloud**.
Actuellement en stage sur du déploiement d'infrastructure cloud-native AWS.

J'aime concevoir des infrastructures propres et reproductibles (Infrastructure-as-Code,
conteneurs, CI/CD) et comprendre la chaîne de bout en bout : du réseau au déploiement applicatif.

---

## Compétences

| Domaine | Technologies |
|---|---|
| Cloud / IaC | AWS, Terraform, Ansible, Docker |
| CI/CD | GitHub Actions, OIDC, ECR/ECS |
| Réseau & systèmes | Cisco (VLAN, OSPF, ACL), Active Directory, Linux |
| Développement | Go, C# / .NET, PHP, Java, JavaScript (Node, React) |
| Bases de données | PostgreSQL, MySQL, SQLite |

---

## Projets mis en avant

### [taskflow](https://github.com/thomaspeyr31/taskflow) — DevOps / IaC sur AWS
API Node/Express déployée sur **AWS ECS Fargate** via **Terraform modulaire**
(VPC, RDS, ALB), avec **state distant** (S3 + DynamoDB) et un pipeline **CI/CD GitHub Actions**
(test → build → plan → deploy, authentification OIDC).

### [taskboard](https://github.com/thomaspeyr31/taskboard) — Application Kanban temps réel
Gestion de tâches type Kanban en **ASP.NET Core**, avec **authentification JWT**,
**temps réel via SignalR**, Entity Framework Core et un frontend intégré.

### Infrastructure cloud-native AWS multi-sites *(projet de stage — code privé)*
Déploiement d'une infrastructure d'entreprise multi-sites (siège + agences) sur AWS,
en **Terraform + Ansible** : VPC segmentés, interconnexion **hub-and-spoke via Transit Gateway**,
**AWS Managed Microsoft AD**, gestion des habilitations au moindre privilège.

---

## Me contacter

- Email : thomassspe@gmail.com
- GitHub : [@thomaspeyr31](https://github.com/thomaspeyr31)
