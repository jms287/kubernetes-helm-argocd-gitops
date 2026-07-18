# Flujo GitOps con Kubernetes, Helm y Argo CD

Proyecto de práctica para implementar un flujo GitOps utilizando Kubernetes, Helm y Argo CD. Incluye un Helm Chart para una aplicación web, despliegue automatizado y sincronización continua desde un repositorio Git.

## Tecnologías
- Kubernetes
- Minikube
- Helm
- Argo CD
- GitHub

## Estructura

```
web-app/
 ├── Chart.yaml
 ├── values.yaml
 └── templates/
```

## Despliegue

helm install web-release ./web-app