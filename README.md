<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&amp;height=180&amp;color=gradient&amp;text=Zakhar%20D.%20%2F%20Zakharden&amp;fontAlign=50&amp;fontAlignY=35&amp;desc=DevOps%20%C2%B7%20SRE%20%C2%B7%20Platform%20Engineer%20%C2%B7%20AI-Powered%20Reliability&amp;descAlign=50&amp;descAlignY=55" alt="Zakhar D. / Zakharden — DevOps, SRE, Platform Engineer" />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Zakharden-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/zakharden/)
[![GitHub](https://img.shields.io/badge/GitHub-Zakharden-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Zakharden)
[![Telegram](https://img.shields.io/badge/Telegram-@Zakhardenn-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/Zakhardenn)
[![Profile views](https://komarev.com/ghpvc/?username=Zakharden&style=for-the-badge&color=orange)](https://github.com/Zakharden)

### DevOps · SRE · Platform Engineer · AI-Powered Operations

<strong>I build Kubernetes-first platforms that ship fast, stay observable, and survive incidents.</strong>

<br/>

<strong>AI-Powered / Open Infrastructure / FinTech & Startup Opportunities</strong>

<br/>

Open to <strong>DevOps / SRE / Platform Engineering</strong> roles in <strong>FinTech, startups, Europe, LATAM, remote-first and international engineering teams</strong>.

</div>

---

## What I Do

I focus on production-grade platforms where releases are repeatable, systems are observable, failures are recoverable, and operational context is ready for humans and AI-assisted workflows.

- **Platform Engineering:** Kubernetes, OpenShift, Helm, Argo CD, GitOps, Docker, Linux, KubeVirt pet-project exposure, multi-environment and hybrid infrastructure patterns.
- **SRE / Production Reliability:** incident response, RCA, high availability, automated failover, zero-downtime migrations, SLI/SLO thinking, error budgets, release reliability, BC/DR readiness.
- **AWS Cloud Infrastructure:** VPC design, IAM least privilege, EC2, EKS, RDS, S3, ALB/NLB, Route 53, ACM, CloudWatch, SSM/Secrets Manager, Terraform-managed environments, private networking, security groups, backups and cost-aware operations.
- **CI/CD & Release Engineering:** Jenkins, GitLab CI/CD, GitHub Actions, canary deployments, automated rollbacks, quality gates, security-scan stages, deployment scripts and controlled production changes.
- **IaC & Automation:** Terraform, OpenTofu, Pulumi, Ansible, Python, Bash, repeatable VM/platform provisioning, multi-data-centre and on-prem/cloud-connected automation.
- **Stateful Platforms:** PostgreSQL, Patroni, etcd, PgBouncer, Envoy, Redis, MongoDB, MinIO, Kafka, Debezium, backups, restore readiness, replication, failover and query/index troubleshooting.
- **Observability:** Prometheus, VictoriaMetrics, Grafana, ELK/Kibana, OpenTelemetry, Jaeger-to-log workflows, dashboards, alerting, RED/USE, Four Golden Signals, capacity and degradation visibility.
- **AI-Powered Ops / IDP:** n8n, AI agents, Streamlit, Backstage-style service catalog patterns, alert enrichment, structured service metadata, runbook-friendly context and support automation.
- **Security & Compliance:** RBAC, SSO, LDAP/Active Directory, Keycloak, OAuth/OIDC concepts, JWT sessions, auditability, access traceability, SOC 2-aware operational controls and sensitive-data discipline.
- **Startup/Product Delivery:** MVP-to-production delivery with CI/CD, IaC, monitoring, guardrails, simple ML/prototyping with Python and scikit-learn when it helps the product.

---

## Production Signals

<div align="center">

| Area | Signal |
|---|---:|
| Production scope | 300+ microservices across Kubernetes/OpenShift |
| Platform size | 30+ Kubernetes/OpenShift nodes |
| Critical services | 99.99% measured uptime |
| Detection speed | ~30 min → under 2 min |
| DB incident MTTR | hours → ~10–20 min |
| Release delivery | every 3 days → daily production releases |
| Deployment speed | 3x faster delivery workflows |
| Toil reduction | 30+ hours/week automated |

</div>

---

## Open Source Impact

Merged upstream contributions focused on Kubernetes, Helm charts, observability, GitOps documentation, dashboard correctness and runtime regression coverage.

| Project | PR | What changed | Status |
|---|---|---|---|
| TFLint | [#2538](https://github.com/terraform-linters/tflint/pull/2538) | Made JUnit testcase names uniquely identifiable by including source ranges, replacing the earlier formatter approach from [#2522](https://github.com/terraform-linters/tflint/pull/2522). | Merged · June 5, 2026 |
| TFLint | [#2525](https://github.com/terraform-linters/tflint/pull/2525) | Added an ignorable-rule configuration path so selected rule findings can be treated as non-blocking while preserving normal issue reporting behavior. | Merged · June 5, 2026 |
| TFLint | [#2524](https://github.com/terraform-linters/tflint/pull/2524) | Fixed recursive inspection issue reporting so no-range diagnostics retain the worker directory context and point at the correct file path. | Merged · June 5, 2026 |
| K8sGPT | [#1650](https://github.com/k8sgpt-ai/k8sgpt/pull/1650) | Added Azure OpenAI API version override support across auth and serve flows, with focused coverage for configuration propagation and provider behavior. | Merged · June 4, 2026 |
| Kubespray | [#13249](https://github.com/kubernetes-sigs/kubespray/pull/13249) | Removed duplicated inline fallback defaults from selected download and Kubernetes preinstall role paths, relying on configured role defaults while keeping behavior unchanged. | Merged · May 27, 2026 |
| Prometheus Community Helm Charts | [#6902](https://github.com/prometheus-community/helm-charts/pull/6902) | Added `kube-prometheus-stack` support for `ThanosRuler` `extraEnv` through a strategic merge patch path for cleaner Ruler deployment extension. | Merged · May 22, 2026 |
| Open Policy Agent / Gatekeeper | [#4557](https://github.com/open-policy-agent/gatekeeper/pull/4557) | Fixed Helm webhook `namespaceSelector` rendering so generated exempt label values are quoted and stay stable as strings. | Merged · May 19, 2026 |
| Prometheus Community Helm Charts | [#6905](https://github.com/prometheus-community/helm-charts/pull/6905) | Fixed invalid `kube-prometheus-stack` `PrometheusRule` rendering when single-alert default rule groups are disabled; updated generated rules and tests. | Merged · May 17, 2026 |
| Prometheus Community Helm Charts | [#6906](https://github.com/prometheus-community/helm-charts/pull/6906) | Fixed `KubeletDown` alert generation with additional aggregation labels to avoid false positives for healthy kubelets. | Merged · May 16, 2026 |
| bpftrace | [#5161](https://github.com/bpftrace/bpftrace/pull/5161) | Added runtime regression coverage around repeated `for` loops and mixed map value types. | Merged · May 13, 2026 |
| Kubernetes Mixin | [#1219](https://github.com/kubernetes-monitoring/kubernetes-mixin/pull/1219) | Fixed API server Grafana dashboard error-budget wording and percentage formatting at the upstream mixin source. | Merged · May 13, 2026 |
| Flux website | [#2553](https://github.com/fluxcd/website/pull/2553) | Added AWS CodeCommit SSH authentication documentation for Flux `source git` and `bootstrap git` workflows. | Merged · May 11, 2026 |
| Prometheus Community Helm Charts | [#6901](https://github.com/prometheus-community/helm-charts/pull/6901) | Fixed duplicate `thanos.image` rendering in `kube-prometheus-stack` generated Prometheus custom resources. | Merged · May 11, 2026 |

## Featured Engineering Work

| Repository | What it demonstrates |
|---|---|
| [heritage-infra](https://github.com/Zakharden/heritage-infra) | End-to-end infrastructure rollout: VM preparation, Kubernetes automation, GitOps delivery, Helm charts and Vault integration. |
| [heritage-cicd](https://github.com/Zakharden/heritage-cicd) | Reference CI/CD pipeline with quality gates, security scanning, container builds, semantic release and GitOps deployment. |
| [heritage-vm-create](https://github.com/Zakharden/heritage-vm-create) | Terraform + Pulumi automation for repeatable VM provisioning and infrastructure rollout patterns. |
| [social-project](https://github.com/Zakharden/social-project) | Startup MVP baseline for a professional social-networking product. |
| [DB-Interface-childs-policl](https://github.com/Zakharden/DB-Interface-childs-policl) | C# + MySQL educational DB interface with procedures, triggers, functions and application logic. |

---

## Tech Stack

<div align="center">

### Platform / Containers / Delivery

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![OpenShift](https://img.shields.io/badge/OpenShift-EE0000?style=for-the-badge&logo=redhatopenshift&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)
![Argo CD](https://img.shields.io/badge/Argo%20CD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![GitOps](https://img.shields.io/badge/GitOps-111111?style=for-the-badge&logo=git&logoColor=white)
![KubeVirt](https://img.shields.io/badge/KubeVirt-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

### CI/CD / IaC / Automation

![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![GitLab CI/CD](https://img.shields.io/badge/GitLab%20CI%2FCD-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)
![OpenTofu](https://img.shields.io/badge/OpenTofu-FFDA18?style=for-the-badge&logo=opentofu&logoColor=black)
![Pulumi](https://img.shields.io/badge/Pulumi-8A3391?style=for-the-badge&logo=pulumi&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

### Observability / SRE

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![VictoriaMetrics](https://img.shields.io/badge/VictoriaMetrics-6218FF?style=for-the-badge)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![ELK](https://img.shields.io/badge/ELK%20Stack-005571?style=for-the-badge&logo=elastic&logoColor=white)
![Kibana](https://img.shields.io/badge/Kibana-005571?style=for-the-badge&logo=kibana&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=for-the-badge&logo=opentelemetry&logoColor=white)
![Jaeger](https://img.shields.io/badge/Jaeger-66CFE3?style=for-the-badge)
![SLO](https://img.shields.io/badge/SLI%20%2F%20SLO%20%2F%20Error%20Budget-111111?style=for-the-badge)

### Stateful Systems / Data / HA

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Patroni](https://img.shields.io/badge/Patroni-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![etcd](https://img.shields.io/badge/etcd-419EDA?style=for-the-badge&logo=etcd&logoColor=white)
![PgBouncer](https://img.shields.io/badge/PgBouncer-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Envoy](https://img.shields.io/badge/Envoy-AC6199?style=for-the-badge&logo=envoyproxy&logoColor=white)
![MS SQL Server](https://img.shields.io/badge/MS%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=for-the-badge&logo=minio&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Debezium](https://img.shields.io/badge/Debezium-111111?style=for-the-badge)
![Apache Superset](https://img.shields.io/badge/Apache%20Superset-20A6FF?style=for-the-badge&logo=apachesuperset&logoColor=white)

### AI-Powered Ops / Internal Tooling / Security

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![AI Agents](https://img.shields.io/badge/AI%20Agents-111111?style=for-the-badge&logo=openai&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Backstage](https://img.shields.io/badge/Backstage-9BF0E1?style=for-the-badge&logo=backstage&logoColor=black)
![Swagger](https://img.shields.io/badge/Swagger%20%2F%20OpenAPI-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)
![Keycloak](https://img.shields.io/badge/Keycloak-4D4D4D?style=for-the-badge&logo=keycloak&logoColor=white)
![LDAP](https://img.shields.io/badge/LDAP%20%2F%20Active%20Directory-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![RBAC](https://img.shields.io/badge/RBAC%20%2F%20SSO%20%2F%20OIDC-111111?style=for-the-badge)
![SOC 2-aware](https://img.shields.io/badge/SOC%202--aware%20Ops-111111?style=for-the-badge)

### Cloud / Product / Languages

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Amazon EKS](https://img.shields.io/badge/Amazon%20EKS-FF9900?style=for-the-badge&logo=amazoneks&logoColor=white)
![Amazon EC2](https://img.shields.io/badge/Amazon%20EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white)
![Amazon RDS](https://img.shields.io/badge/Amazon%20RDS-527FFF?style=for-the-badge&logo=amazonrds&logoColor=white)
![Amazon S3](https://img.shields.io/badge/Amazon%20S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)
![AWS IAM](https://img.shields.io/badge/AWS%20IAM-DD344C?style=for-the-badge&logo=amazoniam&logoColor=white)
![VPC](https://img.shields.io/badge/VPC%20%2F%20Networking-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?style=for-the-badge&logo=amazoncloudwatch&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Yandex Cloud](https://img.shields.io/badge/Yandex%20Cloud-5282FF?style=for-the-badge)
![On-Prem](https://img.shields.io/badge/On--Prem%20Infrastructure-111111?style=for-the-badge)
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=ethereum&logoColor=white)
![TRON](https://img.shields.io/badge/TRON-E50914?style=for-the-badge)
![Polygon](https://img.shields.io/badge/Polygon-8247E5?style=for-the-badge&logo=polygon&logoColor=white)

</div>

---

## GitHub Signals & Fun Widgets

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=Zakharden&amp;theme=algolia&amp;no-frame=true&amp;no-bg=true&amp;row=1&amp;column=6" alt="GitHub trophies" />

<br/>
<br/>

<a href="https://github.com/Zakharden?tab=followers">
  <img src="https://img.shields.io/github/followers/Zakharden?style=for-the-badge&amp;logo=github&amp;label=Followers" alt="GitHub followers" />
</a>
<a href="https://github.com/Zakharden?tab=repositories">
  <img src="https://img.shields.io/badge/Public%20Repos-Open%20Infrastructure-2ea44f?style=for-the-badge&amp;logo=github" alt="Open infrastructure repositories" />
</a>
<a href="https://github.com/Zakharden?tab=pull-requests">
  <img src="https://img.shields.io/badge/Open%20Source-Merged%20PRs-orange?style=for-the-badge&amp;logo=github" alt="Open source merged PRs" />
</a>

<br/>
<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Zakharden&amp;theme=dark&amp;hide_border=true" alt="GitHub contribution streak" />

<br/>
<br/>

![Reliability](https://img.shields.io/badge/reliability-first-orange?style=for-the-badge)
![Incidents](https://img.shields.io/badge/incidents-RCA%20driven-111111?style=for-the-badge)
![Delivery](https://img.shields.io/badge/delivery-rollback%20aware-2ea44f?style=for-the-badge)
![AI Ops](https://img.shields.io/badge/AI--powered-operations-8A2BE2?style=for-the-badge)
![FinTech](https://img.shields.io/badge/FinTech-production%20reliability-0A66C2?style=for-the-badge)
![Startups](https://img.shields.io/badge/Startups-MVP%20to%20Production-FF6B00?style=for-the-badge)

</div>

---

## Experience Highlights

**DevOps / SRE Engineer — Alfa-Bank environment / vendor-side delivery**  
*DFA / RWA / blockchain-backed banking platform · Apr 2023 — Present*

- Operated reliability and deployment workflows for 300+ microservices across Kubernetes/OpenShift clusters.
- Improved release flow from every three days to daily production releases with safer rollout controls.
- Operated PostgreSQL HA with Patroni, etcd, PgBouncer and Envoy: failover, pooling, read/write separation and zero-downtime maintenance.
- Built AI-powered operational workflows with n8n, AI agents and structured service metadata for ticket/status aggregation, alert enrichment and faster triage.
- Led an internal Python + Streamlit operations platform deployed on Kubernetes with LDAP auth, JWT sessions, read-only DB replicas, Swagger discovery, SQL utilities, Kubernetes config diffing, certificate checks and Jira/n8n integrations.
- Delivered infrastructure automation across on-prem and cloud-connected environments using Terraform, OpenTofu/Pulumi, Ansible, Jenkins, Python and Bash.
- Supported secure banking-grade operations: RBAC/SSO, LDAP/AD, Keycloak, controlled production changes, auditability and sensitive-data discipline.

**Lead System Administrator / DevOps — Block4Block**  
*Blockchain infrastructure · May 2022 — Dec 2022*

- Automated provisioning, deployment and operations for blockchain nodes across Ethereum and Polygon using Docker and Ansible.
- Built infrastructure for a crypto ETF portfolio product and supported production transactional workloads from day one.
- Built Python Telegram bots and SQL dashboards for real-time blockchain analytics and operational visibility.

---

## Education

- **Higher School of Economics (HSE)** — Product Management / MBA track
- **Innopolis University** — Software Engineering & Machine Learning Technologies, graduated with honors
- **MIREA — Russian Technological University** — Informatics and Programming
- **Rostelecom + MIREA** — DevOps Engineering & Site Reliability Engineering, graduated with honors

---

## Languages

- Russian — Native
- English — B2

---

## Contact

- Email: **zakhardenn@gmail.com**
- Telegram: [**@Zakhardenn**](https://t.me/Zakhardenn)
- LinkedIn: [**linkedin.com/in/zakharden**](https://www.linkedin.com/in/zakharden/)
- GitHub: [**github.com/Zakharden**](https://github.com/Zakharden)

---

<div align="center">

<strong>I build AI-powered, highly reliable platforms that are boring in production, fast in delivery, and clear during incidents.</strong>

</div>
