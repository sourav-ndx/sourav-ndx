# Sourav Nandy
**Platform Engineer · DevOps Engineer · Solutions Architect · CKA Certified**

[![CKA](https://img.shields.io/badge/CKA-Certified-326CE5?style=flat-square&logo=kubernetes&logoColor=white)](https://www.credly.com/badges/2b6ebf27-cbb6-4e01-bd5f-10757e5efb93/public_url)
[![OpenShift](https://img.shields.io/badge/OpenShift-4.x-EE0000?style=flat-square&logo=red-hat-open-shift&logoColor=white)](https://github.com/sourav-ndx)
[![AWS](https://img.shields.io/badge/AWS-EKS_·_VPC_·_IAM-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)](https://github.com/sourav-ndx/aws-eks-platform)
[![AWS SAA](https://img.shields.io/badge/AWS_SAA-In_Progress-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)](https://github.com/sourav-ndx)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/sourav-nandy-0115)

---

## About

Platform Engineer and Solutions Architect with 9+ years designing, deploying, and operating cloud-native infrastructure at enterprise and telecom scale. Currently leading platform engineering and developer experience on a production multi-cluster OpenShift environment — building software factory tooling that enables a cross-functional team of 25+ engineers to ship independently.

I work across the full platform stack: container orchestration, DevSecOps CI/CD pipelines, GitOps deployments, cloud infrastructure on AWS, observability, advanced networking, and security. Beyond the technical work, I drive architecture decisions, coordinate across Dev, QA, Network, and Infrastructure teams, and own platform initiatives end to end on an Agile PI cadence.

CKA certified. Targeting senior Platform Engineer, DevOps Engineer, and SRE roles.

---

## What I Build & Operate

| Area | Tools & Technologies |
|:---|:---|
| **Container Platforms** | OpenShift 4.x, Kubernetes, EKS, Docker, Helm, ArgoCD, StatefulSets, RBAC, Quay, ECR |
| **CI/CD & GitOps** | GitLab CI (self-hosted shell runners), GitHub Actions (OIDC), ArgoCD GitOps, gated environment promotion (dev → test → prod) |
| **DevSecOps** | SonarQube (SAST, quality gates), Trivy (CVE scanning, CRITICAL block), Quay/Clair (registry scanning), Artifactory, shift-left security |
| **Infrastructure as Code** | Terraform (AWS — VPC, EKS, IAM, S3, modules, remote state, DynamoDB locking), Ansible (playbooks, roles, Ansible Tower, 70+ servers) |
| **Observability** | TIG Stack — Telegraf/InfluxDB/Grafana (production), ELK Stack — Elasticsearch/Logstash/Kibana, Loki + Vector, CloudWatch Container Insights, Fluent Bit |
| **Cloud** | AWS — EKS, VPC, ALB, ECR, IAM/IRSA/OIDC, CloudWatch, S3 · GCP — Compute Engine, kubeadm |
| **Security** | TLS/mTLS, CA-signed certificates, RBAC, IAM/IRSA/OIDC, secrets management, container image scanning, compliance gates, zero-credential auth |
| **Networking** | F5 BIG-IP (iRules, SSL/TLS), F5+CIS, MetalLB (BGP), Multus CNI, Egress IP, NADs, VLAN, NetworkPolicy, tcpdump |
| **Scripting** | Bash, Python, YAML, Jinja2, kubectl, oc |

---

## Repositories

| Repo | What it is |
|:---|:---|
| [gitops-helm-argocd-pipeline](https://github.com/sourav-ndx/gitops-helm-argocd-pipeline) | Production-grade GitOps pipeline — ArgoCD + Helm, gated environment promotion across dev → test → prod, Python-driven image tag automation, GitLab CI DevSecOps integration. |
| [aws-eks-platform](https://github.com/sourav-ndx/aws-eks-platform) | Production-equivalent 3-tier platform on AWS EKS — VPC, ALB, IRSA, CloudWatch, GitHub Actions CI/CD with OIDC. Zero static credentials anywhere. |
| [devsecops-pipeline](https://github.com/sourav-ndx/devsecops-pipeline) | Production-grade 11-stage CI/CT pipeline reference — GitLab CI, SonarQube, Trivy CVE scanning, ArgoCD GitOps, air-gapped runner. |
| [k8s-kubeadm-gcp](https://github.com/sourav-ndx/k8s-kubeadm-gcp) | Kubernetes cluster built from scratch — kubeadm on GCP, Calico CNI, full upgrade v1.28→v1.29, iptables internals. |
| [argocd_gitops](https://github.com/sourav-ndx/argocd_gitops) | GitOps with ArgoCD — nginx, Grafana and Guestbook deployed via Git on a self-built kubeadm cluster. Real debugging, real learnings. |
| [openshift-virtualization-lab](https://github.com/sourav-ndx/openshift-virtualization-lab) | Hands-on OpenShift Virtualization lab — Fedora VM on Red Hat Developer Sandbox, CDI, DataVolumes, real errors and fixes, networking and storage internals documented with screenshots. |
| [ckad-practice](https://github.com/sourav-ndx/ckad-practice) | CKAD exam prep — 33 scenario scripts with setup/verify on Killercoda. |
| [June2026_Sourav_Pathnex](https://github.com/sourav-ndx/June2026_Sourav_Pathnex) | Daily DevOps learning log — Ansible, Terraform, K8s, GitLab CI/CD, Shell Scripts with code snippets. |
| [docker-refresher](https://github.com/sourav-ndx/docker-refresher) | Node.js + Dockerfile — concise Docker concepts reference. |

---

## Currently

- ✅ **GitOps Gated Deployment Pipeline** — ArgoCD + Helm, dev → test → prod with manual gates, Python image tag automation, GitLab CI integration → [gitops-helm-argocd-pipeline](https://github.com/sourav-ndx/gitops-helm-argocd-pipeline)
- ✅ **AWS EKS Platform** — 3-tier app, VPC design, IRSA, ALB Controller, CloudWatch, GitHub Actions OIDC CI/CD → [aws-eks-platform](https://github.com/sourav-ndx/aws-eks-platform)
- ✅ **DevSecOps CI/CT Pipeline** — 11-stage GitLab CI reference, Trivy CVE scanning, SonarQube quality gates, ArgoCD GitOps two-repo model → [devsecops-pipeline](https://github.com/sourav-ndx/devsecops-pipeline)
- ✅ **Kubernetes cluster from scratch** — kubeadm on GCP, full control plane, upgraded v1.28→v1.29 → [k8s-kubeadm-gcp](https://github.com/sourav-ndx/k8s-kubeadm-gcp)
- ✅ **ArgoCD GitOps** on kubeadm cluster — self-healing, automated sync, real debugging → [argocd_gitops](https://github.com/sourav-ndx/argocd_gitops)
- ✅ **OpenShift Virtualization hands-on lab** — Fedora VM on OCP, CDI, DataVolumes, virt-launcher internals, masquerade networking → [openshift-virtualization-lab](https://github.com/sourav-ndx/openshift-virtualization-lab)
- 🔵 Preparing for **AWS Solutions Architect Associate** — renewal in progress
- 🔵 Expanding **Terraform** — module design, remote state, CI/CD integration
- 🔵 Expanding **Python automation** for DevOps workflows

---

📍 Bangalore, India · Open to **Platform Engineer / DevOps Engineer / SRE** roles
