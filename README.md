# Frontend (React)

User Interface for the Marketplace.

## Tech Stack
- React
- Vite
- TypeScript
- MUI


## Environment Setup
1. Configure the variables:
   - `VITE_API_URL`: URL of the MVP Marketplace API (default: `http://localhost:3001`)

## Running
```bash
npm install
npm run dev
```

## Docker
```bash
docker build -t mvp-front-marketplace .
docker run -p 5173:5173 mvp-front-marketplace
```

## Docker Compose
To run the entire system (Frontend + MVP Marketplace API + MVP Marketplace Services + DB):
```bash
docker-compose up --build
```

## fluxograma
Fluxograma da arquitetura desenvolvida.
<img width="5280" height="1186" alt="React Frontend Multi-API-2025-12-12-041133" src="https://github.com/user-attachments/assets/d6a68edb-a1fb-4ac5-b449-b2c700fa3c3c" />
