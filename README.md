# Jenkins CI/CD with Docker Compose

[![Docker](https://img.shields.io/badge/docker-ready-blue.svg)](https://www.docker.com/)
[![License: Apache-2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)

A simple setup to run Jenkins in a containerized environment using **Docker Compose**. This repository helps you get Jenkins up and running locally for CI/CD experimentation and automation workflows.

---

## 📦 What's Included?

- `docker-compose.yml`: Jenkins LTS container with persistent volume
- `jenkins_home/`: Data directory (automatically created) for persistent Jenkins configuration
- Pre-configured ports and volume mappings

---

## 🚀 Getting Started

### Prerequisites

Make sure you have:

- Docker
- Docker Compose

### Run Jenkins

```bash
docker-compose up -d
