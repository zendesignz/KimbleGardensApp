# Kimble Gardens - Internal Operations App

An Astro internal app starter for Kimble Gardens to manage clients, plant records, services, media, and settings.

## Current features
- Tabs: Dashboard, Clients, Plant Records, Services, Media, Settings.
- Active tab highlight so the current page is obvious.
- Local `localStorage` persistence for Clients, Plant Records, and Services.
- Seed demo data included so pages are populated on first run.
- Editable forms for client records, plant records, and service names.

## Add your logo
1. Save your logo file in this project at:
   - `public/logo.png`
2. Refresh the app in your browser.

## Windows setup
1. Open **PowerShell** in the project folder.
2. Install dependencies:
   ```powershell
   npm install
   ```
3. Start the app:
   ```powershell
   npm run dev
   ```
4. Open:
   - `http://localhost:4321`

## Scripts
- `npm run dev` - run development server
- `npm run build` - build production output
- `npm run preview` - preview production build

## Notes
- No backend yet (data is browser local only).
- `node_modules` is ignored and should never be committed.
