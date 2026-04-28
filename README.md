<img src="https://user-images.githubusercontent.com/74038190/213910845-af37a709-8995-40d6-be59-724526e3c3d7.gif" alt="Masthead" />

<h1 align="center">Sam Prem Kumar Thalla</h1>
<h3 align="center">Backend Engineer &nbsp;·&nbsp; Node.js · TypeScript · Java &nbsp;·&nbsp; Distributed Systems · Async Queues · AWS</h3>

<p align="center">
  <strong>Building resilient, self-healing backends and high-throughput distributed architectures.</strong>
</p>

<br/>

<img align="right" alt="coding" src="https://private-user-images.githubusercontent.com/74038190/238353480-219bcc70-f5dc-466b-9a60-29653d8e8433.gif" width="380" />

### 🛠️ Core Engineering Competencies
- **Distributed Systems:** Designing for idempotency, retry mechanisms, and state machine consistency
- **Async Pipelines:** BullMQ/Celery workers, delivery state machines, exponential backoff, dead-letter handling
- **Cloud Infrastructure:** AWS ECS/Fargate container orchestration, S3 reverse proxies, EC2 deployments with NGINX + SSL
- **Fintech Resilience:** Immutable append-only ledgers, SELECT FOR UPDATE double-spend prevention, HMAC-signed webhooks
- **Systems Programming:** Hand-rolled multithreaded HTTP servers in Java; benchmarked with Apache JMeter

### 🔭 Currently Hardening
- 🏗️ **DevOps:** Implementing **Terraform IaC** and **GitHub Actions** CI/CD for automated deployments
- 📐 **System Design:** Deep-diving into LLD (Design Patterns) and HLD through structured self-study
- 📊 **DSA in Java:** Consistently solving Medium patterns (Sliding Window, Graphs, DP) daily

### 🎓 Research & Background
- 📝 **Published:** [MPPT using Cuckoo Search Algorithm (CSA)](https://drive.google.com/file/d/1QUZ3L33mAqRigHwQnwg__ZOjVhmEPucZ/view) — Optimized PV system power output under variable loads using bio-inspired algorithms. ISSN: 2236-6124
- 🎯 Open to **Backend / Platform Engineering** roles in Hyderabad, Bangalore, Pune

---

<br clear="right"/>

## 🏗️ Featured Projects

| Project | Engineering Focus | Key Decision |
|---|---|---|
| [**Vercel Clone — Cloud PaaS**](https://github.com/sampremm/vercel-backend) | CI/CD Automation + Real-time Observability | Solved live build-log streaming using **Redis Pub/Sub + Socket.IO** across isolated ECS/Fargate containers; subdomain-based S3 reverse proxy keeps bucket fully private |
| [**Playto Payout Engine**](https://github.com/sampremm/playto-engine) | Financial Integrity + Concurrency | **Two-tier idempotency** (L1 Redis + L2 dedicated PostgreSQL); `SELECT FOR UPDATE` prevents double-spend — proven by concurrent test (one 201, one 402); immutable append-only ledger |
| [**SnapLink — URL Shortener SaaS**](https://github.com/sampremm/URL-Shortener) | Distributed Scaling | Dedicated **Key Generation Service** (MySQL) for collision-free IDs across 3 stateless replicas behind NGINX; graceful nanoid fallback on service failure |
| [**In-App Notification Engine**](https://github.com/sampremm/In-App-Messaging-System) | Async Delivery + Fault Tolerance | BullMQ/Redis state machine (QUEUED→PROCESSING→RETRYING→SENT/FAILED); **idempotent worker** safe under crashes; 4-container Docker Compose stack |
| [**Java Web Server**](https://github.com/sampremm/multithreaded-webserver-java) | Systems Programming | Built from `java.net.Socket` — single-threaded, multi-threaded, and custom **thread pool** variants; benchmarked 100–1000 concurrent users with JMeter |
| [**StreamYard Clone**](https://github.com/sampremm/streamyard-clone) | Real-time Media | WebRTC peer connections + RTMP ingestion for live broadcast to YouTube |

---

## 🛠 Stack

<p>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" width="40" title="TypeScript"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="40" title="JavaScript"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="40" title="Python"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" width="40" title="Java"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" width="40" title="Node.js"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" width="40" title="Express"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/django/django-plain.svg" width="40" title="Django"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" width="40" title="PostgreSQL"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" width="40" title="MongoDB"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redis/redis-original-wordmark.svg" width="40" title="Redis"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" width="40" title="Docker"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" width="40" title="AWS"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nginx/nginx-original.svg" width="40" title="NGINX"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" width="40" title="React"/>
  <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" width="40" title="Postman"/>
</p>

---

## 🟩 Contributions

<p align="center">
  <img src="https://ghchart.rshah.org/39d353/sampremm" alt="sampremm's Github Contribution Chart" width="100%"/>
</p>

---

<p align="center">
  <a href="https://linkedin.com/in/samprem1">
    <img src="https://img.shields.io/badge/-LinkedIn-blue?style=for-the-badge&logo=Linkedin&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://sam-portfolio-ashy.vercel.app/">
    <img src="https://img.shields.io/badge/-Portfolio-success?style=for-the-badge&logo=google-chrome&logoColor=white" />
  </a>
  &nbsp;
  <a href="mailto:samprem888111@gmail.com">
    <img src="https://img.shields.io/badge/-Email-red?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>
