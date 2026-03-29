<h1 align="center">✨ Fullstack Chat & Video Calling App ✨</h1>
Live Demo: [Stream Meet](https://stream-meet-cvq3.onrender.com)

![Demo App](/frontend/dist/image.png)
![App Screenshot](/frontend/dist/image.png)

Highlights:

- 🌐 Real-time Messaging with Typing Indicators & Reactions
- 📹 1-on-1 and Group Video Calls with Screen Sharing & Recording
- 🔐 JWT Authentication & Protected Routes
- 🌍 Language Exchange Platform with 32 Unique UI Themes
- ⚡ Tech Stack: React + Express + MongoDB + TailwindCSS + TanStack Query
- 🧠 Global State Management with Zustand
- 🚨 Error Handling (Frontend & Backend)
- 🚀 Free Deployment
- 🎯 Built with Scalable Technologies like Stream
- ⏳ And much more!

---

## 🧪 .env Setup

### Backend (`/backend`)

```
PORT=5001
MONGO_URI=your_mongo_uri
STEAM_API_KEY=your_steam_api_key
STEAM_API_SECRET=your_steam_api_secret
JWT_SECRET_KEY=your_jwt_secret
NODE_ENV=development
```

### Frontend (`/frontend`)

```
VITE_STREAM_API_KEY=your_stream_api_key
```

---

## 🔧 Run the Backend

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

