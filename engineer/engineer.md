## Networking:
- [Networking + APIs overview](https://github.com/Vergueirod/networking-guide)

## Paradigms:
- Imperative paradigm
- [Object-oriented paradigm](https://github.com/Vergueirod/oop-concepts)
- Functional paradigm
- Declarative paradigm
- Event-oriented paradigm
- Component-oriented (or modular) paradigm

**Additional/niche paradigms:**
- Logical paradigm
- Dataflow-oriented paradigm
- Aspect-oriented paradigm (AOP)

## Fundamental Concepts / Software Engineer Mindset:
- DDD (Domain-Driven Design)
- SOLID (5 principles of object-oriented design)
- TDD (Test-Driven Development)
- BDD (Behavior-Driven Development)
- Clean Code (Robert C. Martin's clean code principles)
- GRASP (General Responsibility Assignment Software Patterns)
- KISS, YAGNI, DRY (general design principles)
- [Design Patterns](https://github.com/Vergueirod/design-patterns)

## Programming Languages:

- [C](https://github.com/Vergueirod/c-language-notebook)
- [C++](https://github.com/Vergueirod/cpp-language-notebook)
- [Rust](https://github.com/Vergueirod/rust-language-notebook)
- Python
- [Java](https://github.com/Vergueirod/java-language-notebook)
- Go
- TypeScript
- Kotlin
- Angular
- React.JS

## Data Engineering & Storage

### Relational Databases (SQL):
- PostgreSQL
- MySQL
- SQLite
- Query optimization
- Normalization & ACID

### NoSQL Databases:
- MongoDB (Document-based)
- Redis (Key-Value store)
- Cassandra (Wide-column)
- Neo4j (Graph-based)

### Caching:
- Redis
- Memcached

### Data Modeling & Best Practices:
- ER Modeling
- Indexing strategies
- CAP Theorem
- Data consistency models
- Schema design tips

### Big Data & Pipelines:
- Hadoop
- Spark
- Airflow
- ETL/ELT Concepts


## Git:
- [Git commands](https://github.com/Vergueirod/github-guide)

## Big(O):
- [Big(O)](https://github.com/Vergueirod/big-o--notation)

## Software Architecture:
- [Software Architecture](https://github.com/Vergueirod/software-architecture)

## Gateways & Identity Management

### API Gateways:
- **Kong** – Extensible with plugins, ideal for rate limiting, logging, transformations, etc.
- **NGINX** – Reverse proxy, load balancer, TLS termination, basic API gateway features

### Identity & Access Management (IAM):
- **Keycloak** – Open-source IAM, suporte a OAuth2, OIDC, SAML, RBAC
- Concepts: OAuth2, OpenID Connect, SSO, RBAC, Identity Federation

### Reverse Proxy Patterns:
- Layer 7 routing
- TLS offloading
- Caching
- Rate limiting & throttling

## APIs:
- REST
- RESTful
- GraphQL
- gRPC
- WebSocket
- SOAP

## Asynchronous Communication:
- RabbitMQ
- Kafka

## Linux:
- Basic commands

## IaC:
- Terraform

## Virtualization and Containerization:
- Docker

## Container orchestration
- Kubernetes

## Monitoring/observability:
- Metrics
- DataDog
- Grafana

## CI/CD (Continuous Integration / Continuous Delivery)

### Concepts and Best Practices:
- **Continuous Integration (CI)**
  - Automate builds and test runs
  - Validate pull requests and code merges
- **Continuous Delivery vs. Continuous Deployment**
  - *Delivery*: Code is production-ready, but deployment is manual
  - *Deployment*: Code is automatically deployed to production
- **Pipelines as Code**
- **Environment Strategy**
  - Dev, Staging, Production environments
- **Automated Testing**
  - Unit, integration, end-to-end (E2E) tests as part of the pipeline
- **Deployment Strategies**
  - Blue/Green deployments
  - Canary releases
  - Feature toggles
- **Rollback Mechanisms**
  - Versioned deploys, health checks, circuit breakers
- **Monitoring & Alerts**
  - Integrate observability post-deploy

### Common CI/CD Tools:
- **GitHub Actions** – Native to GitHub, easy to use and extend
- **GitLab CI/CD** – Full integrated CI/CD with powerful features
- **CircleCI** – Cloud-native, performant pipelines
- **Jenkins** – Highly customizable, plugin-based system
- **Bitbucket Pipelines** – Simple integration for Bitbucket users
- **Argo CD** – GitOps-based CD for Kubernetes
- **Tekton Pipelines** – Kubernetes-native CI/CD framework

### Frequent Integrations:
- **Docker** – Build, tag, and push images as part of the pipeline
- **Kubernetes** – Deploy using `kubectl`, Helm, or Argo CD
- **Terraform** – Integrate infrastructure provisioning
- **Secrets Management** – Use secure systems (GitHub Secrets, Vault)
- **Notifications** – Slack, Discord, email alerts for pipeline events

### Pro Tips:
- Enforce code quality with **linters and static analysis**
- Use **build/test matrices** to test against multiple versions
- Clearly separate pipeline stages: `build → test → package → deploy → monitor`
- Store **build artifacts** in secure registries (Docker Hub, GitHub Packages, etc.)
- Always version your pipeline configuration (`.yml` files) within the repo

### Example Pipelines (coming soon):
- [GitHub Actions Example](#)
- [CI/CD with Docker + Kubernetes](#)

## Certifications:
- [AWS Cloud Practitioner](https://github.com/Vergueirod/aws-cloud-practitioner)

## DS&A:
- [DS&A](https://github.com/Vergueirod/Blind-75-LeetCode-Questions)

## Artificial intelligence:
- [Mathematics and Statistics](https://github.com/Vergueirod/mathematics-and-statistics)
- [Perceptron](https://github.com/Vergueirod/Perceptron)
- RAG
- LangChain
- Chunks
- Overlap
- Vectorization
- Embeddings
- KNN
- Consensus Similarity
- FAISS
- PostgreSQL (With VectorDB extension - PgVector)

