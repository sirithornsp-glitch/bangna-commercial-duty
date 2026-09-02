# Bangna Commercial Duty

React + Vite app. Data is stored directly in Supabase (URL/key are already
hardcoded in `src/App.jsx`, same as before), so there's no `.env` setup
needed to get it running.

## Deploy to Vercel

1. Unzip this folder.
2. Go to https://vercel.com/new and either:
   - drag-and-drop this folder onto the page, or
   - push it to a GitHub repo first and import that repo.
3. Vercel auto-detects Vite. Framework preset: **Vite**.
   - Build command: `npm run build` (default)
   - Output directory: `dist` (default)
   - Install command: `npm install` (default)
4. Deploy.

## Run locally

```
npm install
npm run dev
```
