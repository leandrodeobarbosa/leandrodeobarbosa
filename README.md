<h1 align="center">Leandro de Oliveira Barbosa</h1>

<p align="center">
  <b>DevOps Engineer · Cloud Native · Platform Engineering</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white" alt="AWS" />
  <img src="https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white" alt="Terraform" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes" />
  <img src="https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white" alt="ArgoCD" /><br>
</p>

## About me

I am a DevOps Engineer focused on cloud infrastructure, CI/CD automation, Infrastructure as Code, Kubernetes, and Platform Engineering.

I use **[DevOpsfera Labs](https://github.com/devopsfera-labs)** as my engineering lab to build and validate production-oriented DevOps and Platform Engineering patterns.

My main initiative is **FlowDX**, a self-service delivery platform concept based on reusable workflows, declarative contracts, GitOps, governance, and developer experience.

## Main Initiative: FlowDX

**FlowDX** is not intended to be a full Internal Developer Platform at this stage.

The current goal is to build a focused platform foundation for **self-service workload delivery**, where application repositories consume standardized platform capabilities instead of rebuilding CI/CD, governance, and delivery logic from scratch.

```text
flowdx-platform
  ├─ contracts
  ├─ reusable workflows
  ├─ templates
  └─ kyverno policies
        |
        | consumed by
        v
flowdx-reference-api
  ├─ Python API
  ├─ Dockerfile
  ├─ Helm chart
  └─ flowdx.yaml
        |
        | CI/CD
        v
Container Registry
  └─ GHCR
        |
        | image
        v
flowdx-gitops
  ├─ ArgoCD Applications
  ├─ Helm values
  └─ cluster config
        |
        | observed by
        v
Kind Kubernetes
  ├─ ArgoCD
  ├─ reference-api
  ├─ Prometheus
  ├─ Grafana
  └─ Kyverno
```

## Engineering Focus

- **Platform Engineering:** reusable workflows, declarative contracts, templates, and governed delivery paths.
- **CI/CD Automation:** GitHub Actions, Docker image builds, GHCR publishing, required checks, and secure automation.
- **GitOps & Kubernetes:** ArgoCD, Helm, Kind, environment-specific values, and workload synchronization.
- **Infrastructure as Code:** Terraform modules, remote state, environment separation, drift detection, and safe plan visibility.
- **Governance & Security:** OIDC, least privilege, Kyverno policies, approval gates, and sanitized pipeline summaries.
- **Observability:** Prometheus, Grafana, and CloudWatch fundamentals.

## Tech Stack

**Cloud & Infrastructure**  
`AWS` `Terraform` `Remote State` `IAM` `OIDC`

**CI/CD & Automation**  
`GitHub Actions` `Reusable Workflows` `Docker` `GHCR` `Python` `Bash`

**Kubernetes & GitOps**  
`Kubernetes` `Kind` `Helm` `ArgoCD`

**Governance, Security & Observability**  
`Kyverno` `RBAC` `Least Privilege` `Prometheus` `Grafana` `CloudWatch`

## Current Focus

- Building the `flowdx-platform` foundation with contracts, reusable workflows, templates, and policies.
- Creating `flowdx-reference-api` as the reference Python API workload.
- Structuring `flowdx-gitops` as the source of truth for ArgoCD and Helm values.
- Validating the full delivery flow locally with Kind, ArgoCD, Kyverno, Prometheus, and Grafana.
- Improving CI/CD governance with required checks, approval gates, OIDC, and sanitized pipeline feedback.

## Contact

- **LinkedIn:** [Leandro de Oliveira Barbosa](https://linkedin.com/in/leandrodeobarbosa)
- **Portfolio:** [leandrodeobarbosa.dev](https://leandrodeobarbosa.dev)
- **Email:** [leandro@leandrodeobarbosa.dev](mailto:leandro@leandrodeobarbosa.dev)

---

<p align="center">
  <i>Building governed delivery paths for cloud-native workloads.</i>
</p>
