# Hi there, I'm Rishabh Saraswat 👋

Computer Science undergraduate at NIT Srinagar, building production-grade distributed backend systems with a strong focus on security and performance.

I believe in not just using tools, but understanding and improving them—evidenced by my contributions to the open-source ecosystem.

---

## 🚀 Open Source Contributions

I actively contribute to the technologies I rely on, focusing on security, performance, and developer experience in distributed systems.

### Apache Cassandra

- **Modernized TLS Handling in cassandra-stress Tool** – Removed hardcoded deprecated cipher suites, added null-checks, and enabled automatic negotiation of secure modern suites (including TLS 1.3 support) while preserving backward compatibility. **Impact:** Stronger security defaults and out-of-the-box TLS 1.3 readiness. [Commit](https://github.com/apache/cassandra/commit/9d89b47c68a6b476135c04b633e7d080a8ebe65f) | [JIRA CASSANDRA-21007](https://issues.apache.org/jira/browse/CASSANDRA-21007)

- **Updated HTTP to HTTPS in README** – Eliminated unnecessary 301 redirects for cleaner, more secure project docs. **Impact:** Better security hygiene and performance for users. [PR #4566](https://github.com/apache/cassandra/pull/4566) | [JIRA CASSANDRA-21110](https://issues.apache.org/jira/browse/CASSANDRA-21110)

- **Fixed Broken "Getting Started" Link** – Updated from outdated `/doc/latest/` to version-specific `/doc/5.0/` for valid documentation links. **Impact:** Improved onboarding for new users. [PR #4550](https://github.com/apache/cassandra/pull/4550) | [JIRA-CASSANDRA-21121](https://issues.apache.org/jira/browse/CASSANDRA-21121)

---

## 🎯 Skills

**Core Backend**: Java, Kotlin, Spring Boot, WebFlux, Reactor
**Distributed Systems**: Kafka, Debezium, gRPC, Cassandra
**Security**: Zero-Trust, mTLS, SCRAM, JWT, MFA
**Data Stores**: PostgreSQL, Redis, MongoDB, Elasticsearch
**Infra**: Docker

---

## 🏆 Achievements

**5-Hour Code Forge Hackathon** – NIT Srinagar (September 2025)  
Secured **2nd place** as the designed backend architecture under extreme time constraints on a 4-member team, designing end-to-end backend architecture, database schemas, and API flows within a strict 5-hour time limit.

---

## 🛠 Tech Stack

**Languages:**  
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

**Frameworks & Libraries:**  
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white) ![Spring WebFlux](https://img.shields.io/badge/Spring_WebFlux-6DB33F?style=flat-square&logo=spring&logoColor=white) ![Project Reactor](https://img.shields.io/badge/Project_Reactor-6DB33F?style=flat-square&logo=spring&logoColor=white) ![gRPC](https://img.shields.io/badge/gRPC-244c5a?style=flat-square&logo=grpc&logoColor=white)

**Data & Messaging:**  
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apache-kafka&logoColor=white) ![Apache Cassandra](https://img.shields.io/badge/Apache_Cassandra-1287B1?style=flat-square&logo=apache-cassandra&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-13aa52?style=flat-square&logo=mongodb&logoColor=white) ![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)

**Infrastructure & Security:**  
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Zero--Trust](https://img.shields.io/badge/Zero--Trust-mTLS%20%7C%20SCRAM-red?style=flat-square)

---

## 🏗️ Featured Projects

### 1. [Lynk](https://github.com/omniCoder77/Lynk) – Flagship Project

**Distributed Real-Time Communication Platform**

A secure, reactive messaging platform engineered for high throughput and massive concurrency.

- **Architecture:** Reactive Microservices (Spring WebFlux) with **Zero-Trust Security Model** across all internal components
- **Persistence:** Custom time-bucketed partitioning strategy in **Cassandra** for infinite chat history scaling
- **Security:** Implemented **mTLS** for all service mesh communication and **SCRAM-SHA-512** for Kafka authentication
- **Performance:** Redis Cuckoo Filters for O(1) space-efficient data validation; Lua scripting for distributed rate limiting; sub-50ms real-time messaging via WebSockets + FCM
- **Resilience:** Resilience4j circuit breakers and Spring Cloud Gateway for robust fault tolerance
- **Authentication:** Passwordless registration/login with optional SMS/SMTP MFA, JWT tokens with access/refresh rotation
- **Testing:** Full test coverage with JUnit and Testcontainers for integration tests
- **Data Layer:** PostgreSQL, Cassandra, Elasticsearch, and Redis for optimal query and caching performance

### 2. [Synapse](https://github.com/omniCoder77/Synapse)

**E-Commerce Microservices Ecosystem**

A comprehensive e-commerce backend demonstrating complex transaction management and polyglot persistence.

- **Architecture:** Event-Driven Microservices using Spring Boot + WebFlux
- **Pattern:** Outbox Pattern + Kafka for reliable eventual consistency across services
- **Persistence:** Polyglot strategy using PostgreSQL (Relational), MongoDB (Product Catalog), Elasticsearch (Search), and Redis (Caching)
- **Security:** Complete authentication, SMS/TOTP-based MFA, and rate limiting
- **Payments:** Integrated Razorpay for payment processing and Twilio for OTP delivery
- **Communication:** gRPC + Eureka for efficient inter-service communication and discovery
- **Testing:** Full test coverage with JUnit and Testcontainers
- **Performance:** Optimized query execution and response times across multiple data stores

---

## Current Focus
**Currently Exploring**
* Consensus algorithms (Raft) and failure handling
* Performance trade-offs in reactive systems
* Secure service-to-service communication at scale

## 📚 Education

**National Institute of Technology (NIT) Srinagar**  
B.Tech in Computer Science & Engineering (August 2024 – Present)

---

## 📈 GitHub Stats

![stats](https://github-readme-stats.vercel.app/api?username=omniCoder77&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)

![languages](https://github-readme-stats.vercel.app/api/top-langs/?username=omniCoder77&layout=compact&theme=tokyonight&hide_border=true)

---

## 📫 Connect with Me

- [LinkedIn](https://www.linkedin.com/in/rishabh-saraswat-669414294)
- [GitHub](https://github.com/omniCoder77)
- [Email](mailto:rishabhsaraswat17@gmail.com)
- [Portfolio](https://omnicoder77.github.io/omniCoder77/)
