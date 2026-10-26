<h1 align="center">Ebrahim Sidat</h1>
<h3 align="center">Senior Linux / DevOps Engineer &nbsp;|&nbsp; Infrastructure Automation &nbsp;|&nbsp; Observability &nbsp;|&nbsp; Cloud Architecture</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/ebrahim-s-a1743414/"><img src="https://img.shields.io/badge/LinkedIn-Ebrahim%20Sidat-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <img src="https://img.shields.io/badge/Location-Pickering%2C%20Ontario%2C%20Canada-555555?style=for-the-badge" alt="Location">
  <img src="https://img.shields.io/badge/Clearance-Secret%20(Level%20II)-1F3A5F?style=for-the-badge" alt="Security clearance">
</p>

---

## Professional Summary

Senior Linux and DevOps engineer with more than 25 years of experience supporting mission-critical, 24/7 operations support systems (OSS) for a national telecommunications carrier. I design, automate and operate large Red Hat Enterprise Linux environments, build monitoring and incident-management pipelines, and apply secure, auditable automation to reduce outages and manual effort.

- **Infrastructure automation** — Ansible and Ansible Automation Platform, Terraform, Jenkins and Red Hat Satellite across large RHEL estates (RHEL 6 through 9)
- **Observability and incident response** — Elasticsearch, Kibana, Metricbeat / Elastic Agent and SNMP pipelines that convert network faults into actionable service-management tickets and on-call pages
- **Cloud and platforms** — Kubernetes / OpenShift, VMware, and public cloud on Google Cloud, AWS and Azure
- **Identity and collaboration** — Microsoft 365 and Entra ID administration, including single sign-on and tenant security
- **Applied AI for operations** — automated alert triage and playbook execution with human approval, audit trails and secure-development (SSDLC) practices

---

## Certifications and Clearance

| Credential | Issuer |
|---|---|
| Professional Cloud Architect | Google Cloud |
| Red Hat Certified System Administrator (RHCSA) | Red Hat |
| Secret (Level II) Security Clearance — active | Government of Canada |

---

## Experience Highlights

**Senior System Integrator, Linux – DevOps** — National telecommunications carrier &nbsp;·&nbsp; *2000 – present*
- Provide system and application support for carrier-grade OSS platforms in a regulated, change-controlled production environment
- Automate patching, provisioning and compliance for RHEL fleets using Satellite, Ansible Tower and Jenkins
- Engineer monitoring dashboards and alerting with the Elastic Stack; integrate network fault management with Jira Service Management and paging
- Earlier role: UNIX Systems Administrator (2002 – 2006)

**Lead IT Administrator & Systems Architect** — Community non-profit organization &nbsp;·&nbsp; *2015 – present (part-time)*
- Architect and administer the Microsoft 365 tenant, identity and security for approximately 100 users
- Manage web hosting, backups and end-user support

---

## Selected Work

### Public repositories

