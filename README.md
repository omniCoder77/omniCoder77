# Hi there, I'm Rishabh Saraswat 👋

Computer Science undergraduate at NIT Srinagar, building production-grade backend systems and contributing to open source.

---

## 🚀 Open Source Contributions
### Apache Cassandra

- Security: Resolved TLS 1.3 connectivity issues in cassandra-stress; implemented Perfect Forward
Secrecy via updated cipher suites to meet modern encryption standards.
Addresses: [Commit](https://github.com/apache/cassandra/commit/9d89b47c68a6b476135c04b633e7d080a8ebe65f) | [PR](https://github.com/apache/cassandra/pull/4499) | [CASSANDRA-21007](https://issues.apache.org/jira/browse/CASSANDRA-21007)

- **Updated HTTP to HTTPS in README** – Eliminated unnecessary 301 redirects for cleaner, more secure project docs.
  Addresses:  [Commit](https://github.com/apache/cassandra/commit/5101d76b21234d629cfc27b8ed4320216fc917fc) | [PR](https://github.com/apache/cassandra/pull/4550)| [CASSANDRA-21110](https://issues.apache.org/jira/browse/CASSANDRA-21110)

- Feature Testing: Engineered a simulation script for "blocked" data scenarios; verified storage utility accuracy for file sizes and date formats, optimizing disk-space diagnostics.
  Addresses: [Commit](https://github.com/apache/cassandra/commit/6bf598dcdec8cc81a870fc5363308022bf11aead) | [PR](https://github.com/apache/cassandra/pull/3993) | [CASSANDRA-20448](https://issues.apache.org/jira/browse/CASSANDRA-20448)

- **Fixed Broken "Getting Started" Link** – Fixed `Getting Started` hyperlink.
  [Commit](https://github.com/apache/cassandra/commit/5101d76b21234d629cfc27b8ed4320216fc917fc) | [PR #4550](https://github.com/apache/cassandra/pull/4550) | [CASSANDRA-21121](https://issues.apache.org/jira/browse/CASSANDRA-21121)

- **Implemented Guardrail for Unprepared Statements** – Developed a new Guardrail configuration to detect, warn, or reject queries that bypass the prepared statement cache (cache misses). **Impact:** Enhances cluster stability and performance by mitigating the overhead caused by ad-hoc query patterns and enforcing client-side best practices.
  Pending commit | [PR #4596](https://github.com/apache/cassandra/pull/4596) | [CASSANDRA-21139](https://issues.apache.org/jira/browse/CASSANDRA-21139)

---

## 🛠 Tech Stack 
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white) ![Spring WebFlux](https://img.shields.io/badge/Spring_WebFlux-6DB33F?style=flat-square&logo=spring&logoColor=white) ![Project Reactor](https://img.shields.io/badge/Project_Reactor-6DB33F?style=flat-square&logo=spring&logoColor=white) ![gRPC](https://img.shields.io/badge/gRPC-244c5a?style=flat-square&logo=grpc&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apache-kafka&logoColor=white) ![Apache Cassandra](https://img.shields.io/badge/Apache_Cassandra-1287B1?style=flat-square&logo=apache-cassandra&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-13aa52?style=flat-square&logo=mongodb&logoColor=white) ![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Zero--Trust](https://img.shields.io/badge/Zero--Trust-mTLS%20%7C%20SCRAM-red?style=flat-square)
---
## 🏗️ Featured Projects

### 1. [Communication Application](https://github.com/omniCoder77/Lynk) – Flagship Project
- **Architecture:** Reactive Microservices (Spring WebFlux) with **Zero-Trust Security Model** across all internal components
- **Persistence:** Custom time-bucketed partitioning strategy in **Cassandra** for infinite chat history scaling
- **Security:** Implemented **mTLS** for all service mesh communication and **SCRAM-SHA-512** for Kafka authentication
- **Performance:** Redis Cuckoo Filters for O(1) space-efficient data validation; Lua scripting for distributed rate limiting; sub-50ms real-time messaging via WebSockets + FCM
- **Resilience:** Resilience4j circuit breakers and Spring Cloud Gateway for robust fault tolerance
- **Authentication:** Passwordless registration/login with optional SMS/SMTP MFA, JWT tokens with access/refresh rotation
- **Testing:** Full test coverage with JUnit and Testcontainers for integration tests
- **Data Layer:** PostgreSQL, Cassandra, Elasticsearch, and Redis for optimal query and caching performance

### 2. [E-Commerce Application](https://github.com/omniCoder77/Synapse)
- **Architecture:** Event-Driven Microservices using Spring Boot + WebFlux
- **Pattern:** Outbox Pattern + Kafka for reliable eventual consistency across services
- **Persistence:** Polyglot strategy using PostgreSQL (Relational), MongoDB (Product Catalog), Elasticsearch (Search), and Redis (Caching)
- **Security:** Complete authentication, SMS/TOTP-based MFA, and rate limiting
- **Payments:** Integrated Razorpay for payment processing and Twilio for OTP delivery
- **Communication:** gRPC + Eureka for efficient inter-service communication and discovery
- **Testing:** Full test coverage with JUnit and Testcontainers
- **Performance:** Optimized query execution and response times across multiple data stores
---
## 📚 Education
**National Institute of Technology (NIT) Srinagar**  
B.Tech in Computer Science & Engineering (August 2024 – Present)

---
## 📫 Connect with Me
- [LinkedIn](https://www.linkedin.com/in/rishabh-saraswat-669414294)
- [GitHub](https://github.com/omniCoder77)
- [Email](mailto:rishabhsaraswat17@gmail.com)
- [Portfolio](https://omnicoder77.github.io/omniCoder77/)
