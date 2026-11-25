# RushHour – Smart Canteen Ordering System

A smart canteen pre-ordering and kitchen management platform designed to reduce waiting time and improve food preparation using historical order analytics.

## Tech Stack

- Frontend: React + Vite
- Backend: Node.js + Express
- Styling: Tailwind CSS
- Analytics: JavaScript
- Charts: Recharts
- Data: Synthetic 30-day order dataset

## Project Structure

- `frontend/` – Student ordering, kitchen and analytics interfaces
- `backend/` – REST APIs, order management and pickup-slot logic
- `data/` – Synthetic historical orders and analytics
- `docs/` – API contract and project documentation
- `tests/` – Test cases and API verification

## Getting Started

### Backend

```bash
cd backend
npm install
npm run dev
```

Backend runs at `http://localhost:5000`.

### Frontend

```bash
cd frontend
npm install
npm run dev
```

Frontend runs at `http://localhost:5173`.

## Core Features

1. Student food ordering with pickup slots.
2. Automatic pickup-slot capacity enforcement.
3. Kitchen order management.
4. Historical order analytics.
5. Cook-ahead recommendations.

## Team Development

All members work on assigned feature branches and merge completed work into `main` through the project integrator.