# 🚀 Master Kubernetes: From Zero to Production Hero

Six real-world apps. Twenty hands-on labs. One rigorous journey to production-grade Kubernetes.

---

## � New Here? Start Here!

**→ [📖 GETTING STARTED GUIDE](docs/GETTING-STARTED.md) ← START HERE**

Complete onboarding in 30 minutes:
- ✅ Tool installation (Rancher Desktop or kind/k3d)
- ✅ Verification steps
- ✅ Your first kubectl command
- ✅ Clear learning path from beginner → expert

---

## 🏁 Quick start (If you already have tools installed)

1. **Install Visualization Tools** → [Lab 0: Visual Kubernetes](labs/00-visual-kubernetes.md) (k9s, stern, kubectl-tree)
2. **Deploy Your First App** → [Lab 1: Weather Basics](labs/01-weather-basics.md)
3. **Track Your Journey** → [LAB-PROGRESS.md](docs/learning/LAB-PROGRESS.md)

**Don't have Kubernetes yet?** → [GETTING STARTED Guide](docs/GETTING-STARTED.md) sets you up in 10 minutes

## 🧭 Lab roadmap
See the full progression (difficulty, prerequisites, success criteria) in:
- [KUBERNETES-LABS.md](docs/KUBERNETES-LABS.md)

Each lab includes: story-driven steps, validation checks, troubleshooting, and challenge mode.

## 🧱 Application portfolio & Lab progression

| Lab | App | Stack | Difficulty | Time |
|-----|-----|------|------------|------|
| **Setup** | 👀 **Visual Tools** | k9s, stern, kubectl-tree | ⭐ | **15m** |
| [Lab 0](labs/00-visual-kubernetes.md) | | Install essential K8s visualization tools | | |
| [Lab 0.5](labs/00.5-docker-compose-to-kubernetes.md) | 🐳 **Docker → K8s Migration** | Compose to manifests | ⭐ | **40m** |
| | | | | |
| **Foundations** | | | | |
| [Lab 1](labs/01-weather-basics.md) | 🌦️ Weather App | Vue + Python + Redis | ⭐ | **20m** |
| [Lab 2](labs/02-ecommerce-basics.md) | 🛒 E-commerce | React + Node + MongoDB | ⭐⭐ | **30m** |
| [Lab 3](labs/03-educational-stateful.md) | 🎓 Educational | Angular + Java + Postgres | ⭐⭐⭐ | **40m** |
| [Lab 3.5](labs/03.5-kubernetes-under-the-hood.md) | 🔧 **K8s Internals** | etcd, controllers, API | ⭐⭐⭐⭐ | **50m** |
| [Lab 4](labs/04-kubernetes-fundamentals.md) | 🏷️ **Fundamentals** | Labels, troubleshooting | ⭐⭐ | **75m** |
| | | | | |
| **Production Ops** | | | | |
| [Lab 5](labs/05-task-ingress.md) | ✅ Task Manager | Svelte + Go + Postgres | ⭐⭐⭐ | **45m** |
| [Lab 6](labs/06-medical-security.md) | 🏥 Medical Care | Blazor + .NET + Postgres | ⭐⭐⭐⭐ | **60m** |
| [Lab 7](labs/07-social-scaling.md) | 📱 Social Media | React Native + Ruby + Postgres | ⭐⭐⭐⭐⭐ | **90m** |
| | | | | |
| **Platform Engineering** | | | | |
| [Lab 8](labs/08-multi-app.md) | 🧩 **Multi-App** | All 6 apps orchestration | ⭐⭐⭐⭐⭐ | **120m** |
| [Lab 8.5](labs/08.5-multi-tenancy.md) | 🏢 **Multi-Tenancy** | Namespaces, isolation | ⭐⭐⭐⭐ | **60m** |
| [Lab 9](labs/09-chaos.md) | ⚡ **Chaos** | Resilience testing | ⭐⭐⭐⭐ | **90m** |
| [Lab 9.5](labs/09.5-complex-microservices.md) | 🔀 **Microservices** | Service mesh patterns | ⭐⭐⭐⭐⭐ | **75m** |
| | | | | |
| **Automation Masters** | | | | |
| [Lab 10](labs/10-helm-package-management.md) | 🪄 **Helm** | Charts, templating | ⭐⭐⭐⭐ | **75m** |
| [Lab 11](labs/11-gitops-argocd.md) | 🤖 **GitOps** | ArgoCD, automation | ⭐⭐⭐⭐⭐ | **90m** |
| [Lab 11.5](labs/11.5-disaster-recovery.md) | 🚨 **Disaster Recovery** | Backup, restore | ⭐⭐⭐⭐ | **60m** |
| [Lab 12](labs/12-external-secrets.md) | 🔐 **Secrets** | External Secrets Operator | ⭐⭐⭐⭐ | **60m** |
| [Lab 12.5](labs/12.5-multi-cloud-secrets.md) | ☁️ **Multi-Cloud** | Cross-cloud secrets | ⭐⭐⭐⭐⭐ | **75m** |
| [Lab 13](labs/13-ai-ml-gpu.md) | 🤖 **AI/ML** | GPU workloads | ⭐⭐⭐⭐⭐ | **90m** |
| | | | | |
| **🔥 Challenges** | | | | |
| [Challenge A](labs/challenge-a-midnight-incident.md) | 🚨 **Midnight Incident** | Troubleshooting drill | ⭐⭐⭐ | **45m** |
| [Challenge B](labs/challenge-b-black-friday.md) | 🛍️ **Black Friday** | Scaling under pressure | ⭐⭐⭐⭐ | **60m** |
| [Challenge C](labs/challenge-c-platform-migration.md) | 🏗️ **Platform Migration** | Zero-downtime migration | ⭐⭐⭐⭐⭐ | **90m** |

