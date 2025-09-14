# Quizlet 

Simple quiz application (React + Express) — lightweight Quizlet  used for learning and demonstration.

## Project structure

- `client/` — React frontend (Create React App) using Tailwind CSS.
- `server/` — Express backend exposing quiz APIs.

## Requirements

- Node.js 14+ (recommended)
- npm or yarn

## Setup

1. Install dependencies for server and client:

   - Using npm:

   ```powershell
   cd server; npm install; cd ..\client; npm install
   ```

   - Or using yarn:

   ```powershell
   cd server; yarn; cd ..\client; yarn
   ```

2. Run the development servers:

   - Start the backend (from `server/`):

   ```powershell
   cd server; npm start
   ```

   - Start the frontend (from `client/`):

   ```powershell
   cd client; npm start
   ```

The create-react-app dev server typically runs on `http://localhost:3000` and the Express server on `http://localhost:5000` (check `server/package.json` for exact scripts and ports).

## Available scripts

- `client/package.json` contains the frontend scripts: `start`, `build`, `test`.
- `server/package.json` contains the backend scripts: `start`, `dev` (if configured).

## Notes

- If the frontend needs to call the backend during development, ensure CORS is enabled on the server or proxy is configured in the React app's `package.json`.
- Tailwind CSS is configured in the client via `tailwind.config.js` and `postcss.config.js`.


