# DevOps & Reliability Pack

Production reliability, security governance, and interface validation for software engineering and site reliability teams. Parses container crash logs to generate blameless postmortems, audits dependency lockfiles for known CVE advisories, and builds standardized OpenAPI specifications.

## Included Agents

- **Log & Incident Analyzer (`log-incident-analyzer`):** Parses server error logs, Docker traces, and system dumps to reconstruct timeline sequences, pinpoint root causes, and draft postmortems.
- **CVE & Dependency Auditor (`cve-auditor`):** Audits project package lockfiles and container manifests against public vulnerability advisories, generating prioritized upgrade plans.
- **API Spec & Mock Builder (`api-spec-builder`):** Inspects backend route definitions and database schemas to generate valid OpenAPI 3.1 specifications, TypeScript interfaces, and mock fixtures.

## Included Workflow

- **Incident and Release Audit (`incident-and-release-audit`):** Pinpoints runtime errors from crash logs, audits dependency security posture, and verifies API contracts prior to deployment.
