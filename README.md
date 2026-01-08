# Servegram

Servegram is a service marketplace platform where anyone can offer services and anyone can consume services.  
It supports ads, real-time chat, presence, and scalable backend architecture.

This repository is a **mono-repo** containing frontend (Next.js) and backend (Node.js).

---

## Tech Stack
- Frontend: Next.js (React)
- Backend: Node.js (Express)
- Database & Realtime: Supabase (PostgreSQL)
- Hosting: Vercel (Frontend), Render (Backend)

---

## Local Setup

### Prerequisites
- Node.js ≥ 18
- npm ≥ 9
- Git

---

### Clone Repository

git clone https://github.com/servegram/servegram.git
cd servegram
Install Dependencies (One Time) : npm run install:all
 
Environment Variables
Create env files (values shared separately):

backend/.env.dev

frontend/web/.env.local

Run Project (Frontend + Backend) : npm run dev

Local URLs
Frontend: http://localhost:3000

Backend: http://localhost:4000

Notes

No database runs locally
Supabase is used for DB, Auth, and Realtime
Do not commit .env files


