# 🚀 Production-Ready Spring Boot: Masterclass

[![Java 21](https://img.shields.io/badge/Java-25-orange.svg)](https://openjdk.org/projects/jdk/25/)
[![Spring Boot 4.x](https://img.shields.io/badge/Spring%20Boot-4.0-brightgreen.svg)](https://spring.io/projects/spring-boot)
[![Docker](https://img.shields.io/badge/Docker-Enabled-blue.svg)](https://www.docker.com/)
[![YouTube Channel](https://img.shields.io/badge/YouTube-JDev%20Production%20Ready-red.svg)]([https://youtube.com@jdev-prod-ready/videos](https://www.youtube.com/@jdev-prod-ready/videos))
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Welcome to the official source code repository for the **Production-Ready Spring Boot Series**. Each directory contains an isolated, runnable, industry-grade implementation designed for zero-friction local execution.

---

## 🛠️ Prerequisites & Local Setup

Ensure the following tools are installed before running any module:

* **JDK 21+** (Azul Zulu or Temurin recommended)
* **Docker Desktop** / **Rancher Desktop** (with Docker CLI enabled)
* **Maven 3.9+** (or use `./mvnw` inside individual module directories)
* **HTTP Client** (Postman, Bruno, or IntelliJ HTTP Client)

```bash
# Clone the repository
git clone [https://github.com/your-username/spring-boot-masterclass.git](https://github.com/your-username/spring-boot-masterclass.git)
cd spring-boot-masterclass
```

### ⚡ How to Run Any Module
To run any individual weekly tutorial, navigate into its folder and execute using Maven wrapper or Docker Compose:

```Bash
# Example: Running Week 01 (Testcontainers Setup)
cd q1-zero-config-dev-experience/01-testcontainers-setup

# Run tests
./mvnw clean test

# Run application locally
./mvnw spring-boot:run
```

### 🤝 Community & Support

YouTube Channel: JDev Production Ready - https://www.youtube.com/@jdev-prod-ready
Report an Issue: Found a bug in a code sample? Open an Issue.
Pull Requests: PRs are welcome for typo fixes and dependency upgrades.

### 📄 License
This repository is licensed under the MIT License. Free to use for personal learning, enterprise reference, or teaching purposes.


<FollowUp label="Want me to generate GitHub Actions CI workflows for automated testing?" query="Generate GitHub Actions workflow YAML files to run tests across all quarterly module directories automatically."/>