# System Design Kit ⚙️

> A curated collection of essential resources, case studies, tools, courses, and playbooks to help you master System Design — from designing your first API to architecting distributed systems that scale to millions of users.

**GitHub Description:** `A curated collection of resources, case studies, tools, and roadmaps to help you go from system design beginner to confidently architecting large-scale distributed systems.`

![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

---

## About

System design is the skill that separates a good engineer from a great one.

This is a curated directory of the best system design resources for every stage of your journey — from understanding client-server architecture to designing systems like YouTube, WhatsApp, and Uber at scale. Whether you're a student preparing for FAANG interviews, an engineer leveling up, or an architect designing production systems, you'll find books, courses, case studies, tools, and communities for every level.

---

## Who Is This For?

- **Students** — Preparing for SDE interviews at product companies
- **Backend Engineers** — Leveling up from writing code to designing systems
- **Senior Engineers** — Preparing for Staff / Principal interviews
- **Engineering Managers** — Understanding trade-offs in architectural decisions
- **Founders & CTOs** — Making the right architectural bets early
- **Anyone** who wants to think in systems, not just code

---

## What's Inside?

- **Roadmaps** — Step-by-step paths from basics to advanced
- **Foundational Concepts** — Networking, protocols, and distributed systems basics
- **Scalability** — Horizontal/vertical scaling, load balancing, and caching
- **Databases** — SQL vs NoSQL, sharding, replication, and CAP theorem
- **Caching** — Strategies, invalidation, CDN, and Redis patterns
- **Messaging & Queues** — Kafka, RabbitMQ, and async communication
- **API Design** — REST, GraphQL, gRPC, and WebSockets
- **Storage & File Systems** — Object storage, blob storage, and CDNs
- **Microservices** — Service decomposition, communication, and patterns
- **Security at Scale** — Auth, rate limiting, and DDoS protection
- **Reliability & Availability** — Fault tolerance, SLAs, and disaster recovery
- **Monitoring & Observability** — Metrics, logs, traces, and alerting
- **Real-World Case Studies** — How top companies built their systems
- **Interview Prep** — Frameworks, templates, and practice problems
- **Books & Courses** — The best learning resources
- **Tools** — Diagramming, load testing, and architecture tools

---

## 📋 Table of Contents

- [Roadmaps](#roadmaps)
- [Foundational Concepts](#foundational-concepts)
- [Scalability](#scalability)
- [Load Balancing](#load-balancing)
- [Caching](#caching)
- [Databases](#databases)
- [Replication & Sharding](#replication--sharding)
- [CAP Theorem & Consistency](#cap-theorem--consistency)
- [API Design](#api-design)
- [Messaging & Event Streaming](#messaging--event-streaming)
- [Microservices Architecture](#microservices-architecture)
- [Storage & CDN](#storage--cdn)
- [Search Systems](#search-systems)
- [Rate Limiting & Throttling](#rate-limiting--throttling)
- [Authentication & Authorization at Scale](#authentication--authorization-at-scale)
- [Reliability & Fault Tolerance](#reliability--fault-tolerance)
- [Monitoring & Observability](#monitoring--observability)
- [Distributed Systems Concepts](#distributed-systems-concepts)
- [Real-World Case Studies](#real-world-case-studies)
- [System Design Interview Prep](#system-design-interview-prep)
- [Books](#books)
- [Courses & Videos](#courses--videos)
- [Cheat Sheets & Quick References](#cheat-sheets--quick-references)
- [Diagramming & Architecture Tools](#diagramming--architecture-tools)
- [GitHub Repositories](#github-repositories)
- [Engineering Blogs](#engineering-blogs)
- [Newsletters & Podcasts](#newsletters--podcasts)
- [Communities & Forums](#communities--forums)
- [Key Articles & Essays](#key-articles--essays)
- [Practice Problems](#practice-problems)

---

## Roadmaps

- [Roadmap.sh - System Design](https://roadmap.sh/system-design)
- [Roadmap.sh - Software Architect](https://roadmap.sh/software-architect)
- [Roadmap.sh - Backend](https://roadmap.sh/backend)
- [Tech Interview Handbook - System Design](https://www.techinterviewhandbook.org/system-design/)
- [System Design Roadmap - GitHub](https://github.com/donnemartin/system-design-primer)
- [High Scalability Learning Path](http://highscalability.com/)
- [ByteByteGo System Design Roadmap](https://bytebytego.com/)
- [Distributed Systems Learning Path - MIT](https://pdos.csail.mit.edu/6.824/)

---

## Foundational Concepts

### Networking Basics

- [Computer Networking - Khan Academy](https://www.khanacademy.org/computing/computers-and-internet/xcae6f4a7ff015e7d:the-internet)
- [HTTP & HTTPS Explained](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview)
- [HTTP/1.1 vs HTTP/2 vs HTTP/3](https://www.cloudflare.com/learning/performance/http2-vs-http1.1/)
- [TCP vs UDP](https://www.cloudflare.com/learning/ddos/glossary/tcp-ip/)
- [DNS Resolution Explained](https://www.cloudflare.com/learning/dns/what-is-dns/)
- [WebSockets Explained](https://www.baeldung.com/java-websockets)
- [Long Polling vs WebSockets vs SSE](https://ably.com/blog/websockets-vs-long-polling)
- [IP Addresses, Ports & Firewalls](https://www.cloudflare.com/learning/network-layer/what-is-a-network/)
- [OSI Model Explained](https://www.cloudflare.com/learning/ddos/glossary/open-systems-interconnection-model-osi/)
- [gRPC vs REST vs GraphQL](https://www.baeldung.com/rest-vs-graphql-vs-grpc)

### Client-Server Architecture

- [Client-Server Model](https://en.wikipedia.org/wiki/Client%E2%80%93server_model)
- [Monolith vs Microservices](https://martinfowler.com/articles/microservices.html)
- [Three-Tier Architecture](https://www.ibm.com/topics/three-tier-architecture)
- [Peer-to-Peer Architecture](https://www.cloudflare.com/learning/network-layer/what-is-a-computer-network/)
- [Serverless Architecture](https://martinfowler.com/articles/serverless.html)

### Proxies

- [Forward Proxy vs Reverse Proxy](https://www.cloudflare.com/learning/cdn/glossary/reverse-proxy/)
- [Nginx as Reverse Proxy](https://docs.nginx.com/nginx/admin-guide/web-server/reverse-proxy/)
- [HAProxy](https://www.haproxy.org/)
- [Envoy Proxy](https://www.envoyproxy.io/)
- [Service Mesh - Istio](https://istio.io/)

---

## Scalability

### Core Concepts

- [Scalability for Dummies](https://www.lecloud.net/tagged/scalability)
- [Horizontal vs Vertical Scaling](https://www.baeldung.com/cs/horizontal-vs-vertical-scaling)
- [Stateless vs Stateful Services](https://www.redhat.com/en/topics/cloud-native-apps/stateful-vs-stateless)
- [The 12-Factor App](https://12factor.net/)
- [Scale Cube - AKF Partners](https://akfpartners.com/growth-blog/scale-cube)
- [Back-of-the-Envelope Calculations](https://bytebytego.com/courses/system-design-interview/back-of-the-envelope-estimation)
- [Numbers Every Engineer Should Know](https://github.com/donnemartin/system-design-primer#latency-numbers-every-programmer-should-know)
- [Latency Numbers - Jeff Dean](https://gist.github.com/jboner/2841832)

### Performance

- [Web Performance Fundamentals - MDN](https://developer.mozilla.org/en-US/docs/Web/Performance)
- [TTFB, FCP, LCP Explained](https://web.dev/vitals/)
- [Connection Pooling](https://www.baeldung.com/java-connection-pooling)
- [Keep-Alive Connections](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Keep-Alive)

---

## Load Balancing

### Concepts & Algorithms

- [Load Balancing Explained - Nginx](https://www.nginx.com/resources/glossary/load-balancing/)
- [Round Robin vs Least Connections vs IP Hash](https://www.cloudflare.com/learning/performance/types-of-load-balancing-algorithms/)
- [L4 vs L7 Load Balancing](https://www.nginx.com/resources/glossary/layer-4-load-balancing/)
- [Consistent Hashing](https://www.toptal.com/big-data/consistent-hashing)
- [Consistent Hashing - Tom White](https://tom-e-white.com/2007/11/consistent-hashing.html)
- [Power of Two Choices](https://www.nginx.com/blog/nginx-power-of-two-choices-load-balancing-algorithm/)
- [Session Persistence / Sticky Sessions](https://www.baeldung.com/cs/load-balancer-session-persistence)

### Tools & Implementations

- [Nginx](https://www.nginx.com/)
- [HAProxy](https://www.haproxy.org/)
- [AWS Elastic Load Balancer](https://aws.amazon.com/elasticloadbalancing/)
- [GCP Cloud Load Balancing](https://cloud.google.com/load-balancing)
- [Traefik](https://traefik.io/)
- [Envoy](https://www.envoyproxy.io/)

---

## Caching

### Concepts & Strategies

- [Caching Strategies - AWS](https://aws.amazon.com/caching/best-practices/)
- [Cache-Aside (Lazy Loading)](https://docs.microsoft.com/en-us/azure/architecture/patterns/cache-aside)
- [Write-Through vs Write-Behind vs Write-Around](https://codeahoy.com/2017/08/11/caching-strategies-and-how-to-choose-the-right-one/)
- [Cache Eviction Policies - LRU, LFU, FIFO](https://www.baeldung.com/java-lru-cache)
- [Cache Stampede / Thundering Herd](https://en.wikipedia.org/wiki/Cache_stampede)
- [Cache Invalidation Strategies](https://martinfowler.com/bliki/TwoHardThings.html)
- [Negative Caching](https://www.cloudflare.com/learning/cdn/what-is-caching/)
- [Distributed Caching](https://www.baeldung.com/distributed-caching)

### Tools

- [Redis](https://redis.io/) *(Most popular)*
- [Redis Data Structures](https://redis.io/docs/data-types/)
- [Redis Cluster](https://redis.io/docs/management/scaling/)
- [Memcached](https://memcached.org/)
- [Hazelcast](https://hazelcast.com/)
- [Apache Ignite](https://ignite.apache.org/)
- [Varnish Cache](https://varnish-cache.org/)

### CDN

- [What is a CDN? - Cloudflare](https://www.cloudflare.com/learning/cdn/what-is-a-cdn/)
- [CDN Caching Strategies](https://www.cloudflare.com/learning/cdn/cdn-cache-control/)
- [Cloudflare](https://www.cloudflare.com/)
- [AWS CloudFront](https://aws.amazon.com/cloudfront/)
- [Fastly](https://www.fastly.com/)
- [Akamai](https://www.akamai.com/)
- [CDN vs Load Balancer](https://www.cloudflare.com/learning/performance/what-is-a-cdn/)

---

## Databases

### SQL vs NoSQL

- [SQL vs NoSQL - MongoDB](https://www.mongodb.com/nosql-explained/nosql-vs-sql)
- [When to Use NoSQL](https://www.mongodb.com/nosql-explained/when-to-use-nosql)
- [Choosing a Database - AWS](https://aws.amazon.com/products/databases/)
- [Polyglot Persistence](https://martinfowler.com/bliki/PolyglotPersistence.html)

### Relational Databases

- [PostgreSQL](https://www.postgresql.org/)
- [MySQL](https://www.mysql.com/)
- [ACID Properties](https://www.baeldung.com/cs/acid-transactions)
- [Database Indexes](https://use-the-index-luke.com/)
- [B-Tree vs Hash Indexes](https://www.postgresql.org/docs/current/indexes-types.html)
- [Query Optimization](https://use-the-index-luke.com/)
- [Database Normalization](https://www.baeldung.com/cs/database-normalization)
- [Transactions & Isolation Levels](https://www.baeldung.com/sql-isolation-levels-vs-each-other)

### NoSQL Databases

- [MongoDB](https://www.mongodb.com/)
- [Cassandra](https://cassandra.apache.org/)
- [DynamoDB - AWS](https://aws.amazon.com/dynamodb/)
- [Redis](https://redis.io/)
- [Neo4j](https://neo4j.com/) *(Graph)*
- [InfluxDB](https://www.influxdata.com/) *(Time series)*
- [Elasticsearch](https://www.elastic.co/)
- [HBase](https://hbase.apache.org/)
- [CouchDB](https://couchdb.apache.org/)

### NewSQL

- [Google Spanner](https://cloud.google.com/spanner)
- [CockroachDB](https://www.cockroachlabs.com/)
- [TiDB](https://www.pingcap.com/)
- [YugabyteDB](https://www.yugabyte.com/)
- [VoltDB](https://www.voltactivedata.com/)

### Data Warehouses

- [Snowflake](https://www.snowflake.com/)
- [BigQuery - Google](https://cloud.google.com/bigquery)
- [Redshift - AWS](https://aws.amazon.com/redshift/)
- [ClickHouse](https://clickhouse.com/)
- [Databricks](https://www.databricks.com/)

---

## Replication & Sharding

### Replication

- [Database Replication Explained](https://www.baeldung.com/cs/db-replication)
- [Master-Slave vs Master-Master Replication](https://www.baeldung.com/cs/active-passive-vs-active-active-replication)
- [Read Replicas](https://aws.amazon.com/rds/features/read-replicas/)
- [Synchronous vs Asynchronous Replication](https://www.baeldung.com/cs/db-replication)
- [MySQL Replication Guide](https://dev.mysql.com/doc/refman/8.0/en/replication.html)
- [PostgreSQL Streaming Replication](https://www.postgresql.org/docs/current/warm-standby.html)

### Sharding

- [Database Sharding - MongoDB](https://www.mongodb.com/features/database-sharding-explained)
- [Sharding Strategies - Horizontal Partitioning](https://www.baeldung.com/cs/horizontal-partitioning)
- [Range vs Hash vs Directory Sharding](https://www.digitalocean.com/community/tutorials/understanding-database-sharding)
- [Resharding & Hotspot Problem](https://aws.amazon.com/blogs/database/choosing-the-right-dynamodb-partition-key/)
- [Consistent Hashing for Sharding](https://www.toptal.com/big-data/consistent-hashing)
- [Vitess - MySQL Sharding](https://vitess.io/)

### Partitioning

- [Horizontal vs Vertical Partitioning](https://www.baeldung.com/cs/horizontal-partitioning)
- [Partitioning in PostgreSQL](https://www.postgresql.org/docs/current/ddl-partitioning.html)
- [Time-based Partitioning](https://www.postgresql.org/docs/current/ddl-partitioning.html)

---

## CAP Theorem & Consistency

### Fundamentals

- [CAP Theorem Explained](https://www.baeldung.com/cs/cap-theorem)
- [CAP Theorem - Martin Kleppmann](https://martin.kleppmann.com/2015/05/11/please-stop-calling-databases-cp-or-ap.html)
- [PACELC Theorem](https://en.wikipedia.org/wiki/PACELC_theorem)
- [Eventual Consistency](https://www.baeldung.com/cs/eventual-consistency-vs-strong-eventual-consistency-vs-strong-consistency)
- [Strong vs Eventual vs Causal Consistency](https://jepsen.io/consistency)
- [Jepsen Analysis - Distributed Systems Safety](https://jepsen.io/)

### Consensus Algorithms

- [Raft Consensus Algorithm](https://raft.github.io/)
- [Paxos Simplified](https://lamport.azurewebsites.net/pubs/paxos-simple.pdf)
- [Two-Phase Commit (2PC)](https://www.baeldung.com/cs/2-phase-commit)
- [Saga Pattern for Distributed Transactions](https://microservices.io/patterns/data/saga.html)
- [Vector Clocks](https://www.baeldung.com/cs/vector-clocks)
- [Gossip Protocol](https://www.baeldung.com/cs/gossip-protocol)

---

## API Design

### REST

- [REST API Design Best Practices](https://www.baeldung.com/rest-api-best-practices-organize-spring-boot-endpoints)
- [RESTful API Design - Microsoft](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)
- [HTTP Methods & Status Codes](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods)
- [API Versioning Strategies](https://www.baeldung.com/rest-versioning)
- [HATEOAS](https://www.baeldung.com/spring-hateoas-tutorial)
- [Pagination in REST APIs](https://www.baeldung.com/rest-api-pagination-in-spring)
- [OpenAPI / Swagger Specification](https://swagger.io/specification/)

### GraphQL

- [GraphQL Official Docs](https://graphql.org/learn/)
- [REST vs GraphQL](https://www.howtographql.com/basics/1-graphql-is-the-better-rest/)
- [N+1 Problem in GraphQL](https://www.baeldung.com/cs/graphql-n-plus-one)
- [GraphQL Persisted Queries](https://www.apollographql.com/docs/apollo-server/performance/apq/)
- [DataLoader for Batching](https://github.com/graphql/dataloader)

### gRPC

- [gRPC Official](https://grpc.io/)
- [Protocol Buffers](https://protobuf.dev/)
- [gRPC vs REST - Performance](https://www.baeldung.com/cs/rest-vs-grpc)
- [gRPC Streaming](https://grpc.io/docs/what-is-grpc/core-concepts/)
- [gRPC-Gateway](https://github.com/grpc-ecosystem/grpc-gateway)

### WebSockets & Real-time

- [WebSockets Explained](https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API)
- [Server-Sent Events (SSE)](https://developer.mozilla.org/en-US/docs/Web/API/Server-sent_events)
- [Long Polling](https://javascript.info/long-polling)
- [Socket.IO](https://socket.io/)
- [Pusher](https://pusher.com/)
- [Ably](https://ably.com/)

### API Gateway

- [API Gateway Pattern](https://microservices.io/patterns/apigateway.html)
- [AWS API Gateway](https://aws.amazon.com/api-gateway/)
- [Kong API Gateway](https://konghq.com/)
- [Apigee - Google](https://cloud.google.com/apigee)
- [Tyk](https://tyk.io/)

---

## Messaging & Event Streaming

### Message Queues

- [Message Queue vs Event Streaming](https://www.baeldung.com/cs/message-queue-vs-event-streaming)
- [RabbitMQ](https://www.rabbitmq.com/)
- [AWS SQS](https://aws.amazon.com/sqs/)
- [Google Cloud Pub/Sub](https://cloud.google.com/pubsub)
- [Azure Service Bus](https://azure.microsoft.com/en-us/products/service-bus)
- [ActiveMQ](https://activemq.apache.org/)
- [NATS](https://nats.io/)

### Event Streaming

- [Apache Kafka](https://kafka.apache.org/)
- [Kafka Architecture](https://kafka.apache.org/documentation/#gettingStarted)
- [Kafka Topics, Partitions, Offsets](https://www.baeldung.com/apache-kafka)
- [Kafka vs RabbitMQ](https://www.baeldung.com/kafka-vs-rabbitmq)
- [Apache Pulsar](https://pulsar.apache.org/)
- [Amazon Kinesis](https://aws.amazon.com/kinesis/)
- [Confluent Cloud](https://www.confluent.io/)

### Patterns

- [Publisher-Subscriber Pattern](https://www.baeldung.com/java-observer-pattern)
- [Event-Driven Architecture](https://martinfowler.com/articles/201701-event-driven.html)
- [Outbox Pattern](https://microservices.io/patterns/data/transactional-outbox.html)
- [Dead Letter Queue](https://www.baeldung.com/spring-amqp-dead-letter)
- [At-Least-Once vs At-Most-Once vs Exactly-Once Delivery](https://www.baeldung.com/cs/message-delivery-guarantees)
- [Idempotency in Message Processing](https://www.baeldung.com/cs/idempotent-operations)

---

## Microservices Architecture

### Fundamentals

- [Microservices - Martin Fowler](https://martinfowler.com/articles/microservices.html)
- [Microservices Patterns - Chris Richardson](https://microservices.io/patterns/)
- [Monolith to Microservices - Sam Newman](https://samnewman.io/books/monolith-to-microservices/)
- [Domain-Driven Design Basics](https://martinfowler.com/bliki/DomainDrivenDesign.html)
- [Bounded Context](https://martinfowler.com/bliki/BoundedContext.html)
- [Service Decomposition Strategies](https://microservices.io/patterns/decomposition/decompose-by-business-capability.html)

### Communication

- [Synchronous vs Asynchronous Communication](https://microservices.io/patterns/communication-style/rpi.html)
- [Service Discovery - Client vs Server Side](https://microservices.io/patterns/client-side-discovery.html)
- [API Gateway Pattern](https://microservices.io/patterns/apigateway.html)
- [Backend for Frontend (BFF) Pattern](https://samnewman.io/patterns/architectural/bff/)
- [Sidecar Pattern](https://docs.microsoft.com/en-us/azure/architecture/patterns/sidecar)
- [Strangler Fig Pattern](https://martinfowler.com/bliki/StranglerFigApplication.html)

### Resilience Patterns

- [Circuit Breaker Pattern](https://martinfowler.com/bliki/CircuitBreaker.html)
- [Bulkhead Pattern](https://docs.microsoft.com/en-us/azure/architecture/patterns/bulkhead)
- [Retry Pattern with Exponential Backoff](https://www.baeldung.com/resilience4j-backoff-jitter)
- [Timeout Pattern](https://www.baeldung.com/resilience4j-timeout)
- [Fallback Pattern](https://resilience4j.readme.io/docs/fallback)
- [Resilience4j](https://resilience4j.readme.io/)

### Data Patterns

- [Saga Pattern](https://microservices.io/patterns/data/saga.html)
- [CQRS Pattern](https://microservices.io/patterns/data/cqrs.html)
- [Event Sourcing](https://martinfowler.com/eaaDev/EventSourcing.html)
- [Database per Service](https://microservices.io/patterns/data/database-per-service.html)
- [Shared Database Anti-Pattern](https://microservices.io/patterns/data/shared-database.html)

---

## Storage & CDN

### Object Storage

- [AWS S3](https://aws.amazon.com/s3/)
- [Google Cloud Storage](https://cloud.google.com/storage)
- [Azure Blob Storage](https://azure.microsoft.com/en-us/products/storage/blobs)
- [MinIO](https://min.io/) *(Open source S3-compatible)*
- [Cloudflare R2](https://www.cloudflare.com/products/r2/)

### Blob Storage Design

- [Designing a Blob Storage System - ByteByteGo](https://bytebytego.com/)
- [Pre-signed URLs for Secure File Uploads](https://docs.aws.amazon.com/AmazonS3/latest/userguide/using-presigned-url.html)
- [Chunked File Uploads](https://www.baeldung.com/java-s3-multipart-upload)
- [Deduplication Strategies](https://www.baeldung.com/cs/deduplication)

### Distributed File Systems

- [HDFS - Hadoop](https://hadoop.apache.org/docs/r1.2.1/hdfs_design.html)
- [GFS - Google File System Paper](https://static.googleusercontent.com/media/research.google.com/en//archive/gfs-sosp2003.pdf)
- [Ceph](https://ceph.io/)
- [GlusterFS](https://www.gluster.org/)

---

## Search Systems

- [Elasticsearch Architecture](https://www.elastic.co/guide/en/elasticsearch/reference/current/glossary.html)
- [Inverted Index Explained](https://www.elastic.co/blog/found-elasticsearch-from-the-bottom-up)
- [Apache Solr](https://solr.apache.org/)
- [Meilisearch](https://www.meilisearch.com/)
- [Typesense](https://typesense.org/)
- [Algolia](https://www.algolia.com/)
- [Full Text Search vs Vector Search](https://www.elastic.co/what-is/vector-search)
- [TF-IDF & BM25 Ranking](https://www.elastic.co/blog/practical-bm25-part-1-how-shards-affect-relevance-scoring-in-elasticsearch)
- [Designing a Search System - ByteByteGo](https://bytebytego.com/)
- [Typeahead / Autocomplete Design](https://www.baeldung.com/cs/autocomplete-architecture)

---

## Rate Limiting & Throttling

### Algorithms

- [Token Bucket Algorithm](https://www.baeldung.com/cs/token-bucket-vs-leaky-bucket)
- [Leaky Bucket Algorithm](https://www.baeldung.com/cs/token-bucket-vs-leaky-bucket)
- [Fixed Window Counter](https://www.baeldung.com/cs/rate-limiting-algorithms)
- [Sliding Window Log](https://www.baeldung.com/cs/rate-limiting-algorithms)
- [Sliding Window Counter](https://www.baeldung.com/cs/rate-limiting-algorithms)
- [Designing a Rate Limiter - ByteByteGo](https://bytebytego.com/courses/system-design-interview/design-a-rate-limiter)

### Implementations

- [Redis Rate Limiting](https://redis.io/glossary/rate-limiting/)
- [Nginx Rate Limiting](https://www.nginx.com/blog/rate-limiting-nginx/)
- [AWS API Gateway Throttling](https://docs.aws.amazon.com/apigateway/latest/developerguide/api-gateway-request-throttling.html)
- [Bucket4j - Java Rate Limiting](https://github.com/bucket4j/bucket4j)
- [Resilience4j Rate Limiter](https://resilience4j.readme.io/docs/ratelimiter)

---

## Authentication & Authorization at Scale

### Authentication

- [JWT - JSON Web Tokens](https://jwt.io/)
- [JWT vs Session Tokens](https://www.baeldung.com/cs/jwt-vs-session)
- [OAuth 2.0 Explained](https://oauth.net/2/)
- [OpenID Connect](https://openid.net/connect/)
- [SAML vs OAuth vs OIDC](https://www.baeldung.com/cs/saml-vs-oauth2-vs-oidc)
- [Single Sign-On (SSO)](https://www.baeldung.com/cs/sso-guide)
- [Multi-Factor Authentication (MFA)](https://www.baeldung.com/spring-security-two-factor-authentication-with-soft-token)
- [Passwordless Authentication](https://auth0.com/passwordless)

### Authorization

- [RBAC vs ABAC](https://www.baeldung.com/cs/rbac-vs-abac)
- [Role-Based Access Control (RBAC)](https://www.baeldung.com/role-and-privilege-for-spring-security-registration)
- [Attribute-Based Access Control (ABAC)](https://www.baeldung.com/spring-security-abac)
- [Zanzibar - Google's Global Auth System](https://research.google/pubs/pub48190/)
- [OPA - Open Policy Agent](https://www.openpolicyagent.org/)

### Tools

- [Keycloak](https://www.keycloak.org/)
- [Auth0](https://auth0.com/)
- [Okta](https://www.okta.com/)
- [AWS Cognito](https://aws.amazon.com/cognito/)
- [Firebase Auth](https://firebase.google.com/products/auth)
- [Supabase Auth](https://supabase.com/auth)

---

## Reliability & Fault Tolerance

### Concepts

- [SLI, SLO, SLA Explained](https://sre.google/sre-book/service-level-objectives/)
- [Availability Numbers (9s)](https://www.baeldung.com/cs/availability-vs-reliability)
- [MTTR, MTBF, MTTF](https://www.baeldung.com/cs/reliability-engineering-mtbf-mttf-mttr)
- [Fault Tolerance vs High Availability](https://www.baeldung.com/cs/fault-tolerance-vs-high-availability)
- [Chaos Engineering](https://principlesofchaos.org/)
- [Disaster Recovery Planning](https://aws.amazon.com/disaster-recovery/)

### Patterns

- [Circuit Breaker](https://martinfowler.com/bliki/CircuitBreaker.html)
- [Bulkhead](https://docs.microsoft.com/en-us/azure/architecture/patterns/bulkhead)
- [Retry with Backoff](https://aws.amazon.com/builders-library/timeouts-retries-and-backoff-with-jitter/)
- [Health Check Pattern](https://microservices.io/patterns/observability/health-check-api.html)
- [Blue-Green Deployment](https://martinfowler.com/bliki/BlueGreenDeployment.html)
- [Canary Deployment](https://martinfowler.com/bliki/CanaryRelease.html)
- [Feature Flags](https://martinfowler.com/articles/feature-toggles.html)

### Tools

- [Chaos Monkey - Netflix](https://github.com/Netflix/chaosmonkey)
- [Gremlin](https://www.gremlin.com/)
- [AWS Fault Injection Simulator](https://aws.amazon.com/fis/)
- [Litmus - Kubernetes Chaos](https://litmuschaos.io/)

---

## Monitoring & Observability

### The Three Pillars

- [Metrics, Logs, Traces - Overview](https://peter.bourgon.org/blog/2017/02/21/metrics-tracing-and-logging.html)
- [OpenTelemetry](https://opentelemetry.io/)
- [Observability vs Monitoring](https://www.baeldung.com/cs/observability-vs-monitoring)

### Metrics

- [Prometheus](https://prometheus.io/)
- [Grafana](https://grafana.com/)
- [Datadog](https://www.datadoghq.com/)
- [New Relic](https://newrelic.com/)
- [AWS CloudWatch](https://aws.amazon.com/cloudwatch/)

### Logging

- [ELK Stack - Elasticsearch, Logstash, Kibana](https://www.elastic.co/what-is/elk-stack)
- [Loki + Grafana](https://grafana.com/oss/loki/)
- [Fluentd](https://www.fluentd.org/)
- [Splunk](https://www.splunk.com/)
- [Structured Logging Best Practices](https://www.baeldung.com/java-structured-logging)

### Distributed Tracing

- [Jaeger](https://www.jaegertracing.io/)
- [Zipkin](https://zipkin.io/)
- [AWS X-Ray](https://aws.amazon.com/xray/)
- [Honeycomb](https://www.honeycomb.io/)
- [Trace Context - W3C](https://www.w3.org/TR/trace-context/)

### Alerting

- [PagerDuty](https://www.pagerduty.com/)
- [OpsGenie](https://www.atlassian.com/software/opsgenie)
- [Alertmanager - Prometheus](https://prometheus.io/docs/alerting/latest/alertmanager/)
- [On-call Best Practices - Google SRE](https://sre.google/sre-book/being-on-call/)

---

## Distributed Systems Concepts

### Core Papers & Concepts

- [Fallacies of Distributed Computing](https://en.wikipedia.org/wiki/Fallacies_of_distributed_computing)
- [The Google File System Paper](https://static.googleusercontent.com/media/research.google.com/en//archive/gfs-sosp2003.pdf)
- [Bigtable Paper](https://static.googleusercontent.com/media/research.google.com/en//archive/bigtable-osdi06.pdf)
- [Dynamo Paper - Amazon](https://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf)
- [MapReduce Paper](https://static.googleusercontent.com/media/research.google.com/en//archive/mapreduce-osdi04.pdf)
- [Spanner Paper - Google](https://static.googleusercontent.com/media/research.google.com/en//archive/spanner-osdi2012.pdf)
- [Raft Paper](https://raft.github.io/raft.pdf)

### Key Concepts

- [Distributed Transactions](https://www.baeldung.com/transactions-across-microservices)
- [Idempotency](https://www.baeldung.com/cs/idempotent-operations)
- [Distributed Locking](https://redis.io/docs/manual/patterns/distributed-locks/)
- [Leader Election](https://www.baeldung.com/cs/leader-election-algorithms)
- [Split Brain Problem](https://www.baeldung.com/cs/split-brain-problem)
- [Backpressure](https://www.baeldung.com/spring-webflux-backpressure)
- [Clock Synchronization](https://lamport.azurewebsites.net/pubs/time-clocks.pdf)

### Courses

- [MIT 6.824 Distributed Systems](https://pdos.csail.mit.edu/6.824/)
- [Designing Data-Intensive Applications - Book](https://dataintensive.net/)
- [Distributed Systems - Cambridge (Free Notes)](https://www.cl.cam.ac.uk/teaching/2122/ConcDisSys/dist-sys-notes.pdf)
- [Martin Kleppmann's Distributed Systems Course](https://martin.kleppmann.com/2020/11/18/distributed-systems-and-elliptic-curves.html)

---

## Real-World Case Studies

### Social Media & Communication

- [How WhatsApp Works - Architecture](https://highscalability.com/blog/2014/2/26/the-whatsapp-architecture-facebook-bought-for-19-billion.html)
- [Twitter Timeline Architecture](https://www.infoq.com/presentations/Twitter-Timeline-Scalability/)
- [Facebook's TAO - Social Graph](https://www.usenix.org/conference/atc13/technical-sessions/presentation/bronson)
- [Instagram Architecture](https://instagram-engineering.com/what-powers-instagram-hundreds-of-instances-dozens-of-technologies-adf2e22da2ad)
- [Discord - Storing Billions of Messages](https://discord.com/blog/how-discord-stores-billions-of-messages)
- [Slack Architecture](https://slack.engineering/flannel-an-application-level-edge-cache-to-make-slack-scale/)
- [LinkedIn Architecture](https://engineering.linkedin.com/architecture)

### Video & Media

- [Netflix Architecture](https://netflixtechblog.com/)
- [Netflix CDN - Open Connect](https://openconnect.netflix.com/)
- [YouTube Architecture](https://highscalability.com/youtube-architecture/)
- [Spotify Architecture](https://engineering.atspotify.com/)
- [Twitch Architecture](https://blog.twitch.tv/en/tags/engineering/)

### Ride-sharing & Maps

- [Uber Architecture](https://eng.uber.com/category/infrastructure/)
- [Uber's Geospatial Index - H3](https://eng.uber.com/h3/)
- [Lyft Architecture](https://eng.lyft.com/tagged/infrastructure)
- [Google Maps Architecture](https://cloud.google.com/blog/products/maps-platform)
- [Ola's Architecture at Scale](https://blog.olamoney.in/)

### E-commerce & Payments

- [Amazon's Dynamo](https://www.allthingsdistributed.com/2007/10/amazons_dynamo.html)
- [Flipkart Engineering Blog](https://tech.flipkart.com/)
- [Stripe's Architecture](https://stripe.com/blog/engineering)
- [PayPal Scalability](https://www.paypal-engineering.com/)
- [Shopify Scaling](https://shopify.engineering/)

### Search & Data

- [Google Search Architecture](https://highscalability.com/google-architecture/)
- [Elasticsearch at Scale](https://www.elastic.co/blog/)
- [Airbnb Architecture](https://medium.com/airbnb-engineering)
- [DoorDash Engineering](https://doordash.engineering/)
- [Pinterest Architecture](https://medium.com/pinterest-engineering)

---

## System Design Interview Prep

### Frameworks & Approaches

- [RESHADED Framework](https://www.baeldung.com/cs/system-design-interview)
- [How to Approach System Design - ByteByteGo](https://bytebytego.com/courses/system-design-interview/scale-from-zero-to-millions-of-users)
- [System Design Template](https://leetcode.com/discuss/career/229177/My-System-Design-Template)
- [4-Step System Design Process](https://www.techinterviewhandbook.org/system-design/)
- [Common Mistakes in System Design Interviews](https://www.baeldung.com/cs/system-design-interview)

### Estimation & Calculations

- [Back-of-the-Envelope Estimation Guide](https://bytebytego.com/courses/system-design-interview/back-of-the-envelope-estimation)
- [Latency Numbers - Jeff Dean](https://gist.github.com/jboner/2841832)
- [Storage Estimation](https://www.baeldung.com/cs/storage-estimation)
- [QPS Estimation](https://www.baeldung.com/cs/system-design-qps-estimation)
- [Powers of Two Table](https://github.com/donnemartin/system-design-primer#powers-of-two-table)

### Common Problems to Practice

- Design a URL Shortener (TinyURL / Bit.ly)
- Design Twitter / X Feed
- Design WhatsApp / Messenger
- Design YouTube / Netflix
- Design Uber / Ola (Ride Sharing)
- Design Google Drive / Dropbox
- Design Instagram
- Design a Search Autocomplete System
- Design a Web Crawler
- Design a Notification System
- Design a Rate Limiter
- Design a Distributed Cache
- Design an API Gateway
- Design a Payment System
- Design a Ticketing System (BookMyShow)
- Design a Job Scheduler
- Design a Live Streaming System
- Design a Distributed Message Queue
- Design Google Maps
- Design a Leaderboard System

### Resources for Practice

- [Grokking System Design - Educative](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers)
- [ByteByteGo](https://bytebytego.com/)
- [System Design Interview - Alex Xu (Book)](https://www.amazon.com/System-Design-Interview-insiders-Second/dp/B08CMF2CQF)
- [Pramp Mock Interviews](https://www.pramp.com/)
- [Exponent System Design Practice](https://www.tryexponent.com/)
- [interviewing.io](https://interviewing.io/)
- [System Design Questions - Glassdoor](https://www.glassdoor.com/)
- [LeetCode System Design Tag](https://leetcode.com/discuss/interview-question?currentPage=1&orderBy=hot&query=system+design)

---

## Books

### Core System Design Books

- [System Design Interview Vol.1 - Alex Xu](https://www.amazon.com/System-Design-Interview-insiders-Second/dp/B08CMF2CQF) *(Best for interviews)*
- [System Design Interview Vol.2 - Alex Xu & Sahn Lam](https://www.amazon.com/System-Design-Interview-Insiders-Guide/dp/1736049119)
- [Designing Data-Intensive Applications - Martin Kleppmann](https://dataintensive.net/) *(Best overall)*
- [Building Microservices - Sam Newman](https://www.oreilly.com/library/view/building-microservices-2nd/9781492034018/)
- [Microservices Patterns - Chris Richardson](https://microservices.io/book)

### Distributed Systems

- [Distributed Systems - Tanenbaum & Van Steen (Free)](https://www.distributed-systems.net/index.php/books/ds3/)
- [Understanding Distributed Systems - Roberto Vitillo](https://understandingdistributed.systems/)
- [Designing Distributed Systems - Brendan Burns](https://www.oreilly.com/library/view/designing-distributed-systems/9781491983638/)
- [Database Internals - Alex Petrov](https://www.databass.dev/)
- [Foundations of Scalable Systems - Ian Gorton](https://www.oreilly.com/library/view/foundations-of-scalable/9781098106058/)

### Architecture & Patterns

- [Clean Architecture - Robert C. Martin](https://www.oreilly.com/library/view/clean-architecture-a/9780134494272/)
- [Software Architecture Patterns - Mark Richards](https://www.oreilly.com/library/view/software-architecture-patterns/9781491971437/) *(Free)*
- [Patterns of Enterprise Application Architecture - Martin Fowler](https://martinfowler.com/books/eaa.html)
- [Release It! - Michael Nygard](https://pragprog.com/titles/mnee2/release-it-second-edition/)
- [The Art of Scalability - Abbott & Fisher](https://www.oreilly.com/library/view/the-art-of/9780134031408/)

### SRE & Operations

- [Site Reliability Engineering - Google (Free)](https://sre.google/sre-book/table-of-contents/)
- [The SRE Workbook - Google (Free)](https://sre.google/workbook/table-of-contents/)
- [Database Reliability Engineering - Haines & Campbell](https://www.oreilly.com/library/view/database-reliability-engineering/9781491925935/)

---

## Courses & Videos

### Free Courses & Playlists

- [MIT 6.824 Distributed Systems (Free)](https://pdos.csail.mit.edu/6.824/)
- [System Design by Gaurav Sen (YouTube)](https://www.youtube.com/@gkcs)
- [ByteByteGo YouTube Channel](https://www.youtube.com/@ByteByteGo)
- [System Design by Arpit Bhayani (YouTube)](https://www.youtube.com/@AsliEngineering)
- [Concept && Coding - Shrayansh (YouTube)](https://www.youtube.com/@ConceptandCoding)
- [TechDummies - Narendra (YouTube)](https://www.youtube.com/@TechDummiesNarendraL)
- [CodeKarle (YouTube)](https://www.youtube.com/@codekarle)
- [System Design by Amazon (YouTube)](https://www.youtube.com/results?search_query=amazon+system+design)
- [KOSS System Design (YouTube)](https://www.youtube.com/@kossiitkgp)

### Paid Courses

- [Grokking Modern System Design - Educative](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers)
- [ByteByteGo System Design Course](https://bytebytego.com/)
- [System Design Interview Course - Exponent](https://www.tryexponent.com/courses/system-design-interview)
- [Rocking System Design - Udemy](https://www.udemy.com/course/rocking-system-design/)
- [Distributed Systems & Cloud Computing - Udemy](https://www.udemy.com/course/distributed-systems-cloud-computing-with-java/)

### YouTube Channels

- [Gaurav Sen](https://www.youtube.com/@gkcs)
- [ByteByteGo](https://www.youtube.com/@ByteByteGo)
- [Arpit Bhayani](https://www.youtube.com/@AsliEngineering)
- [TechDummies Narendra](https://www.youtube.com/@TechDummiesNarendraL)
- [Concept && Coding](https://www.youtube.com/@ConceptandCoding)
- [CodeKarle](https://www.youtube.com/@codekarle)
- [Martin Kleppmann](https://www.youtube.com/@kleppmann)
- [InfoQ](https://www.youtube.com/@InfoQ)
- [Hussein Nasser](https://www.youtube.com/@hnasr)

---

## Cheat Sheets & Quick References

- [System Design Cheat Sheet - GitHub](https://github.com/donnemartin/system-design-primer)
- [Latency Numbers Every Engineer Should Know](https://gist.github.com/jboner/2841832)
- [Back-of-the-Envelope Estimation Cheat Sheet](https://bytebytego.com/courses/system-design-interview/back-of-the-envelope-estimation)
- [CAP Theorem Cheat Sheet](https://www.baeldung.com/cs/cap-theorem)
- [SQL vs NoSQL Decision Chart](https://www.baeldung.com/cs/sql-vs-nosql)
- [Load Balancing Algorithm Summary](https://www.cloudflare.com/learning/performance/types-of-load-balancing-algorithms/)
- [Caching Strategies Summary](https://codeahoy.com/2017/08/11/caching-strategies-and-how-to-choose-the-right-one/)
- [Availability Numbers (Nines)](https://en.wikipedia.org/wiki/High_availability#Percentage_calculation)
- [Microservices Patterns Map](https://microservices.io/patterns/)
- [API Design Best Practices - Microsoft](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)
- [Data Consistency Levels](https://jepsen.io/consistency)
- [Message Delivery Guarantees](https://www.baeldung.com/cs/message-delivery-guarantees)

---

## Diagramming & Architecture Tools

### Diagramming

- [Excalidraw](https://excalidraw.com/) *(Best for whiteboard-style)*
- [draw.io / diagrams.net](https://www.diagrams.net/)
- [Lucidchart](https://www.lucidchart.com/)
- [Miro](https://miro.com/)
- [Whimsical](https://whimsical.com/)
- [PlantUML](https://plantuml.com/)
- [Mermaid.js](https://mermaid.js.org/)
- [Structurizr](https://structurizr.com/) *(C4 model)*
- [C4 Model](https://c4model.com/)

### Load Testing

- [Apache JMeter](https://jmeter.apache.org/)
- [Gatling](https://gatling.io/)
- [k6](https://k6.io/)
- [Locust](https://locust.io/)
- [Artillery](https://www.artillery.io/)
- [wrk](https://github.com/wg/wrk)

### Network & API Tools

- [Postman](https://www.postman.com/)
- [Insomnia](https://insomnia.rest/)
- [Wireshark](https://www.wireshark.org/)
- [curl](https://curl.se/)
- [HTTPie](https://httpie.io/)

---

## GitHub Repositories

- [System Design Primer - donnemartin](https://github.com/donnemartin/system-design-primer) *(270k+ stars)*
- [Awesome System Design](https://github.com/madd86/awesome-system-design)
- [System Design Resources - InterviewReady](https://github.com/InterviewReady/system-design-resources)
- [Awesome Scalability](https://github.com/binhnguyennus/awesome-scalability)
- [Distributed Systems Reading List](https://github.com/theanalyst/awesome-distributed-systems)
- [ByteByteGo Newsletter Code](https://github.com/ByteByteGoHq/system-design-101)
- [System Design 101 - ByteByteGo](https://github.com/ByteByteGoHq/system-design-101)
- [Microservices Patterns - Chris Richardson](https://github.com/microservices-patterns/ftgo-application)
- [Real World System Design](https://github.com/relogX/system-design-questions)
- [Grokking System Design - Solutions](https://github.com/sharanyaa/grok_sdi_educative)

---

## Engineering Blogs

### Must-Read Company Blogs

- [Netflix Tech Blog](https://netflixtechblog.com/)
- [Uber Engineering](https://eng.uber.com/)
- [Airbnb Engineering](https://medium.com/airbnb-engineering)
- [Meta Engineering](https://engineering.fb.com/)
- [Google Research Blog](https://research.google/blog/)
- [AWS Architecture Blog](https://aws.amazon.com/blogs/architecture/)
- [LinkedIn Engineering](https://engineering.linkedin.com/)
- [Stripe Engineering](https://stripe.com/blog/engineering)
- [Cloudflare Blog](https://blog.cloudflare.com/)
- [Discord Engineering](https://discord.com/blog/engineering)
- [Shopify Engineering](https://shopify.engineering/)
- [Dropbox Tech Blog](https://dropbox.tech/)
- [DoorDash Engineering](https://doordash.engineering/)
- [Pinterest Engineering](https://medium.com/pinterest-engineering)
- [Twitter Engineering](https://blog.twitter.com/engineering)
- [Slack Engineering](https://slack.engineering/)
- [GitHub Engineering](https://github.blog/category/engineering/)
- [High Scalability](http://highscalability.com/) *(Aggregates case studies)*

---

## Newsletters & Podcasts

### Newsletters

- [ByteByteGo Newsletter](https://blog.bytebytego.com/)
- [System Design Newsletter - Neo Kim](https://newsletter.systemdesign.one/)
- [Quastor - System Design](https://quastor.org/)
- [Software Design - Arpit Bhayani](https://arpitbhayani.me/newsletter)
- [The Pragmatic Engineer - Gergely Orosz](https://newsletter.pragmaticengineer.com/)
- [Architecture Notes](https://architecturenotes.co/)
- [Level Up Software Engineering](https://levelupsoftwareengineering.substack.com/)
- [Pointer.io](https://www.pointer.io/)

### Podcasts

- [Software Engineering Daily](https://softwareengineeringdaily.com/)
- [The Changelog](https://changelog.com/)
- [Distributed - InfoQ Podcast](https://www.infoq.com/the-infoq-podcast/)
- [SE Radio](https://se-radio.net/)
- [Scaling DevTools](https://podcast.scaling-devtools.com/)
- [Kubernetes Podcast](https://kubernetespodcast.com/)

---

## Communities & Forums

- [r/ExperiencedDevs](https://www.reddit.com/r/ExperiencedDevs/)
- [r/softwarearchitecture](https://www.reddit.com/r/softwarearchitecture/)
- [r/cscareerquestions](https://www.reddit.com/r/cscareerquestions/)
- [r/SystemDesign](https://www.reddit.com/r/SystemDesign/)
- [Blind - Tech](https://www.teamblind.com/)
- [LeetCode Discuss - System Design](https://leetcode.com/discuss/interview-question?currentPage=1&orderBy=hot&query=system+design)
- [High Scalability Community](http://highscalability.com/)
- [InfoQ Community](https://www.infoq.com/)
- [Dev.to - System Design](https://dev.to/t/architecture)
- [Hacker News](https://news.ycombinator.com/)

---

## Key Articles & Essays

### Must-Read

- [The Log - Jay Kreps (LinkedIn)](https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying)
- [You Can't Sacrifice Partition Tolerance - CAP](https://codahale.com/you-cant-sacrifice-partition-tolerance/)
- [Fallacies of Distributed Computing](https://en.wikipedia.org/wiki/Fallacies_of_distributed_computing)
- [A Plain English Introduction to CAP Theorem](http://ksat.me/a-plain-english-introduction-to-cap-theorem)
- [Microservices - Martin Fowler](https://martinfowler.com/articles/microservices.html)
- [CQRS - Martin Fowler](https://martinfowler.com/bliki/CQRS.html)
- [Event Sourcing - Martin Fowler](https://martinfowler.com/eaaDev/EventSourcing.html)

### Architecture Thinking

- [The Twelve-Factor App](https://12factor.net/)
- [C4 Model for Software Architecture](https://c4model.com/)
- [Evolutionary Architecture - Martin Fowler](https://martinfowler.com/articles/is-quality-worth-cost.html)
- [Cell-Based Architecture - AWS](https://aws.amazon.com/solutions/guidance/cell-based-architecture-on-aws/)
- [Zero Downtime Deployments](https://www.baeldung.com/java-zero-downtime-deployment)
- [The Senior Engineer's Guide to Design Decisions](https://www.kitchensoap.com/2012/10/25/on-being-a-senior-engineer/)

---

## Practice Problems

### Beginner Systems

- Design a URL Shortener
- Design a Pastebin
- Design a Key-Value Store
- Design a Rate Limiter
- Design a Cache System

### Intermediate Systems

- Design a Chat Application (WhatsApp)
- Design a Social Media Feed (Twitter)
- Design a Photo Sharing App (Instagram)
- Design a File Storage System (Dropbox)
- Design a Video Streaming Service (YouTube)
- Design a Notification System
- Design a Search Autocomplete

### Advanced Systems

- Design Uber / Ola
- Design a Distributed Message Queue (Kafka)
- Design a Distributed Cache (Redis)
- Design a Web Crawler
- Design Google Maps
- Design a Payment System
- Design a Live Video Streaming System (Twitch)
- Design an Ad Click Aggregation System
- Design a Hotel Booking System (MakeMyTrip)
- Design a Flight Booking System
- Design a Stock Exchange System
- Design a Distributed Job Scheduler

---



## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:

1. **Add a Resource** — Found a useful library, course, or article? Submit a pull request!
2. **Fix Broken Links** — Help keep the list current
3. **Improve Descriptions** — Make resources easier to understand
4. **Suggest Categories** — Help us organize better

### Contribution Guidelines

- Ensure the resource is relevant to Python development
- Provide a working link
- Add a brief description if needed
- Place it in the appropriate category
- Check for duplicates before submitting

---

## Sponsorship

If you find this repository valuable and want to support its growth:

- Sponsor this project to help maintain and expand the collection
- Partner with us to feature high quality tools for founders
- Reach out for collaborations and ecosystem partnerships

For sponsorship or partnership inquiries, connect via X:  
[Avinash Singh](https://x.com/AvinashSingh_20)

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

##  Acknowledgments

This repository is maintained by [Avinash Singh](https://x.com/AvinashSingh_20) Special thanks to all contributors who have helped curate and maintain this collection.

## 💬 Community & Support

- Star this repo to show your support
- Share it with fellow founders and entrepreneurs
- Follow for updates as we add new resources
- Join the discussion in [Issues](https://github.com/avinash201199/System-Design-KIT/issues)

---

**Made with ❤️ by [Avinash Singh](https://x.com/AvinashSingh_20)**

