# IRAQIDIT — DIT Film teal interface

A responsive static front-end prototype for film-production reporting. It includes project cards, project creation/editing, shooting-day records, automatic totals, printable reports, and JSON export.

## Publish with GitHub Pages
1. Upload `index.html`, `style.css`, `app.js`, and `README.md` to the root of your `IRAQIDIT` repository.
2. In **Settings → Pages**, select **Deploy from a branch**, branch **main**, folder **/(root)**, then Save.
3. In **Settings → Pages** or the repository's **Deployments**, open the published website address.

## Important limitation
This version saves data in the current browser using `localStorage`. It does **not** have secure sign-in, a shared database, private client links, or cross-device synchronization. Do not use it for confidential production data or claim its share button creates a live private client report. To make the real client-sharing workflow work, connect a backend/database and implement authentication plus per-project access rules (for example, a Supabase project with carefully configured Row Level Security) before using it with clients.
