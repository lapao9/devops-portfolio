<div align="center">

# 🚀 DevOps Engineering Portfolio

**One real application built from scratch to production**
*Task Manager API — from the command line to Kubernetes on the cloud*

[![Foundations](https://img.shields.io/badge/01-Foundations-00ff9d?style=for-the-badge)](https://github.com/lapao9/devops-foundations)
[![CI/CD](https://img.shields.io/badge/02-CI/CD-00d4ff?style=for-the-badge)](https://github.com/lapao9/devops-cicd)
[![Containers](https://img.shields.io/badge/03-Containers-bf5af2?style=for-the-badge)](https://github.com/lapao9/devops-containers)
[![Infrastructure](https://img.shields.io/badge/04-Infrastructure-ff6b35?style=for-the-badge)](https://github.com/lapao9/devops-infrastructure)
[![Observability](https://img.shields.io/badge/05-Observability-ffd60a?style=for-the-badge)](https://github.com/lapao9/devops-observability)

</div>

---

## 📖 About this Portfolio

This portfolio demonstrates building a **task management REST API** from initial code to full cloud infrastructure — each phase adds a new layer of DevOps maturity.

The same application evolves across 5 projects:
```
Local code  →  CI/CD Pipeline  →  Containers  →  Cloud  →  Monitoring
```

---

## 🗺️ Project Roadmap

| # | Project | Stack | Status |
|---|---------|-------|--------|
| 01 | [**Foundations**](https://github.com/lapao9/devops-foundations) | Python · FastAPI · PostgreSQL · Docker | ✅ Complete |
| 02 | [**CI/CD Pipeline**](https://github.com/lapao9/devops-cicd) | GitHub Actions · GHCR · pytest | ✅ Complete |
| 03 | [**Containers**](https://github.com/lapao9/devops-containers) | Docker · Kubernetes · Helm | 🔄 In progress |
| 04 | [**Infrastructure**](https://github.com/lapao9/devops-infrastructure) | AWS · Terraform · Ansible | ⏳ Planned |
| 05 | [**Observability**](https://github.com/lapao9/devops-observability) | Prometheus · Grafana · ELK | ⏳ Planned |

---

## 🏗️ Final Architecture

Once all projects are complete, the full architecture will look like this:
```
                        ┌─────────────────────────────────────┐
                        │           AWS Cloud (Terraform)      │
                        │                                      │
                        │   ┌─────────────────────────────┐   │
                        │   │     EKS Kubernetes Cluster   │   │
                        │   │                              │   │
          git push      │   │  ┌──────────┐ ┌──────────┐  │   │
              │         │   │  │ Task API │ │ Task API │  │   │
              ▼         │   │  │  Pod 1   │ │  Pod 2   │  │   │
    ┌─────────────────┐ │   │  └────┬─────┘ └────┬─────┘  │   │
    │  GitHub Actions │ │   │       └──────┬──────┘        │   │
    │  CI → tests     │ │   │         ┌────▼─────┐         │   │
    │  CD → deploy    │─┼───┼────────▶│ PostgreSQL│        │   │
    └─────────────────┘ │   │         │   (RDS)   │        │   │
              │         │   │         └───────────┘        │   │
              ▼         │   └─────────────────────────────┘   │
    ┌─────────────────┐ │                  │                   │
    │  GHCR           │ │   ┌──────────────▼──────────────┐   │
    │  Docker Images  │ │   │  Prometheus + Grafana + ELK  │   │
    └─────────────────┘ │   └─────────────────────────────┘   │
                        └─────────────────────────────────────┘
```

---

## 🛠️ Full Tech Stack

**Languages & Frameworks**
- Python 3.12 · FastAPI · SQLAlchemy · Pydantic · pytest

**Containers & Orchestration**
- Docker · Docker Compose · Kubernetes · Helm

**CI/CD**
- GitHub Actions · GitHub Container Registry

**Cloud & IaC**
- AWS (EC2 · RDS · EKS · S3 · VPC · IAM)
- Terraform · Ansible

**Monitoring**
- Prometheus · Grafana · Elasticsearch · Logstash · Kibana

---

## 📂 How to explore this portfolio

**If you're a recruiter with 2 minutes:**
→ Head to [Project 01](https://github.com/lapao9/devops-foundations) and read the README

**If you want to see CI/CD in action:**
→ Head to [Project 02](https://github.com/lapao9/devops-cicd) → Actions tab

**If you want to dive into the code:**
→ Start at [Project 01 · app/routers/tasks.py](https://github.com/lapao9/devops-foundations/blob/main/app/routers/tasks.py)

---

## 📈 Progress
```
[██████████░░░░░░░░░░] 40% complete
Phase 1 ✅  Phase 2 ✅  Phase 3 🔄  Phase 4 ⏳  Phase 5 ⏳
```

---

<div align="center">

**Built as a DevOps engineering portfolio — 2024**

</div>
