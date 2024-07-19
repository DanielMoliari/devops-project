# DevOps Project

## Descrição
Este repositório contém uma aplicação web containerizada, implantada em um cluster Kubernetes com um pipeline de CI/CD.

## Estrutura do Repositório
- **app/**: Código fonte da aplicação web.
- **docker/**: Dockerfile para containerização.
- **k8s/**: Manifests Kubernetes (Deployments, Services, Ingress).
- **.github/**: Configurações de pipeline CI/CD.

## Instruções de Uso

### 1. Construir e Executar Contêineres
```sh
cd app
docker build -t devops-project:latest .
docker run -p 3000:3000 devops-project:latest
