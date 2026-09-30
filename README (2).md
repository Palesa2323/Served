# SERVED — Your next food post, served.

AI-powered creative workspace for food creators. Single-file web app (`index.html`), no build step.

## Run locally
Open `index.html` in a browser.

## Deploy on GitHub Pages
Repo Settings → Pages → Deploy from branch → `main` / root.

## Note on AI
In the claude.ai published version, AI runs through Claude's built-in sample capability. On GitHub Pages that
capability does not exist, so generation needs a small server-side proxy that holds your API key (never put a key in the HTML).
Ideas, chats, themes and saved data use browser localStorage.
