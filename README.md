<h1 align="center">Hi, I'm Denis Makukh 👋</h1>

<p align="center">
  <b>Senior Backend Developer · Java/Kotlin Engineer · Solution Architect</b>
</p>

<p align="center">
  Building scalable backend systems, distributed platforms, integrations and business-critical services.
</p>

<p align="center">
  <a href="https://t.me/denvader">
    <img src="https://img.shields.io/badge/Telegram-denvader-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" />
  </a>
  <a href="https://github.com/DenisMakukh">
    <img src="https://img.shields.io/badge/GitHub-DenisMakukh-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

---

## About me

I am a **Senior Backend Developer** and **Solution Architect** focused on backend engineering, distributed systems and platform architecture.

Currently, I work at **Yandex**, where I develop and architect an internal HR and workforce management platform for logistics operations across **Yandex Market**, **Yandex Lavka** and related business units.

My work combines backend development, architecture, integrations, orchestration, access control, workforce automation and technical leadership.

I enjoy building systems that are not only technically reliable, but also create measurable business value.

---

## Current focus

- Backend development with **Java 25** and **Kotlin**
- Distributed systems and platform services
- Event-driven architecture with **Kafka**
- Workflow orchestration with **Temporal**
- Domain-driven design and access control models
- HR-tech and logistics automation
- High-load business-critical integrations
- Technical leadership and architecture ownership

---

## Current role

### Senior Backend Developer / Solution Architect at Yandex

I work on a workforce management platform for logistics operations.

The platform supports:

- employee and contractor lifecycle processes;
- account management;
- role and access management;
- attendance tracking;
- fact-based work accounting;
- workforce slot distribution;
- integrations with internal Yandex systems;
- integrations with external access control systems;
- business dashboards and monitoring.

The system operates across more than **1,600 logistics locations** and processes **millions of events per month**.

On average, the platform handles around **198 hiring-related performer events** and **197 termination-related performer events** every day.

---

## Selected impact

### Restricted Yandex account platform

Designed and implemented a service for creating restricted Yandex accounts in a dedicated partition for logistics employees and contractors.

Previously, standard Yandex accounts were used for some warehouse scenarios. These accounts created unnecessary cost and operational overhead because warehouse users only needed a limited set of permissions.

The new service provides accounts with a restricted permission model and supports only the actions required for specific logistics workflows.

**Estimated business impact:** up to **7.5M RUB annual savings**.

Technical scope:

- integration with Yandex Passport;
- account lifecycle management;
- role assignment workflows;
- integration with adjacent internal systems;
- orchestration via Temporal;
- asynchronous communication via Kafka;
- fault-tolerant processing;
- monitoring and operational visibility.

---

### Workflow orchestration with Temporal

Designed orchestration logic for complex account and role-management processes.

The service coordinates several distributed steps:

- account creation;
- permission assignment;
- role synchronization;
- calls to internal systems;
- integration with Yandex Passport;
- status processing;
- retries and failure handling;
- asynchronous events via Kafka.

Temporal was used to make multi-step business processes more reliable, observable and easier to recover.

---

### Domain-based access model

Designed a domain-based access model for logistics and business-unit hierarchy.

The model allows permissions to be assigned to specific nodes of the business tree, for example:

- Yandex Market;
- Yandex Lavka;
- city-level nodes;
- logistics facilities;
- partner sorting centers;
- operational units.

This approach made it possible to isolate business logic and access rights across different domains without duplicating platform logic.

Business value:

- faster onboarding of new business units;
- reduced time-to-market for new logistics scenarios;
- more flexible access management;
- better scalability of the platform;
- cleaner domain boundaries;
- simpler support for new operational models.

---

### Attendance and fact-based work accounting

Designed and implemented logic for attendance tracking and fact-based work accounting for Yandex Lavka performers.

The system uses:

- planned work slots;
- actual attendance data;
- external access control system events;
- performer status data;
- business rules;
- operational constraints.

The module helps the business compare planned and actual work, detect anomalies and improve the accuracy of operational accounting.

---

### Workforce slot distribution

Designed and implemented a slot distribution module for Yandex Lavka.

The module receives workforce demand generated by ML engineers and distributes available work slots between performers.

The algorithm takes into account:

- business demand;
- performer preferences;
- availability;
- facility-level restrictions;
- operational priorities;
- attendance context;
- business rules.

**Estimated business impact:** around **200M RUB annual savings** through better workforce allocation, reduced manual work and improved planning accuracy.

---

## Tech stack

### Languages

