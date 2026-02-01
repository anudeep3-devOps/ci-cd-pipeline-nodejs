# ci-cd-pipeline-nodejs
# Production CI/CD Pipeline – Node.js Application

## Use Case
A web application requiring automated builds, quality enforcement,
security scanning, and container-based deployment.

## DevOps Objectives
- Automate CI/CD pipeline
- Enforce code quality and security
- Enable reliable container deployment

## Architecture
GitHub → Jenkins → SonarQube → Security Scans → Docker → Deployment VM

## Pipeline Stages
1. Code Checkout
2. Dependency Installation
3. Static Code Analysis (SonarQube)
4. Quality Gate Enforcement
5. Vulnerability Scanning (Trivy, OWASP Dependency Check)
6. Docker Image Build & Tagging
7. Image Push to DockerHub
8. Container Deployment

## Tools Used
- Jenkins
- Docker
- SonarQube
- Trivy
- OWASP Dependency Check
- Linux (Ubuntu)

## Outcome
- Fully automated deployment workflow
- Fail-fast pipeline with enforced quality gates
- Production-ready container image lifecycle
