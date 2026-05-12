# SQLite Lite Editor

A free, browser-based SQLite database editor modeled after [DB Browser for SQLite](https://sqlitebrowser.org/). Open, browse, query, and edit `.db` files — everything runs locally in your browser with no install required at https://quemeb.github.io/sqlite-lite-editor/. 

Works on **Chromebooks, iPads, Macs, Windows, Linux** — any device with a modern web browser.

## Why This Exists

DB Browser for SQLite is a great desktop tool, but it can't be installed on Chromebooks or iPads. Other online alternatives like sqliteonline.com work, but their interface looks completely different — which can be confusing if you're following tutorials or videos that use DB Browser. SQLite Lite Editor gives you a familiar DB Browser-style layout (Database Structure, Browse Data, and Execute SQL tabs) that runs entirely in the browser.

## Features

- **Open** existing `.db` / `.sqlite` / `.sqlite3` files from your device
- **Create** new databases from scratch
- **Browse** table structure, columns, indexes, views, and triggers
- **Query** with full SQL support (SELECT, INSERT, UPDATE, DELETE, CREATE, ALTER, DROP, etc.)
- **Filter** table data with WHERE clauses
- **Export** modified databases back to `.db` files
- **100% client-side** — your data never leaves your device, no server involved

## How It Works

This app uses [sql.js](https://github.com/sql-js/sql.js/), which is the real SQLite database engine compiled to WebAssembly. Your browser runs the actual SQLite code locally — the same engine used by desktop apps like DB Browser for SQLite.

## Deploy to GitHub Pages

1. **Fork or clone** this repository
2. Go to your repo's **Settings → Pages**
3. Under "Source," select **Deploy from a branch**
4. Choose the **main** branch and **/ (root)** folder
5. Click **Save**
6. Your site will be live at `https://YOUR-USERNAME.github.io/sqlite-lite-editor/` within a minute or two

That's it — the entire app is a single `index.html` file with no build step required.

## Quick Start (no GitHub needed)

You can also just download `index.html` and open it directly in your browser. It works offline after the first load (once the SQLite WASM engine is cached).

## License

MIT — free to use, modify, and distribute.
