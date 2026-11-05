# Northstar — Smart Business Management Dashboard

A responsive, frontend-only business management dashboard built with React, Vite, React Router, Recharts and Lucide icons. It uses mock data and browser `localStorage`; no backend or database is required.

## Features
- Overview with revenue, orders, customer and inventory metrics, charts and low-stock alerts.
- Product catalogue: add, edit, delete, search, category filter, stock status and pagination.
- Sales checkout: customer selection, cart quantities, discounts, stock validation, transaction history and printable receipt/export.
- Customer registration, editing, deletion, profile and purchase history.
- Simulated login, profile settings, dark/light theme and local data persistence.
- Responsive sidebar, toast feedback, confirmation prompts and empty states.

## Requirements
- Node.js 18.0 or newer
- npm

## Setup
1. Extract the ZIP file.
2. Open the extracted `smart-business-dashboard` folder in VS Code.
3. Open the integrated terminal in that folder.
4. Install dependencies:
   ```bash
   npm install
   ```
5. Start the development server:
   ```bash
   npm run dev
   ```
6. Open the local URL printed in the terminal (usually `http://localhost:5173`).

## Demo login
- Email: `admin@northstar.com`
- Password: `password`

The login is a frontend simulation, not real security. Data is stored in the current browser. Use **Settings → Reset demo data** to clear saved data.

## Production build
```bash
npm run build
npm run preview
```

## Notes
- Charts use sample weekly trend data; dashboard totals and operational tables use local application data.
- Product photos load from Unsplash and therefore require an internet connection. All core app functionality works without a backend.
