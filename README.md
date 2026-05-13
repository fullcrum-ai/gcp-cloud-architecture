# ☁️ Google Cloud — Architecture & Skills Challenge Portfolio

**Willington Moreno** · Cloud & Data Solution Architect · [Full.Crum](https://fullcrum.com.au)

> A practical portfolio of Google Cloud architecture patterns, lab implementations, and solutions built during the **Google Cloud Professional Cloud Architect** certification journey.

---

## 🎯 Purpose

This repository documents hands-on work completed across Google Cloud Skills Challenges and certification preparation — translating lab experience into reusable, real-world architecture patterns applicable to enterprise and mid-market engagements across ANZ.

Each module goes beyond lab completion — it captures **architecture decisions, cost considerations, and how each pattern applies to real client scenarios.**

---

## 📂 Repository Structure

```
gcp-cloud-architect/
│
├── 01-core-infrastructure/          # Compute, networking, storage foundations
│   ├── compute-engine/              # VM instances, instance groups, autoscaling
│   ├── cloud-storage/               # Buckets, lifecycle, IAM, transfer
│   ├── vpc-networking/              # VPC design, subnets, firewall rules, peering
│   └── README.md
│
├── 02-kubernetes-and-containers/    # GKE and container architecture
│   ├── gke-cluster-setup/           # Cluster design, node pools, autopilot
│   ├── workload-deployment/         # Deployments, services, ingress patterns
│   └── README.md
│
├── 03-data-and-analytics/           # BigQuery, Dataflow, Pub/Sub
│   ├── bigquery/                    # Datasets, queries, optimisation patterns
│   ├── dataflow-pipelines/          # Batch and streaming pipeline patterns
│   ├── pubsub/                      # Event-driven architecture patterns
│   └── README.md
│
├── 04-ai-and-ml/                    # Vertex AI, Gemini, AI Platform
│   ├── vertex-ai/                   # Model training, deployment, pipelines
│   ├── gemini-integrations/         # Gemini API, multimodal patterns
│   └── README.md
│
├── 05-security-and-iam/             # Identity, access, compliance
│   ├── iam-patterns/                # Roles, service accounts, best practices
│   ├── org-policies/                # Constraints, guardrails
│   └── README.md
│
├── 06-devops-and-cicd/              # Cloud Build, Artifact Registry, deployment
│   ├── cloud-build/                 # CI/CD pipeline patterns
│   ├── terraform-gcp/               # Infrastructure as Code for GCP
│   └── README.md
│
├── 07-architecture-patterns/        # Real-world solution architectures
│   ├── landing-zone/                # GCP organisation landing zone design
│   ├── hybrid-connectivity/         # Cloud Interconnect, VPN, multi-cloud
│   ├── data-platform/               # Modern data platform on GCP
│   └── README.md
│
├── skills-challenges/               # Google Cloud Skills Challenge completions
│   ├── challenge-tracker.md         # Progress tracker across all challenges
│   └── badges/                      # Links to earned badges and completions
│
├── architecture-diagrams/           # All architecture diagrams in one place
│
└── README.md                        # This file
```

---

## 🏅 Skills Challenge Progress

| Challenge | Status | Completed | Badge |
|---|---|---|---|
| Google Cloud Computing Foundations | ✅ Complete | 2025 | [View Badge](#) |
| Cloud Architecture: Design, Implement and Manage | 🔨 In Progress | — | — |
| Implement Load Balancing on Compute Engine | 📋 Planned | — | — |
| Set Up an App Dev Environment on Google Cloud | 📋 Planned | — | — |
| Develop your Google Cloud Network | 📋 Planned | — | — |
| Build Infrastructure with Terraform on Google Cloud | 📋 Planned | — | — |
| Cloud Digital Leader | 📋 Planned | — | — |

> **Certification Target:** Google Cloud Professional Cloud Architect

---

## 🗺️ Architecture Patterns Covered

### Infrastructure & Networking
- VPC design with shared VPC and VPC peering
- Hub and spoke network topology on GCP
- Cloud NAT, load balancing, and Cloud CDN patterns
- Hybrid connectivity — Cloud Interconnect and Cloud VPN

### Data & Analytics
- BigQuery data warehouse design and optimisation
- Dataflow batch and streaming pipeline patterns
- Pub/Sub event-driven architecture
- Modern data platform — GCP equivalent of medallion architecture

### AI & Machine Learning
- Vertex AI pipeline patterns
- Gemini API integration for enterprise use cases
- AI-assisted data processing workflows

### Security & Governance
- Organisation policy framework
- Service account and IAM least privilege patterns
- VPC Service Controls for data perimeter security
- Cloud Armor for application security

---

## 💡 Multi-Cloud Context

This work sits alongside an existing Azure-primary architecture practice. Key comparisons documented throughout:

| Capability | Azure Equivalent | GCP Service |
|---|---|---|
| Virtual Machines | Azure VMs | Compute Engine |
| Kubernetes | AKS | GKE |
| Object Storage | Azure Blob | Cloud Storage |
| Data Warehouse | Azure Synapse | BigQuery |
| Stream Processing | Azure Event Hubs | Pub/Sub + Dataflow |
| ML Platform | Azure ML | Vertex AI |
| IaC | Terraform / Bicep | Terraform / Deployment Manager |
| Serverless | Azure Functions | Cloud Functions / Cloud Run |

> These comparisons help enterprise clients understand GCP capabilities in terms of their existing Azure investments — a practical consulting lens applied throughout this portfolio.

---

## 🛠️ Tools & Prerequisites

```bash
# Google Cloud SDK
gcloud --version

# Terraform
terraform --version

# Python (for scripts and notebooks)
python --version
```

All labs and implementations use:
- **Google Cloud SDK** — gcloud CLI
- **Terraform** — Infrastructure as Code
- **Python 3.9+** — scripts and data processing
- **Cloud Shell** — browser-based environment for quick implementations

---

## 📐 Architecture Diagrams

All architecture diagrams are built with [Excalidraw](https://excalidraw.com) and stored in `/architecture-diagrams`. Each lab and pattern folder links to its relevant diagram.

---

## 🔗 Related Repositories

| Repository | Description |
|---|---|
| [azure-cloud-architecture](#) | Azure landing zones, hybrid cloud, and enterprise patterns |
| [modern-data-stack](#) | Snowflake, dbt, and Python ELT pipeline |
| [databricks-lakehouse](#) | Delta Lake medallion architecture on Databricks |
| [ai-agent-architecture](#) | AI agent patterns on Snowflake Cortex and LangChain |

---

## 👤 About

**Willington Moreno** is a Cloud & Data Solution Architect with 14+ years delivering enterprise architecture across Australia and New Zealand. Founder of [Full.Crum](https://fullcrum.com.au) — an AI and data architecture consultancy based in Brisbane, AU.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/willingtonmoreno)
[![Website](https://img.shields.io/badge/Full.Crum-000000?style=flat-square&logo=google-chrome&logoColor=29B5E8)](https://fullcrum.com.au)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:willington@fullcrum.com.au)

---

*Brisbane, AU · Available for consulting engagements across ANZ*
