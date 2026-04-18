> Available languages / Idiomas disponibles: [*English*](README.md) / [*Español*](README.ES.md)

# Mariano Enrique Torres Ponce - Technology Risk & Applied Cybersecurity

Technology risk and applied cybersecurity consultant with a background in cloud infrastructure, production operations, and resilience-oriented engineering. My work connects technical practice with risk reduction, secure technology use, observability, exposure analysis, and operational decision-making in complex environments.

For current work, writing, and public profile:  
[www.metorresponce.com](https://metorresponce.com)

- Technology Risk · Applied Cybersecurity · Operational Resilience
- Cloud Infrastructure · Production Operations · Exposure & Control
- Observability · Automation · Secure Technology Use

## Highlights
- Technical labs and practical projects focused on resilience, traceability, and risk reduction in modern IT environments.
- Hands-on work around cloud infrastructure, observability, automation, and operational controls.
- Reproducible experiments designed to explore reliability, secure configuration, monitoring, and safer operational practices.
- A technical portfolio built to connect infrastructure knowledge with cybersecurity, governance, and technology risk.

## Featured Projects

### Infrastructure as Code
- **[Terraform Local Demo](https://github.com/metorresponce/terraform-local-demo/blob/main/README.md)** - Reproducible infra without cloud providers (`local` + `random`). CI with `fmt` and `validate`.  
  [![terraform-ci](https://github.com/metorresponce/terraform-local-demo/actions/workflows/terraform-ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/metorresponce/terraform-local-demo/actions/workflows/terraform-ci.yml)

- **[AWS Serverless Local Demo](https://github.com/metorresponce/aws-serverless-local-demo/blob/main/README.md)** - Serverless “without the cloud”: S3 + SQS + DynamoDB on LocalStack, with integration tests and CI in GitHub Actions.  
  [![ci](https://github.com/metorresponce/aws-serverless-local-demo/actions/workflows/ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/metorresponce/aws-serverless-local-demo/actions/workflows/ci.yml)

### Kubernetes & Delivery
- **[Helm Chart Skeleton](https://github.com/metorresponce/helm-chart-skeleton/blob/main/README.md)** - Chart skeleton for K8s deployments with CI (lint + template) and automated releases.  
  [![chart-ci](https://github.com/metorresponce/helm-chart-skeleton/actions/workflows/chart-ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/metorresponce/helm-chart-skeleton/actions/workflows/chart-ci.yml)

- **[Kubernetes Admin Ops Kit](https://github.com/metorresponce/k8s-admin-ops-kit/blob/main/README.md)** - Runbooks-as-code for K8s admins: Ansible playbooks (cordon/drain, ordered restarts, rollback), Helm chart (api/worker/nlp with probes, PDB, NetworkPolicy), and CI with KinD.  
  [![ci](https://github.com/metorresponce/k8s-admin-ops-kit/actions/workflows/ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/metorresponce/k8s-admin-ops-kit/actions/workflows/ci.yml)

### Observability
- **[FastAPI Observability Demo](https://github.com/metorresponce/fastapi-observability-demo/blob/main/README.md)** - FastAPI service with `/metrics`, tests, and CI (pytest + Docker build).  
  [![ci](https://github.com/metorresponce/fastapi-observability-demo/actions/workflows/ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/metorresponce/fastapi-observability-demo/actions/workflows/ci.yml)

- **[GitHub Observability Demo](https://github.com/metorresponce/github-observability-demo/blob/main/README.md)** - Prometheus + Grafana stack + exporter for GitHub metrics.  
  [![compose-validate](https://github.com/metorresponce/github-observability-demo/actions/workflows/compose-validate.yml/badge.svg?branch=main&style=flat-square)](https://github.com/metorresponce/github-observability-demo/actions/workflows/compose-validate.yml)

### AI / ML Technical Experiments
- **[ML Mini Pipeline](https://github.com/metorresponce/ml-mini-pipeline/blob/main/README.md)** - Mini ML pipeline (scikit-learn) that generates synthetic data, trains, and publishes artifacts (`model.pkl`, `metrics.json`) with CI.  
  [![ci](https://github.com/metorresponce/ml-mini-pipeline/actions/workflows/ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/metorresponce/ml-mini-pipeline/actions/workflows/ci.yml)

- **[MLflow Mini Experiments](https://github.com/metorresponce/mlflow-mini-experiments/blob/main/README.md)** - Experiment tracking with MLflow: parameters, metrics, and models; reproducible CI; optional local UI with Docker Compose.  
  [![ci](https://github.com/metorresponce/mlflow-mini-experiments/actions/workflows/ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/metorresponce/mlflow-mini-experiments/actions/workflows/ci.yml)

> All repositories are designed to be reproducible, easy to review, and independent from corporate environments, so they can be tested locally or through GitHub Actions.

## Areas of Focus
- Technology risk and operational resilience
- Applied cybersecurity and secure technology use
- Cloud infrastructure review and production-oriented controls
- Observability, traceability, and monitoring practices
- Automation and reproducible technical validation
- Infrastructure and platform operations in critical environments
