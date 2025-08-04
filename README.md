# CI/CD Node.js App with Docker

This is a simple Node.js application that demonstrates automated build and deployment using GitHub Actions and Docker.

##  Tech Stack
- Node.js
- Docker
- GitHub Actions

##  How it Works
1. Code is pushed to the `main` branch.
2. GitHub Actions:
   - Installs dependencies
   - Runs tests
   - Builds Docker image
   - Pushes image to Docker Hub

##  Docker
Build and run locally:
```bash
docker build -t yourusername/ci-cd-node-app .
docker run -p 3000:3000 yourusername/ci-cd-node-app
