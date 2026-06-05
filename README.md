# Hi, I'm David 👋

I'm building my way into **DevOps and Platform Engineering** through hands-on
projects. I enjoy the infrastructure and operations side of things — making
services run reliably, understanding how the pieces fit together, and writing
down how systems actually work. I learn by building real projects and documenting
them here.

---

## Current focus

- **Linux** as my daily working environment
- **Docker** and **Docker Compose**
- **Kubernetes** and **CKAD** preparation
- **Kustomize** and **Helm**
- **GitOps** with **Argo CD**
- **GitHub Actions** CI
- **Monitoring** and **observability**
- **Backup and restore** strategy
- **Platform Engineering** fundamentals

---

## Main projects

### 1. KubeBase Platform

**[KubeBase Platform](https://github.com/Carrasco515/kubebase-platform)** is my
Kubernetes-focused DevOps and Platform Engineering lab. It shows how a small
FastAPI app moves through a realistic local cloud-native delivery path:
**Docker → Kubernetes → Kustomize → Helm → GitOps with Argo CD → Observability.**

- **FastAPI** app with a small, non-root **Docker** image
- **Kubernetes** base manifests (Deployment, Service, ConfigMap, probes, limits)
- **Kustomize** overlays for dev and prod
- **Helm** chart (`charts/kubebase-api`) with dev/prod values
- **Argo CD GitOps** — the dev Application was synced locally to **Synced & Healthy**
- **Prometheus-style `/metrics`** endpoint and a **Grafana** starter dashboard
- **GitHub Actions** CI, plus architecture, operations, GitOps and observability docs

Everything runs locally in **Minikube**. Prod is example-only and was not applied.

### 2. CloudBase Lab

**[CloudBase Lab](https://github.com/Carrasco515/cloudbase-lab)** is my
self-hosted DevOps homelab, where I run a local private cloud stack with **Docker
Compose**. It's where I practise infrastructure operations, monitoring, backup
strategy, restore testing, security hygiene and documentation as code.

- **Traefik** reverse proxy with local HTTPS
- **Nextcloud** with **MariaDB** and **Redis**
- **Uptime Kuma** monitoring and status page
- **Portainer** for container management and **Vaultwarden** as a password manager
- **Watchtower** with safe, opt-in updates
- **Backup automation**, backup verification and an **isolated restore drill**
- **GitHub Actions** CI, plus architecture and operations documentation

Everything runs locally by default — nothing is exposed to the internet.

---

## What I'm learning

Getting comfortable with **Kubernetes** and **Platform Engineering** fundamentals,
deepening **CI** and **observability** habits, treating **documentation as code**,
and practising reliable, repeatable operations.

---

These repositories document my practical learning projects as I grow into the
field. I'm always open to feedback — feel free to take a look. 💬
