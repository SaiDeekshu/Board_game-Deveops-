# 🎲 BoardgameListingWebApp
  A full-stack Board Game Listing and Review Web Application built using Java and Spring Boot, integrated with DevOps tools for CI/CD automation, code quality analysis, artifact management, containerization, cloud deployment, and monitoring.

## 🛠️ Technologies Used

- **Backend:** Java, Spring Boot, Spring MVC, Spring Security, JDBC
- **Frontend:** Thymeleaf, HTML5, CSS, JavaScript, Bootstrap
- **Database:** H2 Database
- **Testing:** JUnit
- **Build Tool:** Maven
- **Version Control:** Git, GitHub
- **CI/CD:** Jenkins
- **Code Quality:** SonarQube
- **Artifact Management:** Nexus Repository Manager
- **Containerization:** Docker
- **Cloud Deployment:** AWS EC2
- **Infrastructure Automation:** Terraform, Ansible
- **Container Orchestration:** Kubernetes (AWS EKS)
- **Monitoring:** Prometheus, Grafana, Blackbox Exporter

## ✨ Features

- Browse board games and reviews.
- Secure authentication and role-based authorization.
- Users can add board games and write reviews.
- Managers can edit and delete reviews.
- CRUD operations and database connectivity.
- Responsive UI using Thymeleaf and Bootstrap.
- Unit testing using JUnit.
- Automated CI/CD pipeline.
- Docker-based application containerization.
- AWS deployment and application monitoring.

## 🔄 CI/CD Pipeline

The pipeline automates application building, testing, code quality analysis, artifact management, containerization, deployment, and monitoring.

```text
GitHub Repository
        |
        v
Jenkins (CI/CD)
        |
        v
Maven (Build and Test)
        |
        v
SonarQube (Code Analysis)
        |
        v
Nexus (Artifact Management)
        |
        v
Docker (Image Build)
        |
        v
Container Registry
        |
        v
AWS EC2 / AWS EKS (Deployment)
        |
        v
Prometheus (Monitoring)
        |
        v
Grafana (Dashboards)

Terraform → Infrastructure Provisioning
Ansible   → Configuration Management
Blackbox Exporter → Endpoint Monitoring
```

## 🔐 Sample Login Credentials

| Role | Username | Password |
|---|---|---|
| User | `bugs` | `bunny` |
| Manager | `daffy` | `duck` |

*Note: These credentials work only if the corresponding sample accounts are configured in the application.*

## 🔮 Future Enhancements

- Integrate automated security and vulnerability scanning.
- Replace the in-memory H2 database with persistent production storage.
- Implement automated deployment and rollback strategies.
- Enhance application security and scalability.
- Improve monitoring and alerting.
