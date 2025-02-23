# 📦 svfe-api-firmador - Despliegue con Docker Compose

Este repositorio contiene un `docker-compose.yml` optimizado para producción, que permite desplegar el servicio **svfe-api-firmador** de forma eficiente y segura.

## 🚀 Características
- **Despliegue con Docker Compose** 🐳
- **Soporte para `.env`** para configuración flexible
- **Reinicio automático** en caso de fallos
- **Red aislada y volúmenes persistentes**
- **Uso eficiente de recursos (CPU y RAM limitados)**

---

## 📌 **Requisitos**
Antes de comenzar, asegúrate de tener instalado:

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

---

## ⚙️ **Configuración**
### Clonar el repositorio
```sh
git clone https://github.com/cvjuan270/svfe-api-firmador.git
cd svfe-api-firmador
```
### Crear un archivo .env
```sh
PORT=8113 # Cambia el puerto si es necesario
```
### Ejeutar Docker Compose
```sh 
docker-compose up -d
```
### Verificar el Despliegue
```sh
docker ps
```
