> Idiomas disponibles / Available languages: [*Español*](README.ES.md) / [*English*](README.md)

# Mariano Enrique Torres Ponce - Riesgo Tecnológico y Ciberseguridad Aplicada

Consultor en riesgo tecnológico y ciberseguridad aplicada, con experiencia en infraestructura cloud, operación de entornos productivos e ingeniería orientada a la resiliencia. Mi trabajo conecta la práctica técnica con la reducción del riesgo, el uso seguro de la tecnología, la observabilidad, el análisis de exposición y la toma de decisiones operativas en entornos complejos.
Para trabajo actual, publicaciones y perfil público:  
[metorresponce.com](https://metorresponce.com)

- Riesgo Tecnológico · Ciberseguridad Aplicada · Resiliencia Operativa
- Infraestructura Cloud · Operación de Producción · Exposición y Controles
- Observabilidad · Automatización · Uso Seguro de la Tecnología

## Aspectos destacados
- Laboratorios técnicos y proyectos prácticos orientados a resiliencia, trazabilidad y reducción del riesgo en entornos IT modernos.
- Trabajo hands-on sobre infraestructura cloud, observabilidad, automatización y controles operativos.
- Experimentos reproducibles pensados para explorar confiabilidad, configuración segura, monitoreo y prácticas operativas más seguras.
- Un portfolio técnico que conecta conocimiento de infraestructura con ciberseguridad, gobernanza y riesgo tecnológico.

## Proyectos destacados

### Infraestructura como Código
- **[Terraform Local Demo](https://github.com/metorresponce/terraform-local-demo/blob/main/README.md)** - Infraestructura reproducible sin proveedores cloud (`local` + `random`). CI con `fmt` y `validate`.  
  [![terraform-ci](https://github.com/metorresponce/terraform-local-demo/actions/workflows/terraform-ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/metorresponce/terraform-local-demo/actions/workflows/terraform-ci.yml)

- **[AWS Serverless Local Demo](https://github.com/metorresponce/aws-serverless-local-demo/blob/main/README.md)** - Serverless “sin la nube”: S3 + SQS + DynamoDB sobre LocalStack, con pruebas de integración y CI en GitHub Actions.  
  [![ci](https://github.com/metorresponce/aws-serverless-local-demo/actions/workflows/ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/metorresponce/aws-serverless-local-demo/actions/workflows/ci.yml)

### Kubernetes y Entrega
- **[Helm Chart Skeleton](https://github.com/metorresponce/helm-chart-skeleton/blob/main/README.md)** - Esqueleto de chart para despliegues en Kubernetes con CI (lint + template) y releases automatizados.  
  [![chart-ci](https://github.com/metorresponce/helm-chart-skeleton/actions/workflows/chart-ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/metorresponce/helm-chart-skeleton/actions/workflows/chart-ci.yml)

- **[Kubernetes Admin Ops Kit](https://github.com/metorresponce/k8s-admin-ops-kit/blob/main/README.md)** - Runbooks-as-code para administradores de Kubernetes: playbooks de Ansible (cordon/drain, reinicios ordenados, rollback), chart Helm (api/worker/nlp con probes, PDB, NetworkPolicy) y CI con KinD.  
  [![ci](https://github.com/metorresponce/k8s-admin-ops-kit/actions/workflows/ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/metorresponce/k8s-admin-ops-kit/actions/workflows/ci.yml)

### Observabilidad
- **[FastAPI Observability Demo](https://github.com/metorresponce/fastapi-observability-demo/blob/main/README.md)** - Servicio FastAPI con `/metrics`, tests y CI (pytest + Docker build).  
  [![ci](https://github.com/metorresponce/fastapi-observability-demo/actions/workflows/ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/metorresponce/fastapi-observability-demo/actions/workflows/ci.yml)

- **[GitHub Observability Demo](https://github.com/metorresponce/github-observability-demo/blob/main/README.md)** - Stack Prometheus + Grafana + exporter para métricas de GitHub.  
  [![compose-validate](https://github.com/metorresponce/github-observability-demo/actions/workflows/compose-validate.yml/badge.svg?branch=main&style=flat-square)](https://github.com/metorresponce/github-observability-demo/actions/workflows/compose-validate.yml)

### Experimentos Técnicos de IA / ML
- **[ML Mini Pipeline](https://github.com/metorresponce/ml-mini-pipeline/blob/main/README.md)** - Mini pipeline de ML (scikit-learn) que genera datos sintéticos, entrena y publica artefactos (`model.pkl`, `metrics.json`) con CI.  
  [![ci](https://github.com/metorresponce/ml-mini-pipeline/actions/workflows/ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/metorresponce/ml-mini-pipeline/actions/workflows/ci.yml)

- **[MLflow Mini Experiments](https://github.com/metorresponce/mlflow-mini-experiments/blob/main/README.md)** - Seguimiento de experimentos con MLflow: parámetros, métricas y modelos; CI reproducible; interfaz local opcional con Docker Compose.  
  [![ci](https://github.com/metorresponce/mlflow-mini-experiments/actions/workflows/ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/metorresponce/mlflow-mini-experiments/actions/workflows/ci.yml)

> Todos los repositorios están pensados para ser reproducibles, fáciles de revisar e independientes de entornos corporativos, de modo que puedan probarse en local o a través de GitHub Actions.

## Áreas de enfoque
- Riesgo tecnológico y resiliencia operativa
- Ciberseguridad aplicada y uso seguro de la tecnología
- Revisión de infraestructura cloud y controles orientados a producción
- Observabilidad, trazabilidad y prácticas de monitoreo
- Automatización y validación técnica reproducible
- Operación de infraestructura y plataformas en entornos críticos
