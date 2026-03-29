# StreamMeet

Lightweight README — quick info to run the project.

Overview
- Real-time chat and video calling webapp (React + Express + MongoDB + Stream).

Quick start
```bash
# install (from project root)

npm install --prefix backend
npm install --prefix frontend

# run dev
npm run dev --prefix backend
npm run dev --prefix frontend

# build + serve (production)
cd frontend && npm run build
$env:PORT='5001'; $env:NODE_ENV='production'; npm start --prefix backend
```

Environment (minimum)
- Backend: `PORT`, `MONGODB_URI`, `JWT_SECRET`, `STEAM_API_KEY`, `STEAM_API_SECRET`
- Frontend: `VITE_STREAM_API_KEY`

API (short)
- Auth: `/api/auth/*` (signup, login, logout, onboarding, me)
- Users: `/api/users/*` (friends, friend-requests)
- Chat: `/api/chat/token` (Stream token)

Diagrams
- See `docs/architecture.mmd`, `docs/auth-sequence.mmd`, `docs/er-diagram.mmd` for Mermaid diagrams.

License
- Add your preferred license.

Done — concise README. Want me to commit these changes?

