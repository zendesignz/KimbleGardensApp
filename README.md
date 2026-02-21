# Kimble Gardens - Internal Operations App

An Astro-based internal app scaffold for managing clients, plant records, services, media, and settings for Kimble Gardens.

## What is included
- Top navigation tabs: Dashboard, Clients, Plant Records, Services, Media, Settings.
- Local-first data persistence using `localStorage`.
- Seed demo data for Clients and Plant Records so screens are populated on first run.
- Basic tab/page scaffolding ready for iterative UX updates.

## Windows setup
1. Open **PowerShell** in this project folder.
2. Install dependencies:
   ```powershell
   npm install
   ```
3. Start local development server:
   ```powershell
   npm run dev
   ```
4. Open the local URL shown in terminal (expected default):
   - `http://localhost:4321`

## Scripts
- `npm run dev` - Start Astro dev server.
- `npm run build` - Build production output.
- `npm run preview` - Preview production build locally.

## Notes
- This app currently uses browser `localStorage` only (no backend/database).
- `node_modules` should not be committed.
