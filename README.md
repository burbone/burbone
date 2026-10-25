# 👋 Hi, I'm Maxim Burobin

**Java Backend Developer** | Building event-driven and real-time systems with Spring Boot

[![GitHub](https://img.shields.io/badge/GitHub-burbone-181717?style=flat&logo=github)](https://github.com/burbone)
[![Email](https://img.shields.io/badge/Email-m.d.burobin%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:m.d.burobin@gmail.com)
[![Telegram](https://img.shields.io/badge/Telegram-@bur__bone-26A5E4?style=flat&logo=telegram&logoColor=white)](https://t.me/bur_bone)

---

## 🚀 About Me

I'm a **self-taught Java backend developer** passionate about building scalable, real-time applications. I specialize in **Spring Boot**, **REST APIs**, **WebSocket**, **Kafka** and **asynchronous programming**. Currently seeking a **Junior Java Developer** position or internship: remote, or on-site with relocation support.

- 🌱 Learning: Distributed systems, microservices architecture, resilience patterns
- 💼 Open to: Remote positions, or relocation if relocation support is provided
- 📍 Location: Moscow, Russia (UTC+3)
- 🗣️ Languages: Russian (native), English (professional working proficiency)

---

## 🛠️ Tech Stack

### Languages

![Java](https://img.shields.io/badge/Java_21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### Frameworks & Libraries

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)

**Spring Ecosystem:** Spring Web / MVC, WebFlux, WebSocket, Data, Security, AI

### Messaging, Databases & Infrastructure

![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

### Tools & Technologies

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apache-maven&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

### Core Competencies

- RESTful API Design
- Object-Oriented Programming (OOP)
- Event-driven architecture (Kafka, outbox pattern, idempotency)
- Asynchronous programming and multithreading (`CompletableFuture`)
- Concurrent programming (lock-free structures, thread-safe caching)
- WebSocket real-time communication
- Observability (Prometheus, Grafana, Micrometer)
- API integration

---

## 💼 Featured Projects

### [🔗 AI Image Gallery](https://github.com/burbone/picturesAI)

A microservice platform for generating images from text prompts, with history, tags, a feed and recommendations. The AI provider is a replaceable black box; the point of the project is the reliable system around an unreliable external service.

**🎯 Key Features:**

- 🔁 **Outbox pattern**: DB write and Kafka event in one transaction, at-least-once delivery
- 🛡️ **Idempotency** on three levels (Redis, unique index, cached response)
- 🎟️ **Quota reservation with TTL** and priority queue with slot reservation for PRO/FREE plans
- 📡 **WebSocket** status updates with initial state on connect
- 🏷️ **Auto-tagging** of prompts with a local LLM (Ollama) with keyword fallback
- 📊 **Full observability**: metrics, logs and distributed tracing

**🛠️ Tech Stack:**

```
Java • Spring Boot (7 microservices) • Kafka • NATS JetStream • PostgreSQL • Redis
MinIO • Keycloak • React • Resilience4j • Prometheus • Grafana • Loki • Tempo
Testcontainers • k6
```

### [🔗 Crypto Market Data Collector](https://github.com/burbone/crypto)

A real-time market data collector for Bybit and KuCoin with a pluggable `TradingStrategy` interface. Originally a full arbitrage bot; the strategy is removed, the infrastructure stays.

- ⚡ Lock-free price storage (`ConcurrentHashMap` + `AtomicReference`)
- 📦 Batched writes to PostgreSQL, so the database is off the hot path
- 🔄 Scheduled WebSocket reconnects, native `java.net.http.WebSocket` client
- 💼 Paper trading with a virtual account book

```
Java 21 • Spring Boot • WebSocket • PostgreSQL (jsonb) • Actuator • Micrometer
```

### [🔗 Crypto Exchange Arbitrage Analysis Platform](https://github.com/burbone/exchange)

A real-time web application for analyzing cryptocurrency arbitrage opportunities across 5 exchanges (Bybit, Bitget, KuCoin, OKX, HTX).

- ⚡ Real-time price tracking via WebSocket, updates every second
- 📊 Arbitrage matrix comparing buy/sell prices across all exchanges
- 📈 Historical data export to Excel
- 🔄 Concurrent API requests with rate limiting and batching

```
Java 21 • Spring Boot • WebFlux • WebSocket • Apache POI • Jackson • Maven
```

### More

- [🤖 Telegram Job Vacancies Bot](https://github.com/burbone/TelegramJobVacanciesBot): parses IT vacancies and finds relevant ones by meaning using RAG, fully local. `Java` `Spring AI` `Ollama` `PGVector` `Docker`
- [📚 RAG Assistant (GigaChat)](https://github.com/burbone/RagGigachat): question answering over PDF/DOCX/TXT/MD with hybrid search (BM25 + embeddings) and parent-child chunking. `Python` `GigaChat`

---

## 🎓 Learning Journey

**Self-Taught Developer (2023 - Present)**

I've independently learned Java backend development through:

- 📚 Official Spring Framework documentation
- 🎥 Online courses and tutorials
- 💻 Hands-on project implementation
- 📖 Technical books and articles
- 🔍 Source code analysis of open-source projects

**Currently exploring:**

- Kubernetes and cloud-native deployment
- CI/CD pipelines
- Test-driven development (TDD)

---

## 💬 Let's Connect!

I'm actively looking for **remote or relocation-supported Java Developer positions** (Junior level) where I can contribute my skills and keep growing as a developer.

**What I bring:**

- Hands-on experience with Spring Boot, Kafka and event-driven design
- Projects built with production concerns in mind: idempotency, retries, observability
- Ability to learn quickly and independently
- Problem-solving mindset

**Contact me:**

- 📧 Email: <m.d.burobin@gmail.com>
- 💬 Telegram: [@bur_bone](https://t.me/bur_bone)

---

## 🌍 Work Preferences

- **Work Type:** Remote, or on-site with relocation support
- **Availability:** Immediately available for full-time positions
- **Time Zone:** UTC+3 (Moscow)

---

**⭐ If you find my projects interesting, feel free to star them!**
