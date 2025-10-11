<h1 align="center">✨😺 Ducheved — Senior Architect 🧠☁️</h1>
<p align="center">
  <img src="https://media.tenor.com/TmBdFfhuEEsAAAAC/space-cat.gif" width="180"><br>
  <em>Always forward, no retreat. But with a little meow.</em>
</p>

---

<p align="center">
  <img src="https://img.shields.io/badge/Golang-🐹-00ADD8?style=for-the-badge&logo=go&logoColor=white">
  <img src="https://img.shields.io/badge/Rust-🦀-000000?style=for-the-badge&logo=rust&logoColor=white">
  <img src="https://img.shields.io/badge/Kubernetes-☸️-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white">
  <img src="https://img.shields.io/badge/DevOps-Lover💜-444444?style=for-the-badge&logo=linux&logoColor=white">
  <img src="https://img.shields.io/badge/Architect-🏗️-grey?style=for-the-badge">
</p>

---

### 🐾 TL;DR
I design and build **distributed systems** ready for real production.  
Main languages: **Golang 🐹** and **Rust 🦀**.  
15+ years in software engineering and **DevOps / Kubernetes (☸️)**.  
Focus: **high availability**, **security**, and **elegant simplicity**.

---

## 🧩 What I Do
- 🧠 **Architecture & Design** — from concept to deployment.  
- ⚙️ **Reliability & HA** — graceful degradation, idempotent flows.  
- 🛠️ **Platform Engineering** — CI/CD, GitOps, scalable developer experience.  
- 🔐 **Security by Default** — zero trust, defense in depth, verified builds.  
- 📈 **Observability** — logs, metrics, and traces that speak truth.

---

## 🌍 Now
- **Senior Architect at Data Secrets Lab** — I designed and implemented the backend and built a platform for ML engineers.  
- **Creator of [Commucat](https://github.com/Ducheved/commucat)** — an ultra-secure **p2p messenger** with strong privacy and zero metadata leakage.  
  > “Even cats deserve encrypted meows.”

---

## 🦄 Languages and Tools
| Tier | Stack |
|------|--------|
| 💎 Primary | Golang, Rust |
| 🌈 Also Used | TypeScript (Next.js, React), Kotlin, Swift, and a bit of C# |

<sub>No endless tech stacks — only what really matters.</sub>

---

## ☁️ My Architecture Aesthetic
- **Distributed-first mindset** — events, queues, and safe retries.  
- **Operational discipline** — GitOps, immutable infra, canaries, autoscaling.  
- **Data clarity** — strong contracts, deterministic migrations.  
- **Resilience** — recover, retry, never break silently.  
- **Security** — everything encrypted, nothing trusted by default.

---

## 🧭 HA Pattern Example
```mermaid
flowchart LR
  U[Users 😺] -->|HTTPS/gRPC| G[Ingress / API Gateway 🚪]
  subgraph K8s [Kubernetes ☸️]
    G --> S1[Service A]
    G --> S2[Service B]
    S1 <-->|async| MQ[(Message Bus)]
    S2 <-->|async| MQ
    Cache[(Redis Cache 🧊)] <--> S1
    Cache <--> S2
  end
  S1 --> DB1[(PostgreSQL 🐘)]
  S2 --> DB2[(Object Storage 🗃️)]
  subgraph Observability
    OTEL[OpenTelemetry 👁️] --> Metrics[Metrics 📊]
    OTEL --> Traces[Traces 🔍]
    OTEL --> Logs[Logs 📜]
  end
  S1 -- telemetry --> OTEL
  S2 -- telemetry --> OTEL
```
<sub>Focus: graceful failure, fast recovery, and zero drama.</sub>

---

## 🧪 Selected Works
- 🐈 **[Commucat (OSS)](https://github.com/Ducheved/commucat)** — private, encrypted, federated messenger.  
- ⚙️ **Rust utilities** — cryptographic experiments and network tooling.  
- 💬 **Side projects** — from pastebins to protocol explorers.

---

## 💡 Principles I Follow
- High availability is **not optional**.  
- Simplicity is **hard, but sacred**.  
- Observability is **part of design**.  
- Security is **a habit, not a feature**.  
- If it’s **hard to do**, it’s probably **worth doing**.

---

## 💬 Contact
- Telegram: **[@ducheved](https://t.me/ducheved)**  
- GitHub: [github.com/Ducheved](https://github.com/Ducheved)  
- Motto: _"If the code purrs — ship it."_ 😸

---

<p align="center">
  <img src="https://media.tenor.com/Z8wC7fBTceMAAAAi/space-cat-cute.gif" width="180"><br>
  <sub><em>No clichés. No boredom. Only sharp claws, clean code, and cosmic calm.</em></sub>
</p>
