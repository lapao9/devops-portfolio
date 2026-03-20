<div align="center">

# 🚀 DevOps Engineering Portfolio

**Uma aplicação real construída do zero até produção**
*Task Manager API — da linha de comando ao Kubernetes na cloud*

[![Foundations](https://img.shields.io/badge/01-Foundations-00ff9d?style=for-the-badge)](https://github.com/lapao9/devops-foundations)
[![CI/CD](https://img.shields.io/badge/02-CI/CD-00d4ff?style=for-the-badge)](https://github.com/lapao9/devops-cicd)
[![Containers](https://img.shields.io/badge/03-Containers-bf5af2?style=for-the-badge)](https://github.com/lapao9/devops-containers)
[![Infrastructure](https://img.shields.io/badge/04-Infrastructure-ff6b35?style=for-the-badge)](https://github.com/lapao9/devops-infrastructure)
[![Observability](https://img.shields.io/badge/05-Observability-ffd60a?style=for-the-badge)](https://github.com/lapao9/devops-observability)

</div>

---

## 📖 Sobre este Portfolio

Este portfolio demonstra a construção de uma **API de gestão de tarefas** desde o código inicial até infraestrutura completa na cloud — cada fase adiciona uma camada de maturidade DevOps.

A mesma aplicação evolui ao longo de 5 projetos:
```
Código local  →  Pipeline CI/CD  →  Containers  →  Cloud  →  Monitorização
```

---

## 🗺️ Roadmap do Projeto

| # | Projeto | Stack | Status |
|---|---------|-------|--------|
| 01 | [**Foundations**](https://github.com/lapao9/devops-foundations) | Python · FastAPI · PostgreSQL · Docker | ✅ Completo |
| 02 | [**CI/CD Pipeline**](https://github.com/lapao9/devops-cicd) | GitHub Actions · GHCR · pytest | ✅ Completo |
| 03 | [**Containers**](https://github.com/lapao9/devops-containers) | Docker · Kubernetes · Helm | 🔄 Em progresso |
| 04 | [**Infrastructure**](https://github.com/lapao9/devops-infrastructure) | AWS · Terraform · Ansible | ⏳ Planeado |
| 05 | [**Observability**](https://github.com/lapao9/devops-observability) | Prometheus · Grafana · ELK | ⏳ Planeado |

---

## 🏗️ Arquitetura Final

Quando todos os projetos estiverem completos, a arquitetura será:
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
    │  CI → testes    │ │   │         ┌────▼─────┐         │   │
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

## 🛠️ Stack Tecnológico Completo

**Linguagens & Frameworks**
- Python 3.12 · FastAPI · SQLAlchemy · Pydantic · pytest

**Containers & Orquestração**
- Docker · Docker Compose · Kubernetes · Helm

**CI/CD**
- GitHub Actions · GitHub Container Registry

**Cloud & IaC**
- AWS (EC2 · RDS · EKS · S3 · VPC · IAM)
- Terraform · Ansible

**Monitorização**
- Prometheus · Grafana · Elasticsearch · Logstash · Kibana

---

## 📂 Como explorar este portfolio

**Se és recrutador e tens 2 minutos:**
→ Vai ao [Projeto 01](https://github.com/lapao9/devops-foundations) e lê o README

**Se queres ver CI/CD a funcionar:**
→ Vai ao [Projeto 02](https://github.com/lapao9/devops-cicd) → separador Actions

**Se queres ver o código:**
→ Começa pelo [Projeto 01 · app/routers/tasks.py](https://github.com/lapao9/devops-foundations/blob/main/app/routers/tasks.py)

---

## 📈 Progresso
```
[██████████░░░░░░░░░░] 40% completo
Fase 1 ✅  Fase 2 ✅  Fase 3 🔄  Fase 4 ⏳  Fase 5 ⏳
```

---

<div align="center">

**Construído como portfolio DevOps — 2024**

</div>
