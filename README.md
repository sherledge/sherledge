# Hi, I'm Shabeer 👋
**Cloud & DevOps / SRE Engineer** specializing in Infrastructure as Code (Terraform), Kubernetes Platforms, DevSecOps Pipelines, and Autonomous Self-Healing Systems.

---

### 🚀 Highlight Projects

#### 1. [Autonomous SRE & Self-Healing Cloud Platform](https://github.com/sherledge/terraform-aws-platform)
- **Problem:** Deployment failures and pod crashes require manual engineer on-call intervention, driving up MTTR.
- **Solution:** Multi-tier autonomous remediation engine with an escalation ladder (restart → rollback → human escalation), verified via automated chaos testing to achieve **8.55s MTTR**.
- **Tech:** Python, Kubernetes, Prometheus, Grafana, Alertmanager, Chaos Engineering, Webhooks.

#### 2. [Multi-Environment AWS Platform (IaC)](https://github.com/sherledge/terraform-aws-platform)
- **Problem:** Inconsistent staging/production environments and drift.
- **Solution:** Reusable, modular Terraform codebase (VPC, ASG, ALB, RDS, IAM) across `dev`, `staging`, and `prod` with remote state locking and GitHub Actions OIDC pipelines.
- **Tech:** Terraform, AWS (VPC, EC2/ASG, RDS, ALB, IAM), Checkov, TFLint.

#### 3. [Secure DevSecOps Pipeline & GitOps Delivery](https://github.com/sherledge/gitops-config)
- **Problem:** Security vulnerabilities slipping into production and manual cluster deployments.
- **Solution:** Shift-left CI pipeline (Gitleaks, Hadolint, Trivy, pip-audit) driving pull-based GitOps deployment via ArgoCD with automated self-healing and zero-downtime rollouts.
- **Tech:** ArgoCD, Kustomize, GitHub Actions, Docker, Trivy, Gitleaks.

---

### 🛠️ Tech Stack & Tooling
- **Cloud & IaC:** AWS, Terraform, Docker, Kubernetes, Linux/Bash
- **CI/CD & GitOps:** GitHub Actions, ArgoCD, Kustomize, Helm
- **Security & Quality:** Trivy, Gitleaks, Hadolint, pip-audit, Checkov
- **Observability & SRE:** Prometheus, Grafana, Alertmanager, SLO/SLI Multi-Window Burn Rates
