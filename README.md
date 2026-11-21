# Sovrack Starter Templates

Official ready-to-deploy application templates for **Sovrack** — The Open-Core Deployment & Orchestration Platform.

Deploy any of these templates to your own Ubuntu servers in 1 click or using the Sovrack CLI:

```bash
sovrack deploy --template nextjs
```

## 📦 Available Templates

| Template | Runtime | Description | Default Port |
| :--- | :--- | :--- | :--- |
| **`nextjs`** | Node.js 22 | Next.js 15 App Router with Tailwind CSS & Standalone output | `3000` |
| **`nodejs-express`** | Node.js 22 | Express.js REST API with TypeScript & health check | `4000` |
| **`python-fastapi`** | Python 3.12 | FastAPI ASGI web API with Uvicorn and Pydantic | `8000` |
| **`golang`** | Go 1.22 | High-performance Go microservice with Gin / Chi | `8080` |
| **`laravel`** | PHP 8.3 | Laravel 11 web application with Nginx and OPcache | `80` |
| **`static`** | HTML/Nginx | Ultra-lightweight static website with Nginx Alpine | `80` |

## 🚀 Creating a New Template

Each template folder includes:
- Source code ready for Nixpacks automatic detection.
- `sovrack.json` specifying the port, health check path, and recommended resource limits.
