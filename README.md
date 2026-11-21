# Juggle

A private task and time-blocking planner. It's an installable web app (PWA). All data stays on your device: no account, no server.

## Deploy to GitHub Pages
1. On github.com, create a new **public** repo named `juggle`.
2. Choose **Add file → Upload files**, then drag in `index.html`, `manifest.webmanifest`, `sw.js`, `README.md` and the `icons` folder. Commit.
3. Go to **Settings → Pages**. Under Source, pick **Deploy from a branch**, then `main` / `(root)`, and click Save.
4. After about a minute, the app is live at `https://<your-username>.github.io/juggle/`.

## Install on Android
Open the link in **Chrome** and tap ⋮ → **Add to Home screen / Install app**. After that it works offline.

## Updating
Upload the changed files to the repo. The app picks up the new version the second time you open it.

## Notes
- Back up from ⚙︎ → Backup now and then. Clearing Chrome's site data erases the app's data.
- For reminders that always fire, use 📅 To calendar. It sends the item to your phone's calendar app.
