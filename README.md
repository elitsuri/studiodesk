# StudioDesk

> A desktop productivity suite with document editing, file sync, and task management

## ✨ Features
- User authentication with JWT
- CRUD operations for main resources
- RESTful API with proper status codes
- Database migrations and seed data
- Docker containerization

## 🧰 Tech Stack
Electron, TypeScript, React, SQLite

## 🏗️ Architecture
Backend service with Electron, frontend user interface, and database persistence

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/studiodesk
cd studiodesk

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
