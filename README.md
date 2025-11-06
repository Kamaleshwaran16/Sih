# Odisha Smart Traffic Management Dashboard

Production-style **Vite + React 18 + TypeScript + Tailwind + Lucide** dashboard for the Government of Odisha.

**Demo Login**
- Username: `Taffixion`
- Password: `1234@Taffixion`

## Features
- Government-branded login (Taffixion style)
- Live traffic signals (N/S/E/W), manual overrides with 15s timers
- Emergency alerts (auto every 15–25s), acknowledge, countdown
- Real-time vehicle counts & congestion indicator
- Analytics with **custom SVG** charts (line/bar/pie)
- Reports with CSV/Text export and “Print to PDF”
- Settings with fail-safe, dark mode, and JSON export
- Cleanups to prevent memory leaks

## Tech
- React 18 + TypeScript
- Tailwind CSS (dark mode via `class`)
- Lucide icons
- Vite

## Local Dev
```bash
npm install
npm run dev
