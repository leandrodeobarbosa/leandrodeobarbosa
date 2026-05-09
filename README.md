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
  <img src="https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white" alt="ArgoCD" />
</p>

## About me

I am a DevOps Engineer focused on cloud infrastructure, CI/CD automation, Infrastructure as Code (IaC), Kubernetes, GitOps, and Platform Engineering.

I use **[DevOpsfera Labs](https://github.com/devopsfera-labs)** as my engineering lab to build and validate production-oriented DevOps and Platform Engineering patterns.

My main initiative is **FlowDX**, a platform engineering project focused on self-service workload delivery through reusable workflows, declarative contracts, GitOps, Policy-as-Code, and governed automation.

## Production Portfolio

My personal portfolio, **[leandrodeobarbosa.dev](https://leandrodeobarbosa.dev)**, is deployed on AWS using Infrastructure as Code and automated CI/CD pipelines.

The infrastructure includes:

- Amazon S3 for static site hosting
- Amazon CloudFront for CDN and edge delivery
- Amazon Route 53 for DNS management
- AWS Certificate Manager for TLS certificates
- Terraform modules for reusable infrastructure components
- Terraform remote state with S3 and DynamoDB state locking
- GitHub Actions pipelines for application and infrastructure validation/deployment
- Matrix-based infrastructure validation across environments

This live environment serves as a practical foundation where I validate Terraform module design, AWS, CI/CD, OIDC, drift detection, multi-environment workflows, and operational practices.

## Main Initiative: FlowDX

**FlowDX** is not intended to be a full Internal Developer Platform (IDP) at this stage.

The current goal is to build a focused platform foundation where application repositories consume standardized platform capabilities instead of rebuilding CI/CD, governance, container delivery, and Kubernetes deployment logic from scratch.

```text
flowdx-platform
  -> flowdx-reference-api
  -> GHCR
  -> flowdx-gitops
  -> Kind Kubernetes
```

The reference architecture explores:

- reusable GitHub Actions workflows
- declarative workload contracts with `flowdx.yaml`
- FastAPI reference workload with structured JSON logs
- Docker image publishing to GHCR
- immutable GitOps deployments using image digests
- Helm-based Kubernetes packaging
- ArgoCD-based delivery
- Gateway API routing with NGINX Gateway Fabric
- Policy-as-Code with Kyverno
- local validation with Kind, Prometheus, and Grafana

## What I’m demonstrating

- **Live AWS Environment:** personal portfolio deployed with S3, CloudFront, Route 53, ACM, Terraform remote state, DynamoDB state locking, and GitHub Actions.
- **Cloud Infrastructure:** AWS, Terraform, remote state, IAM, OIDC, and drift detection.
- **CI/CD Governance:** reusable workflows, required checks, approval gates, and sanitized pipeline feedback.
- **Container Delivery:** Docker builds, GHCR publishing, traceable image references, and digest-based deployments.
- **GitOps & Kubernetes:** ArgoCD, Helm, Kind, Gateway API, and declarative runtime state.
- **Security & Policy:** least privilege, Policy-as-Code, Kyverno policies, and controlled delivery paths.
- **Observability:** structured logs, Prometheus, Grafana, and CloudWatch fundamentals.

## Tech Stack

**Cloud & Infrastructure**  
`AWS` `Terraform` `Remote State` `S3` `CloudFront` `Route 53` `ACM` `DynamoDB` `IAM` `OIDC`

**CI/CD & Supply Chain**  
`GitHub Actions` `Reusable Workflows` `Docker` `GHCR` `Image Digest`

**Application Runtime**  
`Python` `FastAPI` `Structured Logs`

**Kubernetes & GitOps**  
`Kubernetes` `Kind` `Helm` `ArgoCD` `Gateway API` `NGINX Gateway Fabric`

**Governance, Security & Observability**  
`Kyverno` `Policy-as-Code` `RBAC` `Least Privilege` `Prometheus` `Grafana` `CloudWatch`

## Current Focus

- Building `flowdx-platform` as the platform hub.
- Creating `flowdx-reference-api` as the reference FastAPI workload.
- Structuring `flowdx-gitops` as the GitOps source of truth.
- Validating the delivery flow with Kind, ArgoCD, NGINX Gateway Fabric, Kyverno, Prometheus, and Grafana.
- Improving CI/CD governance with OIDC, required checks, Policy-as-Code, and sanitized feedback.
- Maintaining a live AWS-based portfolio with Terraform, GitHub Actions, and production-oriented operational practices.

## Contact

- **LinkedIn:** [Leandro de Oliveira Barbosa](https://linkedin.com/in/leandrodeobarbosa)
- **Portfolio:** [leandrodeobarbosa.dev](https://leandrodeobarbosa.dev)
- **Email:** [leandro@leandrodeobarbosa.dev](mailto:leandro@leandrodeobarbosa.dev)

---

<p align="center">
  <i>Building governed delivery paths for cloud-native workloads.</i>
</p>
