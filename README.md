DevOps Documentation and Audit Prompts

This repository contains a collection of prompts designed to guide the review and optimization of various DevOps workflows, infrastructure-as-code, and automation scripts. Each prompt is tailored to provide detailed insights and best practices for specific DevOps tasks. These tasks range from analyzing Ansible Playbooks and Dockerfiles to reviewing Kubernetes manifests and CI/CD pipelines. The prompts are intended for senior engineers and junior onboarding, providing clear, structured documentation, and improvement suggestions.
Contents
1. Ansible Playbook – Infra Audit & Explanation

    Purpose: Review and explain an Ansible playbook, focusing on its purpose, potential risks (idempotency, service restarts), and suggestions for scalability or security.

    Deliverables: Executive summary, step-by-step explanation, risk identification, and improvement suggestions.

    Use Case: Ideal for analyzing existing Ansible playbooks for security and performance.

2. Dockerfile – Deep Analysis & Best Practices

    Purpose: Document and audit a Dockerfile for efficiency, security, and maintainability.

    Deliverables: Image purpose summary, line-by-line breakdown, performance/security concerns, and multi-stage build suggestions.

    Use Case: Perfect for containerization and optimizing Docker images, especially for reducing image size or enhancing security.

3. Kubernetes YAML – Manifest Breakdown

    Purpose: Analyze Kubernetes manifests for resource types, startup behavior, and performance optimizations.

    Deliverables: Explanation of resource roles, image and volume usage, readiness/liveness probes, and anti-patterns.

    Use Case: Crucial for ensuring your Kubernetes resources are efficient, secure, and scalable.

4. CI/CD Pipeline – Optimization Review

    Purpose: Audit a pipeline configuration (e.g., GitHub Actions, GitLab CI/CD) for performance, maintainability, and security.

    Deliverables: Overview of pipeline triggers, job breakdown, caching and parallelization, and optimization suggestions.

    Use Case: Ideal for improving CI/CD pipelines, ensuring they are fast, secure, and reusable.

5. Terraform – Resource Documentation

    Purpose: Review Terraform code to provide detailed documentation for infrastructure-as-code, focusing on resource management.

    Deliverables: Provider overview, resource map, tagging/naming conventions, and suggestions for reusability with modules.

    Use Case: Great for documenting Terraform resources, ensuring consistency and best practices in infrastructure management.

6. Bash Script – Automation Review

    Purpose: Review and document a bash script for security, idempotency, and potential improvements.

    Deliverables: Script purpose, step-by-step commentary, security issues, and refactor suggestions.

    Use Case: Perfect for auditing shell scripts and making them more efficient, secure, and maintainable.

7. systemd Service File – Startup Behavior

    Purpose: Document a systemd unit file for internal runbooks, focusing on startup behavior and dependencies.

    Deliverables: Service description, ExecStart, RestartPolicy, environment usage, and hardening suggestions.

    Use Case: Great for documenting systemd services, particularly for production-ready configurations.

8. Prometheus Alerting Rule – Monitoring Audit

    Purpose: Audit and explain Prometheus alert rules for the operations team, with a focus on metric monitoring and alerting.

    Deliverables: Metric being monitored, alert triggers, severity mapping, runbook/dashboard links, and tuning suggestions.

    Use Case: Ideal for setting up and auditing alerting rules, ensuring they are both effective and tuned to avoid false positives.

9. Web Server Config – Security-Focused Review

    Purpose: Review a web server configuration (e.g., Nginx or Apache) with a security focus.

    Deliverables: Configuration block purposes, SSL/TLS settings, performance checks (gzip, cache), and security hardening suggestions.

    Use Case: Best for ensuring that web server configurations follow industry best practices for security and performance.

10. PostgreSQL Backup Script – DR Documentation

    Purpose: Document a PostgreSQL backup script for disaster recovery, with an emphasis on reliability and automation.

    Deliverables: Backup scope, location & retention strategy, compression/encryption checks, and cron/rotation suggestions.

    Use Case: Essential for securing and automating backup processes in a PostgreSQL environment.

11. Docker Compose – Multi-Service Breakdown

    Purpose: Document a Docker Compose file in the context of a microservice architecture.

    Deliverables: Service breakdown, volume/network usage, inter-service communication, and scaling/K8s suggestions.

    Use Case: Perfect for organizing multi-container applications and transitioning them to Kubernetes.

12. Helm Chart Values – Config Guide

    Purpose: Document the values.yaml file for a Helm chart, providing detailed guidance on customizing deployments.

    Deliverables: Purpose of each value, conditional flags, resource requests/limits, and security/access parameters.

    Use Case: Ideal for ensuring that Helm charts are configurable and follow best practices for deployment management.

🚀 How to Use These Prompts

Each prompt provides detailed guidance and frameworks for reviewing and documenting common DevOps artifacts. These can be used for:

    Junior Engineer Onboarding: Use the detailed breakdowns as part of training material.

    Code Audits: Review and optimize existing configurations for efficiency, security, and scalability.

    Internal Documentation: Create clear, structured documentation to support team knowledge and consistency.

🛠 Tools & Technologies Covered

    Ansible: Automation for configuration management and application deployment.

    Docker: Containerization for packaging applications.

    Kubernetes: Orchestration of containerized applications.

    CI/CD Pipelines: Automation for software delivery and integration (GitHub Actions, GitLab CI/CD).

    Terraform: Infrastructure as code for cloud provisioning.

    Bash: Scripting for automation tasks.

    systemd: Linux system management and service management.

    Prometheus: Monitoring and alerting toolkit.

    Helm: Kubernetes package manager for deployment.

    PostgreSQL: Relational database management system.

📚 Contributing

If you'd like to contribute new prompts, improve existing ones, or add more tools, feel free to open an issue or a pull request. We'd love to enhance this collection with more DevOps-related content!
