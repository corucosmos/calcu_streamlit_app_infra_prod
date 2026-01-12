# 🏗️ Infrastructure

Este repositorio contiene toda la configuración de **Kubernetes (K8s)** y los scripts de automatización para el ciclo de vida de la aplicación (Backend FastAPI + Frontend Streamlit).

## 📂 Estructura del Proyecto

```text
infra
    ├── k8s
    │   ├── backend
    │   │   ├── deployment.yaml
    │   │   └── service.yaml
    │   ├── configmap.yaml
    │   ├── frontend
    │   │   ├── deployment.yaml
    │   │   ├── ingress.yaml
    │   │   └── service.yaml
    │   ├── namespace.yaml
    │   ├── sealed-secrets.yaml
    │   └── secrets.yaml
    ├── Readme.md
    └── scripts
        ├── deploy-dev.sh
        ├── deploy-pro.sh