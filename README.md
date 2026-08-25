# Hi, I'm Nguyen Gia Huy 👋

**Backend Engineer** specializing in distributed systems, microservices, and high-performance database architectures[cite: 1].

- 🔭 Currently engineering scalable backend systems with **Java (Spring Boot)** and **C# (.NET 8)**[cite: 1].
- ⚡ Focus areas: High-concurrency optimization, Event-driven systems (Kafka, RabbitMQ), CQRS, and Caching architectures[cite: 1].
- 📍 Ho Chi Minh City, Vietnam[cite: 1]
- 📫 Email: nghuy.0304@gmail.com | [LinkedIn](https://linkedin.com/in/nguyengiahuy-dev)[cite: 1]

---

### 🛠️ Tech Stack & Core Competencies

- **Languages & Frameworks:** Java (Spring Boot), C# (.NET 8), TypeScript (NestJS)[cite: 1]
- **Databases & Caching:** PostgreSQL, MongoDB, Redis[cite: 1]
- **Message Brokers:** Apache Kafka, RabbitMQ[cite: 1]
- **Architectures & Patterns:** Microservices, Event-Driven Architecture, CQRS, Clean Architecture, DDD, gRPC, RESTful APIs[cite: 1]
- **DevOps & Infrastructure:** Docker, Elastic Stack (ELK), AWS S3, Linux, Git[cite: 1]

---

### 💼 Commercial Engineering Highlights

#### **Backend Developer** | TGL Solutions *(Jan 2026 – Aug 2026)*[cite: 1]
*VCC Multi-tenant SaaS Platform*[cite: 1]

- **Latency & Caching Optimization:** Reduced average API response time by **82%** (2549ms $\rightarrow$ 462ms) by executing independent DB checks, Redis queries, and external HTTP calls concurrently via `Task.WhenAll`, paired with a Redis Cache-Aside pattern (24h TTL)[cite: 1].
- **Bounded Concurrency & Batch I/O:** Converted sequential SignalR, AWS S3, and email workloads to chunked `Parallel.ForEachAsync` tasks bounded by `SemaphoreSlim` to safeguard memory and CPU during spikes[cite: 1].
- **Authentication & Security:** Implemented dynamic MFA/TOTP flows via Strategy Factory, AES-GCM secret encryption, action-level RBAC, and event-driven cache/token revocation[cite: 1].
- **Infrastructure & Reliability:** Resolved Nginx routing and WebSocket 101 upgrade defects, and added pre-delete cross-service dependency checks with PostgreSQL unique constraints to reject duplicate concurrent writes[cite: 1].

---

### 🚀 Key Projects

#### [Enterprise Communication Platform (Slack Clone)](https://github.com/CubaNguyen/slack-clone)[cite: 1]
*PoC / R&D Polyglot Microservices Architecture*[cite: 1]

- **Architecture:** Heterogeneous distributed system across NestJS (Identity), Spring Boot (Workspace), and .NET 8 (Real-time Chat)[cite: 1].
- **Data Consistency:** Implemented Transactional Outbox Pattern with Apache Kafka for eventual consistency and idempotent message handling across isolated service databases[cite: 1].
- **Inter-Service Communication:** Integrated gRPC and Protocol Buffers over HTTP/2 for low-latency internal RPC calls[cite: 1].
- **CQRS & Query Optimization:** Decoupled write and read pipelines using ORM command handlers and optimized raw SQL read execution[cite: 1].

---

### 📈 GitHub Analytics
![Gia Huy's GitHub Stats](https://github-readme-stats.vercel.app/api?username=CubaNguyen&show_icons=true&theme=tokyonight)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=CubaNguyen&layout=compact&theme=tokyonight)
