# Reyee Control — EW1200 Admin Panel Prototype

This is a static Cloudflare Pages-ready website prototype.

## Important
The dashboard is currently a UI demo only. It does NOT connect to the Ruijie Reyee EW1200 router. Demo Block/Unblock buttons only change the on-page sample data. Do not enter router credentials into this site.

Before real router control can be implemented, verify that this exact EW1200 firmware offers a supported API or authorized cloud integration for client listing and blocking. Never expose router credentials or management APIs in browser-side JavaScript. Any real integration should use a secured backend/Worker with authentication and least-privilege access.

## Deploy to Cloudflare Pages
1. Create a GitHub repository and upload `index.html` (and this README if desired).
2. In Cloudflare, open Workers & Pages -> Create -> Pages -> Connect to Git.
3. Select the repository.
4. Framework preset: None.
5. Build command: leave empty.
6. Build output directory: `/` (or the repository root, depending on the UI).
7. Deploy.

This prototype has no build step and no external dependencies.
