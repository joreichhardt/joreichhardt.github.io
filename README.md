![Linux](https://img.shields.io/badge/Linux-Expert-blue)
![Terraform](https://img.shields.io/badge/Terraform-IaC-purple)
![Kubernetes](https://img.shields.io/badge/Kubernetes-Orchestration-blue)
![GCP](https://img.shields.io/badge/Google%20Cloud-Platform-yellow)

# Johannes Reichhardt

**Senior Linux / DevOps / Platform Engineer**  
Infrastructure, Automation & Cloud

* Creative by training (Master of Fine Arts (Diplom Freie Kunst), Academy of Fine Arts Munich) 
* Engineer by practice 

* 15+ years of real-world experience in Linux, infrastructure, and automation
* 25+ years Linux User

---

## 🚀 About Me

I design and operate **production-ready infrastructure** with a strong focus on:

- **Infrastructure as Code:** (Terraform-first mindset)
- **Cloud Platforms:** Deep expertise in Google Cloud (GCP)
- **GitOps & Platform Engineering:** Automated toolsets with **Backstage (IDP)** and **Argo CD**
- **CI/CD Architecture:** Self-hosted Gitea & Gitea Actions on Kubernetes
- **Containerization:** Modern Kubernetes standards (GKE / Gateway API)
- **AI Integration:** Deploying and scaling LLM-powered applications

I prefer **pragmatic solutions over over-engineering**.

---

## 📂 Featured Projects

### 🏗️ GCP Platform Engineering Portal (Backstage)
A modern Internal Developer Portal (IDP) designed to automate infrastructure provisioning on Google Cloud Platform.

- **Self-Service:** 10+ ready-to-use Scaffolder templates for GKE, Cloud SQL, GCS, and more.
- **Security:** Keyless authentication via GCP Workload Identity Federation (OIDC) for GitHub Actions.
- **Automation:** Generates Terraform code and CI/CD workflows automatically.
- **Architecture:** Built on the latest Backstage backend system for modularity and performance.
- **Deployment:** Fully containerized and ready for production-scale orchestration.

👉 [GitHub Repository](https://github.com/joreichhardt/backstage-portal)

---

### 🛠️ Cloud-Native GKE Platform Toolset
A fully automated, production-ready GKE infrastructure featuring a complete DevOps stack.

- **IaC:** Fully provisioned via Terraform with GCS state backend.
- **GitOps:** Argo CD for automated application lifecycle management.
- **CI/CD:** Self-hosted **Gitea** with **Gitea Actions** for internal Docker builds.
- **Traffic:** Modern GKE Gateway API for global traffic routing with automatic HTTP-to-HTTPS redirect.
- **Auto-DNS & SSL:** Integrated ExternalDNS and Cert-Manager (Let's Encrypt) via DNS-01 challenge.
- **Observability:** Complete Prometheus and Grafana stack.
- **Security:** GKE Workload Identity for keyless GCP service access.

### ☕ Hannes Albeiro the Paisa  

**Live Platform Links**

- 🚀 Platform Repo: [gke-with-toolset](https://github.com/joreichhardt/gke-with-toolset)  

- 🤖 Demo App: [txt2md](https://txt2md.hannesalbeiro.com)
- ⚙️ Git Ops UI: [Argo CD](https://argocd.hannesalbeiro.com)
- 📊 Observability: [Grafana](https://grafana.hannesalbeiro.com)
- 🍵 Git & CI: [Gitea](https://gitea.hannesalbeiro.com)

---

### 📝 txt2md - AI-Powered Text Processing
A modern full-stack application showcasing the integration of Generative AI into cloud-native environments.

- **Stack:** Python Flask, Markdown rendering, Google Gemini API.
- **Cloud-Native:** Containerized with Docker, deployed via Argo CD on GKE.
- **CI/CD:** Automatic builds via Gitea Actions and Artifact Registry.
- **Architecture:** Leverages modern LLM models (Gemini 2.5 Flash) for high-quality text structuring.
- **Automation:** Versioned deployments with automated rollouts via Argo CD Image Updater.

👉 [GitHub Repository](https://github.com/joreichhardt/txt2md)

---

### ⚙️ Production-ready k3s Cluster with CI/CD
Lightweight Kubernetes cluster with modern, secure deployment pipeline.

- One-command deployment on GCP with Terraform.
- GitHub Actions CI/CD pipeline with keyless OIDC authentication.
- Packer for building custom golden Debian images.
- Designed for small-scale production workloads.

👉 [GitHub Repository](https://github.com/joreichhardt/production-ready-k3s-cluster-automation)

## 🛠️ Tech Stack

**Cloud & Infrastructure**
- **GCP:** GKE, Artifact Registry, Cloud DNS, IAM, GCS
- **IaC:** Terraform (Expert)
- **OS:** Linux (Ubuntu / Debian - 25+ years experience)

**Containers & Orchestration**
- **Kubernetes:** GKE, k3s, Bare Metal
- **Networking:** Gateway API, Ingress, WireGuard
- **GitOps & IDP:** Backstage (Internal Developer Portal), Argo CD

**CI/CD & Developer Tools**
- **Git:** Gitea (Self-hosted), GitHub
- **Automation:** Gitea Actions, GitHub Actions
- **Security:** Cert-Manager, Workload Identity, OIDC

**Observability**
- **Monitoring:** Prometheus, Grafana

**Development & AI**
- **Languages:** Python, Bash/Shell
- **AI:** Google Gemini API Integration

## 📫 Contact

- 📧 Email: [johannes.reichhardt@gmail.com](mailto:johannes.reichhardt@gmail.com)
- 💻 GitHub: [github.com/joreichhardt](https://github.com/joreichhardt)

## ⚡ Philosophy

> "Build systems that are simple, reproducible and actually work in production."

I choose the right tool for the job:
- **Docker** for simple, reliable setups.
- **k3s** for lightweight orchestration.
- **GKE** for enterprise scalability and managed services.
- **Generative AI** to enhance application capabilities.
