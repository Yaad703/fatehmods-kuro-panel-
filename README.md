# FatehMods Kuro Panel

A dark modern web panel with key system for FatehMods — secure and fast.

## Features
- Dark mode UI (Tailwind-ready)
- Key verification system (demo included)
- Admin login and key generator (demo)
- Easy to deploy: Vercel (frontend) + Render (backend)
- Demo credentials included (change after deploy)

## Quick start (local)
1. Backend
   ```bash
   cd backend
   npm install express
   node index.js
   ```
2. Frontend
   ```bash
   cd frontend
   npm install
   npm run dev
   ```
3. Connect frontend to backend (dev):
   ```js
   // in browser console of frontend page
   window.__BACKEND__ = 'http://localhost:4000'
   window.location.reload()
   ```
