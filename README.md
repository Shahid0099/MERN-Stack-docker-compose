# MERN Task Tracker Demo (DevOps Practices)

## Features
- Node.js Express backend with MongoDB
- React frontend
- API for Tasks CRUD
- Dockerized (backend, frontend, MongoDB)
- Uses environment variables

## Quick Start

1. Clone the repo

2. Copy `.env.example` to `.env` in `backend/` and set variables as needed.

3. Build and run with Docker Compose:
   ```sh
   docker-compose up --build
   ```

4. Access frontend at [http://localhost:3000](http://localhost:3000)

## DevOps Practices
- Uses Docker for consistent environment
- Environment variables for config
- Separate services for frontend, backend, db
- (Optional) Add CI/CD setup, logging, and monitoring as next steps