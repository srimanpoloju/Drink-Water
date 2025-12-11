# Drink Water — Simple Static Reminder Site

A tiny static site that encourages drinking water. It contains a basic HTML page with accompanying CSS and JavaScript.

This repository is intentionally minimal and suitable for local preview or deployment to any static hosting provider.

## Files

- `index.html` — Main page and markup.
- `style.css` — Styles for the page.
- `script.js` — Client-side behavior and any timers/notifications.

## Quick start (macOS / zsh)

Option 1 — Open directly (fast):

```zsh
open index.html
```

This opens the page using the file:// protocol. Good for quick checks, but some browser features (fetch, service workers, module imports) may be limited.

Option 2 — Recommended: run a simple HTTP server (Python 3):

```zsh
# then open http://localhost:8000
```

Option 3 — Use VS Code Live Server:

1. Install the "Live Server" extension.
2. Open the project folder in VS Code.
3. Right-click `index.html` → "Open with Live Server" or click "Go Live".

Option 4 — Node/npm based (optional):

```zsh
npm install -g http-server    # or use npx http-server
# then open http://localhost:8080
```

## Development notes

- Use the browser Developer Tools (Cmd+Option+I) → Console and Network to debug JS errors or missing assets.
- If CSS updates do not appear, try a hard reload or disable cache in DevTools.
- If your `script.js` performs fetch requests to external APIs and you see CORS errors, those are caused by the remote server — not the local server.

## Contributing

Small fixes and PRs welcome. For significant features (analytics, persistent reminders, notifications), open an issue first to discuss design.

## License

This project is provided as-is. Add a LICENSE file if you want to choose an explicit license (e.g., MIT).

## Contact

If you need help running or extending this project, reply here with what you'd like to change or any errors you see.
