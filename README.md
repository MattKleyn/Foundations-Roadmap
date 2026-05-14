# DOMAIN 1 — JavaScript Internals & Runtime Mechanics (Weeks 1–3)
## Week 1 — Execution Model & Memory
- Execution context
- Call stack
- Stack vs heap
- Primitive vs reference types
- Garbage collection
- Memory leaks
- Stack overflow (why it happens)
- Hoisting
- Scope chain
- Closures

## Exercises:
- Write code that intentionally causes stack overflow
- Build closure-based utilities
- Visualize memory with diagrams

## Week 2 — Event Loop & Concurrency
- vent loop
- Microtasks vs macrotasks
- Promises
- Async/await
- Generators
- How JS schedules work
- Why async code behaves the way it does

## Exercises:
- Predict event loop output
- Build your own Promise implementation (mini version)
- Build a scheduler with setTimeout + microtasks

## Week 3 — React Internals (the missing layer)
- Virtual DOM
- Fiber architecture
- Reconciliation
- When React triggers rerenders
- Why rerenders happen
- How state batching works
- Why closures cause stale state bugs

## Exercises:
- Build a tiny React clone (50–100 lines)
- Build a custom hook
- Build a component that intentionally causes unnecessary rerenders and fix it

# DOMAIN 2 — Browser Internals & Web Performance (Weeks 4–5)
## Week 4 — Browser Architecture
- Critical rendering path
- DOM construction
- CSSOM construction
- Render tree
- Layout vs paint vs composite
- Reflows
- GPU acceleration
- Event delegation

## Exercises:
- Build a page and measure layout thrashing
- Optimize a slow page
- Use Chrome DevTools Performance tab

## Week 5 — Networking & Performance
- DNS
- TCP handshake
- TLS
- HTTP/1.1 vs HTTP/2 vs HTTP/3
- Caching
- CDNs
- Time To First Byte (TTFB)
- Preload, prefetch, preconnect
- Compression (gzip, brotli)

## Exercises:
- Measure TTFB on your portfolio
- Add preconnect/preload to optimize it
- Compare HTTP/1.1 vs HTTP/2 waterfall

# DOMAIN 3 — Algorithms & Data Structures (Weeks 6–7)
## Week 6 — Core Data Structures
- Arrays
- Linked lists
- Stacks
- Queues
- Hash maps
- Trees
- Graphs

## Exercises:
- Implement each DS from scratch
- Solve 10–15 problems using each

## Week 7 — Algorithms
- Sorting
- Searching
- Recursion
- Sliding window
- Two pointers
- BFS/DFS
- Dynamic programming (light)

## Exercises:
- 20–30 algorithm problems
- Build a small visualization tool for BFS/DFS

# DOMAIN 4 — Backend Architecture & System Design (Weeks 8–10)
## Week 8 — Architecture Fundamentals
- Coupling vs cohesion
- Layered architecture
- Ports & Adapters (Hexagonal)
- Dependency inversion
- API design
- DTOs
- Repositories
- Domain logic vs application logic

## Exercises:
- Refactor Dev Frog Blog into a clean layered architecture
- Add DTOs and repository interfaces

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

## Exercises:
- Add caching to JoSe
- Analyze slow queries in your apps

## Week 10 — System Design
- Load balancing
- Horizontal vs vertical scaling
- Stateless servers
- Message queues
- Event-driven architecture
- Rate limiting
- Idempotency
- Multi-region architecture

## Exercises:
- Design JoSe as a distributed system
- Draw architecture diagrams

# DOMAIN 5 — DevOps, Cloud & Deployment (Weeks 11–13)
## Week 11 — DevOps Basics
- Linux
- SSH
- Environment variables
- Logging
- Monitoring
- CI/CD
- Docker

## Exercises:
- Dockerize Dev Frog Blog
- Add CI/CD with GitHub Actions

## Week 12 — Cloud Practitioner (AWS)
- IAM
- EC2
- S3
- RDS
- Lambda
- API Gateway
- CloudWatch
- VPC basics

## Exercises:
- Deploy Dev Frog Blog to Vercel
- Deploy ML microservice to AWS Lambda

## Week 13 — Cloud Architecture
- Serverless patterns
- Event-driven pipelines
- SQS
- Step Functions
- DynamoDB
- Cloud-native ETL

## Exercises:
- Begin migrating JoSe to AWS
- Build a Lambda-based LLM microservice

# DOMAIN 6 — Software Engineering Practices (Weeks 14–16)
## Week 14 — Clean Code & Patterns
- SOLID
- DRY
- KISS
- YAGNI
- Composition vs inheritance
- Strategy pattern
- Factory pattern
- Observer pattern

## Exercises:
- Refactor JoSe using strategy pattern
- Add dependency inversion

## Week 15 — Testing
- Unit tests
- Integration tests
- E2E tests
- Mocking
- Test doubles
- Coverage

## Exercises:
- Add tests to Dev Frog Blog
- Add tests to JoSe

## Week 16 — Documentation & Professionalism
- README structure
- Architecture docs
- ADRs (Architecture Decision Records)
- API documentation
- Versioning
- Git branching strategies

## Exercises:
- Write full documentation for JoSe
- Add architecture diagrams
