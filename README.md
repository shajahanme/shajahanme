# SHAJAHAN MOHAMMED
writeshajahan@gmail.com | 205-522-3339 | LinkedIn | GitHub | Portfolio | Memphis, TN (Open for Relocation)

## PROFILE SUMMARY
* Software Engineer with a Master’s in Computer Science and 2.5 years of experience engineering scalable, high-performance applications on Azure.
* Proven track record of optimizing distributed systems for high-volume user traffic.
* Expert in transitioning monolithic architectures to event-driven microservices while maintaining 99.9% service reliability.
* Skilled in Java, Spring Boot, and cloud-native infrastructure to drive continuous delivery and operational excellence.

## PROFESSIONAL EXPERIENCE

**Software Engineer, Neuronet Solutions** | Apr 2025 – Present
* Integrated LLM capabilities into core microservices to enhance product intelligence, and developed internal automation tooling that boosted engineering velocity by 20%.
* Optimized Azure-hosted microservices by refactoring legacy logic, achieving a 35% improvement in API latency and a 15% reduction in cloud compute costs for high-scale enterprise modules.
* Drove the adoption of Test-Driven Development (TDD) across the team, increasing code coverage to 85% and reducing user-facing production regressions by 30% across core enterprise workflows.
* Redesigned asynchronous workflows using Java CompletableFuture, enabling the platform to support 2.4x higher user concurrency without performance degradation.
* Automated manual deployment steps using Jenkins and Docker, reducing deployment time by 50% and ensuring consistent, reproducible environments across dev and production.
* Engineered comprehensive telemetry and observability pipelines using the ELK Stack, enabling real-time diagnosis of production incidents and maintaining 99.9% service reliability.

**Software Engineering Intern, Sand Space Technologies** | July 2021 – Dec 2022
* Containerized microservices with Docker and orchestrated Kubernetes deployments, ensuring zero-downtime auto-scaling to support 100k+ daily active users during peak traffic.
* Engineered secure data pipelines leveraging Spring Security (OAuth2) and Azure RBAC, enforcing strict enterprise access controls and ensuring compliance for sensitive user data.
* Optimized SQL schemas and implemented database indexing, achieving 40% faster data retrieval for high-volume reporting modules.
* Migrated manual build processes to Azure DevOps pipelines, reducing release overhead and enabling daily deployments.
* Drove feature development across the full SDLC for core modules, translating business requirements into technical specifications, schema design, and frontend implementation alongside Agile/Scrum teams.

## TECHNICAL SKILLS
* **Languages:** Java (8/11/17), C#, .NET, C++, Python, JavaScript (ES6+), SQL
* **Frameworks:** Spring Boot, Spring Cloud, Hibernate, ReactJS, Node.js, Angular, Express.js
* **Cloud & DevOps:** Azure (App Services, Functions, SQL), AWS, CI/CD (Jenkins, GitHub Actions)
* **Automation & Testing:** Selenium, JUnit, Mockito, Postman, ELK Stack
* **Containerization:** Docker, Kubernetes, OpenShift (OCP)
* **Databases:** MySQL, PostgreSQL, MongoDB, Redis
* **Tools:** Git, Jira, Dynatrace
* **Architecture:** Microservices, Distributed Systems, Event-Driven Architecture, REST APIs, Distributed Caching, Database Sharding, High Availability, Fault Tolerance, Horizontal Scalability
* **AI / Data Processing:** Streaming Analytics, Anomaly Detection, Real-Time Event Processing, LLM Integration

## EDUCATION & CERTIFICATIONS
* **Master of Science, Computer Science** | University of Memphis, TN | Jan 2023 – Jan 2025
* **Bachelor of Technology, Computer Science** | Lovely Professional University, India | Jun 2018 – May 2022
* **Microsoft Azure Fundamentals (AZ-900)**

## PROJECTS

**Distributed Inventory Management System**
* **Technologies:** Java, Spring Boot, Spring Cloud, Kafka, Redis, Docker, MySQL, Resilience4j
* Engineered an inventory platform distributed across 6 microservices (including Order, Payment, and Notification) via Spring Cloud Gateway and Eureka Discovery, guaranteeing 99.9% availability for core workflows.
* Designed an event-driven architecture using Apache Kafka to handle asynchronous order processing, configuring idempotent producers to achieve exactly-once semantics and reducing order sync latency from 120ms to 35ms.
* Implemented Resilience4j Circuit Breakers and retry mechanisms to prevent cascading failures, enabling the system to handle 10k+ concurrent requests during stress testing.
* Integrated Redis distributed caching for frequently accessed stock data, reducing database read load by 45% and improving API response times.

**Real-Time Fraud Detection System**
* **Technologies:** Java, Spring Boot, Kafka Streams, PostgreSQL, MongoDB, Docker, WebSocket
* Developed a high-throughput fraud analysis microservice capable of processing 1M+ transaction events/day in real-time using Kafka Streams.
* Implemented sliding-window anomaly detection algorithms and IP fingerprinting to identify suspicious patterns, reducing fraud detection time from minutes to under 2 seconds.
* Leveraged MongoDB to store high-volume unstructured transaction logs for retrospective audit trails.
* Designed a rule-based engine to score transaction risks, increasing automated threat detection accuracy by 28% and reducing false positives.
* Exposed REST APIs for real-time alerts and integrated WebSockets to push live security dashboards to admin clients.

**Distributed URL Shortener**
* **Technologies:** Java, Spring Boot, Redis, MySQL, Base62 Algorithm, Docker
* Engineered a read-heavy distributed URL shortener handling 10k QPS, utilizing Base62 encoding for unique key generation and MySQL Database Sharding to support massive write throughput.
* Optimized data retrieval speeds by implementing a Least Recently Used (LRU) caching policy in Redis, achieving a 92% cache-hit ratio and an average response time of 12ms.
* Built asynchronous logging and click-tracking analytics using multi-threading to ensure non-blocking user redirection.
