
# 🧱 Trabajo final diplomado

##  Introducción  
Este proyecto consiste en el diseño y despliegue de un microservicio utilizando **Docker**, **Kubernetes**, **Helm**, **ArgoCD** y pipelines de **Azure DevOps**.  
Su propósito es aplicar principios de arquitectura de software moderna, asegurando que las soluciones sean **escalables**, **mantenibles** y alineadas con los requisitos técnicos y del negocio.

---

##  Objetivo  
Diseñar y desplegar un microservicio contenedorizado en Kubernetes, empleando herramientas de orquestación, empaquetado y automatización.


###  Indicadores de desempeño  
- Diseño de arquitecturas de software utilizando estilos y patrones reconocidos.  
- Creación de soluciones escalables y mantenibles.  
- Implementación alineada con requisitos técnicos y del negocio.

---

##  Alcance de la Actividad  
El trabajo incluye:

- Construcción de un microservicio básico.  
- Creación de imágenes Docker.  
- Despliegue en Kubernetes usando Helm.  
- Implementación de GitOps mediante ArgoCD.  
- Automatización de CI/CD con pipelines en Azure DevOps.

---

## Estructura
```
DiplomadoEjercicioFinal/
 ├── servicedemo
 ├── src
 ├── test
 ├── Dockerfile
 ├── README.md
 ├── ServiceDemo.slnx
 ├── azure-pipelines.yaml
 ├── docker-compose.yml
 └── dotnet-tools.json
```

## Pasos del Proyecto

### 1️⃣ Microservicio y Contenedores Docker  
- Crear un microservicio básico (**lenguaje libre: Node.js / .NET / Python / etc.**)  
- Construir el `Dockerfile` correspondiente.  
- Configurar variables, puertos y dependencias del contenedor.  
- Publicar la imagen en un registry (Docker Hub / ACR / etc.).

---

### 2️⃣ Despliegue con Helm  
- Crear un **chart de Helm** para el microservicio.  
- Configurar:
  - `values.yaml` por defecto  
  - Overrides según entorno (dev/test/prod)  
- Definir plantillas para:
  - Deployment  
  - Service  
  - ConfigMaps / Secrets  
  - Ingress (si aplica)

 


