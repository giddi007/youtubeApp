Project Root Overview

Purpose: A small Vite + React demo that implements a YouTube-like UI (video feed, player, sidebar, recommendations).
Entry point: main.jsx mounts the app; the root component is App.jsx.
Pages & components: App pages live in src/Components/Pages (notably Home and Video). Reusable UI is in Components — Feed, Navbar, PlayVideo, Recommended, SideBar.
Data & assets: Sample/video data in data.js; static files in public; images/assets in assets.
Styling: Component-scoped CSS files alongside components (e.g., Feed.css), plus global styles in index.css and App.css.

## Project: YouTube-like Demo

- **Purpose:** Minimal Vite + React demo that replicates a simplified YouTube UI: video feed, player, sidebar, and recommendations.
- **Tech:** React, Vite, plain CSS (component-scoped files).
- **Entry point:** `src/main.jsx` mounts the app; root component is `src/App.jsx`.
- **Key components:** `src/Components/Feed`, `src/Components/Navbar`, `src/Components/PlayVideo`, `src/Components/Recommended`, `src/Components/SideBar`.
- **Sample data & assets:** `src/data.js`, `src/assets/`, and `public/` for static files.
- **Run locally:**
