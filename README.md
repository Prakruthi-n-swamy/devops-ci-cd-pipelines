# devops-ci-cd-pipelines
Collection of Jenkins and GitHub Actions pipeline templates inspired by production DevOps workflows.

## Included Pipelines

### Spring Boot

- Build
- Unit Test
- Docker Build

### Next.js

- Install
- Lint
- Build

### Security

- Snyk Scan
- Checkmarx Scan

## Tools

- Jenkins
- GitHub Actions
- Docker
- Maven
- NodeJS

## Pipeline Flow

```text
Code Commit
    ↓
Build
    ↓
Unit Tests
    ↓
Security Scan
    ↓
Docker Build
    ↓
Deployment
    ↓
Validation
```

## Future Enhancements

- Slack Notifications
- Kubernetes Deployment
- SonarQube Integration
- Terraform Deployment Stage
