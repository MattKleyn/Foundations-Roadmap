# Software Project Compliance & Standards Checklist

## 1. Data Protection
[ ] Have you identified all personal data collected?
[ ] Is data minimized (only what is necessary)?
[ ] Is sensitive data encrypted at rest?
[ ] Is all data encrypted in transit (HTTPS/TLS)?
[ ] Are retention & deletion policies defined?
[ ] Are POPIA/GDPR rights supported (access, deletion, correction)?

## 2. Security
[ ] OWASP Top 10 reviewed and applied
[ ] Input validation & sanitization implemented
[ ] Authentication secure (no plaintext passwords, strong hashing)
[ ] Authorization enforced at every endpoint
[ ] Secrets stored securely (env vars, AWS Secrets Manager)
[ ] Logging avoids storing PII
[ ] Rate limiting implemented
[ ] Error messages do not leak sensitive info

## 3. Cloud & Infrastructure
[ ] IAM roles follow least privilege
[ ] Network security groups configured
[ ] Backups configured
[ ] Monitoring & alerting enabled
[ ] Audit logs enabled
[ ] Infrastructure documented

## 4. API & Architecture
[ ] API documented (OpenAPI/Swagger)
[ ] Versioning strategy defined
[ ] Idempotency for critical endpoints
[ ] Consistent error handling
[ ] No circular dependencies
[ ] Architecture diagrams updated

## 5. Legal & Regulatory
[ ] POPIA compliance verified
[ ] ECTA requirements met (e-commerce, signatures, transactions)
[ ] CPA compliance for consumer-facing systems
[ ] PCI DSS considerations (if payments)
[ ] Data breach response plan defined

## 6. Operational Readiness
[ ] CI/CD pipeline secure
[ ] Dependency scanning enabled
[ ] Vulnerability scanning enabled
[ ] Logging & monitoring dashboards created
[ ] Incident response workflow defined

## 7. Documentation
[ ] README updated
[ ] Architecture docs updated
[ ] ADRs created for major decisions
[ ] Compliance notes included
