# 🎮 Game Hosting Platform

A scalable platform for provisioning and managing game servers with integrated billing and user management.

This project is designed as a foundation for a commercial-grade game hosting service, focusing on automation, modular architecture, and developer experience.

---

## 🔗 Links

- 💼 LinkedIn: https://www.linkedin.com/in/kacperplaczek/
- ☕ Support / Donate: https://buymeacoffee.com/kacperplaczek

---

## 📬 Contact

For commercial usage, licensing, or recruitment inquiries:

- 📧 Email: [xk.placzek@gmail.com](mailto:xk.placzek@gmail.com)

---

## 🏗️ Monorepo Structure

```
/apps
  /website         # website template for project
  /support-panel   # front-end for support panel
  /client-panel    # front-end for client panel
  /api             # backend (REST API, business logic)

/packages
  /ui              # shared UI components
  /types           # shared TypeScript types
```

---

## ⚙️ Tech Stack

### Frontend

- Next.js
- TypeScript
- TailwindCSS

### Backend

- Node.js
- NestJS
- PostgreSQL

### Infrastructure

- Docker
- Nginx

### Payments

- Stripe

---

## 🎮 Core Features

- Game server provisioning
- User dashboard and management panel
- Integrated payment system
- Automated instance lifecycle management
- Server control (start / stop / restart)

---

## 🚀 Getting Started

### Install dependencies

```
pnpm install
```

### Run development environment

```
pnpm dev
```

### Build project

```
pnpm build
```

---

## 📦 Available Scripts

- `dev` – run all services in development mode
- `build` – build all apps and packages
- `lint` – run linters
- `format` – format codebase

---

## 🐳 Docker (optional)

```
docker-compose up --build
```

---

## 📌 Project Scope

This project serves as a foundation for building a production-ready game hosting platform.
It is actively developed and can be extended or adapted for commercial use.

---

## 📄 License

This repository is not licensed for unrestricted commercial use.

For commercial licensing, please contact:
📧 [xk.placzek@gmail.com](mailto:xk.placzek@gmail.com)
