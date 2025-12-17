# Git-to-Docker CI Pipeline

## Project Summary

The **Git-to-Docker CI Pipeline** is a DevOps-focused project that demonstrates how a simple Python application can be containerized, validated, and automatically published as a Docker image using a fully automated CI workflow.

The project follows a production-aligned approach where every code change pushed to the `main` branch triggers a GitHub Actions pipeline that:
- Lints the Dockerfile using best practices
- Builds a Docker image in a clean CI environment
- Securely authenticates with Docker Hub using access tokens
- Pushes the image to a public Docker Hub repository

All Docker image publishing is handled exclusively through CI, eliminating manual builds and ensuring a reproducible, auditable artifact lifecycle.

This project is designed to showcase core DevOps concepts such as containerization, CI automation, secure credential management, and environment-independent application delivery.

## Key Technologies
- Python
- Docker
- GitHub Actions
- Docker Hub
- Hadolint

## Documentation
Detailed technical documentation, architecture explanations, and implementation steps are available in the [`docs/`](./docs) directory.

---

*This repository is part of a structured DevOps learning and portfolio-building initiative, with future projects expanding into Kubernetes, CI/CD releases, and Infrastructure as Code.*

---
