# Foundations Roadmap (21 Weeks)
A comprehensive, stack‑agnostic Computer Science + Software Engineering fundamentals curriculum designed to build deep understanding that transcends frameworks, languages, and trends.

* Security, testing, architecture, cloud, OS, networking, and language theory are integrated throughout.

# DOMAIN 1 — JavaScript Internals & Runtime Mechanics (Weeks 1–3)
## Security Focus
- Prototype pollution
- DOM-based XSS
- Event loop abuse (DoS)

## Week 1 — Execution Model & Memory
- Execution context
- Call stack
- Stack vs heap
- Primitive vs reference types
- Garbage collection
- Memory leaks
- Stack overflow
- Hoisting
- Scope chain
- Closures

## Exercises
- Trigger stack overflow
- Build closure utilities
- Draw memory diagrams

## Week 2 — Event Loop & Concurrency
- Event loop
- Microtasks vs macrotasks
- Promises
- Async/await
- Generators
- Scheduling & concurrency behavior

## Exercises
- Predict event loop output
- Implement a mini Promise
- Build a microtask scheduler

## Week 3 — React Internals
- Virtual DOM
- Fiber architecture
- Reconciliation
- Rerender triggers
- State batching
- Closure pitfalls

## Exercises
- Build a tiny React clone
- Build a custom hook
- Fix unnecessary rerenders

# DOMAIN 2 — Browser Internals & Web Performance (Weeks 4–5)
## Security Focus
- CORS
- CSP
- SameSite cookies
- Secure cookie flags
- Clickjacking

## Week 4 — Browser Architecture
- Critical rendering path
- DOM & CSSOM construction
- Render tree
- Layout vs paint vs composite
- Reflows
- GPU acceleration
- Event delegation

## Exercises
- Measure layout thrashing
- Optimize a slow page
- Use DevTools Performance tab

## Week 5 — Networking & Performance
- DNS
- TCP handshake
- TLS
- HTTP/1.1 vs HTTP/2 vs HTTP/3
- Caching
- CDNs
- TTFB
- Preload, prefetch, preconnect
- Compression (gzip, brotli)

## Exercises
- Measure TTFB
- Add preconnect/preload
- Compare HTTP versions

# DOMAIN 3 — Algorithms & Data Structures (Weeks 6–7)
## Security Focus
- Hash collision DoS
- Regex DoS
- Algorithmic complexity attacks

## Week 6 — Core Data Structures
- Arrays
- Linked lists
- Stacks
- Queues
- Hash maps
- Trees
- Graphs and graph theory
- Sets and set theory

## Exercises
- Implement each DS
- Solve 10–15 DS problems

## Week 7 — Algorithms
- Time complexity (big O, big Theta, big Omega)
- Sorting
- Searching
- Recursion
- Sliding window
- Two pointers
- BFS/DFS
- Intro to dynamic programming

## Exercises
- 20–30 algorithm problems
- BFS/DFS visualizer

# DOMAIN 4 — Backend Architecture & System Design (Weeks 8–10)
## Security Focus
- SQL & NoSQL injection
- Input validation
- Sanitization
- AuthN vs AuthZ
- Rate limiting
- Secrets management
- OWASP Top 10
- Secure API design
- Sensitive logging practices

## Week 8 — Architecture Fundamentals
- Coupling vs cohesion
- Layered architecture
- Ports & Adapters (Hexagonal)
- Dependency inversion
- API design
- DTOs
- Repositories
- Domain vs application logic

## Exercises
- Refactor Dev Frog Blog
- Add DTOs & repository interfaces

## Week 9 — Databases & Caching
- Indexes
- Query optimization
- Transactions
- Isolation levels
- ACID
- CAP theorem
- Consistency models
- Redis
- Caching strategies

## Exercises
- Add caching to JoSe
- Analyze slow queries

## Week 10 — System Design
- Load balancing
- Horizontal vs vertical scaling
- Stateless servers
- Message queues
- Event-driven architecture
- Idempotency
- Multi-region architecture

## Exercises
- Design JoSe as a distributed system
- Architecture diagrams

