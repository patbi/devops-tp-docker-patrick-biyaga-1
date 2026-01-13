# TP DevSecOps avec Docker

![Build and Scan](https://github.com/patbi/devops-tp-docker-patrick-biyaga-1/actions/workflows/docker-deploy.yml/badge.svg)
[![CodeQL](https://github.com/patbi/devops-tp-docker-patrick-biyaga-1/workflows/CodeQL/badge.svg)](https://github.com/patbi/devops-tp-docker-patrick-biyaga-1/actions?query=workflow%3ACodeQL "Code quality workflow status")

## Pipeline DevSecOps

Ce projet implémente un pipeline CI/CD sécurisé pour Docker avec :

- Analyse statique du code (CodeQL)
- Lint du Dockerfile (Hadolint)
- Scan de l'image Docker (Trivy)
- Scan des dépendances (Dependabot)
- Secret Scanning
- Security Gates (blocage sur vulnérabilités critiques)
- SBOM (Software Bill of Materials)

## Architecture de Sécurité