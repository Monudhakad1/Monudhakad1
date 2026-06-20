# Hey, I'm Monu Dhakad 👋

**Backend Developer** • Java & Spring Boot • Microservices • AI Agents  
📍 IET DAVV, Indore | B.Tech | (Final Year)

---

## 🛠️ Tech Stack

**Backend**  
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=spring-boot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat&logo=spring&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat&logo=apache-kafka&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=flat&logo=hibernate&logoColor=white)

**AI & LLM**  
![Spring AI](https://img.shields.io/badge/Spring_AI-6DB33F?style=flat&logo=spring&logoColor=white)
![LangChain4j](https://img.shields.io/badge/LangChain4j-1C3C3C?style=flat&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-Vector_Search-8A2BE2?style=flat)
![Tool Calling](https://img.shields.io/badge/Tool_Calling-LLM-FF6B6B?style=flat)

**Databases & Cloud**  
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-EC2_S3-FF9900?style=flat&logo=amazon-aws&logoColor=white)

**Other**  
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=c%2B%2B&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white)
![JUnit](https://img.shields.io/badge/JUnit5-25A162?style=flat&logo=junit5&logoColor=white)

---

## 🚀 Projects

### 🛒 [ShopSphere](https://github.com/StopSphere/ShopSphere-Main) — Distributed E-Commerce Backend

```
Client → API Gateway → User Service
                    → Product Service
                    → Order Service → Kafka → Inventory Service
                         Saga Pattern          Pessimistic Locking
```

| Pattern | What I built |
|---|---|
| Event-Driven Saga | Kafka-based Order → Inventory flow with compensating rollback |
| Idempotency | ProcessedOrder table — prevents duplicate Kafka message processing |
| Concurrency | Pessimistic locking — prevents overselling on simultaneous orders |
| Fault Tolerance | Resilience4j Circuit Breaker + DLT + Kafka Retry |
| Security | JWT + Role-Based Access Control (ADMIN / CUSTOMER) |

`Spring Boot` `Spring Cloud` `Kafka` `Eureka` `OpenFeign` `Resilience4j` `Docker` `JUnit` `Mockito`

---

### 🤖 [Agentic AI-CodePilot](https://github.com/Monudhakad1/AI-Code-Reviewer) — AI Code Review Agent *(Ongoing)*

Autonomous code review agent that analyzes PRs and detects bugs, code smells, and SOLID violations using LLMs.

- Event-driven pipeline: Gateway (Producer) → Kafka → AI Processor (Consumer)
- LLM-based analysis with **Tool Calling** and **RAG** via **Spring AI** and **LangChain4j**
- Vector Embeddings for semantic code search

`Spring AI` `LangChain4j` `RAG` `Tool Calling` `Kafka` `Docker` `Java 21`

---

### 🔐 [AuthNexus](https://github.com/Monudhakad1/AuthNexus-backend) — Auth & User Management System

- JWT (Access + Refresh tokens) + OAuth2 (Google, GitHub)
- Role-Based Access Control + Swagger/OpenAPI docs

`Spring Security` `JWT` `OAuth2` `MySQL` `Docker`

---

## 📊 DSA & Competitive Programming

🏆 **Global Rank 887** — LeetCode Weekly Contest 487 (40,000+ participants)  
💡 **650+ problems** solved across LeetCode & GeeksforGeeks

[![LeetCode](https://img.shields.io/badge/LeetCode-monudhakad055-FFA116?style=flat&logo=leetcode&logoColor=white)](https://leetcode.com/u/monudhakad055/)
[![CodeChef](https://img.shields.io/badge/CodeChef-asthetic__strik-5B4638?style=flat&logo=codechef&logoColor=white)](https://www.codechef.com/users/asthetic_strik)

---

## 📫 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Monu_Dhakad-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/monu-dhakad-42b525276)
[![GitHub](https://img.shields.io/badge/GitHub-monudhakad1-181717?style=flat&logo=github&logoColor=white)](https://github.com/monudhakad1)
[![Gmail](https://img.shields.io/badge/Gmail-monudhakad055-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:monudhakad055@gmail.com)
