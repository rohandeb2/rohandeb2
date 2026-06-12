<div align="center">

# Hey, I'm Ruhon Deb 👋

### DevOps & Cloud Engineer · SRE · Security Researcher

*Building production-grade infrastructure with Kubernetes, AWS, and GitOps*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ruhon-deb)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rohandeb2)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ruhondeb28@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://rohandevops.co.in)

</div>

---

## 🚀 About Me

I'm a **B.Tech CSE graduate (2026)** from Roorkee Institute of Technology who has spent the last two years building production-grade DevOps systems from scratch — not tutorials, but real multi-service platforms with CI/CD, GitOps, observability stacks, and chaos engineering.

- 🔭 Currently building on **AWS EKS · Kubernetes · Terraform · ArgoCD**
- 🛡️ **Hall of Fame @ Axway.com** for responsible disclosure of a critical source code exposure vulnerability
- 📊 Reduced MTTR from 45 min → 8 min on a distributed tracing platform
- ⚡ Provisioned 11-microservice infra in **12 minutes** with Terraform (down from 4 hours)
- 🎯 Preparing for **AWS SAA-C03** and **Terraform Associate** certifications
- 💬 Ask me about Kubernetes failure modes, SLO burn-rate alerting, or GitOps pipelines

---

## 🏗️ Featured Projects

### 🏦 [BankApp — Production-Grade Banking Platform on AWS EKS](https://github.com/rohandeb2/sspringboot-bankapp)
> Spring Boot · Jenkins · ArgoCD · Terraform · Karpenter · Istio · Kyverno · Velero · Prometheus · Grafana · Loki · Tempo

- Architected full CI/CD + GitOps pipeline on EKS; provisioned all infra via **modular Terraform** with S3/DynamoDB state backend
- **Blue-green deployments** via Argo Rollouts with zero-downtime releases; **Karpenter** for dynamic node autoscaling
- DevSecOps pipeline: Trivy + OWASP ZAP + SonarQube on every push; **Kyverno admission policies** + **Istio mTLS**
- Full observability: Prometheus/Grafana/Loki/Tempo; **Velero + MinIO** 6-hour DR backups targeting 99.9% availability

---

### 📡 [CloudNativeObservability — SRE Platform with SLO/SLI & Chaos Engineering](https://github.com/rohandeb2/observability-SLI_SLO_proj)
> Prometheus · Grafana · Alertmanager · OpenTelemetry · Jaeger · Tempo · Loki · ArgoCD · Sloth · Chaos Mesh · ELK · FastAPI

- **OpenTelemetry auto-instrumentation** across 3 FastAPI microservices (5 signal types: metrics, logs, traces, spans, exemplars)
- **MTTR reduced from 45 min → 8 min** via distributed tracing and log correlation
- **Sloth-based SLO/SLI**: 32 Prometheus recording rules, multi-burn-rate alerting (14.4×/6×), zero SLO breaches over 90 days; false positives cut **67%**
- Chaos engineering via Chaos Mesh (pod kill, network latency, CPU stress); alert firing confirmed within **90 sec of fault injection**
- ArgoCD App-of-Apps GitOps: deploy time **30 min → 90 sec**, zero config drift

---

### 🛒 [OnlineBoutique — 11-Microservice E-Commerce Platform on AWS EKS](https://github.com/rohandeb2/onlineboutique-webapp)
> AWS EKS · Jenkins · ArgoCD · Terraform · Helm · ECR · Route53 · ACM · Trivy · Redis · gRPC · Secrets Manager

- Deployed **cloud-native 11-microservice** platform (Java, Go, Python, Node.js, gRPC) on EKS
- Terraform automation reduced infra provisioning from **4 hours → 12 minutes** (VPC, IAM, 11 ECR repos)
- **11 parallel Jenkins pipelines** with Trivy scanning; end-to-end deploys under 5 min across dev/staging/prod
- **40+ vulnerabilities caught pre-production**; zero security incidents over 6 months

---

## 🛠️ Tech Stack

<div align="center">

**Cloud & Infrastructure**

![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)

**Containers & Orchestration**

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![Istio](https://img.shields.io/badge/Istio-466BB0?style=flat-square&logo=istio&logoColor=white)

**CI/CD & GitOps**

![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white)

**Observability**

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elastic-005571?style=flat-square&logo=elastic&logoColor=white)

**Security & DevSecOps**

![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=flat-square&logo=aquasecurity&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white)
![OWASP](https://img.shields.io/badge/OWASP_ZAP-000000?style=flat-square&logo=owasp&logoColor=white)

**Languages & Scripting**

![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![HCL](https://img.shields.io/badge/HCL-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![YAML](https://img.shields.io/badge/YAML-CB171E?style=flat-square&logo=yaml&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

</div>

---

## 🏆 Achievements

| | |
|---|---|
| 🏅 **Hall of Fame — Axway.com** | Responsibly disclosed a critical vulnerability exposing platform source code with full exploitation chain documentation |
| 🔐 **Security Research** | Disclosed critical vulnerabilities (auth bypass, price tampering, data exposure) across **5+ organizations** with **100% remediation rate** |

---

## 📈 GitHub Stats

<div align="center">

![Ruhon's GitHub Stats](https://github-readme-stats.vercel.app/api?username=rohandeb2&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=rohandeb2&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

## 📬 Let's Connect

I'm actively looking for my first **DevOps / Cloud / SRE role** at funded startups (Series A–C) or remote-first companies. If you're building something interesting, reach out.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ruhon-deb)
[![Email](https://img.shields.io/badge/Send_an_Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ruhondeb28@gmail.com)

</div>

---

<div align="center">
<sub>⚡ This profile is maintained as code — just like my infrastructure.</sub>
</div>
