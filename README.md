# Práctica Unidad 8 — API de tareas

API REST con Express y PostgreSQL (tabla `tareas`), pruebas con `node:test` + `supertest` y CI/CD con GitHub Actions → Render.

```bash
cd backend
cp .env.example .env   # completar DATABASE_URL
npm install
npm run dev            # http://localhost:3000
npm test
```

Rutas: `GET /salud`, `GET/POST /api/tareas`, `GET/PUT/DELETE /api/tareas/:id`.
