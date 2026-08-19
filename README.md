# Manufacturing Order & Production Tracker

Factory login, order creation, and production tracking. The app is split into a React web client and an Express API.

## Layout

- `web/` — Vite + React UI
- `server/` — Express + MongoDB API

## Run

MongoDB must be running locally.

```bash
# terminal 1 — API
cd server
copy .env.example .env
npm install
npm run seed
npm run dev
```

```bash
# terminal 2 — UI
cd web
npm install
npm run dev
```

- API: http://localhost:5000
- Web: http://localhost:5173

## Demo logins

| Role | Phone | Password | Menu |
|------|-------|----------|------|
| Order Creator | `9876543210` | `order123` | Create Order |
| Production Manager | `9123456780` | `prod123` | Orders List, Production Planning, My Tasks |
| Floor Manager | `9988776655` | `floor123` | Orders List, Production Planning, My Tasks |