## 🎒 Learning toolkit
- ✅ [Self-Assessment](docs/learning/SELF-ASSESSMENT.md)
- ⚠️ [Common Mistakes](docs/learning/COMMON-MISTAKES.md)
- 📘 [kubectl Cheatsheet](docs/reference/kubectl-cheatsheet.md) — includes namespace best practices
- 🛠️ [Troubleshooting Hub](docs/troubleshooting/troubleshooting.md)
- 🔐 [Secrets Management](docs/reference/secrets-management.md)
- 🗂️ [Markdown Inventory](docs/MARKDOWN-INDEX.md)

## ✅ Automation & quality checks
- `scripts/check-lab-prereqs.sh` — Verify tools and cluster readiness for each lab
- `scripts/run-link-check-full.sh` — Validate all markdown links
- `scripts/cleanup-workspace.sh` — Clean up Docker/K8s resources between labs

Example:
```bash
# Check if you're ready for Lab 3
./scripts/check-lab-prereqs.sh 3

# Validate all documentation links
./scripts/run-link-check-full.sh

# Clean up resources
./scripts/cleanup-workspace.sh
```

## 🗺️ Repository map

**Complete file inventory**: [REPOSITORY-STRUCTURE.md](REPOSITORY-STRUCTURE.md) — Detailed map of all 77 files

```
├── docs/            # setup, references, labs index
├── labs/            # 23 hands-on labs + 3 challenges + manifests/
├── scripts/         # validators and utilities
├── ecommerce-app/   # React + Node + MongoDB
├── educational-platform/  # Angular + Java + PostgreSQL
├── medical-care-system/   # Blazor + .NET + PostgreSQL
├── social-media-platform/ # React Native + Ruby + PostgreSQL
├── task-management-app/   # Svelte + Go + PostgreSQL
└── weather-app/     # Vue + Python + Redis
```

## 🤝 Contributing
1) Validate links → `./scripts/run-link-check-full.sh`  
2) Test lab prerequisites → `./scripts/check-lab-prereqs.sh <lab-number>`  
3) Clean up workspace → `./scripts/cleanup-workspace.sh`
4) Open a PR with changes and test output

## 💡 Credits
Created by Temitayo Charles Akinniranye — Docker Hub: https://hub.docker.com/u/temitayocharles — Built with ❤️ for engineers who learn by doing.

👉 Start now → [Lab 1: Weather Basics](labs/01-weather-basics.md)