| Repository | Description | Technologies |
|---|---|---|
| [**snmp-trap-jira-bridge**](https://github.com/ebrahimsidat/snmp-trap-jira-bridge) | SNMP v2c/v3 trap receiver that opens Jira Service Management tickets with node-level de-duplication, flap dampening, self-healing field handling and PagerDuty fail-over; hardened systemd unit and container image | Python, pysnmp, Jira REST API, PagerDuty, systemd, Docker |
| [**ansible-rhel-baseline**](https://github.com/ebrahimsidat/ansible-rhel-baseline) | Ansible roles for RHEL 8/9: safe rolling patching, a CIS-aligned security baseline and a read-only fleet health check with Markdown and JSON reports | Ansible, RHEL, CIS Benchmarks, auditd, firewalld |
| [**terraform-gcp-foundation**](https://github.com/ebrahimsidat/terraform-gcp-foundation) | Terraform modules for a secure Google Cloud foundation: private VPC with Cloud NAT and IAP-only SSH, centralised audit logging and additive, validated IAM | Terraform, Google Cloud, tflint, Checkov |
| [**elastic-linux-observability**](https://github.com/ebrahimsidat/elastic-linux-observability) | Elastic Stack lab (Elasticsearch, Kibana, Metricbeat), lifecycle and alerting assets, and `fsmon`, a capacity check with Nagios-compatible exit codes, integration-tested against a live Elasticsearch | Elasticsearch, Kibana, Metricbeat, Python, Docker Compose |
| [**kubernetes-platform-gitops**](https://github.com/ebrahimsidat/kubernetes-platform-gitops) | Hardened Helm chart (restricted Pod Security, read-only root file system, NetworkPolicy, HPA, PDB) delivered with Argo CD; CI deploys it to a kind cluster and runs `helm test` on every change | Kubernetes, OpenShift, Helm, Argo CD, kind, kubeconform |
| [**linux-ops-toolkit**](https://github.com/ebrahimsidat/linux-ops-toolkit) | Incident-response Bash tools: host triage, diagnostic bundles with SHA-256 manifests, dry-run-first disk cleanup and TLS expiry checks with Nagios exit codes | Bash, ShellCheck, bats, RHEL / Rocky Linux, Ubuntu |
| [**m365-admin-automation**](https://github.com/ebrahimsidat/m365-admin-automation) | PowerShell module for Microsoft 365 / Entra ID: bulk onboarding, secure offboarding and licence reclamation via Microsoft Graph, with `-WhatIf`, audit logging and least-privilege scopes | PowerShell, Microsoft Graph, Entra ID, Pester, PSScriptAnalyzer |

Every repository includes automated CI (linting, tests, security scanning), documentation of design decisions,
and contribution and security policies.

### Enterprise work (private repositories)

- **RHEL fleet automation:** patching, provisioning and compliance reporting across large RHEL estates with Satellite, Ansible Tower and Jenkins
- **Network fault-to-ticket automation:** production SNMP alert ingestion feeding Jira Service Management and on-call paging for a national carrier network
- **Infrastructure observability:** Kibana dashboards and Metricbeat / Elastic Agent pipelines for host and service health
- **Netrova** *(in development):* AI-assisted network troubleshooting agent with source-agnostic alert intake, diagnostic playbooks and a headless CI/CD mode

---

## Technical Skills

**Operating systems and platforms:** Red Hat Enterprise Linux 6–9, Linux, UNIX, Red Hat Satellite, VMware vSphere, Proxmox
**Automation and CI/CD:** Ansible, Ansible Automation Platform (Tower), Terraform, Jenkins, Git
**Containers and cloud:** Kubernetes, Red Hat OpenShift, Docker, Google Cloud, Amazon Web Services, Microsoft Azure
**Observability and service management:** Elasticsearch, Kibana, Elastic Agent / Metricbeat, SNMP, Jira Service Management, PagerDuty
**Languages:** Python, Bash, YAML
**Identity and productivity:** Microsoft 365, Entra ID (Azure AD), single sign-on

<p>
  <img src="https://img.shields.io/badge/RHEL-EE0000?style=flat-square&logo=redhat&logoColor=white" alt="RHEL">
  <img src="https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white" alt="Ansible">
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white" alt="Terraform">
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white" alt="Jenkins">
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes">
  <img src="https://img.shields.io/badge/OpenShift-EE0000?style=flat-square&logo=redhatopenshift&logoColor=white" alt="OpenShift">
  <img src="https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white" alt="Google Cloud">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS">
  <img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" alt="Azure">
  <img src="https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white" alt="Elasticsearch">
  <img src="https://img.shields.io/badge/Kibana-005571?style=flat-square&logo=kibana&logoColor=white" alt="Kibana">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" alt="Bash">
</p>

---

## Education

**Diploma in Computer Science** — Pakistan Technologies Computer Institute (PTCI), Karachi &nbsp;·&nbsp; *1996 – 1998*

---

<p align="center"><i>Open to senior DevOps, Site Reliability, Platform Engineering and Cloud Infrastructure roles in the private and public sectors, including federal and provincial government. Hybrid or remote.</i></p>
