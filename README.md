# Vanta Estates

Premium real-estate portfolio website and lead-generation demo.

## Run
No build step is required. Open `index.html` in a browser, or serve the folder with any static server.

Recommended local server:
- VS Code Live Server
- `python -m http.server 8000`

## Pages
- `/index.html` — premium landing page
- `/properties.html` — searchable property collection
- `/property.html?id=aurelia` — property detail
- `/admin/index.html` — local demo CRM/dashboard

## Demo behavior
Lead form submissions are stored in browser `localStorage` under `vanta_leads` and appear in the client portal.

## Important
This is a frontend portfolio/demo implementation. The admin area is not a production authentication system and should not be presented as secure production infrastructure without adding a real backend, server-side authorization, database, rate limiting and secure session management.

Property photography is loaded from Unsplash URLs, so an internet connection is recommended for the full visual experience.