# DOMAIN 5 — DevOps, Cloud & Deployment (Weeks 11–13)
## Security Focus
- IAM
- Least privilege
- Security groups
- HTTPS & TLS
- Secrets Manager
- KMS
- Secure CI/CD
- Dependency scanning
- Container security

## Week 11 — DevOps Basics
- Linux
- SSH
- Environment variables
- Logging
- Monitoring
- CI/CD
- Docker

## Exercises
- Dockerize Dev Frog Blog
- Add CI/CD

## Week 12 — Cloud Practitioner (AWS)
- IAM
- EC2
- S3
- RDS
- Lambda
- API Gateway
- CloudWatch
- VPC basics

## Exercises
- Deploy Dev Frog Blog
- Deploy ML microservice

## Week 13 — Cloud Architecture
- Serverless patterns
- Event-driven pipelines
- SQS
- Step Functions
- DynamoDB
- Cloud-native ETL

## Exercises
- Begin JoSe migration
- Build LLM Lambda microservice

# DOMAIN 6 — Software Engineering Practices (Weeks 14–16)
## Security Focus
- Secure coding patterns
- Threat modelling
- SAST & DAST
- Dependency audits
- Security logging

## Week 14 — Clean Code & Patterns
- SOLID
- DRY
- KISS
- YAGNI
- Composition vs inheritance
- Strategy pattern
- Factory pattern
- Observer pattern

## Exercises
- Refactor JoSe
- Add dependency inversion

## Week 15 — Testing
- Unit tests
- Integration tests
- E2E tests
- Mocking
- Test doubles
- Coverage
- Contract testing
- Property-based testing

## Exercises
- Add tests to Dev Frog Blog
- Add tests to JoSe

## Week 16 — Documentation & Professionalism
- README structure
- Architecture docs
- ADRs
- API documentation
- Versioning
- Git branching strategies
- Semantic versioning
- Release management

## Exercises
- Document JoSe
- Add architecture diagrams

# DOMAIN 7 — Security Fundamentals (Week 17)
## Week 17 — Security Fundamentals
- Secure coding checklist
- Common vulnerabilities
- Threat modeling
- PortSwigger labs
- Secure login flows
- Hardening techniques

## Exercises
- Build secure login
- Harden Dev Frog Blog
- Harden JoSe

# DOMAIN 8 — Programming Paradigms (Week 18)
## Week 18 — Paradigms & Language Theory
- Procedural
- OOP
- Functional
- Declarative
- Imperative
- Event-driven
- Concurrency and parrallelism
- Asyncronous programming
- Reactive
- Actor model
- Immutability
- Pure functions
- Composition vs inheritance

## Exercises
- Rebuild a feature in 3 paradigms
- Convert OOP → FP

# DOMAIN 9 — Language Tradeoffs & Stack Selection (Week 19)
## Week 19 — Choosing a Tech Stack
- Python vs JS vs Java vs C# vs Go vs Rust vs C++
- Dynamic vs static typing
- GC vs manual memory
- Concurrency models
- Performance characteristics
- Ecosystem maturity
- Deployment models
- When to choose what

## Exercises
- Build a stack selection matrix
- Choose stacks for 3 hypothetical projects

# DOMAIN 10 — OS & Networking Fundamentals (Week 20)
## Week 20 — OS + Networking
- Processes & threads
- Scheduling
- System calls
- Virtual memory
- Paging
- File systems
- Sockets
- TCP vs UDP
- DNS
- TLS
- WebSockets
- Reverse proxies (Nginx)

## Exercises
- Build a tiny TCP server
- Inspect system calls
- Configure Nginx reverse proxy

# DOMAIN 11 — Scalability & Maintainability (Week 21)
## Week 21 — Scalability & Maintainability
### Scalability
- Throughput vs latency
- Load testing
- Stress testing
- Bottleneck analysis
- Horizontal vs vertical scaling
- Database scaling
- Caching layers
- Queue-based scaling
- CDN scaling
- Cost-based scaling

### Maintainability
- Cyclomatic complexity
- Coupling & cohesion
- Code churn
- Bus factor
- Test quality
- Architecture boundaries
- Refactoring strategies
- Technical debt management

## Exercises
- Maintainability audit of Dev Frog Blog
- Identify bottlenecks in JoSe
- Write a scalability plan for your ML microservice
