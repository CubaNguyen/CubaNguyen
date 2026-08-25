# Hi, I'm Nguyen Gia Huy 👋

**Backend Engineer** specializing in distributed systems, microservices, and high-performance database architectures.

- 🔭 Currently engineering scalable backend systems with **Java (Spring Boot)** and **C# (.NET 8)**.
- ⚡ Focus areas: High-concurrency optimization, Event-driven systems (Kafka, RabbitMQ), CQRS, and Caching architectures.
- 📍 Ho Chi Minh City, Vietnam
- 📫 Email: nghuy.0304@gmail.com | [LinkedIn](https://linkedin.com/in/nguyengiahuy-dev)

---

### 🛠️ Tech Stack & Core Competencies

- **Languages & Frameworks:** Java (Spring Boot), C# (.NET 8), TypeScript (NestJS)
- **Databases & Caching:** PostgreSQL, MongoDB, Redis
- **Message Brokers:** Apache Kafka, RabbitMQ
- **Architectures & Patterns:** Microservices, Event-Driven Architecture, CQRS, Clean Architecture, DDD, gRPC, RESTful APIs
- **DevOps & Infrastructure:** Docker, Elastic Stack (ELK), AWS S3, Linux, Git

---

### 💼 Commercial Engineering Highlights

#### **Backend Developer** | TGL Solutions *(Jan 2026 – Aug 2026)*
*VCC Multi-tenant SaaS Platform*

- **Latency & Caching Optimization:** Reduced average API response time by **82%** (2549ms → 462ms) by executing independent DB checks, Redis queries, and external HTTP calls concurrently via `Task.WhenAll`, paired with a Redis Cache-Aside pattern (24h TTL).
- **Bounded Concurrency & Batch I/O:** Converted sequential SignalR, AWS S3, and email workloads to chunked `Parallel.ForEachAsync` tasks bounded by `SemaphoreSlim` to safeguard memory and CPU during spikes.
- **Authentication & Security:** Implemented dynamic MFA/TOTP flows via Strategy Factory, AES-GCM secret encryption, action-level RBAC, and event-driven cache/token revocation.
- **Infrastructure & Reliability:** Resolved Nginx routing and WebSocket 101 upgrade defects, and added pre-delete cross-service dependency checks with PostgreSQL unique constraints to reject duplicate concurrent writes.

---

### 🚀 Key Projects

#### [Enterprise Communication Platform (Slack Clone)](https://github.com/CubaNguyen/slack-clone)
*PoC / R&D Polyglot Microservices Architecture*

- **Architecture:** Heterogeneous distributed system across NestJS (Identity), Spring Boot (Workspace), and .NET 8 (Real-time Chat).
- **Data Consistency:** Implemented Transactional Outbox Pattern with Apache Kafka for eventual consistency and idempotent message handling across isolated service databases.
- **Inter-Service Communication:** Integrated gRPC and Protocol Buffers over HTTP/2 for low-latency internal RPC calls.
- **CQRS & Query Optimization:** Decoupled write and read pipelines using ORM command handlers and optimized raw SQL read execution.

---
