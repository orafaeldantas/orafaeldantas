<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:1e3a5f&height=180&section=header&text=Rafael%20Dantas&fontSize=52&fontColor=e2e8f0&animation=fadeIn&fontAlignY=45" alt="Rafael Dantas" width="100%"/>

<h3>Backend Engineer · Python · PostgreSQL · Linux</h3>

<p>Building production-grade business systems, <br/>
from database architecture and API design to containerized deployment on Linux infrastructure.</p>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/orafaeldantas/) &nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/orafaeldantas) &nbsp;
[![Exactum ERP](https://img.shields.io/badge/Exactum%20ERP-Live-22c55e?style=for-the-badge&logoColor=white)](https://exactum.app.br)

</div>

---

## About Me
I have a background in Electrical Engineering, with a focus on backend systems, system architecture, and infrastructure.

I work across the full stack of backend systems, from embedded systems and networking fundamentals to backend services, databases, and Linux-based infrastructure.

My experience with low-level systems and embedded development influences how I design backend software. I think in terms of system behavior, failure modes, and operational constraints, prioritizing reliability, simplicity, and maintainable architecture over complexity.

Currently designing, developing, and operating **Exactum ERP**: a multi-tenant platform built entirely from scratch and deployed in production.

## Core Competencies & Interests
- **Backend & Architecture:** Python (Flask, FastAPI), Backend Systems Design, REST APIs
- **Infrastructure & Reliability:** Linux Server Administration, Observability, Automated CI/CD, Containerization.
- **Data & Databases:** Relational Database Modeling (PostgreSQL), Schema-level Multi-tenancy, Data Engineering.

---

## Featured Projects

### Exactum ERP
[![Repository](https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/orafaeldantas/exactum-api) &nbsp;
[![Production](https://img.shields.io/badge/Production-Live-22c55e?style=flat-square)](https://exactum.app.br)

> Multi-tenant ERP for inventory management, sales operations and POS. Designed, built, and operated from scratch. Currently in advanced alpha — pre-launch, no users yet.

**Live / Implemented:**
- Schema-level multi-tenant architecture
- Inventory management and sales workflows (POS)
- Financial reporting dashboards
- JWT authentication (httpOnly cookies) with RBAC and impersonate functionality
- Redis caching layer
- Unit test coverage
- Automated CI/CD pipeline and Linux VPS deployment

**Architecture & Engineering Work:**
- Designed a multi-tenant architecture from scratch using schema isolation
- Implemented authentication and authorization using JWT (httpOnly access + refresh tokens)
- Built versioned REST APIs with structured error handling
- Defined database migration strategy using Alembic across environments
- Containerized application and orchestrated deployment with Docker and Nginx
- Set up CI/CD pipelines using GitHub Actions for automated production delivery

**Key Architectural Decisions:**
| Layer | Approach |
| :--- | :--- |
| **Multi-tenancy** | Schema-level isolation with SQLAlchemy scoped sessions |
| **Authentication** | JWT (httpOnly) access/refresh with RBAC + impersonate |
| **Caching** | Redis |
| **API Design** | Versioned REST APIs with structured error responses |
| **Migrations** | Alembic with environment-aware revision control |
| **Deployment** | Docker + Nginx + GitHub Actions → Linux VPS |

**Studying / Roadmap:** RabbitMQ · Grafana/Prometheus observability · DDD/DTOs · Groq AI-powered predictive inventory analytics

<br>
<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" alt="Flask"/>
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white" alt="GitHub Actions"/>
</p>

### RFID Automation Platform
> End-to-end IoT platform connecting ESP32 hardware to backend services for RFID authentication and device automation.

ESP32 firmware communicates with a REST backend for device registration, RFID-based access control, and lifecycle management, demonstrating full integration across firmware, networking, and API layers.

<br>
<p align="left">
  <img src="https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" alt="C/C++"/>
  <img src="https://img.shields.io/badge/ESP32-000000?style=flat-square&logo=espressif&logoColor=white" alt="ESP32"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/REST_API-009688?style=flat-square&logo=fastapi&logoColor=white" alt="REST API"/>
</p>

---

## Currently Studying

```text
Software Architecture
├── Architectural patterns (layered, hexagonal, event-driven)
├── Design Patterns (GoF + distributed systems patterns)
└── Scalable System Design

Infrastructure
├── Linux internals & advanced administration
├── Networking (TCP/IP stack, DNS, TLS internals)
└── Distributed Systems fundamentals

Data
└── Data Engineering & pipeline architecture
```

---

## Open to Opportunities

Backend engineering roles focused on backend systems, platform engineering, and infrastructure-heavy products.

Best fit for teams building scalable systems, distributed services, and engineering-driven products.

<p align="center">
  <a href="https://www.linkedin.com/in/orafaeldantas/">
    <img src="https://img.shields.io/badge/Let's%20connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
</p>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e3a5f,100:0f172a&height=100&section=footer" width="100%"/>
</div>
