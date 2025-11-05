# Simple MERN Stack Example

This is a minimal MERN (MongoDB, Express, React, Node) example with a notes API and a small React front-end.

## Requirements
- Node.js (16+ recommended)
- npm
- MongoDB (local or Atlas) — set connection string in backend/.env

## Setup (PowerShell)

Open two terminals.

1) Backend

```powershell
cd "C:\Users\shah fahad\Desktop\New folder\backend"
# install
npm install
# copy .env.example -> .env and edit MONGODB_URI if needed
copy .env.example .env
# start dev server (requires nodemon) or start normally
npm run dev
# or
npm start
```

2) Frontend

```powershell
cd "C:\Users\shah fahad\Desktop\New folder\frontend"
npm install
npm start
```

The frontend expects the backend API at http://localhost:5000/api by default.

## Notes
- The backend uses Mongoose and provides CRUD endpoints at `/api/notes`.
- The frontend is a small React app that lists, creates, and deletes notes.

If you want, I can also run `npm install` for both server and client here, or add Docker files to containerize the app. Tell me which you'd like next.
