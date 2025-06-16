## 🗂️ Topics & Checklist

---

### 1. 📊 SQL & Database Concepts
- [ ] **Basic SQL**
  - SELECT, INSERT, UPDATE, DELETE
  - JOINS: INNER, LEFT, RIGHT, FULL OUTER
  - GROUP BY, HAVING, ORDER BY
- [ ] **Advanced Queries**
  - Window Functions: RANK, DENSE_RANK, ROW_NUMBER
  - CTEs and Recursive Queries
  - Subqueries, EXISTS vs IN
- [ ] **Indexes & Optimization**
  - Types of Indexes (B-Tree, Hash)
  - Index Scan vs Seq Scan
  - EXPLAIN ANALYZE
- [ ] **Transactions**
  - ACID Properties
  - Isolation Levels: Read Uncommitted, Repeatable Read, Serializable
  - Deadlocks & Prevention
- [ ] **DB Design**
  - Normal Forms (1NF to 3NF)
  - ER Diagrams & Relational Mapping

---

### 2. ⚙️ Java Core & Advanced
- [ ] **OOPs + Advanced Concepts**
  - Abstract Class vs Interface
  - SOLID Principles
  - Composition over Inheritance
- [ ] **Collections Framework**
  - List, Set, Map, Queue
  - HashMap Internal Working, Fail-Fast vs Fail-Safe
  - Concurrent Collections
- [ ] **Streams API & Functional Programming**
  - filter, map, flatMap, reduce, collect
  - Custom Collector
- [ ] **Lambdas**
  - Functional Interfaces
  - Method References, Constructor References
- [ ] **Multithreading**
  - Runnable, Callable, ExecutorService
  - Thread Pooling, Synchronization
  - Deadlock, Livelock, Starvation
- [ ] **JVM & Memory**
  - Stack vs Heap, GC Algorithms
  - Classloader, JIT Compiler
  - OutOfMemoryError and how to debug

---

### 3. 🧱 Spring Boot & Microservices
- [ ] **Spring Boot Fundamentals**
  - Starters, Autoconfiguration, Main Class Bootstrapping
- [ ] **IOC & DI**
  - @Component, @Autowired, @Bean, @Configuration
- [ ] **Configuration & Profiles**
  - application.yml/properties
  - @Value, @ConfigurationProperties
- [ ] **REST APIs**
  - @RestController, ResponseEntity, Exception Handling
  - DTOs and Validation (JSR-380)
  - Swagger/OpenAPI Documentation
- [ ] **Testing**
  - Unit Tests (JUnit, Mockito)
  - Integration Testing with @SpringBootTest
- [ ] **Inter-Service Communication**
  - RESTTemplate vs WebClient
  - Feign Clients
  - Kafka/RabbitMQ (Async)
- [ ] **Design Patterns**
  - API Gateway, Circuit Breaker, Retry, Bulkhead
  - Rate Limiting, Idempotency

---

### 4. ☁️ Spring Cloud Ecosystem
- [ ] Eureka Service Registry
- [ ] Spring Cloud Config Server
- [ ] API Gateway (Spring Cloud Gateway)
- [ ] Feign Clients
- [ ] Distributed Tracing (Sleuth, Zipkin)
- [ ] Load Balancing (Ribbon/Feign)
- [ ] Resilience4j: Retry, CircuitBreaker, RateLimiter

---

### 5. 🔐 Spring Security & OAuth2
- [ ] Basic Authentication & Authorization
- [ ] Stateless JWT-based Auth
- [ ] Role-Based Access Control (RBAC)
- [ ] OAuth2 Protocol Deep Dive
- [ ] CORS & CSRF Protection
- [ ] Password Encoding (BCryptPasswordEncoder)

---

### 6. 🧬 ORM & JPA/Hibernate
- [ ] Entities & Repositories
- [ ] JPQL, Native Queries, Criteria API
- [ ] Mapping Types:
  - @OneToOne, @OneToMany, @ManyToOne, @ManyToMany
