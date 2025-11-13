# Lab 11 – CI/CD Pipeline and Monitoring

## Prerequisites
- Docker & Docker Compose
- GitHub account with Actions enabled
- Docker Hub account

## Setup
1. Clone the repo
   ```bash
   git clone <repo-url> && cd Lab11-CICD-Monitoring
   ```
2. Add GitHub secrets:
   - DOCKER_USERNAME
   - DOCKER_PASSWORD

3. Push code to trigger CI/CD pipeline.

## Local Run
```bash
docker-compose up -d
```

## Monitoring Stack
```bash
docker-compose -f docker-compose.monitoring.yml up -d
```

## Access URLs
- Frontend → http://localhost:8080
- Backend → http://localhost:4000/status
- Prometheus → http://localhost:9090
- Grafana → http://localhost:3000 (admin / admin)
