# DevSpace — Free Online Code Editor, Compiler & Playground

A professional, browser-based online code editor and playground for HTML, CSS, and JavaScript. Write code and see live results instantly — no sign-up, no installation, 100% free.

## Features

- **Monaco editor** — the same code editor that powers VS Code, with syntax highlighting and IntelliSense-style completions
- **Live preview** — real-time rendering of your HTML, CSS, and JavaScript as you type
- **Built-in terminal** — run JavaScript and interact with a console right in the browser
- **Multi-tab editing** — switch between HTML, CSS, and JS panels seamlessly
- **Export** — download your code or share your playground session
- **Responsive UI** — works on desktop and mobile browsers
- **SEO-ready** — proper meta tags, Open Graph, and structured markup

## Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript (ES6+)
- **Editor:** Monaco Editor (CDN)
- **Hosting-ready:** single `index.html`, zero build step, deployable anywhere as a static site

## Quick Start

No build step required — it's a single static file.

```bash
# Clone the repo
git clone https://github.com/girishlade111/CodePlayground-MVP.git
cd CodePlayground-MVP

# Open in a browser (any of these)
# 1. Double-click index.html, or
# 2. Serve locally:
npx serve .
# 3. Or: python3 -m http.server 8000
```

Then open `http://localhost:8000` and start coding.

## Project Structure

```
CodePlayground-MVP/
├── index.html   # The entire app: editor UI, preview, terminal, export logic
└── README.md    # This file
```

Everything lives in `index.html` — styles, scripts, and markup. Monaco Editor is loaded from CDN at runtime (requires internet access).

## Notes & Limitations

- Requires an internet connection (Monaco Editor loads from CDN)
- Code runs entirely in the browser — nothing is sent to a server
- JavaScript in the preview executes in an iframe; be careful with untrusted snippets

## Deploy

This is a static site. Any static host works:

- **GitHub Pages:** Settings → Pages → Deploy from branch → `main` / `/ (root)`
- **Cloudflare Pages / Netlify:** drag-and-drop the repo, no build command needed

## License

Free to use and learn from.

## Author

**Built by Girish Lade** — https://ladestack.in

Part of the [LadeStack](https://ladestack.in) free-tools ecosystem.
