# 📚 Zen Shelf Hub — AI-Powered Virtual Library & Digital Sanctuary

<div align="center">

  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:6C63FF,100:00C9A7&height=200&section=header&text=Zen%20Shelf%20Hub&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38" alt="Zen Shelf Hub Banner"/>

  <h3>📖 Read. Reflect. Discover.</h3>

  <p>
    An AI-powered virtual library platform combining immersive digital reading,
    intelligent book analysis, reading habit analytics, and a personalized digital library experience.
  </p>

[![React](https://img.shields.io/badge/Frontend-React%20%7C%20TypeScript-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev/)
[![Spring Boot](https://img.shields.io/badge/Backend-Spring%20Boot%203-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)](https://spring.io)
[![Docker](https://img.shields.io/badge/Deployment-Docker%20Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)

</div>

---

## ✨ Core Pillars

- **🧠 AI-Powered Insights**: Automated summary generation, key quote extraction, and sentiment themes powered by LLMs.
- **📚 Curated Shelves**: Organize reading lists into *Currently Reading*, *Want to Read*, *Completed*, and *Favorites*.
- **📊 Reading Analytics**: Track pages read, reading streaks, genres explored, and completion rates.
- **🐳 Containerized Architecture**: One-click deployment with multi-container Docker Compose.

---

## 🏗️ Architecture

```mermaid
graph TD
    Client[React + TypeScript Web UI] -->|REST API| Backend[Spring Boot 3 API Service]
    Backend -->|Data Persistence| DB[(Relational Database)]
    Backend -->|Text Ingestion| AI[LLM Book Analysis Worker]
```

---

## 🚀 Quick Deployment with Docker

```bash
# Clone the repository
git clone https://github.com/TORBIomar/zen-shelf-hub.git
cd zen-shelf-hub

# Start all services with Docker Compose
docker-compose up -d --build
```

Access the frontend at `http://localhost:3000` and the API at `http://localhost:8080`.

---

## 👨‍💻 Author

**Omar Torbi** — Full-Stack Engineer & Software Architect
- 🌐 **Portfolio**: [omartorbi.engineer](https://www.omartorbi.engineer)
- 💼 **LinkedIn**: [linkedin.com/in/omar-torbi](https://www.linkedin.com/in/omar-torbi-b8340933a/)
- 🐙 **GitHub**: [@TORBIomar](https://github.com/TORBIomar)
- ✉️ **Email**: [torbi.dev@outlook.com](mailto:torbi.dev@outlook.com)
