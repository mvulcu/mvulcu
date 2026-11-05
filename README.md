<p align="center">
  <a href="https://grepme.dev"><img src="https://img.shields.io/badge/Portfolio-grepme.dev-1abc9c?style=for-the-badge" alt="Portfolio"></a>
  <a href="https://grepme.dev/maria-vulcu-cv.pdf"><img src="https://img.shields.io/badge/CV-PDF-2563eb?style=for-the-badge" alt="CV"></a>
  <a href="https://linkedin.com/in/mariavulcu"><img src="https://img.shields.io/badge/LinkedIn-Maria%20Vulcu-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:ping@grepme.dev"><img src="https://img.shields.io/badge/Email-ping%40grepme.dev-e74c3c?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

# Hi, I'm Maria

**DevOps / Platform Engineer** in Jönköping, Sweden · open to remote and hybrid roles across Europe

I work on the path from commit to production: infrastructure as code, CI/CD, Kubernetes, observability and the incidents that show up afterwards. I started in software development, so I'm comfortable in the application code too.

> Most of my production work lives in private client repositories. Case studies and architecture write-ups are on [grepme.dev](https://grepme.dev), and I'm happy to walk through any of it.

---

## 🛠 Building for myself

Two tools I built and run on my own VPS to automate my job search, from provisioning and deployment to TLS. *(Private repositories.)*

|                    | **Career AI**                                                     | **Career Match & ATS Studio**                     |
| ------------------ | ----------------------------------------------------------------- | ------------------------------------------------- |
| **What it does**   | Aggregates, filters and scores job listings from multiple sources | Matches roles to a profile, tailors CVs, tracks applications |
| **Stack**          | Next.js · FastAPI · SQLAlchemy · PostgreSQL + pgvector · Redis    | React · TypeScript · Vite · Node.js / Express     |
| **Delivery**       | GitHub Actions · GHCR · Trivy · GitOps reconcile loop with rollback on failed health checks | GitHub Actions · GHCR                |
| **Runtime**        | Docker Compose · Caddy · systemd timers                           | Docker Compose · Caddy · non-root container       |
| **Security**       | SOPS + age · OAuth2 Proxy · TLS                                   | TLS                                               |

> *If I've done something manually three times, I'd rather spend an evening automating it than a month repeating it.*

---

## 📂 Public projects

| Project | What it shows |
|:--|:--|
| [**maria-guestbook-infra**](https://github.com/mvulcu/maria-guestbook-infra) · [app](https://github.com/mvulcu/maria-guestbook-app) | GitOps delivery on K3s: Argo CD, Argo Rollouts canary releases, Helm, Prometheus / Grafana / Loki, Sealed Secrets, default-deny NetworkPolicies, Trivy in CI. Started as a CI/CD course project and extended well beyond the brief. |
| [**ocp-guestbook**](https://github.com/mvulcu/ocp-guestbook) | Re-platforming a 3-tier app from OpenShift to standard Kubernetes (kind) with Helm, Ingress, cert-manager and a GitHub Actions pipeline. |
| [**terraVPC**](https://github.com/mvulcu/terraVPC) | Modular Terraform for a two-AZ AWS VPC (subnets, IGW, NAT, routing, security groups) with fmt / validate / TFLint in CI. |
| [**backend_CVcloud**](https://github.com/mvulcu/backend_CVcloud) · [frontend](https://github.com/mvulcu/frontend_CVcloud) | GCP Resume Challenge: Cloud Functions, Firestore, Terraform and GitHub Actions. |

---

## ⚙️ Tech stack

**Cloud:** AWS · Azure · Google Cloud · UpCloud · Hetzner · serverless  
**IaC & CI/CD:** Terraform · Bicep · Ansible · Helm · Kustomize · GitHub Actions · GitLab CI/CD · Azure Pipelines  
**Kubernetes & GitOps:** Docker · Kubernetes · K3s · OpenShift · Argo CD · Argo Rollouts · Flux CD · NGINX Ingress · Traefik · cert-manager  
**Observability & security:** Prometheus · Grafana · Loki · Alertmanager · OpenTelemetry · ELK · CloudWatch · Trivy · Gitleaks · SOPS · Sealed Secrets · GitHub OIDC  
**Full-stack & data:** Python · TypeScript · JavaScript · Next.js · React · Node.js · FastAPI · Flask · PostgreSQL · MongoDB · Redis · SQLite  
**Also used in projects:** Go · Java · Spring Boot · PHP · Angular · Vue

---

<p align="center">
  <a href="https://grepme.dev">grepme.dev</a> · <a href="mailto:ping@grepme.dev">ping@grepme.dev</a> · <a href="https://linkedin.com/in/mariavulcu">LinkedIn</a>
</p>
