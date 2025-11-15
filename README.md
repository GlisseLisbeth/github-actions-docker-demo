# 🚀 Demo: GitHub Actions + Docker

Este proyecto demuestra cómo:

- Crear una imagen Docker
- Ejecutarla localmente
- Subirla automáticamente a Docker Hub con GitHub Actions

## 🧩 Requisitos
- Docker
- Node.js
- Cuenta en Docker Hub
- Repo en GitHub

## ▶️ Ejecutar localmente
```
npm install
npm start
```

## 🐳 Construir imagen
```
docker build -t gh-actions-demo .
docker run -p 3000:3000 gh-actions-demo
```

## 🔄 GitHub Actions
Debes configurar en GitHub Secrets:
- DOCKER_USERNAME
- DOCKER_PASSWORD