- [ ] Fetch Types: LAZY vs EAGER
- [ ] Cascade Types & Orphan Removal
- [ ] Entity Lifecycle Methods
- [ ] First & Second-Level Caching

---

### 7. 🐍 Kafka
- [ ] Kafka Basics (Broker, Topic, Partition, Consumer Group)
- [ ] Kafka Producer/Consumer APIs
- [ ] Kafka with Spring Boot
- [ ] Consumer Offsets & Rebalancing
- [ ] Kafka Streams (Basic intro)
- [ ] Kafka Exactly-Once Semantics
- [ ] Kafka Connect (optional)
- [ ] Zookeeper Role & Importance

---

### 8. 🌊 Stream Processing with Apache Flink
- [ ] Flink Architecture (JobManager, TaskManager)
- [ ] DataStream API
- [ ] Table API & SQL
- [ ] Event Time vs Processing Time
- [ ] Windows (Tumbling, Sliding, Session)
- [ ] State Management & Keyed Streams
- [ ] Checkpointing, Savepoints, Fault Tolerance
- [ ] Kafka-Flink Integration
- [ ] CEP (Complex Event Processing)

---

### 9. 🚀 Caching with Redis
- [ ] Redis Setup + Integration with Spring
- [ ] @Cacheable, @CacheEvict, @Caching
- [ ] TTL, LRU & Eviction Policies
- [ ] Redis Pub/Sub & Streams (Optional)
- [ ] Distributed Caching Patterns
- [ ] Cache Consistency & Invalidation

---

### 10. 📡 WebSockets & Realtime Communication
- [ ] WebSocket Fundamentals (Handshake, Upgrade)
- [ ] STOMP Protocol
- [ ] Spring WebSocket with SockJS
- [ ] Message Broker (SimpleBroker vs External)
- [ ] Real-time Notifications & Broadcasting

---

### 11. 🧠 DSA & System Design
- [ ] Arrays, Strings, Hashing, Stacks, Queues
- [ ] Sliding Window, Two Pointers
- [ ] Trees & Graphs
- [ ] Recursion & DP (Top K problems)
- [ ] LLD (Object Modelling, OOP principles)
- [ ] HLD (Load Balancer, Scaling, DB Design)
- [ ] Design Patterns (Factory, Singleton, Strategy)
- [ ] Case Studies: Rate Limiter, URL Shortener, Notification System

---

### 12. 🌍 DevOps & Monitoring
- [ ] Dockerfile, Docker Compose for Spring Apps
- [ ] CI/CD with Jenkins or GitHub Actions
- [ ] Monitoring with Prometheus + Grafana
- [ ] ELK Stack (Elasticsearch, Logstash, Kibana)
- [ ] Health Checks, Metrics Exposure

---

### 13. ☁️ AWS Cloud Fundamentals (Developer & Deployment Focus)

- [ ] **Core AWS Services**
  - EC2 (Instances, Security Groups, Key Pairs)
  - S3 (Object Storage, Versioning, Lifecycle Policies)
  - IAM (Users, Roles, Policies)
  - RDS (PostgreSQL, MySQL on AWS)
  - CloudWatch (Monitoring, Alarms, Logs)

- [ ] **Networking & Access**
  - VPC Basics (Subnets, Route Tables, NAT Gateways)
  - Load Balancer (ALB vs NLB)
  - Security Groups vs NACLs
  - IAM Role usage for EC2 and Lambda

- [ ] **CI/CD & DevOps**
  - CodePipeline, CodeBuild basics
  - Deploying Spring Boot using Elastic Beanstalk
  - ECS with Fargate (Optional but good)

- [ ] **Serverless Architecture**
  - Lambda Functions with Java
  - API Gateway integration with Lambda
  - EventBridge and SQS (intro only)

- [ ] **Storage, Caching, Queues**
  - DynamoDB Basics
  - SQS (FIFO vs Standard Queue)
  - ElastiCache (Redis with AWS)

- [ ] **Best Practices**
  - Cost Optimization Tips
  - Cloud Security Basics
  - Tagging, Billing Alerts
