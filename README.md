# Y. Barış Özgün

### Backend & Cloud Engineer · Distributed Systems · E-Commerce · Automation

I came into software from an unusual direction.

For 25 years, I worked in live tourism operations. In that environment, a broken system meant real people waiting, missed connections, financial loss, and someone having to fix the problem immediately.

Now I build software with the same mindset.

**Reliable backends. Real integrations. Explicit failure handling. Observable systems.**

My work spans backend engineering, cloud infrastructure, e-commerce platforms and automation. I build multi-tenant SaaS platforms, event-driven systems, API integrations and production-oriented infrastructure.

I care less about making a demo impressive and more about building systems that remain predictable after deployment.

**Backend · Cloud · E-Commerce · Distributed Systems · Automation**

🌐 [thebozgun.com](https://thebozgun.com) · 💼 [LinkedIn](https://www.linkedin.com/in/the-bozgun/) · 🐙 [GitHub](https://github.com/BozgunBer-2506)

---

## What I Build

### Backend Engineering

**TypeScript · Node.js · NestJS · Python · FastAPI · Go · PHP**

REST APIs · WebSockets · Authentication · OAuth · JWT · API integrations

### Data & Persistence

**PostgreSQL · MySQL · Redis · SQLite**

Prisma · TypeORM · SQLAlchemy · Alembic

Transactions · Data integrity · Migrations · Query optimization

### Distributed Systems

**BullMQ · Redis · Event-driven pipelines · WebSockets**

Rate limiting · Idempotency · Optimistic concurrency · Keyset pagination · Background jobs

### Cloud & Infrastructure

**AWS · Microsoft Azure · Google Cloud**

Docker · Kubernetes · Linux · Nginx · GitHub Actions · CI/CD

Railway · Vercel · Cloudflare

### E-Commerce & CMS

**Shopware 6 · WordPress · WooCommerce · Symfony · PHP**

B2C e-commerce · Payment integrations · Shipping integrations · CMS architecture · API integrations

### Architecture

**Multi-tenancy · RBAC · Modular monoliths · Event-driven architecture**

OAuth · Webhooks · API design · MCP · Automated testing · Production observability

### Integrations & Automation

**Stripe · PayPal · DHL · Telegram · Slack · Amadeus · n8n**

---

## Selected Engineering Work

### ![Smart Message Center](https://img.shields.io/badge/Smart_Message_Center-1F6FEB?style=for-the-badge)

**Multi-Tenant Communication Platform · Production**

[Repository](https://github.com/BozgunBer-2506/smartmc)

A communication operating system that brings **Telegram, Slack and email** into a unified workspace with automation and cross-provider identity resolution.

The system is designed around a modular monolith rather than premature microservices.

**Engineering highlights:**

* Two-level tenancy: `Organization → Workspace`
* RBAC enforced across mutating operations
* Telegram Bot API integration
* Slack OAuth + Events API
* Event-driven message ingestion
* Redis + BullMQ background processing
* IdentityGraph for cross-provider identity resolution
* Human-in-the-loop identity confirmation
* Rule-based automation engine
* Durable delayed jobs
* ETag / `If-Match` optimistic concurrency
* Redis-backed rate limiting
* Keyset cursor pagination
* WebSocket real-time updates
* Production regression testing
* OAuth credential rotation and incident handling

**Stack:** TypeScript · NestJS · Next.js · PostgreSQL · Prisma · Redis · BullMQ · WebSocket · Docker · Railway

---

### ![Argus](https://img.shields.io/badge/Argus-1F6FEB?style=for-the-badge)

**Investment Intelligence Platform · Active Development**

A capital-preservation-first investment intelligence platform designed around **auditability, data integrity and human control**.

Argus is being developed as a TypeScript monorepo with MCP-based services.

```text
Transaction Ledger
       │
       ├── Cost Basis
       ├── FX
       └── Risk
             │
             ▼
        Market Data
             │
             ▼
      Portfolio Analytics
             │
             ▼
       Decision Support
```

The core principle:

> **Auditability before automation.**

Current engineering areas include:

* Immutable transaction ledger
* FX-aware P&L
* Portfolio return calculations
* Advanced risk metrics
* Read-only market-data services
* MCP server architecture
* PostgreSQL persistence
* Dockerized integration testing
* Full regression suite
* Human-in-the-loop decision support

**Stack:** TypeScript · PostgreSQL · MCP · Docker · pnpm · Turborepo

`Status: Active development`

---

### ![B2B Booking Platform](https://img.shields.io/badge/B2B_Booking_Platform-1F6FEB?style=for-the-badge)

**Multi-Tenant Travel SaaS**

[Live](https://terrific-respect-production-6ef7.up.railway.app/)

A B2B reservation platform for travel agencies built around a unified trip model.

```text
Trip
 ├── Flight
 ├── Hotel
 ├── Car
 └── Transfer
```

Includes:

* Multi-tenant architecture
* `SuperAdmin → Admin → Agent` authorization model
* Unified reservation model
* Automated invoicing
* Mutation audit logging
* PostgreSQL persistence
* CI/CD through GitHub Actions
* Docker-based deployment

**Stack:** React · TypeScript · NestJS · TypeORM · PostgreSQL · Docker · Railway · GitHub Actions

---

### ![EasyArbitHub](https://img.shields.io/badge/EasyArbitHub-1F6FEB?style=for-the-badge)

**Real-Time Crypto Market Intelligence**

[Live](https://easyarbithub.com)

A real-time arbitrage monitoring platform that compares cryptocurrency prices across exchanges and evaluates potential opportunities after accounting for **slippage and transaction costs**.

**Stack:** Python · FastAPI · PostgreSQL · WebSockets · Docker · AWS EC2

---

### ![Techslex](https://img.shields.io/badge/Techslex-1F6FEB?style=for-the-badge)

**Software Marketplace**

[Live](https://techslex.com)

A marketplace for production-ready software projects, allowing developers to sell existing codebases and buyers to acquire working software instead of starting from zero.

Includes marketplace workflows, authentication, project management and Stripe payment integration.

**Stack:** React · TypeScript · Node.js · PostgreSQL · Stripe · Tailwind CSS

---

### ![Headless Shopware 6 Commerce](https://img.shields.io/badge/Headless_Shopware_6_Commerce-1F6FEB?style=for-the-badge)

**Shopware 6 · Headless E-Commerce Platform**

A German B2C e-commerce platform built on a **headless Shopware 6** architecture with payment processing, shipping integration and a decoupled storefront.

Engineering work includes:

* Shopware 6 architecture
* B2C commerce flows
* PayPal integration
* DHL / Pickware integration
* Checkout and payment workflows
* Customer account flows
* GDPR-oriented storefront considerations
* Theme-based Shopware architecture
* React storefront architecture planning
* SEO and technical storefront optimization

**Stack:** Shopware 6 · PHP · Symfony · JavaScript · React · PayPal · DHL / Pickware

---

### ![Travaliz](https://img.shields.io/badge/Travaliz-1F6FEB?style=for-the-badge)

**Travel Search API**

[Live](https://travaliz.vercel.app/)

A Go-based travel search service integrating the Amadeus Self-Service API.

Includes OAuth2 token caching and server-rendered HTML.

**Stack:** Go · SQLite · REST · Amadeus API · Vercel

---

### ![FastAPI Order Management](https://img.shields.io/badge/FastAPI_Order_Management-1F6FEB?style=for-the-badge)

**Production REST API**

[API Documentation](https://fastapipostgresql1702-production.up.railway.app/docs)

A containerized order management API covering CRUD operations, validation, database migrations and PostgreSQL persistence.

**Stack:** Python · FastAPI · PostgreSQL · SQLAlchemy · Alembic · Docker · Railway

---

## Engineering Focus

I enjoy working on the parts of software where complexity becomes real:

**Concurrency**

ETags, conditional requests, race conditions and safe state transitions.

**Distributed Workflows**

Queues, delayed jobs, retries, idempotency and event-driven processing.

**Multi-Tenancy**

Tenant isolation, authorization boundaries and organization/workspace models.

**External Integrations**

OAuth, webhooks, third-party APIs, rate limits and unreliable external systems.

**Data Integrity**

Transactions, immutable ledgers, audit trails, migrations and consistent state.

**Cloud & Infrastructure**

Containerized workloads, CI/CD, networking, deployment and operational reliability.

---

## Engineering Principles

> **Correctness over cleverness.**
> **Explicit failure handling over happy-path demos.**
> **Observable systems over "it works on my machine."**
> **Idempotency over accidental retries.**
> **Transactions over hope.**
> **Tests over manual confidence.**
> **Simple architecture over premature microservices.**
> **Human control over autonomous decisions.**

---

## Technology

### Languages

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)

### Backend

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Symfony](https://img.shields.io/badge/Symfony-000000?style=for-the-badge&logo=symfony&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![BullMQ](https://img.shields.io/badge/BullMQ-E10098?style=for-the-badge&logo=redis&logoColor=white)

### Databases & ORM

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![TypeORM](https://img.shields.io/badge/TypeORM-FE0803?style=for-the-badge&logo=typeorm&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)

### Frontend

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

### E-Commerce & CMS

![Shopware](https://img.shields.io/badge/Shopware-189EFF?style=for-the-badge&logo=shopware&logoColor=white)
![WordPress](https://img.shields.io/badge/WordPress-21759B?style=for-the-badge&logo=wordpress&logoColor=white)
![WooCommerce](https://img.shields.io/badge/WooCommerce-96588A?style=for-the-badge&logo=woocommerce&logoColor=white)

### Cloud

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Microsoft Azure](https://img.shields.io/badge/Microsoft%20Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)

### DevOps & Infrastructure

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)

### Automation & Integrations

![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=for-the-badge&logo=stripe&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)

**APIs & Platforms:** Telegram · Slack · PayPal · DHL · Amadeus · MCP

---

## Certifications

* **AWS Certified Cloud Practitioner (CLF-C02)** · Amazon Web Services · 2026
* **IHK Fachinformatiker, IT-Administrator** · 2026
* **IHK IT Support Specialist** · 2026
* **IHK Cloud Business Expert** · 2026
* **Linux Essentials** · Linux Professional Institute · 2025
* **Agile Software Development & Cloud Engineering** · Syntax-Institut · 2025/2026

---

## Technical Knowledge

Technical study guides, documentation and learning resources I build and maintain.

| Resource                                                       | Focus                        |
| -------------------------------------------------------------- | ---------------------------- |
| [AWS CCP Exam 2026](https://aws-ccp-2026.vercel.app/)          | AWS certification & practice |
| [Linux Guide](https://linux-rehberi-tr.vercel.app/)            | Linux · Bash · CLI           |
| [AWS Cloud Guide](https://aws-cloud-rehberi-tr.vercel.app/)    | Cloud infrastructure         |
| [Python Hub](https://python-rehberi-tr.vercel.app/)            | Python · Web                 |
| [JavaScript Guide](https://java-script-rehberi-tr.vercel.app/) | Modern JavaScript            |
| [Docker Hub](https://docker-rehberi-tr.vercel.app/)            | Containers · DevOps          |

---

## Let's Build Something Useful

I'm interested in opportunities involving:

**Backend Engineering · Cloud Infrastructure · Distributed Systems · E-Commerce · Automation**

If you're building software where reliability, integrations and backend architecture actually matter, let's talk.

🌐 **[thebozgun.com](https://thebozgun.com)**
💼 **[LinkedIn](https://www.linkedin.com/in/the-bozgun/)**
🐙 **[GitHub](https://github.com/BozgunBer-2506)**

---

<sub>Build it. Break it. Understand why. Build it better.</sub>
