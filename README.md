<img src="https://user-images.githubusercontent.com/74038190/213910845-af37a709-8995-40d6-be59-724526e3c3d7.gif" alt="Masthead" />

<h1 align="center">Sam Prem Kumar Thalla</h1>
<h3 align="center">Backend Engineer &nbsp;·&nbsp; Node.js · TypeScript · Python/Django &nbsp;·&nbsp; Queues · Idempotent APIs · AWS</h3>

<p align="center">
  <strong>I build backend systems with async workers, safe transactions, and Dockerized AWS deployments.</strong>
</p>

<p align="center">
  🎯 Open to <b>Backend / Platform Engineering</b> roles · Hyderabad (also Bangalore, Pune, Remote) · Immediate joiner
</p>

---

### 🛠️ What I work on
- **Reliability:** idempotency keys, retries with exponential backoff, state machines
- **Async processing:** BullMQ and Celery workers, Celery Beat recovery of stuck jobs
- **Cloud:** AWS ECS Fargate build tasks, ECR, S3 reverse proxy, EC2 deployments with Docker + NGINX
- **Payments logic:** append-only ledger, `SELECT FOR UPDATE` double-spend prevention, HMAC-signed webhooks
- **CI/CD:** GitHub Actions running tests against real PostgreSQL + Redis, then deploying to EC2
- **Java:** multithreaded HTTP servers on raw sockets, load-tested with JMeter

### 🔭 Currently learning
- 📐 System design (LLD + HLD)
- 📊 DSA in Java

### 🎓 Research
- 📝 **Published:** [MPPT of PV systems under partial shading using Cuckoo Search Algorithm](https://drive.google.com/file/d/1QUZ3L33mAqRigHwQnwg__ZOjVhmEPucZ/view) — ISSN: 2236-6124

---

## 🏗️ Featured Projects

| Project | Focus | Key Decision |
|---|---|---|
| [**Playto Payout Engine**](https://github.com/sampremm/playto-engine) · [Live](https://playto-engine-vert.vercel.app/) | Payments + Concurrency | **Two-tier idempotency** (Redis L1 + PostgreSQL L2); `SELECT FOR UPDATE` prevents double-spend — concurrent test returns one 201, one 402; 2 PostgreSQL shards; Celery Beat recovery; GitHub Actions CI/CD to EC2 |
| [**Vercel Clone — Cloud PaaS**](https://github.com/sampremm/vercel) | Build automation + live logs | Each deploy runs in an isolated **ECS Fargate** task; live build logs via **Redis Pub/Sub + Socket.IO**; subdomain-based reverse proxy over S3 |
| [**SnapLink — URL Shortener**](https://github.com/sampremm/URL-Shortener) · [Live](https://url-shortener-six-sandy.vercel.app/) | Horizontal scaling | 3 stateless replicas behind NGINX; **key-generation service** (MySQL) with nanoid fallback; Redis-cached redirects; rate limit 100 req/15 min |
| [**In-App Notification Engine**](https://github.com/sampremm/In-App-Messaging-System) | Async delivery | BullMQ state machine (QUEUED→PROCESSING→RETRYING→SENT/FAILED); max 3 retries; **idempotent worker**; 4-container Docker Compose + integration tests |
| [**Java Web Server**](https://github.com/sampremm/multithreaded-webserver-java) | Concurrency | Single-threaded, thread-per-request, and thread-pool servers on `java.net.Socket`; JMeter tested at 100–1000 users |

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
  <img src="https://ghchart.rshah.org/39d353/sampremm" alt="sampremm's GitHub Contribution Chart" width="100%"/>
</p>

---

<p align="center">
  <a href="https://linkedin.com/in/samprem1"><img src="https://img.shields.io/badge/-LinkedIn-blue?style=for-the-badge&logo=Linkedin&logoColor=white" /></a>
  &nbsp;
  <a href="https://sam-portfolio-ashy.vercel.app/"><img src="https://img.shields.io/badge/-Portfolio-success?style=for-the-badge&logo=google-chrome&logoColor=white" /></a>
  &nbsp;
  <a href="mailto:samprem888111@gmail.com"><img src="https://img.shields.io/badge/-Email-red?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>