![Java](https://img.shields.io/badge/Java_25-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

### Backend

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-02569B?style=for-the-badge)
![SOAP](https://img.shields.io/badge/SOAP-555555?style=for-the-badge)

### Databases and storage

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=for-the-badge&logo=clickhouse&logoColor=black)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Cassandra](https://img.shields.io/badge/Cassandra-1287B1?style=for-the-badge&logo=apachecassandra&logoColor=white)
![S3](https://img.shields.io/badge/S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)

### Messaging and orchestration

![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Temporal](https://img.shields.io/badge/Temporal-000000?style=for-the-badge)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![Quartz](https://img.shields.io/badge/Quartz-555555?style=for-the-badge)

### Infrastructure

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI/CD-2088FF?style=for-the-badge)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Yandex Deploy](https://img.shields.io/badge/Yandex_Deploy-FFCC00?style=for-the-badge)

---

## Architecture interests

I am especially interested in:

- distributed system design;
- service decomposition;
- domain-driven design;
- event-driven architecture;
- workflow orchestration;
- scalable access control;
- RBAC and domain-based permissions;
- platform engineering;
- high-load backend systems;
- observability and production reliability;
- engineering management and technical leadership.

---

## Previous experience

### RTK IT — Java Developer

Worked on a data management platform and Cluster Manager — a Java/Spring Boot application similar to Apache Ambari.

Key contributions:

- developed backend services for cluster management;
- implemented installation and configuration flows for Hadoop components;
- worked with Zookeeper, HDFS, YARN and Hive;
- helped speed up cluster deployment by around 60%;
- implemented Kerberos authentication support for Cassandra;
- built a Go-based monitoring agent for host-level service checks;
- reduced incident detection time by around 70%.

Tech stack:

- Java;
- Spring Boot;
- Go;
- PostgreSQL;
- Cassandra;
- Hadoop;
- HDFS;
- YARN;
- Hive;
- Zookeeper;
- Kerberos;
- Docker;
- Linux.

---

### Digital Security Research — Team Lead / Backend Developer

Worked on Hide.Digital, a product for digital footprint analysis.

Key contributions:

- developed backend services with Python and FastAPI;
- designed APIs and integration contracts;
- led backend development;
- performed code reviews;
- made architectural decisions;
- integrated frontend, payment systems and external APIs;
- improved API response time by around 40%.

Tech stack:

- Python;
- FastAPI;
- PostgreSQL;
- REST API;
- payment integrations;
- external APIs;
- Docker;
- CI/CD.

---

### NTC Vulkan — Junior Backend Developer

Worked on parsing infrastructure and backend services.

Key contributions:

- optimized parsing workflows;
- improved task execution speed by around 45%;
- implemented asynchronous and parallel processing;
- designed parser manager logic;
- integrated processing through Kafka;
- improved throughput by around 70%;
- reduced stored data volume by around 60% using filtering and optimized storage in PostgreSQL and S3.

Tech stack:

- Python;
- PostgreSQL;
- Kafka;
- S3;
- Docker;
- asynchronous processing.

---

## Leadership and management

Besides engineering, I am interested in technical leadership and product ownership.

My experience includes:

- technical leadership of a 4-person development team;
- task decomposition;
- estimation and planning;
- sprint planning;
- poker planning;
- code review;
- resource allocation;
- collaboration with business analysts;
- architecture review;
- communication with adjacent teams;
- production support and delivery ownership.

I prefer a situational management style: adapting the level of involvement, guidance and autonomy to the task, context and engineer’s experience.

---

## How I work

I like working on complex products where engineering decisions directly affect business outcomes.

My usual approach:

1. Understand the business problem.
2. Identify system boundaries and constraints.
3. Design a scalable domain model.
4. Choose the right integration and orchestration patterns.
5. Decompose the solution into deliverable steps.
6. Align implementation with the team.
7. Deliver to production.
8. Add monitoring and feedback loops.
9. Iterate based on real usage and metrics.

---

## Career interests

I am interested in roles where I can combine backend engineering, architecture and technical leadership.

Relevant directions:

- Solution Architect;
- Lead Backend Developer;
- Team Lead;
- CTO-track roles;
- early-stage products;
- internal platforms;
- complex distributed systems;
- business-critical backend products.

I am highly motivated to build new products, take ownership of complex systems and grow into roles with broader architectural and product responsibility.

---

## Education

**HSE University**  
Business Informatics  
2022–2026

Minor: **Intelligent Data Analysis**  
Faculty of Computer Science  
2023–2025

---

## Contacts

- Telegram: [@denvader](https://t.me/denvader)
- GitHub: [DenisMakukh](https://github.com/DenisMakukh)
